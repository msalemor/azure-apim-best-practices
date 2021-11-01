# Azure API Management

Best practices and recommendations for Azure API Management

## Understand the difference between external and internal mode

- Internal mode: fronts a private IP and allows connectivity to internal and external APIs
- External mode: fronts a public IP and allows connectivity to internal and external APIs

> https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-vnet?tabs=stv2

## Enabled end-to-end encription with Application Gateway WAF mode to inspect incoming requests

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway

## Review your API Management selection, SLA and request limits

> https://azure.microsoft.com/en-us/pricing/details/api-management/

## Use Policies policies to do things like throttle and validate jwt tokens

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-policies

## Add external caching to improve performance

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-cache

## Monitor API Management with Application Insights

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-app-insights#:~:text=Enable%20Application%20Insights%20logging%20for%20your%20API%20,all%20failure%20...%20%209%20more%20rows%20

## Use the DevOPs tools to deploy your APIs

> https://github.com/Azure/azure-api-management-devops-resource-kit

