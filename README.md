# SimpleNet
A simple to use TCP and UDP networking library for .NET Core and .NET Framework.

## Features
* TCP
* UDP
* Incredibly fast serialization using ZeroFormatter
* Plug in your choice of IOC
* Plug in your choice of logging
* Encryption (WIP)

## Supported Frameworks
* .NET Standard 1.6
* .NET Core
* .NET Framework 4.5.2

## Installing
Install-Package SimpleNet

#### Latency Simulator
Install-Package SimpleNet.LatencySimulator

## Getting Started

SimpleNet uses a client-server architecture for communication.

Many clients can connect to a single server.
