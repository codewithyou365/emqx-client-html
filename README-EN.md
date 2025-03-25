[中文版](README.md)

# Click the star✨ to support the author!

# MQTT Client Interface User Guide

## Project Overview

- This is a web-based MQTT client interface that allows users to connect to an MQTT server, publish/subscribe to topics, and view message logs.
- The project uses Docker Compose to start the EMQX MQTT server.

## Quick Start

### 1. Start the MQTT Server

```bash
docker-compose up -d
```

### 2. Open the MQTT Client Interface

Open http://127.0.0.1:8080/index.html in your browser to start using the MQTT client interface.

Use the following command to start the EMQX MQTT server:
![demonstration](https://raw.githubusercontent.com/codewithyou365/emqx-client-html/refs/heads/main/demonstration.gif)

## Client Operations

### Configure MQTT Server
1. Enter the server address in the “MQTT Server URL” field: `ws://localhost:8083/mqtt`
2. Click the “Update Server” button to save the server address.

### Register Client
1. Enter the username (required)
2. Enter the password (optional)
3. Click the “Register” button to connect to the server

### Subscribe to a Topic
1. Enter the topic to subscribe to in the “Topic” field
2. Click the “Subscribe” button

### Publish a Message
1. Enter the topic to publish to in the “Topic” field
2. Enter the message to send in the “Message” field
3. Click the “Publish” button

### Disconnect
1. Click the “Close” button to disconnect the selected client