# Quick Start Guide

Verto API v2.1 supports four main functional areas which are:

![image](https://content.pstmn.io/09df96fc-c453-4a8b-a19b-a535fa2cce16/TWFpbiBTZXJ2aWNlcy5qcGc=)

Using the functions independently or together, you can automate many business use cases. The following diagram illustrates the standard FX and Payment flow which also gives a quick overview of a typical business case.

![image2](https://content.pstmn.io/297125f1-dae9-4cd3-b2f2-24d6a4a3664d/U3VtbWFyeSBGbG93IEhpZ2ggUXVhbGl0eS5qcGc=)

After the successful authentication to Verto API service (1), you can benefit from the following services:

- Check your wallet and balance information (2)
- Check the exchange rate (3)
- Exchange funds (4)
- Create and update Beneficiaries (5)
- Create payments (6)

You can also check the status of exchange and payment transactions using “Get Order Details” and “Get Payment Details” services. You can find the details of these individual services in the following sections.

Please note that you first need to authenticate to the API service by providing an API token in the request. You can get your API token using the AUTHORIZATION service specified below. This service requires you to send your Client ID & API Key which can be found on your Verto account profile. In response you’ll be provided with a token that will be valid for 60 minutes. Simply add this token as header parameter to every request. Your Client ID & API Key set enables you to access many privileges, so be sure to keep them secret!
