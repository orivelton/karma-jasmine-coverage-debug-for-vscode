
## Automated test with Karma and Jasmine

It has been implemented tests with Jasmine and Karma, dashboard with coverage and debugger for VScode.

We have 3 functionalities;

1 - Test with watch in terminal.

2 - Dashboard using Coverage.

3 - Debug for VScode \ O / ... (Other IDEs need to be implemented;)).

## VScode Config for Debug

1 - Add settings to file launch.json 
    
    /.vscode/launch.json

    {
        "type":"chrome",
        "request": "launch",
        "name": "Launch Chrome Karma",
        "url": "http://localhost:9876/?id=9792346",
        "webRoot": "${workspaceRoot}"
    }



## Task runner for terminal

npm run test-dev 

## Task runner Launch Chrome Karma

npm run test-open

## Plugins

http://chaijs.com/

## Automatizador

https://gulpjs.com/

## Karma Reporter

https://www.npmjs.com/package/karma-traackr-reporter
