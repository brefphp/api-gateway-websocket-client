Websocket client for API Gateway Websockets.

Use this library when building websocket APIs with Bref.

## Installation

```bash
composer require bref/api-gateway-websocket-client
```

## Usage

```php
$client = \Bref\ApiGatewayWebsocket\SimpleWebsocketClient::create($apiId, 'us-east-1', 'default');

$client->message($connectionId, 'Hello world!');
```
