---
title: "Deprecating GitHub Notification Endpoint, Migrating to Webhooks"
url: "https://blog.pushover.net/posts/2026/6/github"
date: "2026-06-23"
author: "joshua stein"
feed_url: "https://blog.pushover.net/rss"
---
In 2018 we introduced a custom GitHub API endpoint to receive webhook payloads and convert them to notifications. Earlier this year we introduced full webhook support which enables extracting custom data, allowing you to listen to more GitHub event types and customizing notifications. In light of this, we are deprecating Pushover’s custom GitHub API endpoint and encouraging all users to migrate to this new webhook mechanism.
