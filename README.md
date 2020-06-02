# Getting started with git & GitHub

Right now, this repository contains only these instructions. Your mission, should you choose to accept it, is to add a new file containing your name, one sentence about how you're feeling about Code for Good, and one thing you want to learn this summer.

The name of this file should be your_name.txt, so I would upload a file called `caroline_kaufman.txt`, and it might say:

```Caroline Kaufman

I'm super excited about Code for Good, really happy to reconnect with students I've seen around Halligan and friends who graduated ahead of me, and psyched to see what this awesome team can achieve this summer!

I'm hoping to learn more about mentorship and the qualities/practices of great mentors, and I'm excited to chat with and learn from folks who are interested in tech ethics, data privacy, tech policy, etc too!
```

Ready?

# One step at a time

1. Clone this repository. Click the green button that says "clone or download", copy the URL, open up your terminal, and run `git clone THAT_URL`

2. You should now have a local copy of this project. `cd` into the directory.

3. `git pull` to make sure that your local version of the repository is up to date. Good to go? Now check out your own branch using the command `git checkout -b carolinesbranch`, or whatever you'd like to name your branch. A branch represents one state of a project, and branching is really useful for working on projects in groups! Branching means that I can work on one feature while my teammate works on something else, and we can merge everything back together when we're done.

4. Now, use your favorite text editor to create your file, and fill in the information. Personally, I like vim!

5. Save your file, and run `git status` - you should now see that you have a new file that doesn't exist in the remote repository!

6. Add and commit your file - git tracks all changes to a repository, and when you've made all of the changes you want to make for a particular step in your project, you'll "commit" those changes and upload them to be reviewed by your team. Lexi will go over all of this in the workshop on Thursday! First, `git add YOURFILENAME`, and then `git commit -m "Some message here"`. You can make the message anything you want, you just want it to describe the changes you've made!

7. Now, you've got your changes committed locally, and your next step is to "push" them up to the remote repository on GitHub. To do this, because you created the branch on your local machine, you'll probably need to ask GitHub to create a version of that branch on the remote repository. To do this, you'll run `git push --set-upstream origin YOURBRANCHNAME`.

8. If you navigate back to GitHub, you should now see your branch, and you should be able to open a pull request. A pull request should describe the changes you've made, and it will allow your teammates to review your code before merging it into the project. In this case, I will review your pull request, take a look at your file, and merge it into our repo!

This is a very high-level overview that covers some of the steps but doesn't do much in the way of explaining – if you get stuck, the #git channel is your friend, and if anything feels confusing or you don't understand why you're doing any of this, please tune into Lexi's workshop on Thursday!!!
