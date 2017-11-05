# Show & Tell 1

Let me thank all participants and start by saying that I'm very happy of having met with this smart bunch of people. Let's start with the summary.

## MJ: OpenHouse Torino

I've started by showing my dumb but funny experience with [OpenHouse Torino](http://openhousetorino.it/). On how I made quickly a simple but effective website using WordPress, on a very low budget for free for a non-profit association.

Main takeaways:
	- I made a child theme of [twentyseventeen](https://wordpress.org/themes/twentyseventeen/) mainly removing stuff
	- the only important plugin I've used is [NextGEN Gallery](https://wordpress.org/plugins/nextgen-gallery/) for the building galleries and [WP Gallery Custom Links](https://wordpress.org/plugins/wp-gallery-custom-links/) to customise the links from the gallery in the homepage. That's it! Told you it was easy :P
	- all the pages are static, also the filtering in the main building page is static. That is important for what I need to say next
	- in the weekend of the event we had a massive spike in usage, with around 300 people constantly on the website, for a total of 500,000 pageviews in the week around the event. My very cheap hosting (Bluehost), couldn't cope even by just serving the cached site. So I had to use [Cloudflare](https://www.cloudflare.com/) to statically serve everything. It's been great!

Then I spoke a bit about how I helped out managing volunteers and buildings with a mixture of Google Forms, Google Sheets and Google Apps Script. That was a nasty mess, the only interesting stuff is that it's good to manage fairly big forms (100 elements in a dropdown opening 100 different sections). But it's slow. So you need to process one row at the time and not the entire sheet (which had roughly 500-1000 entries in total). Problem is that when you share the spreadsheets with other people so that they can extract data you cannot trust the "database" anymore. So that's why I had to process the entire sheet every time. Food for thought for the next OpenHouse :)

## Edo: Screeps

[Edoardo](https://about.me/edoardo.tenani) has introduced us to his new drug: [Screeps]()! Thank you!
The game is a lot about reading [documentation](docs.screeps.com), which is great since it's one of the best docs he's seen, he ;)

The game reminds [Liquid wars]() for the lucky people having played it.

Screeps is about coding in JavaScript to automate bots that need to harvest, build things and obviously fight, in a world inhabited by other players.

These games are obviously making people go crazy and code AIs to manage the creeps (the programmable units), for example this one: [bonzAI](https://github.com/bonzaiferroni/bonzAI), seriously.

Because why not, the [Screeps subreddit](https://www.reddit.com/r/screeps)!


## Jelle: YouTube P2P

Jelle, with the company of the [Piramid](http://piramid.studio/) crew presented their latest and very ambitious project, a P2P YouTube.

The idea is that now Google does the hosting and the sharing of adverts revenue between content creators. But why hosting and distribution couldn't be done in P2P?

There are experiments of incentivised file sharing platforms, where you are paid based on how much traffic is passing through your network.

With [Ethereum](https://www.ethereum.org/) you can manage programaticaly the money transfers and with [Webtorrent](https://webtorrent.io/) you can share over P2P videos of the platform.

So now instead of having a website that goes slower if there are many visitors, you have a website that the more people you have the faster it goes! Plus the money incentive should let people keep the browser open to share more and earn more.

Money gets in still through adverts, but they are better shared between people streaming and content creators.

And then they proceed with a very nice and impressive demo of the project, still a work in progress, but proving really well the basic ideas. Impressive.


## Riccardo: Apache superset

[Riccardo](http://menodizero.it/) has presented [Apache Superset](https://superset.incubator.apache.org/) a very nice tool to make data visualisation and analysis in a very powerful tool.

Basic concepts:
	- database
	- slice
	- dashboard

It works with the main RDBM and you can start by doing some codeless data exploration, viz & collaboration.

You can hack it too if you want, it's open source!


## Stefano: Train station master

[Stefano]() has presented his awesome [Station master](http://tsds-steox.rhcloud.com/show?view_mode=both&station_code=S00219) project, using his [Ruby Gem](https://rubygems.org/gems/station_master) to scrape data from the trainlines, like a boss.

He built the project to help a friend passioned with train modeling, that is using his project to show timetables of trains to simulate the lines that are in the model.

This project has struck me particularly, has my grand father has a massive train model on which I spent many hours of my youth. I have to show it to Stefano!

## Silvano: Vue.js

By nigh [Silvano](http://www.sistrall.it/) works on [Contiamoci](http://www.contiamoci.com/), his side project on which he experiments with tech, while helping his partner.

His new investigation is on Vue.js, an easy to use on a legacy project frontend framework.

Good point n.1: you import via script, job done, no precompile, no fluff.
Good point n.2: you start the Vue app, attach it to a DOM id, you are done!

Demo time! Silvano shows a very nice combo: Vue and D3.

He has built an SVG in HTML and Vue, then attached D3 to make the SVG interactive. He shows how you can attach dynamically the nodes, change the data structure and use D3 to create a force tree between the nodes and move all the tree around. Very nice.

Couple of tricks used:
	- string interpolation with {{}}
	- v-for v-bind for directives
	- D3.drag to move nodes around
	- no D3 data-binding, to use Vue and make it faster

Reminds of Angular 1, but better!

Couple of follow up links:
	- [awesome Vue](https://github.com/vuejs/awesome-vue)
	- [Chrome devtools for Vue](https://github.com/vuejs/vue-devtools)
	- [Vuex](https://github.com/vuejs/vuex)
	- [Nuxt](https://nuxtjs.org/)
