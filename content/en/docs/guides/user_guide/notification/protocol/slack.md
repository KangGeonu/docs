---
title: "Slack Protocol"
linkTitle: "Slack Protocol"
weight: 1
date: 2021-08-13
description: >
    Slack Protocol Service
---

# Create Slack Bot Alert Channel

## Overview

We can also add **`Slack`** to our list of `Notification` channels. There are few prerequisites to use Slack Bot on SpaceONE notification service, and the following will guide you to your **SpaceONE** notification journey with your **`Slack`** workspace. 
<br>

## Prerequisites
Install the Slack app on your phone or PC. You will need a **Slack App-Level Token** and **channel**. 
<br>

### How to get Slack App-Level API Token
Open the   `Slack App Directory` of your Slack workspace. 
`Slack Token` is generated by creating a `slack app` and a `bot user`. <br>
Slack App-Level token gives you the ability to handle things that relate to your app as a whole. To generate `Slack Access Token`, Follow the steps above: <br>
1. Visit [here](https://api.slack.com/apps) and create a new slack app. Fill out your App Name and select the development workspace where you'll play around and build your app.

2. `App-Level-Token` section shows the information of tokens which allow your slack app to use features that apply to SpaceONE notification events. Click `Generate Token and Scopes`. Copy the Token information in somewhere. <br>
![slack_generate_app_level_token.png](/docs/guides/user_guide/notification/notification_img/slack_generate_app_level_token.png) <br>
![slack_copy.png](/docs/content/en/docs/guides/user_guide/notification/notification_img/slack_copy_app_token.png)

<br>
3. Go to `Basic Information` section, you can install your app by click on `Install to Workspace` button.  

### How to generate Slack Bot users
Bot users are automated user accounts you can message with directly. You can eventually receive notification messages by inviting Bot User in your channel. 
<br>
1. Go back to your slack workspace console. 
2. Head to  `Manage apps` page by click on `your_workspace_name` on the top-left corner > `Administration` > `Manage apps`
3. On the `Bot User` section, generate the Bot User and give it a name!
4. Go back to your slack workspace console again, and invite the bot by following steps:
    - Go to the channel
    - Click the channel's name, go to `Integrations`, and click `Add apps`.
    - Find the apps we created right before, and add it.
    - Then, click `Add this app` button to a channel.

<br>
<br>

## Add Slack Channel to your Project / User in SpaceONE 
Go to `SpaceONE Console` > `Project` which you want to get alerts through Slack. 
<br>
![telegram_spaceone_console.png](/docs/guides/user_guide/notification/notification_img/telegram_spaceone_consol.png) <br>
<br>
Set information above.
<br>
![slack_add_info.png](/docs/guides/user_guide/notification/notification_img/slack_add_info.png)

Save and Test, now you are ready for SpaceONE Journey with Slack notification channel.


## Troubleshooting <br>


Visit [Slack Basic App Setup](https://api.slack.com/authentication/basics#installing) for an additional explains of new Slack app. 
<br><br>
`Happy SpaceONE-ing with Slack notification channel!`
