# GladLive.AuthService

GladLive is network session service comparable to Xboxlive or Stream. 

The GladLive.ProxyLoadBalancer is the entry point to the GladLive distributed network and preforms this role by providing:
  - Services Authentication requests for the GladLive distributed network
  - Vertically and horizontally scalable
  - RSA key for authentication distributed with clients

## GladLive Services

GladLive.ProxyLoadBalancer: https://github.com/GladLive/GladLive.ProxyLoadBalancer

GladLive.AuthenticationService: https://github.com/GladLive/GladLive.AuthService

## Setup

To use this project you'll first need a couple of things:
  - Visual Studio 2015
  - Add Nuget Feed https://www.myget.org/F/hellokitty/api/v2 in VS (Options -> NuGet -> Package Sources)

## Builds

Available on a Nuget Feed: https://www.myget.org/F/hellokitty/api/v2 (N/A)

##Tests

#### Linux/Mono - Unit Tests
||Debug x86|Debug x64|Release x86|Release x64|
|:--:|:--:|:--:|:--:|:--:|:--:|
|**master**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.AuthService.svg?branch=master)](https://travis-ci.org/HelloKitty/GladLive/GladLive.AuthService) |
|**dev**| N/A | N/A | N/A | [![Build Status](https://travis-ci.org/GladLive/GladLive.AuthService.svg?branch=dev)](https://travis-ci.org/GladLive/GladLive.AuthService)|

#### Windows - Unit Tests

(Done locally)

##Licensing

This project is licensed under the MIT license with the additional requirement of adding the GladLive splashscreen to your product.
