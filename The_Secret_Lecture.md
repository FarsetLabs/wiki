This is a work in progress by <User:Bolster> to share his experiences and frustrations with some of the things universities and colleges DON'T teach software engineering students.

The Big Three
=============

-   Version Control
-   Google-Foo
-   Stack Exchange

Easily, and without a doubt, if I could take one module away from the teaching schedule a year and spend that one hour teaching students just these three topics, I suspect that students would find the tasks and projects given to them significantly easier. University is very good at telling you what you should know. But (at an undergraduate level) it's terrible at making you any good at asking questions and experimenting. These three technologies change that.

Version Control
---------------

Lets get one thing straight. Any time that you are developing software at an undergraduate level (and beyond) YOU ARE GOING TO FUCK UP. Its not that you're (exceptionally) stupid, it's just the reality of not knowing everything (see later sections). Version control does three things that make it essential to development.

-   Commit to change
-   Retroactive diff
-   Branching

### Committment, for phobics

Blah blah blah joke about committment etc. The fact is that you don't build an entire project in one go (if you do, you're exceptionally stupid). You build a minimum product that gets your head around the idea, then add the bells and whistles. Committing at each stage of develop means that the changes you make since the last commit are stored and 'cast in stone'. Not only does this make it easy to understand what you were doing when you come back to the code six months later and are wondering who wrote this shit, since the change in the commit message \*should\* match the change in the code, but it also acts as a project diary without any extra work! With a bit of after-the-fact formatting, you could legitimately present your commit log as a retroactive project plan and your lecturer/supervisor will be VERY happy.

### Time Travel for Neanderthals

The show stopper, the magic of version control, is that you can go back to any point and have a fully working version of your project; you might have dozens of files that you keep adding features to, then your supervisor wants you to re-do a particular graph... (Trust me, it happens, and it's exactly as annoying as you think). With version control, you can roll back to a particular commit and have it EXACTLY AS IT WAS.

Also fantastic for subtle debugging...

### Back to the Future

Once you get to dealing with big projects where multiple people are involved, if you're not using version control effectively, you're gonna have a bad time.

Branching is the ability to say 'Hey, lads, you guys can keep working on the general stuff, but I've got this crazy idea that just might work', you 'branch' off with your 'coolshit' development line, then when you've added the feature you like, it can be merged back into the main development tree (usually without too much trouble).

Version control is a magical tool of wonder, and pain. Practise makes perfect, so use it, even for projects you don't think are 'big' enough; if you can legitimately say 'I know the ancient incantations for merging two divergeant branches in git, mercurial, and subversion', you are infinitely more likely to get the job you want than they guy who things version control is 'Windows Update'.
