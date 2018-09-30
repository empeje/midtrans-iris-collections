# Midtrans - Iris (Disbursement Service) API Postman Collections
[![Docs](https://img.shields.io/badge/midtrans-docs-blue.svg)][IRIS_DOCS]

Iris ❤ Postman!

## Description

This repository contains [Postman](https://www.getpostman.com) collection for various payment API call to [Midtrans][MIDTRANS_SITE] Iris (Disbursement Service) API.

API covered:
* [Iris](https://iris-docs.midtrans.com/#overview)

## Usage Instruction

* Clone the repo

```bash
git clone https://github.com/empeje/midtrans-iris-collections.git
```

* Export the Postman's collection files
* Export the Postman's environment files
* Get your sandbox environment credentials from Midtrans' support team [here][MIDTRANS_SUPPORT].
* Fill the acquired credentials in the environment files.
* Set the Postman active environment to the one that you just filled.
* Try out some APIs

### Automation

We embed some post action via Postman Test in order to add some automation. For example after you call the create beneficiary API we save the `alias_name` to be reused in update beneficiary API, so that it is easy for you to just try the APIs. Open the Postman console for more detail, because we log some output there.

### Environment Variables

We have the following environment variables and we set some default values to each environment

```text
BASE_URL
CREATOR_KEY
APPROVER_KEY
CREATOR_KEY_FACIL
APPROVER_KEY_FACIL
```

## Troubleshooting

WIP. In the meantime please raise an issue [here][ISSUES_LINK] for any issues.

## Changelog

### 30/09/2018
- Collection created.

## Get Help

* [Midtrans][MIDTRANS_SITE]
* [Iris Documentation][IRIS_DOCS]
* Can't find answer you looking for? email to [support@midtrans.com][MIDTRANS_SUPPORT]

[IRIS_DOCS]: https://iris-docs.midtrans.com/#overview
[MIDTRANS_SITE]: https://midtrans.com
[MIDTRANS_SUPPORT]: mailto:support@midtrans.com
[ISSUES_LINK]: https://github.com/empeje/midtrans-iris-collections/issues

