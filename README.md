# Guillermo Marcos Lara - Personal Portfolio
## What I have built and why
For this project I have developed a Personal Portfolio as my submission 
for the Practical Work II assignment in my Fundamentals of Computer 
Engineering course. The objective of said assignment is to create a 
front-end website to display information about me, my career path, a 
topic of my choosing and more.

## Description of my work
The following is a description of my work, ranging from the wechnologies 
employed to each and every one pages that have been developed for the 
website.
### Technologies employed
#### Git & GitHub
For the development of this website I have employed both Git and GitHub as
a Version Control System. I have heavily relied on the command line tools,
frequently using commands such as `$git add`, `$git commit -m ""` or `$git push`.
#### HTML
The structure of the different webpages was built with HTML 5. Each webpage
followed a simple structure, consisting of a navigation bar and the content of
the webpage itself.
```html
<!-- Navegation bar -->
<header class="navbar">
    <div class="home">
        <a href="./index.html" class="fa fa-home"></a>
    </div>
    <div class="pages">
        <a href="./Public/about.html">About me</a>
        <a href="./Public/topic.html">Topic</a>
        <a href="./Public/net.html">Net</a>
        <a href="./Public/degree.html">Degree</a>
        <a href="./Public/contact.html">Contact me!</a>
    </div>
</header>
```
This is the code for the navigation bar found in every .html file.
#### CSS
The styling of the webpage was done through the use of CSS 3. The color palette 
is the following:
- Text: #E4E4F1
- Background: #030307
- Primary: #363644
- Secondary: #1b1b22
- Accent: #d53f3f

The website is reactive to the environment, and certain elements will change
color, size or layout depending on the viewport. Therefore, it is ready to bee
seen and experienced on every device, including mobile phones. Despite that, it
is recommended to be visited from a larger screen, such as a monitor or a
laptop.
#### Development Environment
Instead of an Integrated Development Environment, I have opted for a more
minimalistic approach. I used the terminal-based, opensource Neovim text
editor, a popular fork of the better known vim editor, alongside some plugins. 
For more information, feel free visit my [configuration files](https://github.com/wmarcos15/dotfiles) in my GitHub account.
### Webpages
#### Index
This is the Home Page of the website, it offers an image of my signature (for
cosmetic purposes), a navigation bar, and some links to social media accounts.
#### About me
This page is designed to display a description text (based on what it means to
be a Computer Engineer), some images, some links to social media accounts, and an
embedded CV file.
#### Topic
In this page, we cover information about Large Language Models, my group
presentation topic for the Practical Work I assignment and my chosen topic for
this one. This page offers a title and subtitle, some images and links and
naturally the always present navigation bar.
#### Net
In this page you will find links to my colleagues' Webpages, as well as a brief
description of the page and the navigation bar.
#### Degree
The different subjects and courses of my double degree studies are shown here in
a table format. The subjects are divided into courses, and there is a special
link in the row corresponding to this subject. The navigation bar is present as
well.
##### Fundamentals of Computer Engineering
This page is only accesible via the Degree page, and it shows relevant
information of the subject extracted from its teaching guide. The navigation bar 
is present as well.
#### Contact me!
This page displays a simple, non-functional contact form. Upon hitting the
Submit button, a message will appear, it is purely aesthetic, and it does not
reflect any actual funcionality. The navigation bar is present as well.

## Development Problems
I have decided to divide the problems I have encountered during the development
of this projects into the following categories:
### Git
#### Folder naming incident
At the starting phase of development, I had a directory named Css, and I decided
it would be better to rename it to css, given that it is common practice to
format all the letters in an acronym the same way. This simple, unnoticeable
change led me to a small rabbit hole that got me to `$git rm -rf Css` and `$git
add css`, as well as numuerous and annoying series of file renaming and
reordering in my local machine. 

Even though I am happy with the result of the
renaming, I do no believe that it should have taken me that long to do so. This
mistake roots from a lack of experience with git file managment. Fortunately, I
was able to solve it harmlessly and I learned in the process.
#### Extra files
At the end of the project, there were many extra, unnecessary media files, especially
images, due to numuerous changes of design. This problem was solved easily by
using the `$git rm` command.
#### Commits and good practices
In order to be able to track changes back in time, I decided early on to address
the issue of commit naming in a good manner: I would research a naming
convention and stick to it. Upon said research, I found 
[this article](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
and a few others suggesting that I use imperative mood to write the commit
headline. Even though it was my clear intention to stick to it, I found myself
being inconsistent, wich lead to messy and unclean commits. Although not a fatal
problem, following a better commit structure and better practices will help me
in the long run with larger projects which require scalability.
### CSS
#### Viewport versatility
The idea of making a reactive website that would be able to comfortably be
displayed in a mobile phone meant that I had to solve a number of issues (#1,
#4, #14, among others), as is reflected in many commits (7f45a9a and others).
### General
#### Page layout organization
The idea of orgazing one's mind before beginning to write down the layout of a
webpage should be quite ovbious, and so was it at the beginning of the project,
however, this was soon to be corrupted as I began to write before thinkning,
which inevitably led me to keep coming back to the HTML to change little parts
when adding the css. This is seen in commits such as b1f5c4c or ba5f44f.

This could have been avoided by simply planning a better
layout from the start and commiting myself to it, and so will it be avoided in
the future.
#### Code styling and good practices
The code styling was inconsistent, wich led me to write messy code wich was
sometimes hard to understand, especially when it comes to css. I solved it by
rewritting and commenting some secions.

## Conclusions
Although I was already familiar with the technologies employed, as well as with
the overall process of software design, this project has helped me become a
better, more organized developer, as I have solved practial issues that I will
encounter in real life, specially those related with fundamental habits that
help developers understand each other's codebases and porjects.

This was the first time that I wrote commits thinkning that they would be read
by somebody else, and so it was my first time ever having a second thought on
how to name them, when to make them, and when to do a push.

As I previously mentioned, this was not my first time using HTML or CSS, and the
previous experience (if somewhat limited) was extremely helpful during the
development experience.

My choice of Development Environment was also quite pleasant, and I further
explored Neovim, expanding my knowledge and experience. Using
the command line tools for git was also a known experience to me, but I had
never used Issues (a GitHub tool) to organize myself, which I did this time,
learning a new instrument.

I would say that the project was a success, in terms of both the final result
(which meets the requirement set for the assignment), and learning experience,
as I made the most of it. The website itself is simple, and difficult to scale
if it were to be necessary; this are, however, not the objectives of the project,
as it is meant to teach one how to manage a software project.

I have also learned valueable lessons for future projects, including: 
- I should better organize the structure of my code before applying it.
- I should follow better practices for commit naming and code styling.
- I have learned how to better manage a project using Git and GitHub.

That being said, I believe that the result is a good one, and the combination of
theorical learning and practical work clearly define my future job as an
engineer.
