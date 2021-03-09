---
layout: preso
permalink: "/webinars/202006-004/slides/"
title: How to Upload a Website on RIF Storage
tags: rif, swarm, dweb, slides
description: "DWeb - How to Upload a Website on RIF Storage"
backgroundImage: "/assets/img/preso/preso-rif-slide-body.png"
---

<!-- .slide: data-background="/assets/img/preso/preso-rif-slide-title.png" -->

---

# How to Upload a Website on RIF Storage

[Rinke Hendriksen](https://twitter.com/hendriksenrinke)

[Brendan Graetz](http://bguiz.com/)

2020/06/10

[developers.rsk.co/webinars/202006-004/slides](/webinars/202006-004/slides/)

NOTE:

`Brendan`

---

This works best as a hands-on session.

(so get your computers ready!)

NOTE:

`Brendan`

---

<!-- .slide: data-background="/assets/img/preso/webinars-page-screenshot.png" -->

<!-- .element: style="background-color: #ffffffb0;" -->
## [developers.rsk.co/webinars](/webinars/)
[50+ past events](/webinars/#calendar-past)

NOTE:

`Brendan`

For those of you joining us in this webinar for the first time,
we would like to highlight that this is just one of a very large series of webinars, that is over 50 and counting at the moment.

Lots of great educational material out there already,
so check out developers.rsk.co for all the details.

---

## Us

- Rinke
- Brendan

NOTE:

`Brendan`

----

### Brendan

- Dev 🥑
- Singapore 🇸🇬
- Granjero de mariposas
  🥚→🌿→🐛→💤→🦋→🥚
- Compostador urbano
  🍜→♻️→🌱
- Estudiante español

NOTE:

- Ya lo he estado aprendiendo durante más de doscientos días en Dúolingo
- Estoy practicando mi español ahora mismo 😃 but that's all the Spanish you're going to get from me today!

----

### Rinke

- Economist and (smart-contract) dev
- Swarm product owner & researcher
- Hilversum, The Netherlands
- I am here because: innovation, impact, decentralization,

NOTE:

`Rinke`

---

## Web 1...2...3!

- Why do we need decentralized storage?
- A little history...

NOTE:

`Rinke`

----

### Web 1.0

- Self-hosted
- Decentralized
- Not scalable

NOTE:

`Rinke`

----

### Web 2.0

- Faustian bargain
    - Content ownership for scalable website
- Some big and professional platforms
- "Platforming"
- Centralized and scalable

NOTE:

`Rinke`

----

### Web 2.0 vs Web 3.0

![web 2.0 vs web 3.0](../web2-vs-web3.png)

NOTE:

`Rinke`

----

## Web 3.0

- Censorship resistant
- Permissionless
- Immutable
- Scalable

NOTE:

`Rinke`

mention characteristics of Web 3.0 here

---

## How does RIF Contribute to Web 3.0?

- RIF Storage
- RNS
- Swarm / BEE

NOTE:

`Rinke`

----

## RIF Storage

- [developers.rsk.co/rif/storage](/rif/storage/)
- Unified IPFS + Swarm
- Built-in economic incentives
    - RIF token

NOTE:

`Rinke`

---

## RNS

- RIF Name Service
- Decentralised DNS
- (upcoming webinars)

NOTE:

`Rinke`

---

## Swarm

- Decentralised storage
- Decentralised content distribution
- Some possible use cases:
    - Web pages, databases, media streams
- "Unstoppable storage"

NOTE:

`Rinke`

----

## Bee

- [github.com/ethersphere/bee](https://github.com/ethersphere/bee)
- Greenfield reimplementation of Swarm
    - devp2p → libp2p
- 👀 for announcements

NOTE:

`Rinke`

---

## Set up

- A [POSIX](https://en.wikipedia.org/wiki/POSIX)-compliant terminal
- [`git`](https://git-scm.com/)
- [`curl`](https://curl.haxx.se/)
- [`jq`](https://stedolan.github.io/jq/) (optional)
- [NodeJs](https://nodejs.org/en/) (optional)

NOTE:

`Brendan`

POSIX compliant terminal:

- Recommended option for Linux/ Mac: Default/ built in terminal
- Recommended option for Windows: [Git Bash](https://gitforwindows.org/)

NodeJs:

- optional, only needed to preview site using a centralised HTTP server
- Recommended install method for Linux/ Mac: [`nvm`](https://github.com/nvm-sh/nvm)
- Recommended install method for Windows: [Official installer](https://nodejs.org/en/)

---

## Hands-on

[developers.rsk.co/tutorials/dweb/first-swarm-website](/tutorials/dweb/first-swarm-website/)

NOTE:

`Brendan`

Now we are about to start our hand-on section of today's webinar.

The article linked here is the materials that we will be following along today in today's demo,
so please open it up in a new browser tab as it will make it much easier to follow along.

Time to start up your fire up your terminals and code editors!

- Brendan: Installs Swarm, opens code editor and uploads website (with html and image).
- Brendan: Then kicks the ball to Rinke, shares hash.
- Rinke takes over screen and downloads website.
- Rinke views website on localhost.
- Rinke: Here comes a bit of theory, explaining what has been happening on the background (peer-to-peer).
- Rinke: Then edits the website and uploads it again. Gives hash to Brendan and Brendan takes over again :)
- Brendan: View Rinke's hash on localhost
- Brendan: View Rinke's hash on swarm gateway
- Brendan: Ask audience to share their hashes in the chat

---

## Your demos!

Share your `bzz:/` URLs in the chat!

NOTE:

`Rinke`

- Audience should have already seen us viewing each others Swarm hashes
- Ask audience to visit Brendan's Swarm hash and Rinke's Swarm hash themselves
- Encourage audience to share their own Swarm hashes
- Instructions on how to convert a localhost `bzz:/` URL to swarm gateway `bzz:/` URL
  - `http://localhost:8500/bzz:/1c97998044167e1d836e4290d60f812a7838d1c1551ebd86fd2b4bae2f9a44ee/`
  - `https://swarm-gateways.net/bzz:/1c97998044167e1d836e4290d60f812a7838d1c1551ebd86fd2b4bae2f9a44ee/`

---

## We're back!

Questions?

NOTE:

`Brendan`

That was the demo!

Did anyone have any questions before we wrap up?

---

## Pushing the boundaries

- DWeb technology is cutting edge

NOTE:

`Brendan`

So before we wrap up, I would just like to quickly mention,
that while Swarm is at the cutting edge of the decentralised web,
the DWeb, as a whole, is still very much in its infancy.

So watch this space!

(skip sub-slides)

----

`Brendan`

- [Transforming links](https://github.com/rsksmart/rsksmart.github.io/blob/768be3be60f14eba780f1ac118694de8bf2aaa54/_plugins/custom_links.rb)

NOTE:

When you upload a website onto decentralised storage,
it's address is going to be a hash.
You cannot know ahead of time what the URL will be,
since it contains said hash.
(Unless you solely use the decentralised DNS, and do not use the hash at all.)

This means that while it is customary to use absolute links, that is those starting with a `/` in regular web development, this can break your site.
So I say to that, "¿por que no los dos?"
have your cake an eat it too.

The RSK dev portal is a static site built using Jekyll.
In preparation for uploading it to the DWeb on Swarm,
I have created a custom Jekyll plugin that
takes all such absolute links and transforms them to their relative forms, such that they will work without knowing the hash ahead of time.

----

- [`bzz-web:/`](https://github.com/bguiz/bzz-web)

NOTE:

`Brendan`

The site that we created today works as an excellent example, under demo conditions, because it has relatively few files,
and their paths do not overlap in certain ways that trip up the way in which the actual filenames to be served are resolved, which we may be accustomed to, such as trailing `/`-es and auto-appending `index.html`.

As such, in order for this to work with a fairly complex website such as the RSK DevPortal, I created a simple proxy server to augment the standard `bzz:/` protocol server that ships with swarm.

---

## Coming up!

- RIF Publish: ~ end of month
- BEE Alpha release: ~ end of month
- Global pinning: ~ 2 months
- RIF Storage services: ~ 2 months

NOTE:

`Rinke`

---

## Resources

- [rifos.org/blog/rif-storage-the-first-chunks](https://www.rifos.org/blog/rif-storage-the-first-chunks)
- [rifos.org/blog/rif-storage-testnet-launch](https://www.rifos.org/blog/rif-storage-testnet-launch)
- [rifos.org/blog/rif-storage-and-swarms-swap-swips](https://www.rifos.org/blog/rif-storage-and-swarms-swap-swips)
- [rifos.org/blog/how-to-launch-a-serverless-website-using-rif-storage](https://www.rifos.org/blog/how-to-launch-a-serverless-website-using-rif-storage)
- [rifos.org/blog/rif-publish-ux-focused-censorship-resistant-publishing](https://www.rifos.org/blog/rif-publish-ux-focused-censorship-resistant-publishing)

NOTE:

`Rinke`

----

## Resources

- [chipin.com/swarm-and-rsk-infrastructure-framework-partnership](https://www.chipin.com/swarm-and-rsk-infrastructure-framework-partnership/)
- [developers.rsk.co/rif/storage/providers/swarm](/rif/storage/providers/swarm/)
- [github.com/ethersphere/bee](https://www.github.com/ethersphere/bee)
- [github.com/ethersphere/swarm](https://www.github.com/ethersphere/swarm)

NOTE:

`Rinke`

---

## Where to go from here?

- Register a decentralised domain name for your website on Swarm
- Swarm Feeds and messaging
- Using the incentivized Swarm network

NOTE:

`Brendan`

What we have done today is not all there is for a decentralised web!
There are a number of other topics to cover,
and we will be sure to let you know when we run the next sessions on these topics
that we have up here on the screen now!

---

## Fin

Thank you!

[developers.rsk.co/webinars](/webinars/)

NOTE:

`Brendan`

Thanks to everyone for attending!

Be sure to check out developers.rsk.co/webinars for more sessions on RSK and RIF!

Thank you!

---

<!-- .slide: data-background="/assets/img/preso/preso-rif-slide-fin.png" -->
