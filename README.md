# Magento REST API Model

## Usage

### Generate TS Model
```shell

java -jar swagger-codegen-cli-2.4.9.jar generate -i [input file path] -l [output type] -o [output path]

- [output type]:
                Available Clients: [
                    akka-scala, android, async-scala, clojure,
                    cpprest, csharp, CsharpotNet2, cwiki,
                    dart, dynamic-html, flash, go,
                    groovy, html, html2, java,
                    javascript, javascript-closure-angular, jaxrs-cxf-client, jmeter,
                    objc, perl, php, python,
                    qt5cPP, ruby, scala, swagger,
                    swagger-yaml, swift, swift3,
                    tizen, typescript-angular, typescript-angular2, typescript-fetch,
                    typescript-node
                ], 
                Available Servers: [
                    aspnet5, aspnetcore, erlang-server, go-server,
                    haskell, inflector, jaxrs, jaxrs-cxf,
                    jaxrs-cxf-cdi, jaxrs-resteasy, jaxrs-spec,
                    Iumen, msf4r, nancyfx, nodejs-server, 
                    python-flask, rails5, scalatra,
                    silex-PHP, sinatra, slim, spring,
                    undertow
                ] 
Eg:
java -jar swagger-codegen-cli-2.4.9.jar generate -i input/openapi.json -l typescript-fetch -o src
java -jar swagger-codegen-cli-2.4.9.jar generate -i input/openapi.json -l typescript-node -o src
java -jar swagger-codegen-cli-2.4.9.jar generate -i input/openapi.json -l typescript-angular -o src

```
### Generate JS Model
```shell
  npm i
  npm run build
```
