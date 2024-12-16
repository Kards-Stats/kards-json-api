# Kards JSON API OpenAPI Definition

**[![Build and Deploy](https://github.com/Kards-Stats/kards-json-api/actions/workflows/build-deploy.yml/badge.svg)](https://github.com/Kards-Stats/kards-json-api/actions/workflows/build-deploy.yml)**

Docs can be found here [https://kards-stats.github.io/kards-json-api/](https://klutzybubbles.github.io/kards-json-api/)

## What is Kards

Kards is 'THE MODERN CCG MEETS CLASSIC WAR GAMING' [Kards Website](https://www.kards.com/).

The one thing it lacks is any form of statistics or history data. This is why i dove head first into the game to figure out if i could grab that information myself, this is the result of my findings.

The postman collection is currently the most complete collection of requests i have found, although the web socket communications are still yet to be decoded.

## OpenAPI Definition is WIP

OpenAPI definition of the kards backend API (not the web socket). Hopefully this can help myself and others create some useful applications for kards, until they release an official API.

## Information Source

All the information in this repository has been collected through Fiddler, Wireshark and browsing the kards API. This method of information collecting will never be 100% and because of this, the documentation may not be 100%.

## Postman

The postman folder has all known requests to date, the openapi definition is here to show response and request parameters as well as return codes known.

Any requests marked as used to work got changed either because they revealed private information or they changes it since the update.

Tested on version 1.1.4844
