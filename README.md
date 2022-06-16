# Azure API Management

Best practices and recommendations for Azure API Management

## Overview

Azure API Management is a hybrid, multicloud management platform for APIs across all environments. This article provides an overview of common scenarios and key components of API Management.

https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts

## API Management - Concerns

API Management is a product where many concerns need to be accounted for including

- Networking: internal vs external deployment, end-to-end encryption, DNS, etc.
- API Management: API definitions, Polcies, Subscritpions, Producs, etc.
- Developer Portal: custominazation, access, etc.
- Monetization: Rest calls to get API usage information
- Development: API Development, Swagger, OpenAPI specs, etc.
- DevOps/GitOps: ARM, Bicep, Terraform
- Monitoring: ApplicationInsights and Log Analytics

## Definitions

- Gateway: the endpoint for incoming requests into APIM
- Portal: the place where customer can signup to access the different product and APIs
- Policies: XML code that can be applied to the request pipeline at different scopes (api, product, subscription) to modify, validate, extract data, etc.
- Product: collection of APIs

## Service Concerns

- Infrastructure: Internal vs External, end-to-end encryption vs SSL offloading, DNS for internal services, etc.
- Administration: Manage users, products, apis, policies at different scopes
- Devlopemnt of APIs: Swagger
- DevOps: DevOps
- Governance: RBAC, policies, locks, cost, and monitoring

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

## DevOps

### API Management GitOps

> https://github.com/Azure/apiops

### Use the DevOPs tools to deploy your APIs

> https://github.com/Azure/azure-api-management-devops-resource-kit

## Authetication with API Management (Video)

> https://www.youtube.com/watch?v=jgPAWJMB4ME
