# iOS-Code-Review
Code review checklist for iOS


## Definition of Code Review:

### According to Wikipedia :

Code review is systematic examination (sometimes referred to as peer review) of computer source code. It is intended to find mistakes overlooked in the initial development phase, improving the overall quality of software.

#### What should you care about when doing a review?

You definitely should check code integrity — does the style match previous solutions, does it follow agreed conventions? Are features implemented correctly(for this point i would advice if the PR creator could add .GIF image that explain how the feature works that would be nice), does the old source code work correctly after changes?

#### Why you should care about code review in your development process?

For sure because it ensures code integrity :) , catches what others’ eyes didn’t see. It allows to learn and share your knowledge and expertise, strengthens communication in the team and builds good relationships due to conversations about what you have in common — code and programming skills ;)!

    Personally i have seen that lately in my current project. the team had problems in communication but after conversations we did in code review the communication became much more better.

Consider code review as an investment into the future. If you don’t catch bugs now you will definitely have to conquer them in the future.

#### What if you didn’t perform code reviews

Imagine a company X. It delivers mobile app solutions for multiple clients. Their team is small and at some point they cannot meet clients’ demands. So they decide to outsource some of the work to an external company. They give project requirements to this company and meet again after 3 months to receive app source code. But the app is useless — it freezes at network calls, CoreData.ConcurrencyDebug flag crashes all the time. The project is delayed for a few months, team has to start from a scratch. They wish they had reviewed outsourced code on a daily basis…

#### Do you want to perform code reviews?

This is usually the question that gets lack of enthusiasm from the audience :(. But really, are we too busy to improve??

This was an introduction to code review. Now let’s get deeper into the code review process, present some tips & tricks when performing a review and also focus on some mistakes when reviewing a swift code.

As iOS developer most of things i think of are somehow related to iOS platform as of now Swift is my main programming language, but i think there are generic things not related to the platform or specific programming language. So let’s spill them out 🚀
General Tips:

    It is said that a review goes best when conducted on less than 400 lines of code at a time. You should do a proper and slow review, however, don’t spend on it more than 90 minutes ⏰

you definitely will get tired after that time. It’s tiring to write and understand your own code and it’s even more tiring to understand someone’s.

After some years of experience in software development you know what common programming mistakes are. You also do realize what solutions to common problems are most efficient. It’s a good practice to write it down and to check code being reviewed against a checklist ✅ — it leads improved results. Checklists are especially important for reviewers because, if the author forgets a task, the reviewer is likely to miss it too.

In the git flow mentioned, code can get merged after receiving agreed number of approvals for a pull request. The number should depend on your team size, but it’s good to get at least ⓵ !😀

When you recommend fixes to the code, suggest their importance 💬. Maybe some of them could be postponed and extracted as separate tasks. Before approving a pull request, verify that defects are fixed 🔧🔨.

Spread in your company a Good Code Review Culture in which finding defects is viewed positively 😀. The point of software code review is to eliminate as many defects as possible, regardless of who “caused” the error. Few things feel better than getting praise from a peer. Reward developers for growth and effort. Offer as many positive comments as possible. I always try to put a line saying that a solution is good and clever (if it really is 😉).

You can also benefit from The Ego Effect 💎. The Ego Effect drives developers to write better code because they know that others will be looking at their code and their metrics. No one wants to be known as the guy who makes all those junior-level mistakes. The Ego Effect drives developers to review their own work carefully before passing it on to others.

And don’t bother with code formatting style …

… there are much better things on which to spend your time, than arguing ☔️ over the placement of white spaces.

Looking for bugs and performance issues is the primary goal and is where the majority of your time should be spent.


## Points 
1. Git flow
2. Git commit messages
3. Naming Conventions
4. Whitespace Rule
5. Important coding standards
