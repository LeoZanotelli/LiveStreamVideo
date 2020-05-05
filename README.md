# Livestream-Clone-Android

## Building the app
Add a file inside project root directory named `secret.properties` having the following contents:
```
StreamApiKey=xxx
UserToken=xxx
```
Replace `xxx` with your values. 

* `StreamApiKey` is a public key which you can get by registering your chat app on getstream.io.
* `UserToken` is a JWT token of your app user. You can generate one here: https://getstream.io/chat/docs/token_generator/?language=kotlin. You'll need to pass there your private key (from getstream.io dashboard) and your desired user id.
