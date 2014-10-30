# hubot-ambush
A hubot script to leave messages for people

Port from https://github.com/github/hubot-scripts/src/scripts/ambush.coffee

See [`src/ambush.coffee`](src/ambush.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-ambush --save`

Then add **hubot-ambush** to your `external-scripts.json`:

```json
[
  "hubot-ambush"
]
```

## Configuration

None :)

## Command
Example: `hubot ambush <user name>: <message>`

## Sample Interaction

```
user1> hubot ambush user2: Ohai! You forgot your card at lunch!
Hubot> Ambush Prepared
user2> That was a great lunch!
Hubot> user2: while you were out, user1 said: Ohai! You forgot your card at lunch!
```
