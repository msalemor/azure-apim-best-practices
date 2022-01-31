# Azure API Management

Best practices and recommendations for Azure API Management

## Definitions

- Gateway: the endpoint for incoming requests into APIM
- Portal: the place where customer can signup to access the different product and APIs
- Policies: XML code that can be applied to the request pipeline at different scopes (api, product, subscription) to modify, validate, extract data, etc.
- Product: collection of APIs

## Review the key concepts documentation

> https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts

## Understand the differences between external and internal modes

> https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-vnet?tabs=stv2

## Enable end-to-end encription with Application Gateway WAF mode to inspect incoming requests

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway

## Review your API Management SKU selection, SLAs, units, and request limits

> https://azure.microsoft.com/en-us/pricing/details/api-management/

## Use policies to do things like throttle and validate jwt tokens

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-policies

## Add external caching to improve performance

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-cache

## Monitor your API Management with Application Insights

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-app-insights#:~:text=Enable%20Application%20Insights%20logging%20for%20your%20API%20,all%20failure%20...%20%209%20more%20rows%20

## Use the DevOPs tools to deploy your APIs

> https://github.com/Azure/azure-api-management-devops-resource-kit

