---
area: restApi
level: 0
title: REST API
redirect_from: "/"

sections:
  general: 
    title: General Information
    anchor: gi
    secs:
     addresses: 
        title: Addresses
        anchor: gi-addresses
     formats: 
        title: Formats
        anchor: gi-formats
     security: 
        title: Security
        anchor: gi-security
     parameter: 
        title: Url Parameter
        anchor: gi-parameter
     codes: 
        title: Status Codes
        anchor: gi-codes
     response: 
        title: Response
        anchor: gi-response
  dataservice:
    title: Data Service
    anchor: ds
    secs:
      serviceInformation: 
        title: Service Information
        anchor: ds-service-information
      configuration: 
        title: Configuration
        anchor: ds-configuration
      catalogs: 
        title: Catalogs
        anchor: ds-catalogs
      inspectionPlan: 
        title: Inspection Plan
        anchor: ds-inspection-plan
      measurementsAndValues: 
        title: Measurements And Values
        anchor: ds-measurements-and-values
---
<h1 id="{{page.sections['general'].anchor}}">{{page.sections['general'].title}}</h1>

{% include_relative 011-general.md %}

<h1 id="{{page.sections['dataservice'].anchor}}">{{page.sections['dataservice'].title}}</h1>

{% include_relative 012-dataservice.md %}
