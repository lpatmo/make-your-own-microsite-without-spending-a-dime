# Make Your Own Microsite without Spending a Dime

### Training Tag(s): Advanced Online Organizing
#### Starts: Friday, Jul. 15 4:00 PM
#### Ends: Friday, Jul. 15 5:15 PM
#### Room: 102
#### Trainer: Linda Peng (http://twitter.com/lpnotes), Developer at We Also Walk Dogs ([Actionkit.com](http://actionkit.com))

In this workshop, you’ll learn enough HTML/CSS to create (and understand how to edit) your very own microsite. We’ll show you how to get your new website hosted for free on Github Pages, how to attach a custom domain name to your newly launched site and how to create your own online community (including how to embed a signup form) using platforms like Slack, Facebook, or Mailchimp. Plus, the technical skills you’ll learn can be applied to other parts of your work, allowing you to master tasks like creating email templates and modifying WordPress sites.

This training is an introduction to web development for online organizers who want to learn how to launch their own microsite for free. No prior experience with HTML, CSS or Git is needed.

To get the most out of the workshop, please bring your laptop and join the [Facebook Group](https://www.facebook.com/groups/lindatraining).

## What you need to bring
1. A laptop
2. A bit of faith in magic.

## Remember:
1. You can do it!!!
2. Please ask for help when you get stuck. Post your question on the Facebook group.

## Schedule
4pm-4:40pm - Walkthrough and explanations

4:40pm-5:15pm - Q&A, Implementation Help


## Setup
1. Join the Facebook group here: [https://www.facebook.com/groups/lindatraining](https://www.facebook.com/groups/lindatraining)
2. Create a github account, and download Git from https://git-scm.com/download/win if you're on a Windows machine and https://git-scm.com/download/mac if you're on a mac machine. We'll be using Github to host our small website. Github offers revision control and source code management, and is often used to host public open-sourced software projects.
3. Fork this repository by going to https://github.com/lpatmo/make-your-own-microsite-without-spending-a-dime and clicking on the "fork" button.
4. Download Sublime (https://www.sublimetext.com/) if you don't already have a favorite text editor.
5. Open up your Terminal or PowerShell. (On a mac, find it in Applications -> Utilities)
6. Navigate to your file path of choice using `ls` and `cd` on Mac, or `dir` and `cd` on Windows.
7. `git clone` your repository into a folder of your choice: 
```$ git clone https://github.com/lpatmo/make-your-own-microsite-without-spending-a-dime.git microsite```
8. Click to open up the project *folder* in your text editor of choice.
9. Right click and grab the URL of the index.html page of your project. Paste it into your web browser.

## HTML and CSS walkthrough
- HTML (building blocks, inline vs. block elements)
	- font styles ([Google Fonts](https://fonts.google.com/))
	- h1, h2, h3, etc.
	- Facebook og tags
	- <p>
	- <a href="" target="_blank">Link</a>
	- <span> vs. <div>
	- <img src="something.jpg"/>
	- <br />
- CSS (styling)
	- classes vs. IDs
	- You choose the selector names.
	- [Comprehensive CSS reference from Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
	- [Clearfix](http://stackoverflow.com/questions/8554043/what-is-clearfix)
- What are media queries?
- How to save images in the `images` folder and URL paths
- JSFiddle.net, CodePen.io, etc.
- WEB INSPECTOR DEMO (it's the most useful tool you'll have!)

### HTML and CSS Practice
- How do I change the color theme of the site?
- How do I change the background?
- How do I change the font style of all my fonts?
- How do I do something I don't know how to do? (Google)
- How do I make the title bigger?
- How do I move the sidebar to the left instead of the right?
- How do I add a bit of spacing between sidebar and the <article>? (padding vs. margin)


## How do I deploy my site?
1. Why use Git? (audience question)
2. `git status`, `git add .`, `git commit -am "commit message"`, and `git push`
3. Create a branch named `gh-pages`: ```$ git checkout -b gh-pages```
Make sure your home page is at the base of your repo directory and is named index.html so that GitHub knows to display it. If you're not sure what branch you're in, type `$ git branch`. If you want to switch to another branch, type `$ git checkout [NAME OF OTHER BRANCH]`.
4. Push your new branch to Github: ```$ git push origin gh-pages```
5. After a few minutes, you'll see your brand new microsite at http://username.github.io/projectName/ 

## What if I want a custom domain name?
0. Domain names can cost anywhere from $0.99 cents/year to a few thousand dollars. Typically, I would expect to pay between $10-$15 per year for a domain.
1. If you've bought a domain name from NameCheap, follow the instructions [here](https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages).
2. If you've bought a domain name from GoDaddy, follow the instructions [here](http://mycyberuniverse.com/web/configuring-a-godaddy-domain-name-with-github-pages.html)


## "I'm stuck!" Tips
1. Look at the suggestion in your Power Shell or Terminal.
2. Google the error message or the thing you're trying to do!
3. Talk out the problem with someone sitting near you.
4. Post your error or a question on the [Facebook Group](https://www.facebook.com/groups/lindatraining)

