---
title: "Anonymize IPs"
tags: ["privacy", "anonymize", "gdpr", "features"]
date: 2016-03-23
draft: false
---

From Doorbell's initial launch we've focused on security and privacy. Encrypting data in the database, encrypting the database at rest, penetration tests, and the list goes on.

One of the most important privacy factors (even before GDPR came into effect) has been to protect the location of customers.

<!--more-->

## How does it work?

When you enable IP address anonymization, we anonymize the IP address as soon as possible.

We set the last octet of IPv4 addresses and the last 80 bits of IPv6 addresses to zeros. The full IP address is never saved in the database, and never shared with any 3rd parties.

We also go through any past IP addresses in the database and run them through the same process.

## How do I enable it?

If you go to your [applications's setup page](https://doorbell.io/applications/setup#general), you'll find a new section under **General Settings** > **Privacy**.

![](/img/features/anonymize-ips.png)

To start anonymzing IP addresses simply select the checkbox, and click the Save button!

## Try it out

So go ahead and try it out, it is available on [all of our plans](https://doorbell.io/pricing?ref=blog-customer-profiles), including our free plan!

Go ahead, give it a try! If you haven't got an account yet, go sign up now: [https://doorbell.io](https://doorbell.io), it's free!

PS You can keep up to date either via this blog, or you can follow Doorbell on [Twitter](https://twitter.com/doorbell_io).

<style type="text/css">
    .post-detail img {
        max-width: 320px;
        display: inline-block;
        margin: 0 20px;
    }
</style>
