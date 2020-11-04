# Hosting Resume on GitHub Pages

This is a step by step guide for publishing your resume on GitHub Pages. 
[Resume Page](https://sayeedkhannabil.github.io/mdExampleFor3040/) visit this link to see an example of a static site where a Markdown formatted resume is hosted.

## Purpose

The purpose of this guide is to show how to format a resume written in Markdown and create a static site for the resume with GitHub page and Jekyll.


## Prerequisites

Before starting, there are few prerequisites that needs to be fulfilled.

1. A  Markdown formatted resume.
1. GitHub account.
1. Git (optional)
1. Idea about Markdown syntax

Markdown is a lightweight markup language that is used to format text. A Markdown formatted resume is simply a resume written with Markdown language. To proceed on to the next step, you should have your own resume written with Markdown language. 

GitHub is a hosting service for git which is a distributed version control system. To create a static site with GitHub Pages, a GitHub account is mandatory.

Having a basic knowledge of Markdown syntax is necessary to edit the resume in the future.


## Instructions

* ### Creating GitHub Repository and Uploading the Documents

1. Click the '+' sign in the upper-right corner of the GitHub home page and select *New repository*. ![New Repository](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/newRepo.png?raw=true)
1. Put a name in the *Repository name*. You can add description if you want. Tick the *Add a README file* checkbox if you want to automatically create a README.md file when the repository is built.![Repo Name](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/rpName.png?raw=true)


1. Click 'Add file' and select 'upload files'. ![Upload file](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/upload.png?raw=true)
1. The name of the file of resume must be *index.md*.
1. Write something in the 'commit changes' box and press 'commit changes' button. ![commit changes](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/afup.png?raw=true)

From Etter's book, we know that Distributed version control system is a great a way make contribution easier for developers. With GitHub, you can have all of the benefits of a distributed version control. You will be able to change anything in real time and be able to see the changes after a few time in the GitHub Pages. You will also be able to give permission to anyone that want to contribute on your GitHub Pages and they will be able to do it from their own machine.

* ### Creating GitHub Pages with Jekyll

1. Go to 'Settings'. ![settings](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/settings.png?raw=true)
1. Scroll Down to 'GitHub Pages'.
1. Click *none* and select branch *main*. Then click *save*. After a while you will your site will be published. ![publish](https://github.com/sayeedkhannabil/mdExampleFor3040/blob/main/images/GitHubpages.png?raw=true)
1. Select *Change Theme* and click the theme you want. Then press *select theme* to apply the desired theme.

According to Etters's book, Static Websites is great for speed, simplicity, portability, and security. GitHub Pages is very convenient for making static sites. There is nothing to worry about the site getting hacked.  And since its a static site, crashing the sites is almost impossible. But to add more functionality to the site, using a site generator use necessary. Jekyll is such a site generator. Static site generator basically creates a working website, if provided with a lightweight markup content and a theme. 



Here is a example of how the final version will look like. ![gif](https://media.giphy.com/media/XnQyascxmzQlz4gIEO/giphy.gif)


* ### More Resources

* [Markdown Tutorial](https://www.markdowntutorial.com/)

* [Modern Technical Writing](https://www.amazon.ca/s?k=modern+technical+writing+by+andrew+etter&crid=2BPWTAVDA01EL&sprefix=modern+tech%2Caps%2C438&ref=nb_sb_ss_ts-oa-p_3_11)

* [Jekyll Themes](https://jekyllthemes.io/)



## Authors and Acknowledgment

This article is written by [sayeedkhannabil](https://github.com/sayeedkhannabil).

Credits goes to: 

* Andrew Etters's book *Modern Technical Writing*.
* Slate Jekyll theme.
* Group member of 3040



## FAQs

* Why is Markdown better than word than a word processor?

  __Ans__ : Markdown is free, convenient and make the developers interested to contribute where other editors like WYSIWYG is expensive and harder to contribute.

* Why is my resume not showing up?

  __Ans__: Sometimes it takes time to generate GitHub Pages. It is better to wait some time to check again for the published site.