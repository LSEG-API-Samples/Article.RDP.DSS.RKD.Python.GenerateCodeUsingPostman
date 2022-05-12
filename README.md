# Generate code for a REST API call using Postman in just a few clicks
Have you ever had to implement a request for an API call in any programming language? If so and in case you haven’t heard about this, the Postman application can convert an API request into a code snippet in a programming language in just a few clicks.

## Required Python libraries
- **requests** must be installed before the code execution
- **JSON** doesn’t need to be installed as it’s the standard Python package that comes with the Python installation)

## What's the problem?

Let's say I have the postman collection with the API request that's working properly and I want my application to call it, hence, I need to convert this API call into a code for an application, what do I need to do?
The answer is I need to Find the proper library for calling a REST API in the programming language that I'm using, then learn how to use it and try implementing, testing, and fixing issues in the code if there are any.

## What if there's an easier way to do so?
I bet you already knew the tool named Postman, which is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs — faster. Plus, Postman can convert an API request into a code snippet in the programming language or framework of your choosing. You can use this generated code snippet in your front-end applications.

## This can be done in a few clicks as the GIF below
![gif-postman-dss](https://user-images.githubusercontent.com/89068039/168149913-ce15a3ee-9454-413b-a698-3fbad22327fe.gif)
1. In the Postman app of the request, click on the Code button on the toolbar at the right of the screen
2. The 'Code snippet' tab will be shown
3. Click on the dropdown to select the programming language you prefer
4. Type to search for the language, here we're using Python with Requests Library
5. Now the Python code for this API call is generated, click the 'Copy snippet' button to copy the code into the clipboard

## Conclusion
To implement a request for an API call as a code, other than the developer needs to write the code and test each change in the payload, the Postman application can be used to test an API call and generate the code for the call in any programming language you’d like with just a few clicks.
Do you think this is convenient and a very useful function? Feel free to leave a comment for any discussion regarding this article or any Refinitiv API usage in the [Developer Community (Q&A Forum)](https://community.developers.refinitiv.com/index.html). I’d be more than happy to discuss it with you.
   
## Reference
- [Postman](https://www.postman.com/)
    - [Generate Code Snippets](https://learning.postman.com/docs/sending-requests/generate-code-snippets/)
- [Refinitiv Data Platform APIs](https://developers.refinitiv.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis)
    - [Quickstart guide for Refinitiv Data Platform](https://developers.refinitiv.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/quick-start)
    - [RDP Postman Starter Collection and Tutorial Samples](https://developers.refinitiv.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/download)
    - [RDP Postman Tutorials](https://developers.refinitiv.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/tutorials)
    - [RDP API Q&A Forum - RDP API and I would like to use it through Postman](https://community.developers.refinitiv.com/questions/88325/rdp-api-and-i-would-like-to-use-it-through-postman.html)
- [Refinitiv DataScope Select - REST API (DSS API)](https://developers.refinitiv.com/en/api-catalog/datascope-select/datascope-select-rest-api)
    - [Quickstart guide for DSS API](https://developers.refinitiv.com/en/api-catalog/datascope-select/datascope-select-rest-api/quick-start)
    - [DSS API Documentation](https://developers.refinitiv.com/en/api-catalog/datascope-select/datascope-select-rest-api/documentation)
    - [DSS REST Tutorials Postman collection](https://developers.refinitiv.com/en/api-catalog/datascope-select/datascope-select-rest-api/download)
- [Refinitiv Knowledge Direct API (RKD API)](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api)
    - [Quick Start Guide](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/quick-start)
    - [Documentation](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/documentation)
    - [Development Guide](https://developers.refinitiv.com/en/api-catalog/refinitiv-knowledge-direct/refinitiv-knowledge-direct-api-rkd-api/documentation#development-guide)
