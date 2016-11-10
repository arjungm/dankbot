<img align="right" src="http://i.imgur.com/j3dV8LI.png">
# DankBot
A Dank Discord Bot

[![Go Report Card](https://goreportcard.com/badge/github.com/coolbrow/dankbot)](https://goreportcard.com/report/github.com/coolbrow/dankbot)

## Adding DankBot to a Discord Server

Simple! Just click [this link](https://discordapp.com/oauth2/authorize?client_id=245577797244944385&scope=bot&permissions=59392) and select your server

<br/>
## Commands
### Images
* `SombraDance`
  * http://i.imgur.com/lq3TwJi.gif

### Reddit Search
* `/reddit [subreddit] [query]`
  * Searches given subreddit with query and returns top result. 
  * If no query is given, returns current top subreddit item
  
> **Note:** Ignores sticky posts 

<br/>
## Setup and Run

This assumes you already have a working Go environment, if not please see
[this page](https://golang.org/doc/install) first.

**Download dankbot:**

```sh
go get github.com/coolbrow/dankbot
cd $GOPATH/src/github.com/coolbrow/dankbot
```

**Create token file:**
>**Note:** Client tokens are found on your [Discord application page](https://discordapp.com/developers/applications/me)

```sh
echo YOUR_CLIENT_TOKEN > token
```

**Run DankBot:**

```sh
./run.sh
```

And that's it!

