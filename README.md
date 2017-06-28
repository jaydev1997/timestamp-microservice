# Timestamp Microservice API

## What is this?

This is a microservice API project for Free Code Camp that will accept either a human
readable date or a unix formatted date and return a json response with the date formatted
as both. If the input is neither it will return `null` values.

You can test it at [https://.herokuapp.com/](https://.herokuapp.com/)

### Usage

```
https://.herokuapp.com/January 10, 2015
```
```
https://.herokuapp.com/1420848000
```

### Sample Output

```javascript
{
  humanReadable: "January 10, 2015",
  unix: "1420848000"
}
```

### Running this project

Simply launch it with node using `npm run start` or `node server.js`.
