# Shout [![](https://badge.fury.io/js/shout.png)](https://www.npmjs.org/package/shout)

*/!\ This is a fork containing the following Pull Requests:*
* https://github.com/erming/shout/pull/449/files
* https://github.com/erming/shout/pull/346/files
* https://github.com/erming/shout/pull/455/files

*Also, you have to change the root path on the `client/js/shout.js` file:*
```
sed -i @PATHTOCHANGE@/myShoutPath@g client/js/shout.js
```
This will allow shout to be run on a non-root directory.

### [Try the Demo](http://demo.shout-irc.com/)

__What is it?__  
Shout is a web IRC client that you host on your own server.

__What features does it have?__  
- Multiple user support
- Stays connected even when you close the browser
- Connect from multiple devices at once
- Responsive layout — works well on your smartphone
- _.. and more!_

## Install

```
sudo npm install -g shout
```

## Usage

When the install is complete, go ahead and run this in your terminal:

```
shout --help
```

For more information, read the [documentation](http://shout-irc.com/docs/).

## Development setup

To run the app from source, just clone the code and run this in your terminal:

```
npm install
grunt
./index.js --port 8080
```

And if you don't have [grunt](http://gruntjs.com/getting-started) installed already, just run `npm install -g grunt-cli`.

## License

Available under [the MIT license](http://mths.be/mit).
