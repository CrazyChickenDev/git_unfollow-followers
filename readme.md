<p align="center"><img src="https://github.com/CrazyChickenDev/git_unfollow-followers/blob/master/Sentrytocat.jpg" width="300px" height="300px"> </img>
</p>
<h1 align ="center">GitHub Unfollow Everyone</h1>
<h4 align ="center">:fallen_leaf:Start Anew. Unfollow everyone who you currently follow on GitHub.</h4>

## Cli

```
$ npm install --global github-unfollow-everyone
```
```
$ github-unfollow-everyone <username> <password>
```

_:warning::warning: Running this command will **irreversibly** unfollow everyone who you currently follow!_

## Api

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
