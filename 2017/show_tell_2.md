# Show & Tell 2

Very busy and interesting session. First time in Toolbox, with many coworkers.

I've started introducing my recent talk about naivechain https://github.com/matjack1/naivechain showing some code and live demoing.

## Fabio da Soghe, Cognitio

Fabio has presented [Plenus](https://www.plenus.cloud/), their new PaaS based on Kubernetes. An easier way to use container-based software.
Containers are more efficient than normal OS virtualisation. They don't need the entire OS, they just needs their dependencies.
Kubernetes is a container orchestrator, it's one of the most active projects on Github.
Pokemon GO is using Kubernetes. Scaled more than 40 times than expected.
Plenus simplify Kubernetes by dealing with container management to production. Configurated with YAML files (and an Electron application).
Coder -> Plenus platform /OR/ kubectl -> Cloud.

They are looking for collaborators, beta testers, real users. I'm going to try it myself soon!


## Carlo Perassi, Kiwifarm

Carlo has presented [Objection.js](http://vincit.github.io/objection.js/) an ORM well integrated with Hapi.JS. Very good documentation, well worth using.
Nice features: eager load of relations, nice error management, rollback, etc.
Links: https://www.vincit.fi/blog/nested-eager-loading-and-inserts-with-objection-js/

Then he showed also [Realworld.io](https://github.com/gothinkster/realworld) an amazing project where many people built a clone of Medium in different backends and frontends that can be composed and tried. Very cool.


## Nicola & Gabriele

They have built some sort of simulation of Lotka-Volterra (prey-predator) system.
Agent based paradigm. Simple system that has a collective intelligence.
Every object/agent thinks about the environment, moves, and acts on the arrival point.

They used D3 for viz. Demo: https://gabrielelabanca.github.io/alifesgame/
Applause.

Similar: NetLogo -> sheep wolf example http://ccl.northwestern.edu/netlogo/models/WolfSheepPredation


## Giampaolo Mancini (TrampolineUP)

He focuses on the "I" of IoT. The radio transmissions.
An example are nodes with AA batteries that transmit very few data. For this use case two protocols shine: SigFox and LoRa. Also Arduino has a Sigfox board. LoraWan is more interesting than Sigfox but lacking of network. Devices do broadcast transmissions. Base stations receive data, dedup, and stream to application. Sigfox has done the base station infrastructure.
The law defines that duty cycle is limited to 1%. Bitrate and bit transmitted define the speed of transmission. Sigfox says 12 bytes every 15 minutes. Rover transmissions to Mars have more bandwidth!!
You can't use JSON, too much space wasted! So they have developed a solution: catalog of documents that are sent depending on the device ID.
Client developed in C/C++/Micropython/Python/F#, very flexible!


## Edoardo Tenani
3.14 15 9
What's the human record of number of Pi digits remembered? 70,030 digits for world record. 100,000 unofficial record. 16h of talking. WHAT!
Apparently they've used the method of loci to remember a lot of information.
https://en.wikipedia.org/wiki/Method_of_loci

[Slides](http://slides.com/endorama/method-of-loci)
