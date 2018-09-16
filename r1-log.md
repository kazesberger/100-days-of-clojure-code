# #100DaysOfCode Log - Round 1 - Klaus Azesberger

The log of my #100DaysOfCode challenge. Started on [September 15, Saturday, 2018].

## Log

### R1D0 Self-introduction / Status Quo

#### WhoAmI

* Started as Java Dev in 2008-01 at my first and current company Infonova aka Bearingpoint Tech @ Graz/Styria/Austria
* Father of 2 (* 2017-09 and * 2014-09) (yes, the love for/with my wife seems to peek around new years eve ;-))
* After working on rather monolithic Software in telecommunication business I transformed into the CI/Automation guy at my company
* responsible for the so called Development infrastructure which apart from the ubiquitous Atlassian stack includes some open source tools and domain specific tools. most notably we run a dynamic (jenkins-) build cloud with Mesos
* Currently occupied with continuously improving logging and monitoring (grafana/prometheus/kafka/ELK/riemann) while getting into K8s with babysteps.

#### why clojure?
* I think there are many good reasons for FP to become more popular
* I looked for a general purpose FP lang that strongly encourages or even forces you to apply a clean way of FP. for instance i found scala and kotlin not to be fit for this purpose.

#### How/What did i learn up to now?

* i found great support at https://www.meetamentor.co/
    * https://twitter.com/timothypratley?lang=de
    * http://www.jakubborys.com/
* founded a small clojure learning group at my company in an attempt to create a space where i can apply clojure during work hours too (for even more practice)
* read 
    * living clojure by carin meier aka gigasquid
    * [clojure polymorphism](https://leanpub.com/clojurepolymorphism/)
    * and in parts some other clojure books
    * [official guides](https://clojure.org/guides/getting_started)
    * "in-progress-ish" [clojure applied](https://pragprog.com/book/vmclojeco/clojure-applied)
* did some tutorials or parts of it
    * one that i started and intend to finish is [green-coder's transducer exercises](https://github.com/green-coder/transducer-exercises)
* 4clojure challenges (solved the first ~60 up to now)
* did some config files parsing and rest-calls-automation with clojure at work
* contributed to [a riemann plugin](https://github.com/infonova/riemann-history)
* *invested/wasted a lot of time reading and re-reading about stuff and not actually coding* this is what brought me here. 
* i officially quit almost all activities regarding my all time hobby of being a musician in wind and brass bands by end of current season (2018-11) (...for at least 2 years) 

#### how do i feel about myself

* I feel like i missed 10 years of coding experience while i've been mostly configuring/debugging/supporting, walking down the path of being an admin- or devops-guy at best.
* So while I'm considered to be a Senior or even Architect within my current company, I'd call myself a beginner regarding my coding skills.
* As I know the importance of practicing habits from being a hobby-musician (once made it into a member of the upper austrian brass band for 1 project), I'm confident that i can pull this off.
* I believe this challenge is *exactly* what I need to do.

### R1D1 - 2018-09-15

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/minesweeper][1]            | nope

#### description

I initially thought this would be easy for me.
Gonna look up some of the public solutions and probably retry this on another day (at least 1w in the future).

#### TIL

* map-indexed
* besides that mostly practicing experience, because i super-hard-tried to solve this without leaving my IDE (cursive atm).

#### thoughts / feelings

I'm not too disappointed. I know that I need to learn a lot. I'm only a bit concerned about whether I'm already on the right track meaning "Am I learning/practicing the right way". eg. should I peek more/less/never into solutions.

### R1D2 - 2018-09-16

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/minesweeper][1]            | yes
[exercism.io/series][2]                 | yes
[exercism.io/collatz-conjecture][3]     | yes
[exercism.io/beer-song][4]              | yes (not optimized yet though)

#### description

Yesterday I got help from [Timothy Pratley](https://github.com/timothypratley) to quickly revisit the minesweeper puzzle and realize that sometimes it helps not to tryhard too much on the clj-idiomatic stuff.
Also learned a thing or two by looking at the other solutions to the minesweeper puzzle.  
Decided to continue with the exercism puzzles. and did some of the first really easy hackerrank examples.
Noticed that I'm now practically a rock star in the clojure world ;-) as I got inderectly linked via [planetclojure](https://twitter.com/planetclojure) -> [porkostomus' blog](https://porkostomus.gitlab.io/posts-output/2018-09-15-hundred-days-of-code/?utm_source=dlvr.it&utm_medium=twitter)

#### TIL

* dont tryhard on idiomatic stuff (though I'd highly recommend reading several solutions)

#### thoughts / feelings

Fired up :-) Need to put more thought into possible side projects.

[1]:https://github.com/kazesberger/exercism-clj/tree/master/minesweeper
[2]:https://github.com/kazesberger/exercism-clj/tree/master/series
[3]:https://github.com/kazesberger/exercism-clj/tree/master/collatz-conjecture
[4]:https://github.com/kazesberger/exercism-clj/tree/master/beer-song
