---
title: BC Address Geocoder
description: Locate and standardize your addresses with the BC Address Geocoder.
image: "https://openclipart.org/image/300px/svg_to_png/271858/flat-map-gray.png"
persona: Developer
---

# BC Address Geocoder

## Service Overview
The BC Address Geocoder can be used to resolve the physical locations (i.e., latitude and longitude) and correct, standardized form of civic and non-civic addresses in British Columbia.  It is a web service that is accessible via a REST application programming interface (API).

A full list of materials and sample applications can be found at the **[Geocoder homepage](https://www2.gov.bc.ca/gov/content/data/geographic-data-services/location-services/geocoder)**.
* https://www2.gov.bc.ca/gov/content/data/geographic-data-services/location-services/geocoder


## Where to start
In addition to the **[Geocoder homepage](https://www2.gov.bc.ca/gov/content/data/geographic-data-services/location-services/geocoder)**, a full list of resources, parameters, formats and coordinate systems can be found in the **[API console](https://catalogue.data.gov.bc.ca/dataset/physical-address-geocoding-web-service/resource/40d6411e-ab98-4df9-a24e-67f81c45f6fa/view/1d3c42fc-53dc-4aab-ae3b-f4d056cb00e0)**. 


## Sample requests
* See the **[API console](https://catalogue.data.gov.bc.ca/dataset/physical-address-geocoding-web-service/resource/40d6411e-ab98-4df9-a24e-67f81c45f6fa/view/1d3c42fc-53dc-4aab-ae3b-f4d056cb00e0)** for a full list.

## Search by address

https://geocoder.api.gov.bc.ca/addresses.json?addressString=(ADDRESS STRING)
```console
https://geocoder.api.gov.bc.ca/addresses.json?addressString=1012%20Douglas%20St%2C%20Victoria%2C%20BC
```

## Search by coordinate
https://geocoder.api.gov.bc.ca/sites/nearest.json?point=(COORDINATES)
```console
https://geocoder.api.gov.bc.ca/sites/nearest.json?point=-122.377%2C50.121
```

## Search within an area (BBOX)
https://geocoder.api.gov.bc.ca/sites/within.json?bbox=(COORDINATES)
```console
https://geocoder.api.gov.bc.ca/sites/within.json?bbox=-119.51%2C49.48%2C-119.53%2C49.50
```

## Sample web application

The Location Services in Action application (https://ols-demo.apps.gov.bc.ca/index.html) demonstrates how to use the BC Address Geocoder in a web app.

The source can be found in the following repo.
* https://github.com/bcgov/ols-devkit/tree/gh-pages/ols-demo


## API Keys

The Geocoder can be used anonymously or with API keys.
API keys can be requested with the API Key Request application (http://kq.apps.gov.bc.ca)

A complete list of API key resources can be found in the API Management Services DevHub page.
* https://developer.gov.bc.ca/openshift-wiki/Z1yJPxt

## Anonymous Requests:
*  Limited to 500 requests per minute

## Developer API keys:
*  Rate limit is defined by the API owner and shown in your developer dashboard (https://gwa.apps.gov.bc.ca/).
*  API keys rotate every 90 days. New keys are automatically generated and listed in your developer dashboard

![Developer Dashboard](https://raw.githubusercontent.com/bcgov/gwa/master/img/Enable_API_Keys.JPG)
Figure 1: Developer Dashboard

## Production API keys:
*  Unlimited requests. Currently reserved for B.C. Government production applications.

## Contact Us
If you have or are planning on integrating the BC Address Geocoder into your own applications, we encourage you to **[contact DataBC](https://forms.gov.bc.ca/databc-contact-us/)** and ask to receive important updates.
