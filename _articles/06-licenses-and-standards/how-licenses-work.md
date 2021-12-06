---
layout: page
title: "How licenses work"
module: "6.1"
date: 2021-04-07 14:05:56
#time: "30 min"
following: _articles/06-licenses-and-standards/oh-licenses.md
summary: "And how they can work for your project"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---
* TOC
{:toc}

### Licenses and patents

A common question people developing open projects get is “Are you not afraid that if you do not patent/protect your idea, China/boogeyman/next door neighbour is simply going to copy you and take your project/community away from you?”.

A common concept when starting a new project/idea is that it needs to be protected at all costs, otherwise potential competitors would simply come by and steal it away, making it faster, better and cheaper than you.

Well known protection mechanisms are copyright law and patents. Which in their own way give exclusive rights to develop/explore a certain idea/resource to the copyright/patent holders. In principle, this is not a terrible idea per se, as when they first started, they were thought to be giving developers time and space to properly develop their ideas and bring excellent tools/projects/art to the wider public. In a way incentivising innovation and creative work.

Unfortunately, as a lot of things that do not get revised and updated, these systems have been shown to actually work against innovation, making the innovative process more expensive, slower and generating things that only reach a few hands. Moreover, when ideas are patented they also prevent people from working on them as a base for their work, so there is a smaller number of derivative work.

Maybe this will become clearer with a practical recent example: 3D printers.

Fused deposition modelling 3D printing technology has been available since the 1980's when the first designs for creating a 3D printer using plastic filament as "ink" were patented by Stratasys. Over the next 30 years, while the patents were active, 3D printers were big, expensive machines, only available for companies with deep pockets. Also, there were only so many materials that could be printed on one of these machines. As soon as the patents expired, Prof. Adrian Boywer, a researcher at the University of Bath, released one of the first open source 3D printers, kick-starting the RepRap movement.

Today, ~10 years after the first open source models were available, the 3D printing industry is worth 12.6 billion US Dollars, and 3D printers can be found in most places of the earth, and even at the International Space Station, where they are used to print replacement and repair parts. Moreover, they are available in all sorts of sizes, formats, and printing resolution (from meters to micrometers) and are capable of printing many different materials (such as plastics, concrete, chocolate, gels, metal, etc).

As an alternative to patents and copyright, a lot of people have poured quite some time in creating licenses that, instead of putting a fence around an idea, make the point of making sure the licensed project can be used by as many people as possible, while crediting the original developers.

These licenses establish how the work should be used (is commercial use allowed or not) and re-shared (should derivative work be shared always under the same license) - More details will be given below). Some known examples of these licenses are Creative Commons v4.0 (CC) licenses, GNU General Public License v3.0 and the CERN open hardware license v2.0.

### Elements of licenses (attribution, report back, etc)

Common elements covered in the open source licenses include (but are not limited to):

- Attribution: Should/must original authors be attributed or not
- Use areas: Is the project allowed to be used in any/all areas (e.g. is there text in the license that prohibits use in potentially harmful areas?)
- Commercialisation: can the project be used for commercial purposes
- Derivatives: Are derivatives of the project allowed? and if so, how should/must they be shared?

### Copyleft and non-copyleft licenses

As mentioned above, one of the features of Open Source licenses is that they provide a guideline on how derivative work should be re-shared, that is, should the derivative be shared under the same license and conditions, or can the derivative be shared under different licenses and conditions?

Some licenses mandate that all derivatives and derivatives of derivatives must be shared under the same original license, generating what is called a "viral effect", where one original project can be the starting point of many derivative projects that in turn also require derivative work to be re-shared openly. These licenses are sometimes bundled under a "copyleft" classification. Examples here include Creative Commons Attribution Share Alike 4.0, GNU GPL 3.0, CERN Open Hardware Licence Version 2 - Strongly Reciprocal licenses.

Licenses that do not specify how derivative work should be re-shared are, by exclusion, classified as "non-copyleft" licenses. In practical terms, this means that any derivative work from a certain project can be made private, which is completely fine from the point of view of the licenses, but it could lead to a missed opportunity in a community, where derivative and interesting work would not be available to all. Examples here include Creative Commons Attribution 4.0, MIT and CERN Open Hardware Licence Version 2 - Permissive licenses

### Licensing hardware design, licensing documentation, licensing software

When we consider open source hardware projects, licensing has a special angle, as hardware projects can be composed of different “domains”, each having its pertinent license.

We are going to cover this in more detail, but here is one example to get you thinking about this: Your project may be composed of 3D printed parts, some electronics and software to control those electronics. In this case, your project would need three licenses: One for the software code and for the 3D designs (here you could use one of the CC licenses, or GNU GPL), one for the hardware itself (here you could use the CERN OHL license), and one for other documentation, like building instructions, user guide, etc. (here you could use again CC licenses).

Make sure to check this module's resources for useful tools to help choosing licenses!

### {{ site.assignment }} Get an overview on how licenses work
- Browse through the resources below to learn about the different available licenses and their "ethos"

### Resources
- [Too long, didn't read on legal issues around OSH](https://faircloud.eu/nextcloud/index.php/s/J7yL2jD7bESdDEZ)
- [Open Source licenses explained](https://www.whitesourcesoftware.com/resources/blog/open-source-licenses-explained/)
- [Creative Commons (CC)](https://creativecommons.org/)
- [Wikipedia: Copyleft](https://en.wikipedia.org/wiki/Copyleft)
- [Wikipedia: Open Source licenses](https://en.wikipedia.org/wiki/Open-source_license)
- [choosealicense.com - Onlinetool which can help you to find the right license for yur project](https://choosealicense.com/)
- [fossa blog: How to choose the right license?](https://fossa.com/blog/how-choose-right-open-source-license/)
- [Github Documentation: Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)
- [How Open Hardware will take over the world](https://www.youtube.com/watch?v=Rfu_MKgu2Ik)
