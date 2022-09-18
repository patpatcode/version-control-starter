# Version control homework starter

_HELLO_, and welcome to this homework on version control.

In this homework assignment, you'll use version control to
track changes to some files. It's easy and fun (for me).

## Short instructions

After starting the assignment by accepting the GitHub Classroom invitation,
you'll have a repo on GitHub with this file in it. I want to to add a file to
that repo called "me.txt". That file needs to have your class nickname
somewhere in it. My class nickname is "bald-chicken". Yours is different.
Add that file to your repo and commit it. 

## Verbose instructions

This file is called `README.md`, and it is written
in [markdown](https://en.wikipedia.org/wiki/Markdown)
format, which is a popular format for writing documentation.
If you're looking at the file on GitHub, it is likely that
the Markdown has been compiled to HTML for your viewing
pleasure. In that case, it will have clickable links,
text with different formatting, and other niceties.

I'm about to commit this file to version control. In fact,
I'll do so right now. There, it is done. I just made commit
`549436792173a8addb41f3ad46442ef5ecd1c468`---a unique commit
hash (or id) that has never before existed and shall never
again in the entire history and future of space time. Now
I'll make another. Boom, done.

If I type `git log` on my computer's terminal (if I'm in
the directory where this file is), I see the following output

```
commit 24ba3842101024b1c7b4a1baa5d0f3f6bd722729 (HEAD -> refs/heads/main)
Author: Kyle L. Jensen <kljensen@gmail.com>
Date:   Mon Aug 12 14:41:42 2022 -0400

    Continue to pontificate

commit 549436792173a8addb41f3ad46442ef5ecd1c468
Author: Kyle L. Jensen <kljensen@gmail.com>
Date:   Mon Aug 12 14:41:04 2022 -0400

    Initial commit. I LOVE VERSION CONTROL
```

I want you to do more-or-less what I just did. I want you to create a file
called "me.txt" and put your class nickname into it. Your class nickname is
something like "silly-eagle" and you can find it in your "dashboard" on the
class website. The names are randomly generated and unique per class member.

How can do you do that? Well, the _easiest_ way is to use GitHub CodeSpaces
to do your work in the cloud. But, you can also do it on your laptop! Most
"real" developers would do such a thing on their laptop.

Here's how you do the assignment on GitHub. After you accept the invite for
this assignment, go to your assignment's repo.

1) Click on the green "Code" button in your repo.
2) Click on "create codespace" or similar. Wait while the VM is created.
3) You should be sitting now in a web-version of the code editor called "Visual Studio Code".
4) Use your judgement, figure out how to create a file called `me.txt` that has
   your class nickname in it. Save that file.
5) Do `git add me.txt` and then `git commit -m "add file with my nickname"`
6) Do `git push origin main` to push your edited repo up to GitHub.
7) Browse your GitHub assignment repo in another tab and verify that your
   `me.txt` file appears in your `main` branch.
8) Close the editor.

Kyle will post a video of all this.

