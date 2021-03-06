# Bandwidth Template

## Description
A template to be used to build Bandwidth apps

## Running The App

### Environmental Variables
The following environmental variables need to be set

| Variable | Description |
|--|--|
| MESSAGING_ACCOUNT_ID | Your Bandwidth Messaging account ID |
| MESSAGING_API_TOKEN | Your Bandwidth Messaging API token |
| MESSAGING_API_SECRET | Your Bandwidth Messaging API secret |
| MESSAGING_APPLICATION_ID | Your Bandwidth Messaging application ID |
| VOICE_ACCOUNT_ID | Your Bandwidth Voice account ID |
| VOICE_API_USERNAME | Your Bandwidth Voice API username |
| VOICE_API_PASSWORD | Your Bandwidth Voice API password |
| VOICE_APPLICATION_ID | Your Bandwidth Voice application ID |

### Callback URLs For Bandwidth Applications

| Callback Type | URL |
|--|--|
| Messaging Callback | <url>/callbacks/messaging/callbacks.php |
| Inbound Voice Callback | <url>/callbacks/voice/inbound.php |

### Commands
Run the following commands to get started

```
composer require bandwidth/sdk
php -S localhost:<some-available-port>
```
