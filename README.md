# bone-stock-site

Make sure git is installed, I recommend using homebrew.

About homebrew
https://brew.sh/

Installing homebrew & git instructions:
https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-mac-md

Create a github account.

How to add SSH keys to a github account:

https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/#platform-mac

Fork the repo in your account.

clone your repo:

It will look something like this, but instead of my account name, it will be yours

    git clone git@github.com:bradchesney79/bone-stock-site.git

You will automatically be in what is called a branch, the name of the branch will be "master".

Create a new branch:

(this is an advanced usage, you can create a branch then check it out separately-- just learn this shortcut from the beginning)

    git checkout -b 20190213-my-branch

Make a change in the code:

Add title text...
Maybe something in the body...

Save the file.

Check the status of the files:

    git status

Add the files to the tracking index:

    git add index.html

(optionally you can add all the files listed by status with "git add .")

Now you have to commit them to the versioning system, a specific marker for the state of the code at this point in time on your branch:

  git commit -m"add content to index.html"

(The -m"message" switch is how you give a human readable indicator as to what you changed.)

Push your changes to your repo:

    git push origin 20190213-my-branch

At this point ping me with a text that has a link to your github repo.

That link will look like this:

https://github.com/bradchesney79/bone-stock-site

Atlassian, the makers of bitbucket have a good intro tutorial that is better and more in depth-- but it is a lot the same.

https://www.atlassian.com/git/tutorials

Bitbucket is a direct competitor service to github... they are crazy similar. Atlassian is qualified to teach git.

You probably won't need anything in Migrating to Git and you can probably hold off on the Advanced stuff.

Atlassian also makes the "free" Source Tree git GUI
What I feel is better is git Tower for Mac, but it is not free


Feel free to ping me with questions.
