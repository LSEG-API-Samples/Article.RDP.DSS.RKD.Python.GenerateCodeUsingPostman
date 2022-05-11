# Generate code for a REST API call using Postman in a few clicks (with Refinitiv Knowledge Direct API (RKD API))
Have you ever had to implement a request for an API call in any programming language? If so and in case you haven’t heard about this, the Postman application can convert an API request into a code snippet in a programming language in just a few clicks.

## Required Python libraries
- **requests** must be installed before the code execution
- **JSON** doesn’t need to be installed as it’s the standard Python package that comes with the Python installation)

## What is Refinitiv Knowledge Direct API (RKD API)?
The Knowledge Direct API offers a wide range of Refinitiv information and services delivered in a request-response scenario via web services using today’s industry standard protocols (SOAP and XML). Connectivity can be via HTTP and HTTPS, over the Internet or Delivery Direct.
Knowledge Direct for Wealth Management offers access to Refinitiv hosted content and capabilities. It integrates into your own advisor solutions, customer facing investment portals, online trading platforms and provides data through a powerful and uniform suite of APIs, eliminating the need for investment at your site. Knowledge Direct for Wealth Management enables your advisors and customers to make better financial decisions, by providing access to market moving and insightful news, company information and financial markets.

## Let’s start discovering RKD API using its Support Portal
Prior to running examples, it is recommended to review the available content offered by the RKD API services.
RKD API’s [Support Portal](https://support-portal.rkd.refinitiv.com/SupportSite/Home/UserHome) is a basic implementation of the overall RKD API functionalities in a simple and intuitive interface. This tool enables developers to make RKD API service calls and check the returned results.
The Support Portal requires an RKD API user account for access.
![rkd-00](https://user-images.githubusercontent.com/89068039/167948028-1c469356-8c1c-458e-b519-f3cf5f693639.png)

## Conclusion
To implement a request for an API call as a code, other than the developer needs to write the code and test each change in the payload, the Postman application can be used to test an API call and generate the code for the call in any programming language you’d like with just a few clicks.
Do you think this is convenient and a very useful function? Feel free to leave a comment for any discussion regarding this article or any Refinitiv API. I’d be more than happy to discuss with you.

## Reference
- [Postman](https://www.postman.com/)
    - [Generate Code Snippets](https://learning.postman.com/docs/sending-requests/generate-code-snippets/)
- [Refinitiv Knowledge Direct API (RKD API)](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api)
    - [Quick Start Guide](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/quick-start)
    - [Documentation](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/documentation)
    - [Development Guide](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/documentation#development-guide)
