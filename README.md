# node-red-contrib-iot-tp
Custom Node-RED node for IoT TP
# node-red-contrib-iot-tp

## Overview

This Node-RED node converts the input message payload into lowercase characters.

## How to use

Connect this node to a node that sends a string payload. The node converts the payload to lowercase and forwards the message to the next node.

Example:

`HELLO IOT TP` → `hello iot tp`

## Prerequisites

- Node-RED

## Example flow

Inject → lower-case → debug

## Changelog

- 1.0.0: Initial release of the lower-case node.