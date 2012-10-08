!SLIDE
# Git It On
Git is the latest and most exciting piece of SCM in a long time, even better it's 100% open source.  Git is now the main source control on drupal.org. Easy to install and super flexible, source control isn't just for the corporate types anymore.    This introductory session highlights how to use Git not only as a source control client in a team setting, but how to manage just about any kind of electronic information.

   Providing the unique perspectives of a serial team developer and a freelance designer, this session will cover topics like:

!SLIDE
# How to set up your repository
  How to use it, screencast of installing it (on mac?), creating a repo.
    Possibly add integration to Netbeans, Eclipse.
  ## Ubuntu
  ## Mac
  ## Windoze?

!SLIDE
# How to commit

  ## Make changes, rewrite, delete, mutate, etc.
  ## Commit it & push
!SLIDE
# How to share with others
  Getting it offsite (GH, Bitbucket, self-hosted with an rPi)
    Benefits of getting it offsite - dead hard drives happen


!SLIDE
# Branching and merging to maximize efficiency on a project

!SLIDE
# How to use git to do other neat things besides manage your project code
  Use it to manage your configuration files, your memoires, that novel you;ve been kicking around in your head, heck even a blog (GH pages).

!SLIDE
# How to contribute back to the community by using git

This could be a presentation in & of itself. But the best way to get involved using git is to use git to submit patches on D.O.  For the uninitiated, here's the cliff notes version.
  Step 1: Discover bug.
  Step 2: Find fix.
  Step 3: Clone project.
  Step 4: Make fix on git clone.
  Step 5: Make patch.
  Step 6: Submit patch.
  Step 7: Glory in the victory.

http://drupal.org/documentation/git

http://drupal.org/node/707484


!SLIDE
# Tricky tips and tricks to make git fly - with a publicly shared git config file, shared using (what else) GIT!
  git tips and tricks, whiz bangs and headslappers
    Post gitconfig to GH

!SLIDE
# Why git is so special, why should anyone who works in web design / development should use it.
       git remembers your past.
        It remembers everything, including passwords
        git reset -> git commit --amend -> change pwd - you're hosed.
        Everything's in patches, can be emailed.

    Git can be used offline, like on the train, or on a 9 hour flight to Sao Paulo, nudge nudge.
!SLIDE
    Encourages a branching style of concurrent development
      Why concurrent - more stable - bandwidth
      BASE - Mike - views - panels - features - custom fields
        \                                                       \ Merge
         Marlene - theme - jQuery - views tpls (pay attention)   - merge branches - resolve merge conflict - deploy and happy day
     GH also has this neat concept called pull request, which is basically you asking for a branch merge.

     What if DEV X's code was crap - cherry picking the best commits is trivial.
     Branching branches, why not?  But that goes into the weeds.

!SLIDE
# Identifying the suck, how git helps find what broke & (if you care) whodunnit.

        Git bisect makes finding the bug, post commit, easier.
        Binary search, start with good and bad, find bad

        Git blame - "For instance, Git can instantly tell you where does THIS LINE come from, even if this line moved across different files over years."

!SLIDE
# Besides D.O. who else is using Git?  (Hint: the answer may surprise you)
  Linux Kernal, Ruby, Gnome, Microsoft, Netflix, Android, Facebook, Google, Perl, PostgreSQL, Rails, Gnome, KDE, X.org, and more.

!SLIDE
## Government:
  We the People is a petition webapp that allows authenticated users to submit petitions directly to the Whitehouse.  Guess what, it's a Drupal distro (insert kermit freak gif).

  NASA has a GH acct.

!SLIDE
  German legislature now has released their draft legislation on GH, this is HUGE.  Github's repos can be made public, so now ppl can view ammendments to pending legislation.
  Laws are the operating system of society, the scope of the project is enormous and the clients expectations can be a nightmare.
  Not only are the laws on GH, but tools to implement this locally. https://github.com/bundestag/gesetze-tools

!SLIDE
Education: Bill Fitzgerald from Portland's own Funny Monkey suggested that git could be used by teachers to build, share and maintain curricula. Info graphic included: https://s3.amazonaws.com/easel.ly/all_easels/33386/Teacher_Git/image.jpg   http://funnymonkey.com/thinking-about-the-verbs

Warning: This session may contain odd humor, awkward metaphors, sudden flashes of inspiration and an intense desire to register for a GitHub account.

