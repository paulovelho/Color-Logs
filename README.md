#Color-log

###Node.js module to get better logs. 

Color-log works as console.log logger on Node.js but with extra data and colors to make easier find the lines on your log files.

## Installation

  npm install color-log

## Usage
You can use all of them as console.log(), send just a string, multiple strings or mix strings and objects.

    var log = require('path/color-log.js')(isLogEnabled, isDebugEnabled, __filename);
    
    log.Debug(...);
    log.Info(...);
    log.Warning(...);
    log.Error(...);



## Tests

  npm test


## Sample

- 06 Jun 15:40:36.045 - **[file_name.js]** DEBUG: message {object to value also} *-> BLUE*
- 06 Jun 15:40:36.045 - **[file_name.js]** INFO: message {object to value also} *-> GREEN*
- 06 Jun 15:40:36.045 - **[file_name.js]** WARNING: message {object to value also} *-> YELLOW*
- 06 Jun 15:40:36.045 - **[file_name.js]** ERROR: message {object to value also} *-> RED*

![Color-log](http://i60.tinypic.com/2lm1g1f.png)



## Release History

* 0.1.0 Initial release