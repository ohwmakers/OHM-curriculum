---
layout: page
title: "Documentation standards"
module: "6.3"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/06-licenses-and-standards/findability.md
summary: "And why do we need them"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---
* TOC
{:toc}

### Hardware standards:
  - The importance of standards (compatibility, reproducibility, repairability, guideline)  
  - What is a suitable standard for my project?
  - Examples of open standards and how to apply them to your project (eg DIN spec)
  - What are the standards in your region? (Europe CE, Brazil INMETRO, etc)

An important point to observe from open source projects is that due to their distributed nature, they normally do not follow one specific standard. In other words, as project X is brought to reality, its developers might have had a certain train of thought on how to organise their documentation, and this can be completely different from what the developers of project Y would have thought about. Although this is in principle OK, as in theory all projects should be documented well enough for anyone to understand them, it does bring the added complexity of having to navigate through different documentation styles, with different levels of completeness.

One way to decrease this complexity (which is not exclusive to open hardware) is to create standards and make sure different projects and people have incentives to follow them. For instance, if you are in Europe and you sell consumer goods, there is a strong incentive for you to follow certain standards, so that your products get a "CE certification" which testify that your products pass certain controls and safety measurements.

Another example of the benefits of standards, comes from the materials needed to build projects. No matter where you are in the world, buying an 3mm metric bolt will always give you something that fits in a thread designed for that bolt size. So even when we are not thinking about standards, we are making use of them.

In OSH, the first standards are starting to be created and gain traction, and they cover different OSH aspects. We are going to cover two of them:

- The first standardisation we need is defining what exactly is open source hardware. In this case, this entails defining what kind of files should be shared (drawing, schematics, build plans, bill of materials, etc), in what format (editable X non-editable formats, proprietary X open formats, etc). The Open Source Hardware Association (OSHWA) has come up with a [definition](https://www.oshwa.org/definition/) (these has been translated in other languages - they can be found in the dropdown menu at the page header) for OSH covering these and other aspects. OSHWA also runs a certification program, which is free of charge and provides a way for developers to clearly display that their designs conforms with OSHWA's definition. This is quite useful for everyone, since users/collaborators/developers already know what to expect from the project's repository/documentation.

- For hardware documentation, there is a [DIN](https://www.din.de/en) (Deutsches Institute fuer Normung - The German Institute for Standardization) specification, created by a joint effort of many people from the OSH community in collaboration with DIN. Specifically, it is [DIN SPEC 3105](https://gitlab.com/OSEGermany/OHS/uploads/b35d1b22a3ec13f968de08c6b106cbda/DIN_SPEC_3105_v0.10.0.zip). A general explanation on the standard and its potential impacts can be found here [DIN standard for OSH documentation](https://journalopenhw.medium.com/din-spec-3105-explained-2cce6134c207). One thing to note is that the DIN Spec for OSH was made with an industry/commercialisation goal in mind, so conforming fully with this specification is not complicated, but could can be a bit time consuming.

### {{ site.assignment }} Update your documentation to make use of OSH standards
- OSHWA certification
 - revisit your documentation and adjust it so that it is conforming with the [OSHWA certification](https://certification.oshwa.org/)(no need to submit for certification just yet!)
- (optional) 3105 DIN specification
 - update your documentation so it is one step closer to fulfil [DIN SPEC 3105](https://gitlab.com/OSEGermany/OHS/uploads/b35d1b22a3ec13f968de08c6b106cbda/DIN_SPEC_3105_v0.10.0.zip)

### Resources
- [Requirements for technical documentation of OSH (including licensing):](https://gitlab.com/OSEGermany/OHS)
- ['What is the "Source" of Open Source Hardware?', J. Bonvoisin,  R. Mies,  J. Boujut, R. Stark](https://depositonce.tu-berlin.de/bitstream/11303/7259/2/2017_bonvoisin_et-al.pdf)
- [OSH DIN spec explained](https://journalopenhw.medium.com/din-spec-3105-explained-2cce6134c207)
- [Open KnowHow](https://www.internetofproduction.org/open-know-how)
- [What is OSHWA certification](https://certification.oshwa.org/process.html)

**Additional Standards**
- [EN 45554 - standard for repairability](https://www.en-standard.eu/csn-en-45554-general-methods-for-the-assessment-of-the-ability-to-repair-reuse-and-upgrade-energy-related-products/)
