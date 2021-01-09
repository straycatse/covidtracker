# CovidTracker

This is a module for the [MagicMirror²](https://github.com/MichMich/MagicMirror/).

This module displays data about Covid cases and deaths in Sweden.

Data is collected from the Covid Api (https://covid-api.com/) provided by Johns Hopkins CSSE. 

## Using the module

To use this module, add the following configuration block to the modules array in the `config/config.js` file:
```js
var config = {
    modules: [
        {
            module: 'CovidTracker',
            config: {
                // See below for configurable options
            }
        }
    ]
}
```

## Configuration options - No config options currently available for this module.


| Option           | Description
|----------------- |-----------
| `option1`        | *Required* DESCRIPTION HERE
| `option2`        | *Optional* DESCRIPTION HERE TOO <br><br>**Type:** `int`(milliseconds) <br>Default 60000 milliseconds (1 minute)
