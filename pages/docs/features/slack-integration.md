# Slack Integration

## Overview

Connect Mixpanel to your Slack workspace to help share reports with your colleagues faster. You can (1) set up an alert to send a message to a Slack channel, (2) set up a Board Subscription to send a message to a Slack channel, or (3) share previews of any Mixpanel report in Slack.

To send an alert to a Slack Channel, see [Custom Alerts](/docs/features/alerts). To set up a board subscription to a Slack Channel, see [Advanced Board Functionality - Subscriptions](/docs/boards/advanced#board-subscriptions).

The Mixpanel application for Slack will also automatically unfurl a preview of any Mixpanel link, including chart images for certain reports, making it easy for anyone in your Slack workspace to learn from your Mixpanel analyses.

## Enable the Integration

To enable the integration, log in to both Mixpanel and Slack, then click [here](https://mixpanel.com/slack/oauth?slack_v2=true) to authorize the slack workspace:

![/Screen_Shot_2020-06-15_at_10.41.00_PM.png](/Screen_Shot_2020-06-15_at_10.41.00_PM.png)

After clicking allow, you'll return to Mixpanel, where you'll see a success banner:

![/Screen_Shot_2020-06-15_at_10.42.06_PM.png](/Screen_Shot_2020-06-15_at_10.42.06_PM.png)

At this point, Mixpanel is a part of your Slack workspace, and any Mixpanel links you send in Slack will unfurl with metadata, and if applicable a chart preview.

Once at least one member of your Mixpanel organization has set up the Mixpanel Integration for Slack for their account, any other members of the Slack workspace will see a prompt the next time they paste a Mixpanel link. The prompt will ask them to connect their own Mixpanel account to Slack as well. If they choose to do so, Slack will guide them through the authentication flow. Once they have successfully connected Mixpanel to Slack, any further links they paste in Slack will unfurl.

## Using the Integration

Once you've set up the integration, Mixpanel links pasted in Slack will unfurl. Most links will provide some basic link metadata, and links to Insights, Flows, Funnels, or Retention reports will also include a chart preview, for example:

![/slack_app_demo.png](/slack_app_demo.png)

## Slack Integration Permissions

Mixpanel does not restrict who can enable the Mixpanel integration for Slack. However, your Slack workspace may limit who can perform the connection.

After Mixpanel is connected to Slack, any Slack user who posts a Mixpanel link will be prompted to connect their own account, in order to unfurl report previews. By performing this integration at the user level, it ensures that only reports the user has access to will unfurl in Slack.

## Slack Integration Privacy

The Mixpanel app for Slack adheres to Mixpanel's overall privacy policy, available in full here: [https://mixpanel.com/legal/privacy-policy/](https://mixpanel.com/legal/privacy-policy/).