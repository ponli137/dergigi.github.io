---
layout: page
title: Projects
---

### 21 Ways

Bitcoin is different things to different people. [21 Ways](https://patreon.com/dergigi) is my attempt
to embrace this prismatic nature of Bitcoin, exploring 21 different ways to look at Bitcoin.
It is an ambitious project, trying to dive deep into Bitcoin's different facets, including
its roots, pre-history, history, civil war, technologies built on top of Bitcoin,
surrounding economic thought, and much more. You can
[support me on Patreon](https://patreon.com/dergigi) if you want to have a look behind the
scenes and get a glimpse of this work in progress.

{% include image.html path="/assets/images/bitcoin/projects/21ways.png" link="https://patreon.com/dergigi" %}

* Patreon: [21 Ways](https://patreon.com/dergigi)

### 21 Lessons

[21 Lessons][21lessons] is a bit of an unusual book. But hey, Bitcoin is a bit of an unusual
technology, so an unusual book about Bitcoin might be fitting. This book came to be because
of one simple question: *What have you learned from Bitcoin?* I tried to answer this
question in a single tweet. Then the tweet turned into a tweetstorm. The tweetstorm turned
into an article. The article turned into three articles. Three articles turned into 21
Lessons. And 21 Lessons turned a book.

{% include image.html path="/assets/images/bitcoin/projects/21lessons.png" link="https://21lessons.com" %}

* Website: [21lessons.com][21lessons]
* Purchase: [Paperback][paperback], [Kindle](https://amzn.to/3bvM49P), [Audiobook](https://amzn.to/2ZeUsYX)
* Source: [GitHub](https://github.com/21-lessons/21lessons-book)

[paperback]: https://amzn.to/2Wa4qJo
[21lessons]: https://21lessons.com/

---

### Bitcoin Resources

While falling down the Bitcoin rabbit hole I tried to absorb as much content in the form of
books, articles, and podcasts as humanly possible. [Bitcoin Resources][bitcoin-resources] is
my attempt to catalog and signal-boost the best and most insightful content in the Bitcoin
space. Since its inception, a growing number of people have started to contribute by
selecting and curating content.

{% include image.html path="/assets/images/bitcoin/projects/bitcoin-resources.png" link="https://bitcoin-resources.com" %}

* Website: [bitcoin-resources.com][bitcoin-resources]
* Twitter: [@BtcResources](https://twitter.com/BtcResources)
* Contribute: [GitHub](https://github.com/bitcoin-resources/bitcoin-resources.github.io/blob/master/CONTRIBUTING.md), [Telegram](https://t.me/BitcoinResourcesCom)
* Source: [GitHub](https://github.com/bitcoin-resources/bitcoin-resources.github.io)

[bitcoin-resources]: https://bitcoin-resources.com/

### Bitcoin Quotes

[Bitcoin Quotes][bitcoin-quotes] is an experiment in micropayments around a growing
collection of Bitcoin-related quotes. As of this writing, 300+ quotes have been sourced and
indexed, in both audio and written form. The source of each quote will be revealed upon
paying ~2¢ in sats. I hope that these quotes will inform, inspire, and delight those who
stumble upon them. There is also a rudimentary [API][API] if you want to integrate these
random quotes into a project of yours. Follow the [twitter bot][btc_quotes] of this project
to get random quotes in your timeline.

{% capture time_seed %}{{ 'now' | date: "%s" }}{% endcapture %}
{% assign random = time_seed | times: 1103515245 | plus: 12345 | divided_by: 65536 | modulo: 32768 | modulo: 11 %}
{% capture n %}{% if random < 10 %}{{ '0' | append: random }}{% else %}{{ random }}{% endif %}{% endcapture %}
{% assign randompath = "/assets/images/bitcoin/projects/bitcoin-quotes" | append: n | append: ".png" %}
{% include image.html path=randompath link="https://bitcoin-quotes.com" %}

* Website: [bitcoin-quotes.com][bitcoin-quotes]
* Twitter: [@btc_quotes][btc_quotes]
* Source: [GitHub](https://github.com/dergigi/btc-quotes)

[bitcoin-quotes]: https://www.bitcoin-quotes.com/
[btc_quotes]: https://twitter.com/btc_quotes
[API]: https://www.bitcoin-quotes.com/quotes/random.json

### Einundzwanzig

[Einundzwanzig][einundzwanzig] - the German word for 21 - is a collaboration of multiple
German-speaking bitcoiners, started by Markus and myself. Started as a simple weekly podcast
focused on news in the Bitcoin space, the project continues to morph, evolve, and expand. In
addition to the weekly news show, Einundzwanzig now also dives deeper into some topics by
interviewing various experts in the German-speaking Bitcoin world. We also started to
release readings of the best Bitcoin content, thanks to the growing availability and quality
of German translations.

{% include image.html path="/assets/images/bitcoin/projects/einundzwanzig.png" link="https://einundzwanzig.space/podcast/" %}

* Hosts: [Daniel], [Dennis], [Fab], [Gigi], [Markus]
* Website: [einundzwanzig.space](https://einundzwanzig.space/)
* Podcast: [einundzwanzig.space/podcast][einundzwanzig]
* Twitter: [@\_einundzwanzig\_](https://twitter.com/_einundzwanzig_)
* Community: [t.me/einundzwanzigpodcast](https://t.me/einundzwanzigpodcast)

[Daniel]: https://twitter.com/danielwingen
[Dennis]: https://twitter.com/dennisreimann
[Fab]: https://twitter.com/fabthefoxx
[Gigi]: https://twitter.com/dergigi
[Markus]: https://twitter.com/MarkusTurm
[einundzwanzig]: https://einundzwanzig.space/podcast/

### 21 Lektionen

Since 21 Lessons is released under a permissive creative commons license, it has been
translated into multiple languages. *[21 Lektionen: Meine Reise in den Bitcoin
Kaninchenbau][paperback-de]* is based on the German translations of Rene and CryptoMulde,
revised and adapted by myself.

{% include image.html path="/assets/images/bitcoin/projects/21lektionen.png" link="https://amzn.to/2Z2zts3" %}

* Purchase: [Paperback][paperback-de], [Kindle](https://amzn.to/2Z2zts3)
* Source: [GitHub](https://github.com/21-lessons/21-lessons-book-de)

[paperback-de]: https://amzn.to/2AtlfWZ

### Quotable Satoshi Twitter Bot

Building upon the great work of the Satoshi Nakamoto Institute, I wrote a twitter bot to
disseminate the most insightful and interesting quotes of Satoshi Nakamoto. Simply follow
[@QuotableSatoshi][quotablesatoshi] on twitter to get historical quotes from the inventor of
Bitcoin in your timeline.

{% include image.html path="/assets/images/bitcoin/projects/quotablesatoshi.png" link="https://twitter.com/QuotableSatoshi" %}

* Twitter: [@QuotableSatoshi][quotablesatoshi]
* Source: [GitHub](https://twitter.com/quotablesatoshi)

[quotablesatoshi]: https://twitter.com/quotablesatoshi

### Contribution: The Bitcoin Times

Launched by Alex Svetski in 2019, The Bitcoin Times is a publication that distills complex
topics in the world of Bitcoin into digestible pieces. As of this writing, two editions have
been published. I was one of the co-authors of the second edition, along with Rory Highside,
Nic Carter, Aleks Svetski, Robert Breedlove, Dan Held, Connor Brown, and Hass McCook.

{% include image.html path="/assets/images/bitcoin/projects/bitcoin-times.png" link="https://bitcointimes.news" %}

* Website: [bitcointimes.news][bitcoin-times]
* Twitter: [@TimelessBitcoin][timeless-bitcoin]

[bitcoin-times]: http://bitcointimes.news
[timeless-bitcoin]: https://twitter.com/TimelessBitcoin

### Contribution: Citadel 21

Citadel21 is a Bitcoin cultural zine launched by Hodlonaut and Katoshi in May 2020. Its
mission is to pull nuggets of high signal content out of the noisy chaos. I wrote an
[optimistic letter to bitcoiners][vol1] around the globe, published in the first volume, and
a piece on [identity and pseudonymity][vol4], published in the fourth volume.

{% include image.html path="/assets/images/bitcoin/projects/citadel-21.png" link="https://citadel21.com" %}

* Website: [citadel21.com][citadel21]
* Twitter: [@ctdl21][ctdl21]

[citadel21]: https://www.citadel21.com
[ctdl21]: https://twitter.com/ctdl21
[vol1]: https://www.citadel21.com/dear-bitcoiners-an-optimistic-letter
[vol4]: https://www.citadel21.com/true-names-not-required

### Contribution: 21ism Bitcoin Art Collective

[21ism][21ism] aims to celebrate artists across mediums, inspired to create by
the ultimate expression of freedom – Bitcoin. Art is one of the languages it
speaks & every month, 21ism takes a spin on the “Creative Carousel” to feature
new Artists. I had the pleasure and the honor to be the first featured writer.
My article [“What is 21ism?”][21ism-gigi] is accompanied by a multitude of
visual and multimedia art that make the words shine in more ways than one.

{% include image.html path="/assets/images/bitcoin/projects/21ism.png" link="https://21ism.com" %}

* Website: [21ism.com][21ism]
* Twitter: [@twentyoneism][twentyoneism]

[21ism]: https://21ism.com/
[21ism-gigi]: https://21ism.com/portfolio-item/gigi/
[twentyoneism]: https://twitter.com/twentyoneism

### Code Contributions

When I'm not writing I try to contribute to open source projects where I can.
Apart from trivial fixes and contributions in various projects, I've worked on
adding [Tor] and [Dojo] support to Samourai Wallet's Sentinel app for iOS (see
[video]). I also made some corrections to [BIP 2], [BIP 16], and [BIP 69]. I
recently joined the [Swan][joined-swan] engineering team and published a set of
[extended public key tools][xpub-tools] as open source software. Follow me on
GitHub to see what I'm up to.

* GitHub: [github.com/dergigi](https://github.com/dergigi)

[Tor]: https://github.com/Samourai-Wallet/Sentinel-iOS/pull/11
[Dojo]: https://github.com/Samourai-Wallet/Sentinel-iOS/pull/14
[video]: https://twitter.com/dergigi/status/1259397717144547328?s=20
[BIP 2]: https://github.com/bitcoin/bips/blob/master/bip-0002.mediawiki
[BIP 16]: https://github.com/bitcoin/bips/blob/master/bip-0016.mediawiki
[BIP 69]: https://github.com/bitcoin/bips/blob/master/bip-0069.mediawiki
[joined-swan]: {% post_url /collections/bitcoin/2020-08-18-why-i-joined-swan-bitcoin %}
[xpub-tools]: https://github.com/swan-bitcoin/xpub-tool
