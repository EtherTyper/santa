# Santa's list
Submit your present guidelines to Santa while learning encryption ideology, JSON notation, and even git workflow. The guide is still _**being wriiten**_, much less is it even being edited and proofread, so I'd suggest that people stay away unless if they're looking to make it better.

Table of Elements:
- Part I: For Santa's Managers
  - Chapter 1: Dependencies
  - Chapter 2: Forking
    - 2.1 - GitHub Style
    - 2.2 - Local Server
- Part II: For Children

# Part I: For Santa's Managers
## Dependencies

The first thing you'll need to do to get this repository setup for your kids is to install tools or setup accounts for them, depending on how you intend to run the project.

Your kids have two main options: To do it via GitHub, which is the clean, easy system that rendered this README for you, and git, the CLI, or Command Line Interface, that GitHub does the nitty gritty on. I've found that GitHub is much easier to use than git for kids, taking away the confusion of remote versus local repositories and adding built in issue resolution systems. However, they've made some more important limiting changes as well, including the removal of distinction between fast-forward and commit merging, and the requirement to "annotate" commits and tags. It's completely your choice to make.

Also, you should think about whether to give them push access. If not, they'll have to go through a merge process with the maagement, (you), before they can submit changes, and will learn about Pull Requests. If so, they simply have to sync their commits to get them on the list immediately.

### Installing git

Navigate to <https://git-scm.com/downloads> and select the binary that's appropriate for your devices. I'm not going in depth about support, but keep in mind that git is designed for Unix like devices. Also, make sure that your kids have access to the repository, so that they can submit changes, somehow, whether it means hosted git repositories or else.
## Forking

Now, after that, you need to fork the project. Not all work can be on the Vanilla
### Through git

After everything is installed and ready, you can open git via the command line. In the top right corner of this page, there If you take that URL and plug it into a command like this:

```shell
$ git clone https://github.com/EtherTyper/santa.git
```
