# Exercise 5 - Enable SaaS and Deploy the Project
## Enable SaaS

### Make Application Multitenant
We will now make our application multitenant.

In order to make our application multitenant we need to click on the 'Guide Center' icon shown in the below Screenshot. Expand the options once on that page. Click 'Enable SaaS in your Application'.

![Picture](./images/1.png)

Expand 'Enable SaaS' option. Click on 'Enable SaaS' button.

![Picture](./images/2.png)

Another page will open with more information on SaaS. Click 'Enable SaaS' there too. 

![Picture](./images/3.png)

A dialog will open up. Click 'Enable SaaS' again. Keep in mind that enabling SaaS here is an irreversible change.

![Picture](./images/4.png)

Now when you click on the 'Project Explorer' icon, it will show 'SaaS' beside your app name.

![Picture](./images/5.png)

### Deploy App

Make sure to remember to have HANA Cloud running in your Cloud Foundry before starting the deployment.

Now type 'cf login' in the terminal and put your API Endpoint and username and password to login to Cloud Foundry so that you can deploy your app.

![Picture](./images/6.png)

Click on the 3 dots to the right of the Project and click 'Deploy Project'. It will start the deployment process by first building the application and then deploying it.

![Picture](./images/7.png)

### Check the deployed app in BTP Cockpit

After the process has completed in the terminal, you can check the deployment by going to your BTP account. Navigate to the space you had deployed the app in. You will be able to see your application in the 'Applications' tab.

![Picture](./images/8.png)

## Summary

You have now deployed your app as a multitenant app. We will now make some configurations and subscribe to the app as a tenant.

Continue to - [Exercise 6 - Subscribe to your Multitenant App](../ex6/README.md)