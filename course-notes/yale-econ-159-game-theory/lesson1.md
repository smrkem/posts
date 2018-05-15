# 1. Introduction: five first lessons

[0:30s] looked for handouts online for Game 1 and Game 2. There are resources available for download on the course [homepage](https://oyc.yale.edu/economics/econ-159), but have yet to find these specifically.

There are 2 textbooks. 

Main: Dutter - Strategy and Games
more rigorous: J Watson - Strategies
reccommended: thinking strategically

Just there as backup. Not required.

## What is game theory?

[0:58s] A method of studying strategic situations.

```A setting where outcomes that affect you depend on actions by you and by others```

Strategic situations do not include perfect monopolies where there is no competition, or perfect competition where actors are price takers and don't need to worry about the actions of others.

All 'imperfect' competition is strategic.

## GAME 1
### The Prisoner's Dilemma  

Give each person a choice between &#0946; and &#0945;. Then grades are awarded by:  

<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | B-, B- | A, C
&#0946; | C, A | B+, B+

</td></tr>
</table>  

### Evil Git Payoffs  

I can assign possible payoffs. Assuming all I care about is my own grade - a _selfish_ set of payoffs would be:

<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | 0, 0 | 3, -1
&#0946; | -1, 3 | 1, 1

</td></tr>
</table>  

Where I prefer A to B+ to B- to C.  

---
### Def<sup>_N_</sup>  
> We say that my strategy &#0945; ___strictly dominates___  my strategy &#0946;, if my payoff from  
> &#0945; is strictly greater than that from &#0946;, regardless of what others do.
---
  

---
### Lesson 1  
> Do not play a ___strictly dominated___ strategy. If instead I play the ___strictly dominating___strategy, I do better in every case.
---

Maybe I should choose &#0946; though - since if everyone chooses &#0946; we all get 1, but if everyone chooses &#0945; then we all only get 0. 

But this involves some _magical reasoning_ where I can affect other people's reasoning, and even if everyone else does choose &#0946; - then I'm still better off choosing &#0945;.

In the Prisoner's Dilemma - each person is given the choice of ratting the other guy out (&#0945;) and not ratting the other guy out (&#0946;). If both players rat then they each get 2 years, and if neither player rats then they each get 1 year. If one player rats out another - they go free while the other gets 5 years.


<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | 2, 2 | 0, 5
&#0946; | 5, 0 | 1, 1

</td></tr>
</table>  

This game plays out in many situations.

2 roommates share a room - each would like to have the other clean up, and not do any cleaning themselves. If the other guy _doesn't_ clean up - then you're best off not cleaning up either because you don't want to be guy doing all the cleaning. If the other guy _does_ clean up - then the room is clean so who cares. 

Firms competing for the same bid. Each has an incentive to undercut the other, since they don't want to be undercut themselves.

---
### Lesson 2  
> The most rational choice from rational players can lead to bad outcomes.
---  

Actors can communicate, collude and make contracts with each other - but the contracts need to be enforceable. 

### Indignant Angel Payoffs  

What if I assign new payoffs? If everything is the exact same, except now if I get an A and my pair gets a C, I suffer some 'moral' penalty that takes my 3 down to a -1. Similarly, if I get a C I additionally suffer some 'indignation' that takes my -1 down to -3.

<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | 0, 0 | -1, -3
&#0946; | -3, -1 | 1, 1

</td></tr>
</table>  

_Note: in this example the pre-indignation C is somehow a -1 where getting a C before was already at -3._

Here there is no ___strictly dominant___ strategy. An &#945; strategy is better against &#945;, and a &#946; strategy is better against &#946;. This is an example of a _co-ordination problem_.  


---
### Lesson 3 
> Payoffs matter. Game Theory can tell you how to get optimal payoffs - but not what your payoffs should be.
---  

### Evil Git vs Indignant Angel  

Now let's say I am an evil git, but I know my pair will be an Indignant Angel. My payoff's are those from the Evil Git table, but my pair's are from the Indignant Angel table.

<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | 0, 0 | 3, -3
&#0946; | -1, -1 | 1, 1

</td></tr>
</table>  

Here my &#945; strategy is still ___strictly dominant___. Choosing &#945; always results in better payoffs for me - my payoffs haven't changed at all.  

Say however I am now the Indignant Angel playing against an Evil Git:  


<table>
<tr><td>me</td>
<td>
pair<br>  

   -   | &#0945; | &#0946;
------ | --------- | ----
&#0945; | 0, 0 | -1, -1
&#0946; | -3, 3 | 1, 1

</td></tr>
</table>  

The Indignant Angel still has no dominant strategy - &#0945; is better against &#0945;, and &#0946; is better against &#0946;. But in this case the Indignant Angel _knows_ that their pair _does_ have a dominant strategy, and so their pair will choose &#0945;, and so Indignant Angel should also choose &#0945;.


---
### Lesson 4 
> If you don't have a dominant strategy, put yourself in other people's shoes and try to figure out their payoffs and what they will do.
---  
