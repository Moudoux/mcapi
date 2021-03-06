# mcapi

> An unofficial Node.js library for fetching data from Mojang

Get user data, translate usernames <-> UUID's, get username history and more with promises.

## Usage

First import the library using:

```js
    const mcapi = require('mcapi');
```

To get the corresponding UUID of a username simply type:

```js
    let uuid = await mcapi.usernameToUUID("Deftware";
```

## oAuth

This library also supports [MC-oAuth](https://mc-oauth.net/), to use oAuth simply type:

```js
    let uuid = await mcapi.oAuthToUUID("<6 digit oauth code>");
```

You get the 6 digit oauth code from joining `srv.mc-oauth.net` with your Minecraft client.
