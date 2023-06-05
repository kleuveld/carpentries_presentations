---
title: Carepentries git evaluation
author: Koen Leuveld
---

# Workshop details
- Date: friday 2-6-2023
- Instructor: Koen (plus Elisa for pts. 1-4 on thursday)
- Helpers: Thomas, Stephanie, Tycho, Eva


# Summary
Things went reasonably well until authenticating to GitHub: authentication through http didn't work on macs, so we had to spend a lot of time to keep the macs on board, while the windows people were waiting around. That introduced chaos that we never quite recovered from. The workshop is generally chaotic anyway, since it many people miss details here and there meaning they get into trouble later. And it's super difficult to spot some of these mistakes (like having a git repo within a git repo). Overall though, we covered all material, and people seemed to get the right ideas about what you can do with git.

# What went well

- I removed all references to git checkout, and replaced them with git restore. This also made it unnecessary to discuss advanced concepts such as detached heads.
- Describing git as a cloakroom seemed to work: git add is putting your coat on the table/desk of the cloakroom, git commit is the staff hanging away your coat.
- Having some real-life examples of git repos was nice.
- Having done a big chunk of the git lesson a day before was nice. This allowed to pretty much reach the end of the material. (Except the bit on branches I wanted to add.) 

# What can be improved

- Pacing is difficult: there are always people who miss a crucial bit. And it's not like the progamming lessons, where there's slow people and fast people, and you pace it to be the happy middle middle between the two. In the git lesson, people who seem fast at one point are behind at others. You thus really need to read the room to check if the pace is right at each point (which is difficult given the inherent chaos in the room), and have frequent recaps to allow people to catch up. Towards the end of the workshop, I went too fast here and there for everyone to follow properly.
- Related to this: displaying a history of commands is important, but complicated because there's so much fluff (git log, git status...) and at a certain point there's two terminal windows, so two sets of histories. Perhaps it's best to put all key commands of an episode on a slide that you can easily during the recap moments. Perhaps give all participants a "cheat sheet" with those same commands. This can be printed or digital.
- Http authentication doesn't work on Apple. So everyone should do ssh authentication. If you follow the commands, this shouldn't be too difficult, even if you don't understand what the commands mean (though the instructor should definitely know some basics about public key encryption). Making sure everyone has a copy of the instructions to set up ssh is needed.
- In the "Collaboration" episode I made half the people Vlad, and the other Wolfman. First, the Vlads were "owners" who did nothing while the Wolfmen ("collaborators") followed me to make changes to the repos of the Vlads. And then the roles were reversed. I think it's better if everyone just commits to the repo of their neighbor. And then everyone can check if they received the updates of their neighbors. That way everyone is doing the same thing at the same time, and you have more control over the pace.
- In that same episode, having two terminal windows open (one for owner and one for collaborators) isn't needed, and is confusing. The two terminal windows are probably worth it in the conflicts episode though.
- Maybe: the main focus of the git part we do the day before should be cloning into a github repo? We can make a GitHub repo with course materials and such. It should be private, so that authentication is required. Anyone who successfully authenticated can leave, anyone who hasn't is helped by helpers.

