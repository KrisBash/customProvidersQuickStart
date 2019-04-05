# Microsoft.CustomProviders QuickStart contents

# Microsoft.CustomProviders overview

## Basic code examples
Example Azure Functions handler apps can be found in `/examples`, categorized by language. These are basic code skeletons that implement the required API contracts and authorization, but do not perform actual extensibily operations.

## Custom Providers
Functional examples of custom providers that facilitate extensibility scenarios can be found in `/providers`. These contain Azure Functions handler apps and ARM templates that demonstrate their use. 

#Azure Functions tools
- VS Code and Functions extension
- Azure Functions Core Tools

#### Configuring logging
In Azure Functions, logging settings are defined in host.json. To enable informational logs for all Functions, the following config can be used:
`{
  "version": "2.0",
  "logging": {
    "fileLoggingMode": "always",
    "logLevel": {
      "default": "Information"
    }
   }
}`

### Contributing


This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct](https://opensource.microsoft.com/codeofconduct/faq/) FAQ or contact opencode@microsoft.com with any additional questions or comments.This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.