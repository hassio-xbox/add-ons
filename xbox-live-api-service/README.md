# Xbox Live API Service

This service, which relies on Xbox Live Credentials Manager and Redis, provides Xbox Live API access by acting as a proxy to the actual Xbox Live API. Use this service for when you wish to write custom components for hass.io that take advantage of the Xbox Live API.

This add-on is a direct port the work that provides clip data for https://guardian.theater. It was designed for scale which is why it is broken into three parts.

## Installation

Before you install this add-on please first install the Redis add-on (included as part of this add-on suite) as well as the Xbox Live Credentials Manager add-on. These three add-ons work together to provide the services.

There is no need to modify the configuration unless you want to change the port or, for advanced use cases, in the event you need to modify how to find the Redis server.