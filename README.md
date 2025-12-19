What are Azure App Service plans?
An Azure App Service plan defines a set of compute resources for a web app to run. An app service always runs in an App Service plan. Azure Functions also has the option of running in an App Service plan.

When you create an App Service plan in a certain region, you create a set of compute resources for that plan in that region. Whatever apps you put into the App Service plan run on those compute resources, as defined in the plan.

 Important

Managed Instance is in preview, available for Windows web apps in select regions, and limited to Pv4 and Pmv4 pricing plans. More regions to follow. Linux and containers aren't supported.

Each App Service plan defines:

Operating system (Windows, Linux)
Region (West US, East US, and so on)
Number of virtual machine (VM) instances
Size of VM instances (small, medium, large)
Pricing tier (Free, Shared, Basic, Standard, Premium, PremiumV2, PremiumV3, PremiumV4 IsolatedV2)
