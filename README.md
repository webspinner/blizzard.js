# Blizzard.js Example App

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/benweier/blizzard.js/tree/example)

## Routes

Once the app is deployed, hit the app URL with one of these paths.

e.g.
http://blizzardjs-example-app.herokuapp.com/wow/us/achievement/2144
http://blizzardjs-example-app.herokuapp.com/wow/eu/realms

Route params denoted with `?` are optional.

### World of Warcraft

```
/wow/:origin/achievement/:id
/wow/:origin/auction/:realm
/wow/:origin/boss/:id?
/wow/:origin/challenge/:realm
/wow/:origin/character/:realm/:name
/wow/:origin/data/:key
/wow/:origin/guild/:realm/:name
/wow/:origin/item/:id
/wow/:origin/mount
/wow/:origin/pet/:key?/:id?
/wow/:origin/pvp/:bracket
/wow/:origin/quest/:id
/wow/:origin/realms
/wow/:origin/recipe/:id
/wow/:origin/spell/:id
/wow/:origin/zone/:id?
```

### Starcraft 2

```
/sc2/:origin/profile/:id/:name/:key?
/sc2/:origin/ladder/:id
/sc2/:origin/data/:key
```

### Diablo 3

```
/d3/:origin/data/:key/:id
/d3/:origin/era/:id?/:leaderboard?
/d3/:origin/season/:id?/:leaderboard?
/d3/:origin/profile/:tag/:hero?
```

### Account

```
/account/:origin/user
/account/:origin/wow
/account/:origin/sc2
```
