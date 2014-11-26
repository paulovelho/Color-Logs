#Color-logs

###Node.js module to get better logs. 

Color-logs works as console.log logger on Node.js but with extra data and colors to make easier find the lines on your log files.

## Installation

  npm install color-logs

## Usage
You can use all of them as console.log(), send just a string, multiple strings or mix strings and objects.

    var log = require('color-logs.js')(isLogEnabled, isDebugEnabled, __filename);
    
    log.debug(...);
    log.info(...);
    log.warning(...);
    log.error(...);


## Sample

- 06 Jun 15:40:36.045 - **[file_name.js]** DEBUG: message {object to value also} *-> BLUE*
- 06 Jun 15:40:36.045 - **[file_name.js]** INFO: message {object to value also} *-> GREEN*
- 06 Jun 15:40:36.045 - **[file_name.js]** WARNING: message {object to value also} *-> YELLOW*
- 06 Jun 15:40:36.045 - **[file_name.js]** ERROR: message {object to value also} *-> RED*

![Color-logs](http://i59.tinypic.com/15mb9y9.png)

## Testing

	npm i
 	npm test

## Release History

* 0.5.3 Fixed path file on log for windows

* 0.5.0 Added support for lowercase funcions name

* 0.2.3 Simply update readme image

* 0.2.2 Enabled again test

* 0.2.1 Disabled test

* 0.2.0 Fixed test and enabled and disable bug and log

* 0.1.0 Initial release
