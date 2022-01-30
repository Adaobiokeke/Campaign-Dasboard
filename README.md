### Campaign-Dasboard

### Project Description

The campaign dashboard is a dashboard that fetches campaigns, lists their ids and names from an endpoint:localhost:4000/campaigns.
Clicking either the id or the name takes to the dashboard for the campaign.

## Project Features

-The Dashboard pings the server every 5 second to get a new data for a given id clicked on the table.

-The Dashboard has a counter tab that increments every 5 seceonds as it pings the server(keeps count of iteration/pull).

-The Dashboard displays other tiles for the diferent data it fetches every 5 seconds.

-The Most recent Clicks are generated from the Endpoint.

-The Most recent Users are generated from the Endpoint.

-The Most recent Clicks are generated from the Endpoint.

-The Most recent Click-Through-Rate(CTR) is calculated by : ((Total Clicks/Total Impression) * 100).

-The Total Clicks are calculated by adding initial clicks to most recent clicks and it keeps accumulating.

-The Total users are calculated by adding initial users to most recent users and it keeps accumulating.

-The Total impressions are callculated by adding initial impressions to most recent impressions and it keeps accumulating.

-The Total CTR is calculated by adding initial CTR to most recent CTR and it keeps accumulating.
