
## Testes automatizado com Karma e Jasmine

Para a qualidade do software foi implementado testes com Jasmine e Karma, dashboard com
coverage e debug para VScode.

Temos 3 funcionalidades;

1 - Teste com watch no terminal.

2 - Dasboard utilizando Coverage.

3 - Debug para VScode \O/... (Outras IDEs é precisa ser implementado ;) ).

## Config do VScode para Debug

1 - Adicione as configurações ao arquivo launch.json 
    
    /.vscode/launch.json

    {
        "type":"chrome",
        "request": "launch",
        "name": "Launch Chrome Karma",
        "url": "http://localhost:9876/?id=9792346",
        "webRoot": "${workspaceRoot}"
    }

## Task runner

npm run test-dev // teste no terminal com watch

npm run test-open // Dashboard com a análise de cobertura feito pelo Coverage


## Plugins

http://chaijs.com/

## Automatizador

https://gulpjs.com/

## Karma Reporter

https://www.npmjs.com/package/karma-traackr-reporter