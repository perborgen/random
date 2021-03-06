# CLI for live-streaming your local dev environment

![node](https://img.shields.io/node/v/scrimba.svg) ![https://join.slack.com/t/scrimba/shared_invite/enQtNDE4MzY0NDY3NzkyLWFhMzg1YzQ4ZWIwOGMyYzhiZTYxMmEyZTAzMTE5ZTBmMzE4ZDA5ZjM1N2ZjMDZjMmE5M2M4ZDNkN2JjNGM2YzQ](https://img.shields.io/badge/slack-join%20chat-brightgreen.svg?longCache=true&style=flat&logo=slack) 

[Scrimba](https://scrimba.com:9000/@welcome) is a screen sharing tool for developer teams. It's command line-based and allows you to do the following:

* **Live stream** your local dev environment to a URL
* **Collaborate** in real-time and discuss via voice chat
* **Keep a recording** of the session afterwards

The most popular use-cases are code review, onbarding, and documentation. 

## Quick-start
```bash
# install the CLI
$ npm -g install scrimba

# navigate to your project
$ cd my-awesome-project

# start a live stream
$ scrimba start
```

This will open the `my-awesome-project` folder as a _scrim_ in Chrome, which will look something like this:

![](https://i.imgur.com/hDwDZ4l.png)

Now you'll be able to interact with your local workspace via this _scrim_. This means that you can edit and save files, and run commands in the terminal. To start collaborating, simply share the URL with a colleague and she'll be able to jump into your local workspace instantly.

## All features

* **Codebase**, terminal and browser sharing
* **Real-time** collaboration
* **Mouse pointer** for each participant
* **Voice** chat
* **Conferences** (up to 4 people)
* **Record** sessions
* **Dashboard** for recorded sessions

## Feedback

This is an experimental feature, and you're likely to encounter bugs. Please report any bugs, quirks, or invconveniences to us via our [Slack group](https://scrimba.slack.com/), as it'll help us improve the experience. We'd also love to hear any suggestions you might have. You can also follow us reach out at [Twitter](https://twitter.com/scrimba_com).

## Limitations
It currently only works to stream via Google Chrome

## Troubleshooting

If you have trouble installing scrimba without sudo, read up on [fixing-npm-permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

```
prebuild-install WARN install EACCES: permission denied, mkdir '/path/to/node_modules/node-pty-prebuilt/build'

# If you really need to install with sudo, and get the error above, install using --unsafe-perm:
sudo npm install -g scrimba --unsafe-perm



```
