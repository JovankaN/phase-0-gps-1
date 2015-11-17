#What git concepts were you struggling with prior to the GPS session?

I really only understood how to do a git pull, but had not practiced much with git fetch and git merge. I now understand these much better, though still have some outstanding questions (see below). More important than the conceptual understanding was the practice! Particularly the pull request sequence, since in week 1 we were merging our own pull requests.

#What concepts were clarified during the GPS?

I thought that merely pushing code to the remote repository constituted a pull request... I didn't realize that you had to actually go to GitHub to make the pull request. The whole process is now clearer to me, though I have to imagine some developers are so CLI-oriented that they try not to go into GitHub - is there a way to go through the pull request process from your command line?

#What questions did you ask your pair and the guide?

I asked about fetch/merge syntax. My pair and I asked about markdown syntax for embedding an image inline, since the documentation mentioned putting links but not how to put in an image (that ! is tricky).

After my guide left, my pair and I played around with a Chrome extension that lets you view markdown files via drag-and-drop, so that we could see whether our markdown attempts had been successful. I am realizing now that the extension was totally unnecessary (it was really designed to help you work offline), since we could have just opened the .md file in Chrome directly, but we got there one way or another.

#What still confuses you about git?

So we had an interesting experience... during the merge conflict section, we followed directions by adding a line to a file in a small-conflict branch and adding a different line to the same file the master branch. But then I accidentally typed git merge *origin* small-conflict instead of git merge *master* small conflict.

What I would have expected that to do was merge the remote repository (which I've understood to be origin) with the small-conflict branch. And since the remote repository hadn't had its master changed, there shouldn't have actually been any conflict - there was only one line that had been added, and that was in the small-conflict branch.

But somehow the origin had actually picked up the line change that we made to the master branch. So when we tried to merge, we got exactly the same conflict we would have gotten if we'd tried to merge master with small-conflict. This makes me think that the origin is actually a trickier concept than I'd realized - it's not just the remote version. Would love to talk to someone about this to understand better - I'm feel like I have the fundamentals so am ready to have my mind blown.

#How was your first experience of pairing in a GPS?

Really awesome. I was a bit nervous going in (as was my pair), but she was very easy and fun to work with, as was my guide. We had a good time experimenting and trying new things - there were a couple moments of "I don't know what will happen if we do this." "Let's do it then!"

We worked for a full 2 hours! So that's a good sign.