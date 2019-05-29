---
layout: post
title: "Twitter Monitor"
date: 2019-05-28
excerpt: "A lightweight, silky smooth Twitter monitor."
project: true
tag:
- discord
- supreme
- aio
- development
- nodejs
- node
- javascript
- typescript
- twitter monitor
- twitter api
comments: true
---

### About
Sycer's **Twitter Monitor** creates a websocket-connection with Twitter's API to stream tweets from specified users. Once we recieve that tweet packet, it is processed and sent to all our clients.
What makes Sycer differnt from our competitors is our seamless transition from recieve the tweet packet to processing it within Discord's API. Within a mere 3 seconds after a tweet is posted, we process 
that packet within milliseconds and send them on your webhooks.

### Feature List
* posts on webhook
* custom list of accounts (up to 100)
* option to filter out replies & retweets
* option to enable OCR (capture text from images) (slower)
* branding: footer text, footer icon and color
* 3-5 second delay from tweet => send

### Images
{% capture images %}
	https://i.imgur.com/agyMH0X.png
	https://i.imgur.com/7t8b3gn.png
	https://i.imgur.com/gbsAKVl.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of Twitter Monitor" cols=3 %}

---

{% capture images %}
	https://i.imgur.com/ScxUj2w.png
	https://i.imgur.com/p9qCf0Q.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of Twitter Monitor" cols=2 %} 

### Pricing
$15 per month
$40 lifetime

### Other
Would you like a live demo? Come join my [Discord Server](https://discord.gg/Agg6yFV)


