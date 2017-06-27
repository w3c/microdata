# microdata
A [proposed update](https://w3c.github.io/microdata) to the
[W3C microdata specification](https://www.w3.org/TR/microdata/).

This work aims to bring the specification in line with deployed implementations and publish it as a W3C Recommendation.

[Substantive changes](https://w3c.github.io/microdata/#changes) are documented in the specification, major technical changes include:

In the [26 June Working Draft](https://www.w3.org/TR/2017/WD-microdata-20170626/)
* Remove special Drag-and-Drop functionality
* Use `itemtype` as a vocabulary identifier.
* Add a global `content` attribute as a mechanism to explicitly define property values
* Allow `data`, `meter` and `time` elements to use their text content as a value.
* Allow `itemid` more liberally.

In the [First Public Working Draft](https://www.w3.org/TR/2017/WD-microdata-20170504/)
* Remove the Microdata DOM API
