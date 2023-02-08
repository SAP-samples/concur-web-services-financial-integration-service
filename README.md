# SAP-samples/repository-template
This default template for SAP Samples repositories includes files for README, LICENSE, and .reuse/dep5. All repositories on github.com/SAP-samples will be created based on this template.

# Containing Files

1. The LICENSE file:
In most cases, the license for SAP sample projects is `Apache 2.0`.

2. The .reuse/dep5 file: 
The [Reuse Tool](https://reuse.software/) must be used for your samples project. You can find the .reuse/dep5 in the project initial. Please replace the parts inside the single angle quotation marks < > by the specific information for your repository.

3. The README.md file (this file):
Please edit this file as it is the primary description file for your project. You can find some placeholder titles for sections below.

# SAP Concur Client Web Services - Financial Integration Service
<!-- Please include descriptive title -->

<!--- Register repository https://api.reuse.software/register, then add REUSE badge:
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/REPO-NAME)](https://api.reuse.software/info/github.com/SAP-samples/REPO-NAME)
-->

## Description
<!-- Please include SEO-friendly description -->
This repository provides the basic example of Financial Integration Service APIs used by SAP Concur customers. The calls within the collection demonstrate 
the following process steps: 
•	Get Financial Transactions
•	Acknowledge each Financial Transaction
•	Confirm each Financial Transaction posted (success or fail)
•	Mark each Financial Transaction as paid (optional but recommended)

## Requirements
In order to use this repository you will need
1) The Web Service Administration role within SAP Concur (to be able to create SAP Concur applications)
2) Postman (to be able to use the files included in this repository)
3) Have downloaded / installed the Authentication Postman collection [found here](https://github.com/SAP-samples/concur-web-services-authentication).

## Known Issues
No known issues.

## How to obtain support
This project is provided "as-is", with no expected changes or support.
The complete Financial Integration Service documentation [can be found here](https://developer.concur.com/api-reference/financial-integration/v4.financial-integration.html).

For additional information, please [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing
This repository is provided "as-is".

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
