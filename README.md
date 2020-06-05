# TEI Publisher From Scratch

This repository contains data and assignments for our online workshop «Stay Home Learn TEI Publisher From Scratch». It is a 3-part online course taking place on the 8th, 15th, and 22nd of June, always at 4-5 pm (CEST). 
(Find your local time via these links: 
[Session 1](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Stay+Home+Learn+TEI+Publisher+From+Scratch+Session+1&iso=20200608T16&p1=37&ah=1), 
[Session 2](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Stay+Home+Learn+TEI+Publisher+From+Scratch+Session+1&iso=20200615T16&p1=37&ah=1), and 
[Session 3](https://www.timeanddate.com/worldclock/fixedtime.html?msg=Stay+Home+Learn+TEI+Publisher+From+Scratch+Session+1&iso=20200622T16&p1=37&ah=1).)

The online session will be lecture-like with room for questions. Afterwards attendants are encouraged to work through a list of weekly assignments. Usually the first assignment for each topic will be covered in the online session, but we recommend that participants carry out the assignment on their own too.

## Preliminaries

The online session will be hosted on jitsi. Please use the following URL to connect:

https://meet.jit.si/e-editiones-events

Should anything go wrong during the event, we will inform you via [twitter](https://twitter.com/eeditiones) and the slack channel mentioned below.

Participants are strongly encouraged to join the dedicated **#workshop** channel on the [e-editiones slack](https://join.slack.com/t/e-editiones/shared_invite/zt-e19jc03q-OFaVni~_lh6emSHen6pswg) for asking questions, but also to help others with the assignments. We hope to have a lively discussion there and would love to see participants **support each other**. Due to the large number of participants, we won't have enough tutors to answer every question.

You may also want to clone this repository or download its contents as a zip file. This way you can look at the example documents on your own machine. To clone or download, click the green *Clone or Download* button on the top right of the [landing page](https://github.com/eeditiones/workshop) of this repository.

### Software

A server will be **provided** for everyone to work on the exercises, so all you need is a decent web browser (Chrome, Firefox, and Safari work; the latest Edge on Windows works despite being slow; and IE definitely doesn't).

Due to the large number of attendees the common server might become overloaded. We thus **encourage more experienced users** to either:

####  1. Install TEI Publisher on your local machine. 

The basic steps are described in the [TEI Publisher documentation](https://teipublisher.com/exist/apps/tei-publisher/doc/documentation.xml?id=installation). However, we would recommend to install the release candidate for TEI Publisher 6.

The release candidate is not available on eXist's public package  repository yet, so you would need to download it manually: 

1. Download the `.xar` from the [github release page](https://github.com/eeditiones/tei-publisher-app/releases/tag/6.0.0-RC1)
2. If you installed an older version of TEI Publisher before, check if you are offered updates for `tei-publisher-lib`. You need version 2.8.7 of this package.
3. Go to the eXist Dashboard/Package Manager, click on the *Upload* button, and select the downloaded `tei-publisher-6.0.0-RC1.xar`

#### 2. Use a docker image

Using docker is a good alternative for the workshop, though it comes with a small performance penalty. The installation process is described in the [docs](https://teipublisher.com/exist/apps/tei-publisher/doc/documentation.xml?id=docker). 

Again we recommend to use the release candidate for TEI Publisher 6, so in the docker commands, replace `existdb/teipublisher:latest` with `existdb/teipublisher:6.0.0-RC1`.

## Assignments

[Week 1](assignments/A1.md)

## Helpful Literature and Websites

Working with TEI Publisher requires some knowledge of TEI, basic XPath and a little CSS. If you don't know any XPath yet, we recommend to read the short [introduction](https://newtfire.org/courses/dh/explainXPath.html) linked below.

### XML

* [Introduction to XML](https://newtfire.org/courses/dh/explainXML.html)
* [A Gentle Introduction to XML](https://tei-c.org/release/doc/tei-p5-doc/en/html/SG.html)

### CSS

* [Mozilla MDN](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [DevDocs](https://devdocs.io/css/): searchable reference of CSS features and properties

### XPath

* [Follow the XPath!](https://newtfire.org/courses/dh/explainXPath.html): short introduction to XPath
* [XPath and XQuery Functions](https://www.w3.org/TR/xpath-functions-31/): the official W3C specification covering all standard XPath functions
* [XQuery for Humanists](https://xquery.forhumanists.org/): book with companion website

### TEI

* https://teibyexample.org/
* [TEI Guidelines](https://tei-c.org/guidelines/):  the ultimate reference

### TEI Processing Model

* [Section 22.5.4.1 of the TEI Guidelines](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/TD.html#TDPMPM): the official specification of the TEI Processing Model
* [TEI Publisher Documentation](https://teipublisher.com/exist/apps/tei-publisher/doc/documentation.xml?id=odd-customization)