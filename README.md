# slackinviter

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

This is a [slackin](https://github.com/rauchg/slackin) clone written in Go because... Node.js bloat and Go is much nicer :-)

Install or update with `go get -u github.com/devopsisraelslack/slackinviter`. Run `slackinviter` with `-h` for help, it just takes [recaptcha secret + sitekey](https://www.google.com/recaptcha/admin) + [slack api token](https://api.slack.com/custom-integrations/legacy-tokens) + [a slack channel id (for invites logging)](https://api.slack.com/methods/channels.list/test) + CodeOfConduct page URL as parameter, and listenAddr.

See https://cognitive.io/post/rewriting-the-gophers-invite-form-in-go/ to understand why I decided to rewrite Slackin in Go.

## What does it look like?
Visit https://devopsisraelslack.herokuapp.com to see the real thing, or look at this

![screenshot of slackinviter](http://i.imgur.com/KeYawPn.png)

## Features
* A 5 field form: email, first + last name, job title, company.
* A Code of conduct checkbox
* Recaptha, meaning that you can verify your people signing up. This means no bot spam.
* Picture of Slack chat logo.
* Free hosting using Heroku.
* Easy to set up, and quick and easy to use!
