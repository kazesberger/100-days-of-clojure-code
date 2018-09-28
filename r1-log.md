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

### R1D3 - 2018-09-17

Task                                    | completed
----------------------------------------| -------------------- 
[PR for porkostomus' ctrain][5]         | yes

#### description

In response to [porkostomus' blog post "2018-09-16-day-2"][6] I tried to figure out what the problem was and i think i succeeded in finding a proper solution.

#### thoughts / feelings

* porkostomus' idea with the rasppi is great. there are so many gadgets for mini-NES-like stuff out there - I think this is a wonderful idea to make something similar to play with code puzzles. 
* filing a PR felt great :)
* sadly this will be my only task for today - not feeling that great today (yet another sore throat)

### R1D4 - 2018-09-18

#### description

Continued solving Exercism puzzles. 

#### thoughts / feelings

Exercism puzzles have quite wide range of difficulty despite all labelled "easy".
I learned way more by doing the 4clojure puzzles (where I'm currently at problem #60). But Exercism still helps me to find better solutions in less time. 

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/nucleotide-count][7]       | yes
[exercism.io/two-fer][8]                | yes
[exercism.io/hamming][9]                | yes
[exercism.io/phone-number][10]          | no (out of time not bc too hard)

### R1D5 - 2018-09-19

#### description

Finished phone-number exercism from yesterday. 
Decided to do some more 4clojure problems for now although they really getting difficult for me.

#### thoughts / feelings

Don't know when i'll be having my first day of this challenge where i won't complete any puzzle. been there will happen again i guess :)

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/phone-number][10]          | yes
[4clj-60][11]                           | yes (although i need to dig more into the lazy-seq topic)

### R1D6 - 2018-09-20

#### description

Had less time today so i did some exercisms again. more 4clj next time i hope. or maybe I'll have a look at past advent of code challenges.

#### thoughts / feelings

Tried to reach out to the maintainers of 4clojure because I want to improve this imho very important service for clojure beginners.

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/reverse-string][12]        | yes         
[exercism.io/clock][13]                 | yes  
[exercism.io/bob][14]                   | yes

### R1D7 - 2018-09-21

#### TIL

* lazy-cat
* fnil
* group-by

#### description

Decided to focus on 4clojure until finished. 

#### thoughts / feelings

Lazy-seqs are still a bit "magical" to me (construction mainly and lacking xp which stuff realization triggers although this is most of the time pretty obvious)

Task                                    | completed
----------------------------------------| -------------------- 
[exercism.io/rna-transcription][15]     | yes
[4clj-62][16]                           | yes 
[4clj-63][17]                           | yes 

### R1D8 - 2018-09-22

Continuing 4clj. The gaps in my "done" list (like 4clj-64) are (up to now) educational exercises too easy to mention.
Had a mentor-session with Timothy pratley again. Quickly discussed my [ansible-role-spec][18] project which I'm about to start and poked at some code for it.   

#### TIL

* empty
* keep
* need to think more often of 'some'
* drop is better for (map inc (range)) *blushing in shame* mainly bc of 2-arity drop [n coll]
* [expound](https://github.com/bhb/expound) is a very nice addition to clojure spec.
* [entr](http://www.entrproject.org/) is a nice cli-tool to run commands on file change.

#### thoughts / feelings

Not sure whether my [ansible-role-spec][18] tool will be useful for a broader audience but I'll definitely write it and am going to use it once the first version is done. 

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-65][19]                           | yes
[4clj-66][20]                           | yes
[4clj-67][21]                           | yes

### R1D9 - 2018-09-23

Continuing 4clj. Made it to 4clj73 but didn't solve it yet.    

#### TIL

* re-seq (need to look a bit more into regex stuff, maybe there are still some 4clj exercises to practice/learn this - otherwise i could contribute some)

#### thoughts / feelings

Feeling really good as I waste a lot less time re-learning stuff I've already forgotten by doing this daily. (yes, I've become an old man... xD) 

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-69][22]                           | yes
[4clj-70][23]                           | yes
[4clj-73][24]                           | nope

### R1D10 - 2018-09-24

Today i had one of my regular code kata sessions with a friend. we solved some 4clj.    

#### TIL

* read-string (although with eval dangerous under certain conditions) can be handily used to dynamicly parse string-data.
* destructuring is very useful in any scenario where specific elements/parts of your data have special meaning (so kinda always drastically reducing code)

#### thoughts / feelings

:) 

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-73][24]                           | yes
[4clj-74][25]                           | yes
[4clj-75][26]                           | nope

### R1D11 - 2018-09-25

4clj.    

#### TIL

* flatten obviously only flattens sequential things like vector, list, seqs but not maps and sets.
* trampoline recursion (find it a bit hard to read though atm)

#### thoughts / feelings

:) 

I kinda want to get over these puzzles asap to get more into a bit more real world stuff. but my spare time without interruptions is very limited atm. 
But there is hope: working on better organisation of work and family and by November 24th I quit playing in my wind band.

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-75][26]                           | yes
4clj-76                                 | yes
[4clj-77][27]                           | yes

### R1D12 - 2018-09-26

4clj.    

#### thoughts / feelings

:) very tired today though. 

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-78][28]                           | yes
[4clj-79][29]                           | nope (but I'm close to a shitty first solution)


### R1D13 - 2018-09-27

4clj.
Discovered [GeeksForGeeks.org](https://www.geeksforgeeks.org/) which is among other things an awesome source of algorithmic problems.

#### TIL

* for some reason that i dont understand yet one cannot use apply on macros (like and). in my case (every true? (and ...) solved my task.
* once again (re-)learned that sets can be used as functions and predicates.

#### thoughts / feelings

I wonder whether there is still a barrier that is like "tinking in clojure".
I can't shake off the feeling that I still have a moment in front of me where it should make "click" somehow, 
but probably it's just a matter of practice and a more gradual "click" than I "feel".

Anyways I'm curious what I will think of this once I've overcome this feeling.

Task                                    | completed
----------------------------------------| -------------------- 
[4clj-79][29]                           | nope (i checked the solutions and realized i misunderstood the task)
[4clj-80][30]                           | yes
[4clj-81][31]                           | yes



[1]:https://github.com/kazesberger/exercism-clj/tree/master/minesweeper
[2]:https://github.com/kazesberger/exercism-clj/tree/master/series
[3]:https://github.com/kazesberger/exercism-clj/tree/master/collatz-conjecture
[4]:https://github.com/kazesberger/exercism-clj/tree/master/beer-song
[5]:https://github.com/porkostomus/ctrain/pull/1
[6]:https://porkostomus.gitlab.io/posts-output/2018-09-16-day-2/
[7]:https://github.com/kazesberger/exercism-clj/tree/master/nucleotide-count
[8]:https://github.com/kazesberger/exercism-clj/tree/master/two-fer
[9]:https://github.com/kazesberger/exercism-clj/tree/master/hamming
[10]:https://github.com/kazesberger/exercism-clj/tree/master/phone-number
[11]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj60.clj
[12]:https://github.com/kazesberger/exercism-clj/tree/master/reverse-string
[13]:https://github.com/kazesberger/exercism-clj/tree/master/clock
[14]:https://github.com/kazesberger/exercism-clj/tree/master/bob
[15]:https://github.com/kazesberger/exercism-clj/tree/master/rna-transcription
[16]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj62.clj
[17]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj63.clj
[18]:https://github.com/kazesberger/ansible-role-spec
[19]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj65.clj
[20]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj66.clj
[21]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj67.clj
[22]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj69.clj
[23]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj70.clj
[24]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj73.clj
[25]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj74.clj
[26]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj75.clj
[27]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj77.clj
[28]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj78.clj
[29]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj79.clj
[30]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj80.clj
[31]:https://github.com/kazesberger/clj-katas/blob/master/src/foreclojure/4clj81.clj

