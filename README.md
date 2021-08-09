# node-red-contrib-xvfb

This Node-Red module wraps the `node-xvfb` allowing you to run GUI based node modules, e.g. `node-red-contrib-nbrowser` without having to run X separately.

## Installation

To install this module you will need to ensure you have installed Xvfb in whatever mechanism makes sense for your host system, i.e. apt, yum, etc. After that you can install this module use Node-Red GUI installer or console command:

```
npm install node-red-contrib-xvfb
```

## Usage

Add a "start xvfb" node to your flow before you try to run any GUI modules. To save resources you can also call "end xvfb" when you have finished.

## Credits

This was created from code found on the `node-red-contrib-nbrowser` issues list: https://github.com/Steveorevo/node-red-contrib-nbrowser/issues/17
