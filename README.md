# ali-oss-download
## Installation
```
npm install -g ali-oss-download
```

## Configuration file
You should create a configuration file. Example: 

```
// YOUR-CONFIG-FILE.js
module.exports = {
  visitor: {
    region: '<OSS region>',
    accessKeyId: '<OSS accessKeyId>',
    accessKeySecret: '<OSS accessKeySecret>',
    bucket: '<OSS bucket name>',
    secure: true,
  },
}
```

## Usage
```
ali-oss-download CONFIG-JS-FILE REMOTE-PATH LOCAL-FILE [OVER-WRITE]
```
