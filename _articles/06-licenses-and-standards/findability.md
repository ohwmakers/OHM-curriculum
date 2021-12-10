---
layout: page
title: "Findability standards"
module: "6.4"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/07-community-and-communication.md
summary: "How to help others find your project"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---
* TOC
{:toc}

### Open hardware growth and multiple platforms/formats

Hardware projects have grown at an extreme pace over the last couple of years, in many different communities and spaces. Science, agriculture, fashion, sustainability, are some examples of specialised communities that are developing their own projects, platforms and tools for sharing.

While this is great, since it shows how OSH is growing and becoming more and more diverse, it also makes the space a bit fragmented, as several niche platforms/communities develop and they might miss progresses and solutions created by "neighbouring" colleagues.

As an example, some of these platforms are listed below, and visiting a couple of them shows the above point quite clearly. Some are specific to 3D printing, some have a wiki format, some only have projects that have been OSHWA certified (see unit 6.3 for more details on the OSWHA certification program).

|Platform|main interest|note|
|--|--|--|
|[Open Hardware Observatory](https://en.oho.wiki/wiki/Home)|Open Hardware projects|A central location for open hardware projects including an index on how open/reproducible projects are|
|[OSHWA certification directory](https://certification.oshwa.org/list.html)|Open Hardware projects|a list of open source hardware projects that have OSHWA certification|
|[Prusa Research Repository](https://www.prusaprinters.org/)|3D printing|allows users to share design files for parts that can be 3D printed|
|[Thingiverse](https://thingiverse.com)|3D printing|allows users to share design files for parts that can be 3D printed|
|[NIH 3D print exchange](https://3dprint.nih.gov/)|3D printing| focused on medical/research/educational models|
|[Instructables.com|Instructions in general (for building hardware or not)|freemium model|
|[Wikifactory](https://wikifactory.com/)|Hardware in general|platform to create instructions and guidelines|
|[Wikifab](https://wikifab.org/wiki/Accueil)|Hardware in general|platform to create instructions and guidelines|
|[Instructables](https://www.instructables.com)|Hardware in general|platform to create instructions and guidelines|
|[Hackaday.io](https://hackaday.io)|hardware in general|allows users to share design files for complete projects, no matter how simple or complex they are|
|[GitHub](https://github.com)|Software and hardware projects|platform for hosting git repositories|
|[GitLab](https://about.gitlab.com/)|Software and hardware project|platform for hosting git repositories|
|[Appropedia](https://www.appropedia.org/Welcome_to_Appropedia)|Hardware in general|Appropriate technologies wiki|
|[Open Neuroscience](https://open-neuroscience.com)|OS projects for Neurosciences|several hardware projects|


### The need for findability standards

This large number of platforms available for sharing create the need for an appropriate system to find projects.

That is, how can we make sure we have searched everywhere for a project before we start something from scratch, and also, how can we make sure our project will be found by others? We tend to think that simply having a "google" for things will give us a pretty good overview of what is available, but this often times leads to projects being missed altogether, since sometimes they do not show in the first page of google.

Also, relying on Google for this is problematic from another stand point, where we do not know what kind of algorithms are being used to bring up results, and we become dependent on this "black box" that might as well be gone tomorrow for whatever reason.

Luckily there are people working on solving this issue. Most prominent currently (as of 22/04/2021) is the [OpenKnowHow project](https://www.openknowhow.org/), which has organised a gathering with different networks working on open hardware so that they could collaboratively create and implement an [Open Hardware Standard](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/wiki), that is among other things, taking care of making OSH easier to find (see section below for more details).

### OpenKnowHow project and derivatives, and how to implement it

The Open KnowHow project has created a system that allows projects to be found, no matter in which platform they are hosted, while giving developers the opportunity to add interesting meta-data to their projects, increasing the chances of people understanding at which stage the project is, if it has been replicated by people other than the developers, if it has documentation in more than one language etc.

This increased findability is achieved when a small standardized text file (in YAML format) is created: It should contain contain links to where documentation is hosted, whether or not the project has been reproduced by a third party, what kind of tools are needed to build that specific project, if the documentation is available in different languages, if the work is a derivative of another project, keywords for the project, etc.

Once a project has this file, a webcrawler finds and indexes it in a [searchable repository](https://search.openknowhow.org/) which serves as a unifying place for all the projects that live in many different platforms.

[Appropedia](https://www.appropedia.org), a wiki portal hosting open source sustainability related projects, is a great example of the use and the development of a derivative of the Open KnowHow standard. Open KnowHow manifests can be downloaded from each project's page. Here is an example for an [grey water system](https://www.appropedia.org/AEF_greywater)

Below you will see how to add the Open KnowHow standard to your project and how to include it into the database.

### {{ site.assignment }} Add an Open KnowHow manifesto to your project

- Follow [these instructions](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/wiki) to create a .yml file to include your project in [openknowhow.org](https://openknowhow.org) (You can use [this online form](https://okh.makernet.org/form) to create the .yml file)

### Resources
- [Open Know-How manifest](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/src/branch/master/1)
- [Open Know-How searchable database](https://search.openknowhow.org/)
