# pm2 START

```js
import nodeStart from 'kin-pm2-start';

const config ={
  "name"        : 'this is a name',
  "script"      : "main.js",// entry js
  "watch"       : false,
  "env": {
      "PORT": "8000"
  }
}
nodeStart(config);
```
