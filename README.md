![http://i.imgur.com/RmD50NR.jpg](http://i.imgur.com/RmD50NR.jpg)

# KhoaiJS-Flag

## Install

**Bower**

```bash
bower install --save khoaijs-flag
```

## Usage

```js
Flag.hasFlag('test');//false
Flag.flag('test');
Flag.hasFlag('test');//true
Flag.isFlagged('test');//true

Flag.flagStatus('test');//true
Flag.flag('test', false);
Flag.flagStatus('test');//false
Flag.hasFlag('test');//true
Flag.isFlagged('test');//false
```