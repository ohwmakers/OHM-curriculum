---
layout: page
title: "Documenting for whom?"
module: "3.5"
date: 2016-10-06 14:05:56
time: "20 min"
following: _articles/04-open-hardware-specifics.md
summary: "Open hardware projects and their audiences"
prereq: "Have completed all previous sections and modules"
materials: "Pen or pencil and paper"
---
<p align="center">
<img src="https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/img/work_in_progress_banner.svg" width="80%"/>
</p>
* TOC
{:toc}

### Content

#### Plan you documentation before you actually start documenting

Documenting your project is a really crucial step and really makes the difference on whether a project is only going to be usable by its creators, or by a wider community. In open projects, where creators/developers are encouraged to share their work early and often, documentation should be considered a "living", often changing part of the project, and "waiting for the project to be done" before starting documentation increases the chances that documentation stays on the "back burner" for too long, preventing others from contributing/using your work. 

Therefore, it is a good idea to think about how, what and in which system you are going to document your project. Additionally(see below), you should also think about who is your audience and what kind of information they need to be able to join as users and/or developers. 

Here are some suggestions on what to consider before starting your documentation plan:

- Every time you work on your project, set aside sometime to take notes, make drawings, photos, small videos of what you have done. Both negative and positive outcomes should be documented! (knowing what does not work is as important as knowing what works). This will save a lot of work down the line and give others a sense of where the project is going and the rationale between certain decisions.
- Keep language in your documentation simple and precise, try to avoid jargon where possible (and when not possible, try to explain what the jargon means) remember that not everyone has the same language level and/or are not as knowlegeable in the field as you are. 
- Make sure you are using tools to document your project that are easy access for you and others, and also that allow for your work to be easily exported to other formats/hosted in different platforms (see below).

#### Docs for users/devs/building
  - ##### Differentiate between user and developer branches/versions
  
  When thinking about project documentation, one should think about the different "audiences" that will be interacting with your project (for instance, a project will have users and developers), and also the different branches of a project (at some point there could be a working prototype that users can test and try, and a development prototype where new things are being created/improved).

  In order to accomodate for these two different aspects (audience and branches), projects should consider compartimentalizing their documentation, that is, create different documentation packages that cater for these different things:
  
  - One package, aimed at users, should be about building and using the tool described in the project
    - It should include things like the bill of materials, what skills are needed in order to build it (is soldering required? do I need to be able to work with glass? etc), 
    - how to put all components together and in which order. 
    - Optimally it should contain information about testing the device for the first time to make sure things work properly, what are common failures and how to solve them (troubleshooting), and how to calibrate/maintain the device, to make sure it works well over time.
  
  - One package, aimed at developers, should be about the "guts" of the device, what software it is using, how all the internal parts are connected, how the hardware communicates with the software and with other parts. Including known issues and limitations is also a good thing, as together with a list of wished improvements they help guide the work of developers.



  - ##### Documentation needs to be easy to use/modify (using mature OS tools and text formats contributes to that)
  
  Besides thinking about to whom and what kind of documentation your project needs, you should also think about how you are going to distribute your documentation. Sharing the documentation in editable format allows others to also work on the documentation, either to improve it (by creating a translation for instance), or to adapt to their possible variants of your project.
  
  The most common editable formats are from "traditional" word processing software, such as Microsoft Word, LibreOffice, Google Docs, etc. While it is completely fine to work with them, they are not very handy when it comes to adding other media, such as photos, videos, drawings etc. 
  
  Luckly there are other formats available that are more friendly towards these type of media being embbeded and formatted in the documentation. One of those formats is Markdown, a plain text formatting syntax that allows texts to easily be rendered and converted to many different formats (PDF, HTML, .DOC, etc). More details about it can be found [here](https://www.ultraedit.com/company/blog/community/what-is-markdown-why-use-it.html). In fact this entire curriculum is written in Markdown! take a look [here](https://raw.githubusercontent.com/ohwmakers/OHM-curriculum/gh-pages/_articles/03-building-open-projects/docs-for-whom.md) to see this page as its original Markdown writeup.

  We highly recommend projects to adopt Markdown as their writing format, BUT if you cannot invest the time to learn and use it at the moment, stick to the tool you are most confortable with! After all, the MOST MOST important thing is that you document your project and share it in an easy to access editable format so that others can contribute to it!


  - ##### language is different (NOTE ANDRE: not sure what this means)

### {{ site.assignment }} Make a plan for your documentation
- Decide on a writing platform/system
- Make sure you regurlarly dedicate time to work on documenting things
- Remember that documentation needs to be aimed at different audiences:
  - Users with different initial knowledge and skills
  - Developers that can bring skills and help to different project aspects



### Resources

#### Markdown 
https://www.ultraedit.com/company/blog/community/what-is-markdown-why-use-it.html  
https://hackmd.io/  

#### Documentation tools
https://www.docubricks.com/  
https://gitbuilding.io/  
