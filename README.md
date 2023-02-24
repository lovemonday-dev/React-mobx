# React-mobx

The SoundCloud Client in React + MobX made with passion.

## Includes

* react v. 16
* react-router v. 4
* mobx
* mobx-react
* normalizr
* lodash-fp
* airbnb-extended eslint
* enzyme v. 3
* Soundcloud API.

## Features

* login to SoundCloud
* show your personal stream
* show favorite tracks, followers and followings
* inifite scroll + paginated fetching
* follow people
* like tracks
* player play/stop/forward/backward track
* playlist
* sort tracks by plays, likes, comments, reposts, downloads
* filter tracks by duration
* search tracks by name and artist

## Run

1. Clone Repository.
2. Exchange CLIENT_ID in `../src/constants/authentification.js` with your own from [SoundCloud for Developers](https://developers.soundcloud.com/) and use `http://localhost:8080/callback` as `Redirect_URI` for your Soundcloud App
3. `npm install`
4. `npm start`
5. visit http://localhost:8080
6. `npm test`


