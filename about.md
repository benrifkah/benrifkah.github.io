---
layout: page
title: About Me
permalink: /about/
---

Greetings, My name is BenRifkah Bergsten-Buret, Ben for short. I was raised in the Pacific Northwest and currently live in Seattle, Washington.

Since 2005 I've supported the [University of Washington's Clinical Trials Center](https://www.biostat.washington.edu/research/centers/uwctc) which serves as the data coordinating center of the Resuscitation Outcomes Consortium (ROC), one of the world's largest emergency medicine research initiatives. We continue to perform ground breaking research and develop new tools to support it.

I'm supporting a collection of web applications written in Perl, JavaScript, jQuery, Prototype.js, HTML::Mason, Moose, PHP, Laravel and Bootstrap. I'm actively developing platform and deployment tools to handle the repetitive tasks and keep our small team productive.

I've handled server installs, upgrades, migrations, failures and decommissions. I'm implementing systems compliant with federal HIPAA, 21 CFR 11 electronic signature regulations.

Through all of this I completed training and served as a parenting instructor at [Break Through Learning Center](https://btlconline.com/about/ben/). I also volunteer as a web administrator and [Code.org hour of code](https://code.org/) facilitator for my son's elementary school. I assisted the [International RRP ISA Center](http://rrpwebsite.org/) as a client liaison through their last website redesign.

If your team is about making a difference in the world, in any business sector, [I'd love to hear from you](http://goo.gl/forms/OJSoCD6WrvfH11p33).

## [HeartMap Dynamic AED Registry](https://heartmap.uwctc.org/)
One of my current projects is maintaining and developing the website and platform for the HeartMap Dynamic AED Registry. This is a community improvement project to make life saving Automated External Defibrillators (AEDs) available to bystanders who witness a cardiac arrest.

I support this multi-phase project in development and system administration capacities:

### Find 'em
Locate the AEDs by enlisting the general public to participate in crowd-sourcing contests to find AEDs in their area to win cash prizes. Contests have been conducted in Philadelphia, Seattle, Pittsburgh and Tucson and other locations. More contests are in planning stages. I developed the post-pilot platform using the Laravel PHP framework. The contest web application supports users on all modern mobile platorms as they scour the city and report AED locations. It leverages geolocation and Google places through progressive enhancement to assist in address entry and validation.

### Tag 'em
Verify AEDs reported in contests and label them with 2-dimensional barcode (QR code) stickers that will prompt people to scan and report AED use and maintenance. Staff at participating universities access the labeler web application to visit, verify and label the AEDs. My responsibilities included designing and implementing the labeling user experience and reporting system. I also developed the QR codes using [Douglas Crockford's Base32 encoding](http://www.crockford.com/wrmg/base32.html) in order to reduce typing errors when using the fallback text url.

### Track 'em
The AED registry is now open for bystanders and AED owners to report the status and maintenance of AEDs. For recording non-clinical interactions we employ progressive data capture using a short wizard and small data forms rather than long forms. This short circuits the traditional concept of web "conversions" ensuring that we get some usable data even if users abandon reports before completing them.

### Use 'em
This phase, currently under development is a registry of cardiac events. Emergency medical service providers at participating agencies access our registry to report when they are called to the scene where an AED has been used by bystanders to treat a patient. This leverages the UWCTC Clinical Data Entry platform currently supporting the ROC studies. A key responsibility of mine has been to abstract the data entry authentication/authorization making it pluggable to allow integration with other platforms including Laravel and Django.

### Save Lives!
The final phase currently in design is to make the AED location information in the registry available to 3rd parties and the general public so that they can be easily located when they are needed. I'm currently tracking FDA Unique Device Identifiication (UDI) technical standards and implementation so that our team is ready to hit the ground running and integrate with the Global UDI Database (GUDID).
