# microdata
A [proposed update](https://w3c.github.io/microdata) to the
[W3C microdata specification](https://www.w3.org/TR/microdata/).

This work aims to bring the specification in line with deployed implementations and publish it as a W3C Recommendation.

[Substantive changes](https://w3c.github.io/microdata/#changes) are documented in the specification, major technical changes include:

In the current editors' draft:
* Clarify that microdata does not guarantee ordering of properties
* Remove the conversion to JSON-LD


In the [10 October Working Draft](https://www.w3.org/TR/2017/WD-microdata-20171010/):
* Add a normative algorithm to convert microdata to RDFa
* Add a normative algorithm to convert microdata to JSON-LD

Changes in previous Working Drafts include:
* Remove the special unimplemented Drag-and-Drop functionality
* Use `itemtype` as a vocabulary identifier.
* Add a global `content` attribute as a mechanism to explicitly define property values
* Allow `data`, `meter` and `time` elements to use their text content as a value.
* Allow `itemid` more liberally.
* Allow for the use of microdata in languages other than HTML
* Remove the Microdata DOM API

## Participating in the work
This specification is formally managed by the [W3C Web Platform Working Group](https://w3.org/WebPlatformWG).
Further information about contributing to this document is available in [the guide to contributing](CONTRIBUTING.md).

All W3C activity, including working in this repository, is conducted according to the W3C Code of Conduct,
to help ensure a friendly, resepectful environment for discussion. 
In the unlikely and unfortunate event that you are aware of a breach of that code, 
as well as being able to follow the procedures listed in the Code or further procedures relevant to the circumstance,
you are welcome to contact any of the editors, chairs and staff of the Web Platform Working Group in confidence,
who will do their best to assist you in following up and fixing problems.
