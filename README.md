# Timestamp Microservice API

## What is this?

This is a microservice API project for Free Code Camp that will accept either a human
readable date or a unix formatted date and return a json response with the date formatted
as both. If the input is neither it will return `null` values.

You can test it at [https://unixtimemicroserve.herokuapp.com/](https://unixtimemicroserve.herokuapp.com/)

### Usage

```
https://unixtimemicroserve.herokuapp.com/August 15, 1947
```
```
https://unixtimemicroserve.herokuapp.com/-706320000
```

### Sample Output

```javascript
{
  humanReadable: "August 15, 1947",
  unix: "-706320000"
}
```

### Running this project

Simply launch it with node using `npm run start` or `node server.js`.
