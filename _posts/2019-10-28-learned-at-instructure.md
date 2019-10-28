--- 

layout: default 

title:  "My Internship with Instructure" 

date:   2019-10-28 11:21:00 -0700 

published: true

categories: jekyll update 

---

# What I Learned at Instructure

Over the summer I worked as a software engineering intern at Instructure.
The experience was both exciting and daunting.
My coding up to this point was mostly haphazard and personal.
I would throw some automation at tedious work processes,
perform one-off data analyses,
meet contrived and well-specified requirements for school assignments,
or cobble together messy code to address a particular need of my own.
The only person I was accountable to was myself.

My internship is my first time being paid explicitly for coding.
It's also my first time coding in collaboration with a team.
The differences are stark and exciting,
so I wanted to document what I learned working with a professional
software development team for the first time.

## My Contribution

Instructure's two major products, Canvas and Bridge,
are both learning management systems,
designed to track learning progress and scores.
Canvas targets education use cases, such as
universities and schools, while Bridge targets businesses.
I worked on Bridge, doing full stack work.
This included Ruby, Ruby on Rails, JavaScript, and React.

My project involved implementing "Learning Tool Interoperability" (LTI) features for Bridge.
LTI tools allow third-party apps (like Piazza and YouTube) to integrate with learning platforms, like Canvas and Bridge.
This goes further than just embedding an app.
LTI also transfers user authentication, which means a user can avoid logging in to an account with the third party website.
For example, say you create a website that administers online quizzes.
With LTI, a student could take your website's quiz embedded in Canvas, without needing to login or
create an account with your website.
They would just be able to take the quiz without ever leaving Canvas.
This makes the overall experience more seamless for users.

One feature LTI offers is the ability for third-party apps to send student score data.
If a student takes a quiz through an LTI tool, the tool can send their score
back to be recorded in Canvas. Bridge didn't have this feature
yet, so my summer internship focused entirely on implementing it.
I had to read the LTI spec,
plan how to implement it with Bridge, and execute on that plan.
It was a great project, that exposed
me to many facets of software engineering.

## Working with a Software Team

As I said, this was my first "real" software engineering job.
My code wasn't just for my own use--it had to be up to standard for my team.
And to be sure, Instructure's software practices and standards are impressive!
It makes sense,
since they're primarily a software company.
But it was gratifying to work with a
company and a team that maintains and develops software in such a disciplined manner.

My team used Scrum (we scrummed?). To a meticulous planner such as myself, the Scrum workflow is appealing.
Plan a sprint, report progress via daily standups, and
reflect on setbacks and accomplishments after two weeks.
I loved it.
I could see how a team might start going through the 
motions of the workflow, but at least with my team, it appeared highly productive and meaningful.

My project required careful planning and collaboration with other teams.
I needed to coordinate a testing strategy with the QA team,
and consider user concerns with the product team.
It was great to collaborate with these two teams in my project, and I appreciated the support.
Building a quality product is everyone's responsibility, but the separation
of concerns at the job level seems effective to me.

In particular, I appreciated the product team.
Designing a coherent user experience is something I need to work on.
There are so many aspects that I'm still not used to thinking about.
So it was helpful to work with people whose whole job is to take the user into consideration.

Instructure also conducts review on all committed code, before it gets pushed to production.
Code reviews were the most effective learning opportunities for me.
Feedback on the quality of my code, when I was introducing unnecessary complexity, or reinventing the wheel,
was incredibly helpful as I was learning Ruby and the Instructure codebase.
It taught me better coding practices, style, and approaches.

## Improvements for Next Time

Before starting the internship, I worked my way through two books to learn Ruby and Ruby on Rails:
_Learn Enough Ruby to be Dangerous_ and _Ruby on Rails Tutorial_ (both by Michael Hartl).
While I'm glad I spent time familiarizing myself with the language, I think I could have been more effective.
There was no reason to spend a lot of time literally copying the project presented in the books.
About a month into my internship, I decided to start making my own rails project (a cook book
app), and that did a lot more for me in terms of understanding the Rails framework.
Learning a little from the book, and then applying what I learned to a project of my own, seems like a better approach.

Another improvement would be seeking feedback early and often.
The first few weeks, I wanted to avoid being perceived as a burden, so I was more willing to take a long time figuring things out on my own.
But not only did this make my first few weeks a bit tedious, it also delayed learning some non-obvious things up front that
could have been useful. If I did it again, I'd be a somewhat "leaky faucet" at the beginning, asking lots of questions.

## Conclusion

Instructure was a phenomenal company to intern with.
I was impressed with their software engineering culture, and their committment to excellence.
I also appreciate that they took a chance on someone like me, without any software engineering experience.
Instructure comes highly recommended!
