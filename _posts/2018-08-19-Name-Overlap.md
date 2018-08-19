--- 

layout: default 

title:  "Family Name Overlaps" 

date:   2018-08-19 08:00:41 -0700 

published: true

categories: jekyll update 

---

Required reading to understand the importance of this post: the poem _[Too Many
Daves](https://www.poemhunter.com/poem/too-many-daves/)_ by Dr. Seuss. Please
read before continuing.

Dr. Seuss here highlights a serious problem: having the same name in the family
can lead to serious confusion. If you don't take care with naming your children,
you will have _name overlap_, and by that point it will be too late.

You may think yourself clever. Perhaps your thinking "Well, I'll just name my
children all different names! Who even names all their kids Dave!?" 

Don't be lulled into this false sense of security. The real danger is not in
accidentally naming all 23 of your children Dave. It's the pesky people that
_marry into your family_ that pose the threat of name overlap. There is nothing
stopping them from marrying someone with a name that your family already has.

Now, you may be thinking that the probability of a person in your family
marrying someone with a name your family already has is low. There may have been
a time that I thought that as well. But the cold, harsh truth has reared its
ugly face in my own life. That’s right, within my immediate family, we have not
one, not two, but three name overlaps.

Two of my sisters married men with the same name. One of my wife’s sisters
married a guy named the same name as one of my wife’s brothers. And one of my
sister-in-laws has a homonym for one of my sisters names! Now, we live in this
hellish family dynamic where we have to jump through all sorts of verbal hoops
and perform myriads of linguistic gymnastics to sort this out in everyday
conversation.

It is a nightmare.

And I don't think it's all that uncommon. Let's try to find out
how common name overlaps are, and how they can be avoided.

<hr>

<h2>Methodology and Data</h2>

So this investigation is a simulation, not a survey. I just take the probability
distributions from [Social Security
Administration’s](https://www.ssa.gov/oact/babynames/) baby names dataset.
I simulate families with N children and their spouses. The children are drawn
from the top 20 names from the SSA. The spouses are drawn from all the names.

Also, I'm counting name overlaps among children and their spouses. I'm not
involving parents, grandparents, uncles, roommates, pets, etc.

<h2>Results</h2>

<h3>Name Diversity Over Time</h3>

One quick note about names. Our names have become much more diverse in recent
years, as evidenced by the graph below. Back in 1880, the top 20 names for the
year accounted for nearly 57.2% of all male names and almost 36.4% for all
female names! Compare that to 2017, where the top 20 male names account for
below 14.33% and female is 13.3%

<img src="/assets/01-name-overlap.png">

Presumably, the name overlap problem would have been much worse in 1880. How did
they even work! Every day of their lives was probably a "Too Many Daves"
situation!

<h3>Only 90's Kids Will Remember...</h3>

To keep things simple, let’s just look at names from one year, 1990.

I ran 55 family configurations: from 1 to 10 children, and varying the number of
females in the family (0% to 100%). For each configuration, I did 1000 random
samples. 

As an aside, I’m making two important assumptions. First, I’m assuming all the
children are born in 1990. Yes, the simulations with 10 children 
decuplets! Also, I’m assuming that the children each marry someone also born in
1990 . No marrying someone older/younger than yourself!

Consider the chart below. 

<img src="/assets/02-name-overlap.png">

Note a couple of things.

First, The higher number of children you have, the higher likelihood of a name
overlap. With 5 children, you're already starting to reach the 20% mark of
having a name overlap.

Second, notice how having more equal numbers of male and female children raises
the probability. There are still overlaps with all male or all female families,
but not as many. 

These are pretty high probabilities! But perhaps you're thinking that this is
all contrived, because we're picking the top 20 names, but if you picked
slightly less common names, the probabilities wouldn't be nearly as high.

Not so. Check out this chart below, which is picking from the top 100 names.

<img src="/assets/03-name-overlap.png">

You're still in the 12-16% range for a family of 5! I feel like that's high!
However, the probabilities do go down across the board. I'm sure that if you
picked from the top 1,000 or 10,000 names, you could mitigate the likelihood
more.

<h2>Conclusion</h2>

We identified a few ways to avoid the nightmare of having name overlaps in your
immediate family

* Have fewer children

* Have all boys or all girls. Equal numbers of each gender is bad news!

* Name your children with less common names

* Try your best to not have children in the 1880s.

Unfortunately, my analysis only includes name overlap among children and their
spouses. Even in this limited scope, things look grim. And this is for you
children _you_ get to name!

I have _not_ taken into account name overlap across in law families, among
uncles, grandparents, nieces, or nephews. The problem only gets worse!

So, I guess my parting word is, good luck.
