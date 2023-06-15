# Introduction

<p>Notifications are an essential component of ROQ SaaS application as they allow users to receive important updates and stay informed about relevant events. In this guide, we will walk you through the process of adding a new notification to your SaaS application using ROQ Console and the GraphQL API. Please ensure that you have access to the <a href="https://console.roq.tech/">ROQ Console</a> and have created a <a href="https://app.roq.ai/">SaaS application</a> before proceeding with this documentation.</p>

## Creating a Notification Template

--> can add screenshot of the notification page from the console

<p>To add a new notification, you need to create a notification template in the ROQ Console. Follow these steps:</p>

- Login to the ROQ Console using your credentials.
- Navigate to the &quot;Notification Templates&quot; section.
- Click on the &quot;Create New Template&quot; button.
- Provide a name for your notification template.
- Specify the content and format of the notification using the available options, such as text, HTML, or a predefined template.
- Save the notification template.

## Configuring an Integration (Email Channel)

--> can add screenshot of email settings from the console notification tab

<p>If you intend to use the email channel for sending notifications, you need to configure the integration. Follow these steps:</p>

- Ensure that you have access to an email delivery service provider, such as Sendgrid.
- In the ROQ Console, go to the &quot;Integrations&quot; section.
- Locate the integration options and select the email delivery service provider you wish to use (e.g., Sendgrid).
- Provide the necessary configuration details, such as API key, SMTP settings, or any other required information.
- Save the integration settings.


## Triggering the Notification via GraphQL API

<p>Once you have created the notification template and configured the integration (if required), you can trigger the notification using the GraphQL API. Follow these steps:</p>

- Access the GraphQL API endpoint for your SaaS application.
- Use the appropriate GraphQL mutation to trigger the notification. Consult the API documentation for the specific mutation and its input parameters.
- Provide the necessary input parameters, such as recipient email address, notification template ID, and any dynamic content if applicable.
- Execute the mutation to trigger the notification.

--> can show the graphQL mutation code here as an example

## Video tutorial
To assist you further in understanding the process of adding a new notification, we have created a video tutorial. Please watch the tutorial using the following link: <a href="https://www.loom.com/share/3ed6ee07435945e0a23d2aff0cb1ef6c">Notification Tutorial Video</a>
  
--> can embed the actual video here rather then using link
