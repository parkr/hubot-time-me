# Hubot: hubot-time-me

Location-aware queries about users for hubot.

Where is parkr? What time is it at parkr's location? Hey Hubot, parkr's now
in a new location.

See [`src/time-me.coffee`](src/time-me.coffee) for full documentation.

## Installation

Add **hubot-time-me** to your `package.json` file:

```bash
npm install --save hubot-time-me
```

Add **hubot-time-me** to your `external-scripts.json`:

```json
["hubot-time-me"]
```

Run `npm install`

Go to https://timezonedb.com and register for an account. You should receive an API key that you can then tell Hubot about. Just set the environment variable `HUBOT_TIMEZONEDB_API_KEY` to the API key provided :zap:

## Sample Interaction

```
user1>> hubot parkr is in Ithaca, NY
hubot>> Ok, updated parkr's location to 'Ithaca, NY'
user1>> hubot where is parkr
hubot>> parkr is in Ithaca, NY.
user1>> hubot time me parkr
hubot>> It's currently Thursday, March 13 at 18:39 PM. in Ithaca, NY.
```
