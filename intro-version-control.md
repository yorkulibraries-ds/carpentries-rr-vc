# Introduction to Version Control

## Recording the history of your projects
### What is version control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

### Why is version control important?
Version control is better than mailing files back and forth!
- Nothing committed to version control is lost. 
- Saving previous versions allows us to revert back to previous versions as needed, much like an "undo" button.
- Version control systems automatically notifies users when another teammate overlooks or overwrites someone elses changes.

## Question?
How do you record the history of your projects?

### Bad - Run on file names
![final_PhD](https://user-images.githubusercontent.com/57642282/201141942-94b3395a-9972-442c-a5d9-3d085b28d42a.png)

[PhD Comics](http://www.phdcomics.com)

### Good - Informatively named files
```
   2013-10-14_manuscriptFish.doc
   2013-10-30_manuscriptFish.doc
   2013-11-05_manusctiptFish_intitialRyanEdits.doc
   2013-11-10_manuscriptFish.doc
   2013-11-11_manuscriptFish.doc
   2013-11-15_manuscriptFish.doc
   2013-11-30_manuscriptFish.doc
   2013-12-01_manuscriptFish.doc
   2013-12-02_manuscriptFish_PNASsubmitted.doc
   2014-01-03_manuscriptFish_PLOSsubmitted.doc
   2014-02-15_manuscriptFish_PLOSrevision.doc
   2014-03-14_manuscriptFish_PLOSpublished.doc
```

## Better - Saving everything together at once

Everytime you make a save, you zip the entire directory that your project files are in and save it with a date.

## Best - Version Control
<img width="614" alt="ropensci_RNeXML" src="https://user-images.githubusercontent.com/57642282/201142849-97f7ecda-378c-44d5-a70e-2e07e5f07490.png">

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)

## How does a version control system work?
- Version control systems start with a base version of the document and then save just the changes you made at each step of the way.
- You can think of it as a tape: if you rewind the tape and start at the base document, then you can play back each change and end up with your latest version.

![software_carpentry](https://user-images.githubusercontent.com/57642282/201143207-88a9f320-7fe5-4132-9d64-3e1a3914e6ae.png)

[Software Carpentry](https://software-carpentry.org/)

- You can then think about "playing back" different sets of changes onto the base document and getting different versions of the document.

![Visual representation of merging changes](https://user-images.githubusercontent.com/57642282/201143482-23343565-8647-44a7-88b4-ce60469f5ca0.png)

[Software Carpentry](https://software-carpentry.org/)

## Git and Github
Git and GitHub are <b>not the same thing</b>. 
- Git is an open-source, version control tool created in 2005 by developers working on the Linux operating system; 
- GitHub is a company founded in 2008 that makes tools which integrate with git.<br>
<b>Source:</b> https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

## Why use Git and GitHub

### Why use Git?
- Makes you fearless
- Easy to set up
- Allows you to take a snapshot of every stage of your project history
- Takes up minimal space
- Creates a easy navigable map to the history of all changes made

### Features of using a Hosting Service Like GitHub
- Backup of your project
- No need for a server: easy to set up
- GitHub's strong community: your colleagues are probably already there
- Provides tools to help enhance collaboration
- A common location to share off your work

### Example

<img width="614" alt="ropensci_RNeXML_2" src="https://user-images.githubusercontent.com/57642282/201140953-70eb5137-8a13-4166-ba77-993be59d7921.png">

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)
