# dsb-postman

## Disclaimer

The artefacts in this repo are offered without warranty or liability, in accordance with the [MIT licence.](https://github.com/ConsumerDataStandardsAustralia/java-artefacts/blob/master/LICENSE)

[The Data Standards Body](https://www.csiro.au/en/News/News-releases/2018/Data61-appointed-to-Data-Standards-Body-role)
(DSB) develops these artefacts in the course of its work, in order to perform quality assurance on the Australian Consumer Data Right Standards (Data Standards).

The DSB makes this repo, and its artefacts, public [on a non-commercial basis](https://github.com/ConsumerDataStandardsAustralia/java-artefacts/blob/master/LICENSE)
in the interest of supporting the participants in the CDR eco-system.

The resources of the DSB are primarily directed towards assisting the [Data Standards Chair](https://consumerdatastandards.gov.au/about/)
for [developing the Data Standards](https://github.com/ConsumerDataStandardsAustralia/standards).

Consequently, the development work provided on the artefacts in this repo is on a best-effort basis,
and the DSB acknowledges the use of these tools alone is not sufficient for, nor should they be relied upon
with respect to [accreditation](https://www.accc.gov.au/focus-areas/consumer-data-right-cdr-0/cdr-draft-accreditation-guidelines),
conformance, or compliance purposes.

## Overview

This repository contains a Postman collection for the Energy and Banking sector, as well as the Common API calls as published by the DSB.
The collections are part of the Postman workspace DSB-SCHEMA-TEST and can be found  [here](https://www.postman.com/winter-shadow-541400/workspace/dsb-schema-tests).


# Postman Collection Test Suite


## Using the Postman collection
```
CDR Banking Sector Conformance Tests vX.XX.X.postman.json
```
This Postman collection contains the API unit tests and can be run as a test suite (Postman Collection Runner). This will run all tests for the number of iterations specified in the * .collection-run.postman.json* file. Each array element will trigger a collection run.

The collection can also be run against an environment defined in * .postman-environment.json*.

---

### Using a Postman environment

The API tests can also be run in conjunction with the *xxx.postman_environment.json* configuration file. Similarily to the *xxx.collection-run.postman.json* file this can be configured for a specific data holder server.

To achieve this import the configured *xxx.postman_environment.json* as an Environment in Postman.

<img src="https://raw.githubusercontent.com/ConsumerDataStandardsAustralia/dsb-schema-tools/master/images/Pm_Screen4.JPG?token=AETEGIINYZ5ZM634AFT6ZITBBH4Y4" width=600>

---

*The files DSB.collection-run.postman.json and DSB.postman_environment.json
are configured to work with the published data-holder server maintained by DSB and available in the ConsumerDataStandardsAustralia/java-artefacts repository.*
