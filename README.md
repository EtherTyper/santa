# Santa's list

Submit your present guidelines to Santa while learning encryption ideology, JSON notation, and even git workflow. The guide is still _**being wriiten**_, much less is it even being edited and proofread, so I'd suggest that people stay away unless if they're looking to make it better.

Table of Elements:
- Part I: For Santa's Managers
  - Chapter 1: Dependencies
    - 1.1 Installing git
    - 1.2 Getting GitHub
    - 1.3 Congrats!
  - Chapter 2: Forking
    - 2.1 Local Server
    - 2.2 Through GitHub
    - 2.3 Almost Done
  - Chapter 3: Access
    - 3.1 Local Server: Push Access
    - 3.2 Through GitHub: Collaborator Access
    - 3.3 You're Dismissed
  - Chapter 4: Management
    - 4.1 Why Self Manage
    - 4.2 Local Server: Patches and Pulling
    - 4.3 Through GitHub: Integrated Management and the Issues System
    - 4.4 Keeping Up
- Part II: For Santa's Elves
  - Chapter 1: Encrypting Present Guidelines

# Part I: For Santa's Managers

## Dependencies

The first thing you'll need to do to get this repository setup for your kids is to install tools or setup accounts for them, depending on how you intend to run the project.

Your kids have two main options: To do it via GitHub, which is the clean, easy system that rendered this README for you, and git, the CLI, or Command Line Interface, that GitHub does the nitty gritty on. I've found that GitHub is much easier to use than git for kids, taking away the confusion of remote versus local repositories and adding built in issue resolution systems. However, they've made some more important limiting changes as well, including the removal of distinction between fast-forward and commit merging, and the requirement to "annotate" commits and tags. It's completely your choice to make.

Also, you should think about whether to give them push access. If not, they'll have to go through a merge process with the maagement, (you), before they can submit changes, and will learn about Pull Requests. If so, they simply have to sync their commits to get them on the list immediately.

### Installing git

On an accessible family computer the repository will be easy to access from, navigate to <https://git-scm.com/downloads> and select the binary that's appropriate for your device. I would recommend a shared laptop with multiple accounts, or a wifi shared server, so your kids can communicate to the repository. However, Pro Git has much better examples for hosted git solutions in [Chapter 4.1](https://git-scm.com/book/en/v1/Git-on-the-Server-The-Protocols) than I could give.In this example, I'm going to use separate accounts on my Macbook.

Also, I'm not going in depth about support, but keep in mind that git is designed for Unix like devices. A failed git client or server can ruin the entire experience.

### Getting GitHub

Navigate to <https://github.com>, and, if you're not signed in, a login or signup prompt will appear like this:

![signin](https://cloud.githubusercontent.com/assets/16024539/12304719/9e351444-b9f6-11e5-9a83-d4e014367d5c.PNG)

Sign up as it tells you, and when you're done, you can optionally visit <https://desktop.github.com/>. I highly recommend you install this, as it lets your kids upload images, work offline, etc. And, in the end, they can still use it with the web interface.

### Congrats!

Now you have git set up and ready. In the next chapters, we'll talk about how you can setup a Christmas tradition over this efficient workplace structure. Have fun!

## Forking

Now, after that, you need to fork the project. Not all work for Santa's list can be immediately submitted to the Vanilla copy of Santa's List. However, and I say this in a serious tone, apprximately 40 example profiles from real people are welcome to be merged into this repository. Examples from y'all on the frontier makes it much easier for those who come afterward. If you think you have one while this notice is still up, shoot me a PR!

### Local Server

After everything is installed and ready, you can open git via the command line. In the top right corner of this page, there If you take that URL and plug it into a command like this:

```shell
$ git clone --bare https://github.com/EtherTyper/santa.git (OR OTHER URL IF LISTED)
Cloning into 'santa'...
remote: Counting objects: 172, done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 172 (delta 4), reused 0 (delta 0), pack-reused 162
Receiving objects: 100% (172/172), 34.07 KiB | 0 bytes/s, done.
Resolving deltas: 100% (102/102), done.
Checking connectivity... done.
```

### Through GitHub

In the top right corner of this page is a button labeled "fork".

![fork](https://cloud.githubusercontent.com/assets/16024539/12304937/ca38948e-b9f7-11e5-8efc-288dbafeadbb.png)

Click it, and your very own copy of the repository will be created. You should make it private, if you don't want other prying eyes decrypting the present data with a generic private key.

### Almost Done

Awesome! You have your own copy of Santa's List to record changes to. This is also what your kids will use if you give them push access. If not, they'll use _**their own forks**_ of _**your fork**_. Next, you need to set them up to supply patches to the list.

## Access

###### NOTE: The majority of this section takes place AFTER Part II, meaning your child should already have their own copy of your fork, and know how to use it. Separate instructions for them on how to connect to your repository is advised, as I am unaware of them protocol you chose. If you want to teach them about open source collaboration models, you can skip this chapter.

Yay! Now, you just need to give them access. This isn't quite the easy part, though.

### Local Server: Push Access

For local server purposes, I'm not going to go into authentication details, as it again depends on the protocol. In the simple, local protocol, file, everyone can push and pull who has equivalent access to the file system. As I'm writing this on a MacBook, that's the scenario I'll consider. Again, [Chapter 4.1](https://git-scm.com/book/en/v1/Git-on-the-Server-The-Protocols) of Pro Git will help.

### Through GitHub: Collaborator Access

On the front page of your repository at github.com, navigate to Settings, and then Collaborators.

![collaborators](https://cloud.githubusercontent.com/assets/16024539/12362612/e2eed8d8-bb89-11e5-857a-ad93d69f8335.PNG)

Here, you can add your little muffins' usernames, so they can directly contribute. This way, there is no need for your maintenance.

### You're dismissed

Now, your kids can use the guide in Part II to manage the repository themselves. If you or they screw something up with the JSON file, or something else, file an issue. Or, if you're willing to declassify your code.

# Part II
