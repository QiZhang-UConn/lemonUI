# Lemonwire: A Discord Bot Music Playlist Management System

## About Lemonwire

A music playlist management web application named Lemonwire. The app consists of a front-end, named **LemonUI** written in Javascript and HTML, and a back-end named [**LemonAPI**](https://github.com/JonahLandry/lemonAPI) written in Java8 with Spring framework. Both parts of the application are deployed to AWS cloud with DevOps. Lemonwire utilzes LavaPlayer, Discord4J, and YouTube API to allow you pull music and create playlists via url of YouTube and other music sources. Lemonwire users may login with their Discord accounts via OAuth2 connection. Playlist information will be persist in Postgres database; Users may manage their playlists on the web UI with the ability of adding, deleting, sharing playlists, and add songs to seleted playlist. The music playlists will be utilized by a Discord bot named [**Lemonwire**](https://github.com/JonahLandry/lemonwire) and being played in a Discord voice channel.

## LemonUI

## Features
1. Login with Discord by OAuth2 link
2. Create/Edit/Delete playlists if you have the CREATOR role
3. Add/Delete tracks to a playlist
4. Invite/delete friends to access your private playlist

## Technology Utilized
1. JavaScript
2. HTML
3. CSS
4. YouTube API

## LemonAPI
The service communicates with the API created here: https://github.com/JonahLandry/lemonAPI

## Lemonwire (Bot)
The discord bot runs off the code created here: https://github.com/JonahLandry/lemonwire

## Contributors
- Danh Tran
- Dario Robinson
- Jonah Landry
- Minh Tuan Nguyen
- Qi Zhang
