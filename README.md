# Tumblring

[![Build Status](https://travis-ci.org/dmcclccam/tumblring.svg)](https://travis-ci.org/dmcclccam/tumblring)

This is a command-line module to let you know if you (or someone else) rebloged today or yesterday.

### To install

_Requires [Node.js](http://www.nodejs.org)_

```bash
$ npm install -g tumblring
```

### To use

```bash
# for today
$ tumblr [tumblrusername]
# for yesterday
$ tumblr [tumblrusername] -y
```

**Options**
- `-y` returns _yesterday's_ contributions

#### Example

`$ tumblr dmcclccam` or `$ tumblr dmcclccam -y`

Will return either:

```Bash
---
✔︎ dmcclccam rebloged 14 times today!
---
```
or

```Bash
---
✗ dmcclccam didn't rebloged today.
---
```

### Test

```Bash
$ npm test
```

Currently just checks the 0 reblogs state.