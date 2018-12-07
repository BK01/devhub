---
title: Geomark Web Service
description: Create and share geographic areas of interest over the web in a variety of formats and coordinate systems
image: "https://openclipart.org/image/300px/svg_to_png/199995/primary-kig-polygon.png"
persona: Developer
---

# Geomark Web Service

## Service Overview
The Geomark Web Service allows you to create and share geographic areas of interest over the web in a variety of formats and coordinate systems. This service is especially helpful when you need to share an area of interest with people who require that the data be in a different format, or they use different mapping software.
Geomarks are immutable and expire after 90 days.

A full list of materials and Geomark web applications can be found at the **[Geomark homepage](https://www2.gov.bc.ca/gov/content?id=F6BAF45131954020BCFD2EBCC456F084)**.
* https://www2.gov.bc.ca/gov/content/data/geographic-data-services/location-services/geomark-webservice


## Where to start
In addition to the **[Geomark homepage](https://www2.gov.bc.ca/gov/content?id=F6BAF45131954020BCFD2EBCC456F084)**, a full list of resources, parameters, formats and coordinate systems can be found in the **[API console](https://catalogue.data.gov.bc.ca/dataset/geomark-web-service/resource/5c237fac-851c-4cd9-987c-d5cc5a0da7e9/view/fd2f9b17-8527-4a89-a552-7786d36ba1f1)**. 


## Sample requests

## Get information about a particular geomark

https://apps.gov.bc.ca/pub/geomark/geomarks/**(GEOMARK ID).(FILE FORMAT)**
```console
https://apps.gov.bc.ca/pub/geomark/geomarks/gm-abcdefghijklmnopqrstuv0bcislands.json
```

## Get geomark feature

https://apps.gov.bc.ca/pub/geomark/geomarks/**(GEOMARK ID)**/feature.json
```console
https://apps.gov.bc.ca/pub/geomark/geomarks/gm-abcdefghijklmnopqrstuv0bcislands/feature.json
```

## Web application

The Geomark Web application (http://apps.gov.bc.ca/pub/geomark/geomarks) demonstrates how to use Geomark.


## API Keys

The Geomark Web Service does NOT require the use of API keys.


## Contact Us
If you have or are planning on integrating the BC Address Geocoder into your own applications, we encourage you to **[contact DataBC](https://forms.gov.bc.ca/databc-contact-us/)** and ask to receive important updates.