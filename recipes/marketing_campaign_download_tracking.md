---
type: recipe
title: Marketing Campaign Download Tracking
platforms:
- ios
- android
---

# Marketing Campaign Download Tracking

------

When you complete this guide, you will have the ability to run powerful marketing campaigns with download tracking. You will know how many installs are being driven by word of mouth versus ad campaigns, and how well Facebook does compared to Twitter and SMS. You can do analysis comparing your marketing links to individualized links shared by your users.

One screenshot is worth a million... dollars on spent on non-performant ads and expensive tools to track those ads:

![the goal](/img/ingredients/analytics_and_custom_events/dashboard_summary.png)

Let's get started. Seeing install numbers (as opposed to merely clicks) requires doing some setup both on the Dashboard and within your {{page.platform_formatted}} app.

## Configuring the Dashboard for your {{ page.platform_formatted }} app
{% ingredient dashboard_setup/app_name %}{% endingredient %}
{% ingredient dashboard_setup/web_url %}{% endingredient %}
{% ingredient dashboard_setup/store_or_custom_url %}{% endingredient %}
{% ingredient dashboard_setup/uri_scheme %}{% endingredient %}
<!--- /Configuring the Dashboard-->


## Configuring your {{ page.platform_formatted }} app
{% ingredient sdk_setup/installing_the_sdk %}{% endingredient %}
{% ingredient sdk_setup/branch_key %}{% endingredient %}
{% ingredient sdk_setup/uri_scheme %}{% endingredient %}
{% ingredient sdk_setup/init_session %}{% endingredient %}
{% ingredient sdk_setup/handle_deep_link %}{% endingredient %}
<!--- /Configuring the Client-->


## Creating your Link

{% ingredient dashboard_links/creating_links %}
	{%override screenshot_description%}One example description if you want to treat this guide is: "Marketing our launch on Facebook."{%endoverride%}
{% endingredient %}

{% ingredient dashboard_links/tags %}{% endingredient %}

{% ingredient dashboard_links/alias %}
	{%override optional%}(Optional -- highly recommended){%endoverride%}
{% endingredient %}

{% ingredient dashboard_links/og_tags %}{% endingredient %}
{% ingredient dashboard_links/end %}{% endingredient %}
<!--- /Creating your Link -->


## Conclusion and Advanced Options

That's it! You now have *campaign- and channel-specific links* that can be shared on social media, pushed out via email, or embedded in ad campaigns. 

Every *user click*, every *fresh install*, and every *subsequent open* can be attributed back to an individual link. 

If you go the additional step of allowing users to share via Branch links, you can compare your campaigns to word-of-mouth. If this interests you, check out our guides on the following topics:

* [Incentivized Referral Program](/recipes/incentivized_referral_program/{{page.platform}}/)
* [Personalized Invite System](/recipes/personalized_invite_system/{{page.platform}}/)
* [App Content Share with Deeplink](/recipes/app_content_share_with_deeplink/{{page.platform}}/)

And as always, please email us at [contact@branchmetrics.io](mailto:contact@branchmetrics.io) if you have any questions!