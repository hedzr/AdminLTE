# NOTES

## At first

```bash
npm install -g bower npm
npm install && bower
```


## dev

`grunt` or `grunt watch` or `grunt default` to build the modifications instantly.

`grunt less` to build the distributes to `dist` folder;

`grunt less uglify includes`


## import and use


**Bower**

The original version from [Almsaeed Studio](https://almsaeedstudio.com)

```bash
bower install admin-lte
```

The modificated version from [Hedzr](https://github.com/hedzr/)

```bash
bower install https://github.com/hedzr/AdminLTE.git --save
```

The `master` branch:

```bower.json
{
  "dependencies": {
    "AdminLTE": "https://github.com/hedzr/AdminLTE.git#master"
  },
}
```
