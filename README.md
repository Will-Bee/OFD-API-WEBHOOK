# OFD-API

## Usage
- Send notifications to your webhook without recompiling the whole project
- I used this in my project when I designed my own device looking for optic fiber cable
    - OFD stands for Optic Fiber Detector


## Features

- Easy to set up
- Administration in production
- Logging
- Passwords encrypted
- Works on any server with running PHP


## API Reference

#### Get all items

```http
GET OFD/api/?secret=yourSecret
```

| Parameter | Type     | Description                | Example value |
| :-------- | :------- | :------------------------- |:--------------|
| `secret`  | `string` | **Required**. Your API key | `yourSecret`  |


#### Api response

```json
{"URL":"https://your.url/of/webhook","text":"Your notes go here"}
```


## API & Administration

- For changing API response data: `OFD/`
- For changing Password: `OFD/passwd/`
- For changing Secret: `OFD/secret/`
- To see logs: `OFD/log/`
- To get API response `OFD/api/?secret=yourSecret`
## Setup

- Upload whole project on your server running PHP
- Go to `OFD/` and customize API response data
- Go to `OFD/passwd` and change your password
- Go to `OFD/secret` and change your API secret

#### Default values
- Password: `heslo`
- Secret: `fairytales`
## Author

- [@Will-Bee](https://github.com/Will-Bee)

