# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- My preference is to choose an App Service over a VM for this application:
- My reason is as follows:
    - i am not a web developer. as such, i can use a App Service to quickly and easily deploy an app.
    - App Service is a PaaS service and so transitions much of the responsibility over to the cloud provider. There i can simply focus on my app.
    - I don't have to worry about manually setting a web server when using an App Service.
    - I don't have to worry about high availability and scalability as that is built into an App Service considering that it is a PaaS service.
    - App Service also makes it very easy for me to inegrate my Git repo.
    - Generally speakig cost is cheaper on App Service as well. This could vary depending on the configuration. But especially in this case i was able to use the free tier for the App Service.
### Assess app changes that would change your decision.
- not all porgramming languages are supported on App Service. If my web app was built using one of those languages I would have to use a VM.
- if i need total control over the infrastructure that would require me to use a VM.