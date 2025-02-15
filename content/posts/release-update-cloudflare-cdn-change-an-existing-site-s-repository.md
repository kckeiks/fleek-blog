---
template: post
draft: false
title: Release Update - Cloudflare CDN, & Change an Existing Site’s Repository
slug: release-update-cloudflare-cdn-change-repository
date: 2021-08-24T04:00:00Z
socialImage: https://storageapi2.fleek.co/fleek-team-bucket/blog/Cloudflare-UpdateRepo/Cloudflare-NewRepo.png
canonical: ''
description: 'We''ve added the ability to use Cloudflare as your CDN option. You can
  now also change the base repository for any of your hosted sites.  '
category: Announcement
tags:
- Release
- GitHub
- CDN
- Cloudflare

---
![](https://storageapi2.fleek.co/fleek-team-bucket/blog/Cloudflare-UpdateRepo/Cloudflare-NewRepo.png)

We just made some exciting enhancements to our Fleek.co platform that we wanted to share ⚡️ As always, user’s input drives the features we release. Keep on requesting so that we can keep on building 🚀

So what’s new this week on Fleek?

* New Cloudflare CDN Option
* Change an Existing Site’s Repository

# New Features

## Cloudflare CDN Option

![](https://storageapi2.fleek.co/fleek-team-bucket/blog/Cloudflare-UpdateRepo/cloudflare2.png)

First on the docket, we’ve added the ability to use **Cloudflare for CDN/Cache/DNS** features instead of the default Fleek CDN/Cache layer on BunnyCDN. We wanted to provide users with an alternative they can select based on their needs.

The cool thing? You’ll still benefit from Fleek’s CI/CD pipeline for deploying to IPFS! This is because you will use a cool combo of Cloudflare & DNS Link, that ensures you don't need to manually update your IPFS hash on Cloudflare each time you make a deployment.

![](https://docs.fleek.co/domain-management/imgs/cloudflare3.png)

Same easy IPFS hosting as before, but with another sturdy CDN alternative provider. For information on how to make this change to your site visit our Fleek Docs: [Setting Up Cloudflare](https://docs.fleek.co/domain-management/custom-dns-domains/#setting-up-cloudflare).

## Update Existing Site with a New Repo

![](https://storageapi2.fleek.co/fleek-team-bucket/blog/Cloudflare-UpdateRepo/NewRepo.gif)

Migrating your **already deployed site** **to a new Github repo**? With this new feature update, gone are the days of having to create an entirely new site through Fleek in order to do this. From your already deployed site, find your way to **Setting > Build & Deploy > Continuous Deployment > Edit Settings**.

From here, select or search for your repository of interest. Boom, your existing site has now been populated with the build from your new Github repository. It's that easy!

## Wrapping it up 🗞️

Well, that’s it for today’s release notes! Make sure to stay tuned for more Fleek.co updates to come.

As always, feel free to reach out to us on Twitter or Discord to let us know about any features, bugs, or improvements you think our team should take care of next 🤟

* [Sign up](https://app.fleek.co) to try Fleek ⚡️
* Join our [Community Chat](https://discord.com/invite/yVEcEzmrgm) 💬
* Follow us on [Twitter](https://twitter.com/FleekHQ) 🐦
* Subscribe to our [Youtube channel ](https://www.youtube.com/channel/UCBzlwYM0JjZpjDZ52-SLUmw)📺
* Check out our [Tech Docs](https://docs.fleek.co/) ✍️