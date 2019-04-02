
### `Intro`
mkdir with 'p' on the base mkdir '{recursive: true}' doesn't seem to work so here's this little util

#### `Install`
``` bash
npm install --save git+https://git@github.com/anzerr/fs.mkdirp.git
```

### `Example`
``` javascript
const mkdir = require('fs.mkdirp');

mkdir('foo/bar/cat/dog').catch(console.log);

```
