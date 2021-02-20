# Tentacle-bookmarklet
 Add blog to tentacle subscription list inspired by this [tweet](https://twitter.com/tentacleapp/status/1282360699558268929?s=20)
# Setup
Make a new bookmark and add the following script to the URL part
```javascript
javascript:(function()%7Bvar addToTentacle %3D 'https%3A%2F%2Ftntcl.app%2F'%2B window.location.href %2B''%3Bwindow.location.assign(addToTentacle)%7D)()
```
