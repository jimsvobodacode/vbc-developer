---
title: Provision the service
description: Link your Nexmo Voice API Application and configure one or more VBC numbers.
navigation_weight: 3
---

Once you have enabled the Smart Numbers add-on in your VBC account and created a Nexmo Voice API Application, you are ready to provision the Smart Numbers service. This involves selecting which numbers to use and associating them with your Nexmo Voice API Application.

1. Sign into [the VBC Admin Portal](https://admin.vonage.com)

2. In the left-hand navigation menu, select the **Business Apps > Smart Numbers** menu option.

    > **Note**: If you do not see the **Smart Numbers** menu option, you must [enable the add-on](/smart-numbers/guides/enable-addon).

3. Each row in the table refers to a Smart Number. Click one of your unconfigured Smart Numbers to edit it.

4. On the **Edit Smart Numbers Service** page:
  1. Enter a name for the service.
  2. Select at least one direct dial number that you will call to access the Nexmo Voice API application.
  3. Paste in your Nexmo Voice API `application_id`.
  4. Ensure that the **Smart Number Status switch** is set to **Active**.
  5. Click the **Save** button.

  ![Edit your Smart Number](/assets/images/vbc/edit-smart-number.png)

> You have now provisioned the Smart Numbers service and are ready to begin developing your application. See this [list of resources](/smart-numbers/guides/vbc-resources) to get started.
