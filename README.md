# Azure API Management

Best practices and recommendations for Azure API Management

## Overview

Azure API Management is a hybrid, multicloud management platform for APIs across all environments. This article provides an overview of common scenarios and key components of API Management.

https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts

## Definitions

- Gateway: the APIM endpoint for incoming requests
- Backend: the backend API
- Portal: the place where customer can signup to access the different product and APIs
- Policies: XML code that can be applied to the request pipeline at different scopes (api, product, subscription) to modify, validate, extract data, etc.
- ```<Base>```: withing the scope XML, this indicates scope inheritance. In other words, execute the scoppe policiy before
- Product: collection of APIs

## Service Concerns

API Management is a product requiring many concerns to be accounted for:
  
- Networking: internal vs external deployment, end-to-end encryption, DNS, etc.
- API Management: API definitions, Polcies, Subscritpions, Producs, etc.
- Developer Portal: custominazation, access, etc.
- Monetization: Rest calls to get API usage information
- Development: API Development, Swagger, OpenAPI specs, etc.
- DevOps/GitOps: ARM, Bicep, Terraform
- Monitoring: ApplicationInsights and Log Analytics
- Governance: RBAC, policies, locks, cost, and monitoring

## Key concepts

> https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts

## Networking

### External and internal modes

> https://docs.microsoft.com/en-us/azure/api-management/api-management-using-with-vnet?tabs=stv2

## End-to-end encryption

Enable end-to-end encription with Application Gateway WAF mode to inspect incoming requests.

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-integrate-internal-vnet-appgateway

## Service Limits (SKU selection, SLAs, units, and request limits):

**Note:** API has request limits, selecting the right size and SKU is very important for a successful deploment.
  
> https://azure.microsoft.com/en-us/pricing/details/api-management/
  
## Policies
  
Use policies to do things like throttle and validate jwt tokens.

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-policies

## Caching
  
Add external caching to improve performance.

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-cache

## Monitoring
  
Monitor your API Management with Application Insights.

> https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-app-insights#:~:text=Enable%20Application%20Insights%20logging%20for%20your%20API%20,all%20failure%20...%20%209%20more%20rows%20

## DevOps

### API Management GitOps

> https://github.com/Azure/apiops

### Use the DevOPs tools to deploy your APIs

> https://github.com/Azure/azure-api-management-devops-resource-kit

## Authetication with API Management (Video)

> https://www.youtube.com/watch?v=jgPAWJMB4ME
