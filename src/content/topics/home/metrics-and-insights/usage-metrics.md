---
title: "Account usage metrics"
excerpt: ""
---
## Overview
This topic explains how to understand the billing and usage metrics visualized in the Account Settings page. 

## Understanding limits on monthly active users
Your agreement with LaunchDarkly includes a limit of Monthly Active Users (MAUs). We understand that a company's user base can grow unexpectedly over time. We never stop or throttle service if you exceed your MAU, nor do we bill you for MAU overages. All users in your environment will continue to evaluate feature flags correctly, regardless of your MAU.

We do, however, limit the amount of user information that saves in your dashboard. When you exceed your MAU, new users and changes to existing users, such as new attributes, do not appear in the dashboard.
## Understanding billing metrics
Billing metrics are located under Account Settings > Billing.  These billing metrics show how many client and server-side monthly active users (MAUs) you’re tracking in LaunchDarkly, the number of projects and environments you have set up, and the number of seats you’re using under your plan. You can easily see your usage, and adjust your plan as you need to accommodate your application’s or organization’s growth.
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/a6af8b3-Billing_Usage_Metrics.png",
        "Billing Usage Metrics.png",
        2880,
        1500,
        "#dcdbda"
      ]
    }
  ]
}
[/block]

## Understanding usage metrics
Usage metrics are located under Account Settings > Usage.  These usage metrics tell you more about how your application and members of your organization are using LaunchDarkly. You can see how many LaunchDarkly seats, projects, and environments your organization is using. You can also see how many unique MAUs LaunchDarkly is tracking, broken out by browser and mobile MAUs. You can also see the number of server connections your application has with LaunchDarkly, and you can visualize that by hour, day, or over the past month to see trends.
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/c9cc762-Usage_Metrics.png",
        "Usage Metrics.png",
        2880,
        1500,
        "#dcdbda"
      ]
    }
  ]
}
[/block]
If you have Experimentation or Data Export enabled, you can see metrics related to that usage. For Experimentation, you can see the number of experimental events as well as the average over the last hour up to the last 60 days. For Data Export, you can see the number of events published along with the average—again, from a time period as short as one hour to as long as the last 60 days.


[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/65f7ec8-Experiments_Metrics.png",
        "Experiments Metrics.png",
        2880,
        1500,
        "#d3d1d1"
      ]
    }
  ]
}
[/block]