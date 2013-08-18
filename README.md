btn-api
=======

## Install
```
npm install btn-api
```


##How to use


##require it
```javascript
var Btn = require('btn-api')
```

##init it
The first argument should be your API key
```javascript
var btn = new Btn('your-magic-key')
```
##Usage

Snatch list first argument is  how many to return
```javascript
btn.getUserSnatchlist(50, console.log)
```
Userinfo
```javascript
btn.userInfo(console.log)
```

Inbox
```javascript
btn.getInbox(console.log)
```

## Docs
http://btnapps.net/apigen/class-btnapi.html