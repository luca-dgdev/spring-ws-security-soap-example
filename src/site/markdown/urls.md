# Endpoint URLs

Each combination of authentication methods and WSS implementations is mapped to their own URL:

|Authentication method|WSS Implementation|URL|
|:-:|:-:|:-:|
|None|None|[http://localhost:8080/swss/unsecure/entities](http://localhost:8080/swss/unsecure/entities)|
|Plain Password|XWSS|[http://localhost:8080/swss/password/plain/xwss/entities](http://localhost:8080/swss/password/plain/xwss/entities)|
|Plain Password|WSS4J|[http://localhost:8080/swss/password/plain/wss4j/entities](http://localhost:8080/swss/password/plain/wss4j/entities)|
|Digested Password|XWSS|[http://localhost:8080/swss/password/digest/xwss/entities](http://localhost:8080/swss/password/digest/xwss/entities)|
|Digested Password|WSS4J|[http://localhost:8080/swss/password/digest/wss4j/entities](http://localhost:8080/swss/password/digest/wss4j/entities)|
|Signature|XWSS|[http://localhost:8080/swss/signature/xwss/entities](http://localhost:8080/swss/signature/xwss/entities)|
|Signature|WSS4J|[http://localhost:8080/wss4j/signature/xwss/entities](http://localhost:8080/wss4j/signature/xwss/entities)|
|Encryption|XWSS|[http://localhost:8080/swss/encryption/xwss/entities](http://localhost:8080/swss/encryption/xwss/entities)|
|Encryption|WSS4J|[http://localhost:8080/wss4j/encryption/xwss/entities](http://localhost:8080/wss4j/encryption/xwss/entities)|

## WSDL

Additionally there is a WSDL file for each of these endpoints, which is created by just adding the ".wsdl" suffix to the URL.

|Authentication method|WSS Implementation|URL|
|:-:|:-:|:-:|
|None|None|[http://localhost:8080/swss/unsecure/entities.wsdl](http://localhost:8080/swss/unsecure/entities.wsdl)|
|Plain Password|XWSS|[http://localhost:8080/swss/password/plain/xwss/entities.wsdl](http://localhost:8080/swss/password/plain/xwss/entities.wsdl)|
|Plain Password|WSS4J|[http://localhost:8080/swss/password/plain/wss4j/entities.wsdl](http://localhost:8080/swss/password/plain/wss4j/entities.wsdl)|
|Digested Password|XWSS|[http://localhost:8080/swss/password/digest/xwss/entities.wsdl](http://localhost:8080/swss/password/digest/xwss/entities.wsdl)|
|Digested Password|WSS4J|[http://localhost:8080/swss/password/digest/wss4j/entities.wsdl](http://localhost:8080/swss/password/digest/wss4j/entities.wsdl)|
|Signature|XWSS|[http://localhost:8080/swss/signature/xwss/entities.wsdl](http://localhost:8080/swss/signature/xwss/entities.wsdl)|
|Signature|WSS4J|[http://localhost:8080/wss4j/signature/xwss/entities.wsdl](http://localhost:8080/wss4j/signature/xwss/entities.wsdl)|
|Encryption|XWSS|[http://localhost:8080/swss/encryption/xwss/entities.wsdl](http://localhost:8080/swss/encryption/xwss/entities.wsdl)|
|Encryption|WSS4J|[http://localhost:8080/wss4j/encryption/xwss/entities.wsdl](http://localhost:8080/wss4j/encryption/xwss/entities.wsdl)|