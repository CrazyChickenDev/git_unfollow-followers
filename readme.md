<img src="https://github.com/CrazyChickenDev/git_unfollow-followers/blob/master/Sentrytocat.jpg" width="300px" height="300px"></img>

<p1 align="center"><h1>GitHub Unfollow Everyone</h1></p1>

:fallen_leaf: _Start Anew. Unfollow everyone who you currently follow on GitHub._

## CLI

```
$ npm install --global github-unfollow-everyone
```
```
$ github-unfollow-everyone <username> <password>
```

_:warning::warning: Running this command will **irreversibly** unfollow everyone who you currently follow!_

## API

```
$ npm install --save github-unfollow-everyone
```

```javascript
var unfollowEveryone = require('github-unfollow-everyone');

unfollowEveryone('<username>', '<password>', function(error) {
  if (error) {
    console.log('oops. an error occurred:', error);
    return;
  }
  console.log('done.');
});
```
