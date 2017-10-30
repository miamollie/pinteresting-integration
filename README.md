# README

This project is a very basic example of working with the Pinterest JavaScript SDK (PDK)

The two functions covered are authentication and fetching pins from a given board.

Pinterest API docs: https://developers.pinterest.com/docs/api/overview/

PDK https://developers.pinterest.com/docs/sdks/js/

### Use

Before using the API, Pinterest requires that you register an App with them and generate an App ID. The ID is used in authentication requests, there is one hard coded into this repo but to use the API properly you should go and and register your own App.

The Pinterest API uses Oauth 2.0 for authentication, and requires a request redirect uri to be HTTPS, so in order to run this locally you must start a HTTPS server.

You can do this any way you'd like, but I used [pyhttps](https://github.com/talhasch/pyhttpsouter) by @talhasch which was quick and easy to get up and running.

```
sudo easy_install pip

sudo pip install pyhttps
```

Then to use the https server

```
pyhttps
```

and the project will be running at

```
https://localhost:4443
```
