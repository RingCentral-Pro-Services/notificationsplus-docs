# Quick Start

[Notifications+](https://notificationsplus.ps.ringcentral.com) allows you to configure notifications for inbound and outbound call events on your [RingCentral®](https://ringcentral.com) account. Notifications are customizable and delivered in real-time via SMS, email, webhook or [Glip®](https://app.ringcentral.com). A summary of available features includes:

* **Alerts when sensitive or inappropriate numbers are called** from your account, including who placed the call.
* **Know who called for help and where they are** in the event of an emergency.
*  **Customizable** notification triggers, message content and delivery options.
* **Bulk orchestration** of notifications and settings.
* **Simulation mode** to test notifications without needing to actually trigger them.

For full documentation visit the [user guide](https://www.???.com/guide).

## Requirements

Chrome or Firefox web browser and a [RingCentral®](https://ringcentral.com) account.

## Logging In

Log in to [Notifications+](https://notificationsplus.ps.ringcentral.com) using your  [RingCentral®](https://ringcentral.com) credentials at the following URL:

> [https://notificationsplus.ps.ringcentral.com](https://notificationsplus.ps.ringcentral.com)

New accounts automatically receive a **free 14-day trial period** upon first login. After the trial period expires, *you must contact your Account Executive or Sales Representative to purchase a subscription* for your account.

## Building Your First Notification

After logging in you are presented with the notifications screen. This is where all notifications and their settings are managed. A default **911 Notification** has already been populated for you. If turned on, this default notification will alert you if any user on your RingCentral® account calls 911.

To get started, we'll walkthrough setting up and using an example notification together.  This notification will alert us if any user on our RingCentral® account places a call to +18885287464 (the RingCentral® support phone number):

1. First, click the **+New Notification** button to begin configuring a new notification. Give the new notification a friendly name, this example will use **RingCentral Support**.

2. Next, provide the phone number that, when called from your RingCentral® account, will trigger this notification. In this example it's **+18885287464**.

3. Set the call direction that will trigger this notification. In this example, we only want to know if a user from our account makes a call **to** +18885287464, so select **Outbound**.

4. Now decide which call objects can trigger this notification (e.g. what users/extensions or sites will trigger this notification when calling +18885287464). For this example, **accept the "all users" default and click Next**. This means that when any user on your account calls +18885287464, a notification will be triggered.

5. Select the delivery method(s) used to receive the notifications and define the content of the notification's message. The delivery methods are: SMS, email, webhook or [Glip®](https://app.ringcentral.com). For this example, let's try SMS. **Enter the phone number(s) you'd like to use to receive the notifications** (e.g. your phone number) into the SMS field. Separate multiple numbers with commas.

6. Lastly, define the content of the notification's message. This is the text you will see when receiving the notification. Click into the text area and type the words **RingCentral support called on:**, then click on the **Timestamp** variable to the right. The timestamp variable embeds the actual event's date/time into the notification's message content. Go ahead and add the remaining variables so you can observe their behavior while testing the notification.

7. When you are finished, click **Next** to confirm and then click **Create** to create the new notification.

8. Let's test it! From the notifications home screen, click the checkbox next to your new notification then click **Simulate**. You should receive an SMS shortly containing the notification. You can use the simulate feature to test any notification you have configured without actually triggering the notification.
