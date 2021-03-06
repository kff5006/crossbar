title: Table of Contents
toc: [Documentation, Table of Contents]

# Table of Contents

## Getting Started

* [Getting Started](Getting Started)

## Administrators

* [Basic Concepts](Basic Concepts)
* [Installation](Installation)
   * Docker Images
      * [Using Docker](Using Docker)
   * Other Platforms
      * [Installation on (generic) Linux](Installation on Linux)
      * [Installation on Mac OS X](Installation on Mac OS X)
      * [Installation on Windows](Installation on Windows)
   * Setup on IaaS and PaaS Providers
      * [Setup on Amazon EC2](Setup-on-Amazon-EC2)
      * [Setup on Heroku](Setup-on-Heroku)
      * [Setup on OpenShift](Setup-on-OpenShift)
   * Demo Instance
      * [Demo Instance](Demo Instance)
* [Administration](Administration)
   * [The Command Line](Command Line)
   * [Node Configuration](Node Configuration)
      * [Processes](Processes)
         * [Controller Configuration](Controller Configuration)
         * [Guest Configuration](Guest Configuration)
         * [Native Worker Shared Options](Native Worker Options)
         * [Container Configuration](Container Configuration)
         * [Process Environments](Process Environments)
         * [Router Configuration](Router Configuration)
            * [Router Realms](Router Realms)
            * [Router Components](Router Components)
            * [Router Transports](Router Transports)
               * [Transport Endpoints](Transport Endpoints)
               * [WebSocket Transport](WebSocket Transport)
                  * [WebSocket Options](WebSocket Options)
                  * [WebSocket Compression](WebSocket Compression)
                  * [Cookie Tracking](Cookie Tracking)
               * [RawSocket Transport](RawSocket Transport)
               * [Web Transport and Services](Web Transport and Services)
               * [Flash Policy Transport](Flash Policy Transport)
            * [Web Services](Web Services)
               * [Path Service](Path-Service)
               * [Static Web Service](Static-Web-Service)
               * [File Upload Service](File-Upload-Service)
               * [WebSocket Service](WebSocket-Service)
               * [Long-Poll Service](Long-Poll-Service)
               * [Web Redirection Service](Web-Redirection-Service)
               * [Reverse Proxy Service](Reverse Proxy Service)
               * [JSON Value Service](JSON-Value-Service)
               * [CGI Script Service](CGI-Script-Service)
               * [WSGI Host Service](WSGI-Host-Service)
               * [Resource Service](Resource-Service)
            * [HTTP Bridge](HTTP Bridge)
               * [HTTP Bridge Publisher](HTTP Bridge Publisher)
               * [HTTP Bridge Subscriber](HTTP Bridge Subscriber)
               * [HTTP Bridge Caller](HTTP Bridge Caller)
               * [HTTP Bridge Callee](HTTP Bridge Callee)
               * [HTTP Bridge Webhook](HTTP Bridge Webhook)
            * [MQTT Broker](MQTT Broker)
            * [Authentication](Authentication)
               * [Anonymous Authentication](Anonymous Authentication)
               * [Challenge-Response Authentication](Challenge-Response Authentication)
               * [Cookie Authentication](Cookie Authentication)
               * [Ticket Authentication](Ticket Authentication)
               * [Cryptosign Authentication](Cryptosign Authentication)
               * [TLS Client Certificate Authentication](TLS Client Certificate Authentication)
               * [Dynamic Authenticators](Dynamic Authenticators)
            * [Authorization](Authorization)
   * [Logging](Logging)
   * [Going to Production](Going-to-Production)
      * [Running on privileged ports](Running on Privileged Ports)
      * [Secure WebSocket and HTTPS](Secure WebSocket and HTTPS)
      * [TLS Certificates](TLS Certificates)
      * [Payload Encryption (Cryptobox)](Cryptobox Payload Encryption)
      * [Automatic startup and restart](Automatic Startup and Restart)
      * [Network Tuning](Network Tuning)
      * [Reverse Proxies](Reverse Proxies)
      * [SSL/TLS Interception Proxies](SSL-TLS-Interception-Proxies)
      * [Browser Support](Browser Support)
      * [WebSocket Compliance Testing](WebSocket Compliance Testing)
      * [Stream Testee](Stream Testee)

## Programmers

* [Application Scenarios](Application Scenarios)
* [Programming Guide](Programming Guide)
   * General
   [URI Format](URI Format)
      - [Logging in Crossbar.io](Logging in Crossbario)
      - [Error Handling](Error Handling)
      - [Session Meta Events and Procedures](Session Metaevents and Procedures)
      - [Development with External Devices](Development-with-External-Devices)
   * [WAMP Features](WAMP Features)
      - Session
         + [Session Meta Events and Procedures](Session Metaevents and Procedures)
      - [Publish & Subscribe (PubSub)](PubSub)
         + [How Subscriptions Work](How Subscriptions Work)
         + [Basic Subscriptions](Basic Subscriptions)
         + [Subscriber Black- and Whitelisting](Subscriber Black and Whitelisting)
         + [Publisher Exclusion](Publisher Exclusion)
         + [Publisher Identification](Publisher Identification)
         + [Pattern-Based Subscriptions](Pattern Based Subscriptions)
         + [Subscription Meta Events and Procedures](Subscription Meta Events and Procedures)
         + [Event History](Event History)
      - [Remote Procedure Calls](RPC)
         + [How Registrations Work](How Registrations Work)
         + [Basic Registrations](Basic Registrations)
         + [Caller Identification](Caller Identification)
         + [Progressive Call Results](Progressive Call Results)
         + [Pattern-Based Registrations](Pattern Based Registrations)
         + [Shared Registrations](Shared Registrations)
         + [Registration Meta Events and Procedures](Registration Meta Events and Procedures)
      - [Error Handling](Error Handling)
      - [URI Format](URI Format)
   * Frameworks and specific Scenarios
      - [Adding Real-Time to Django Applications](Adding Real Time to Django Applications)
      - [[AngularJS Application Components]]
      - [Database Programming with PostgreSQL](Database Programming with PostgreSQL)
   * Crossbar.io features
      - [Starting and Stopping Crossbar.io](Starting and Stopping Crossbario)
      - [Logging in Crossbar.io](Logging in Crossbario)
      - [Configuring Crossbar.io's Logging](Configuring Crossbario Logging)
   * [Crossbar.io Demo Instance](Demo Instance)
* [Application Templates](Application Templates)
* [Examples](Examples)

## More

* [Compatibility Policy](Compatibility-Policy)
* [Crossbar.io Code License](Crossbar-License)
* [Crossbar.io Documentation License](Documentation-License)
* [Contributing to the Project](https://github.com/crossbario/crossbar/blob/master/CONTRIBUTING.md)**
* [Contributing FAQ](Contributing FAQ)
* [FAQ](FAQ)
