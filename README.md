# WebExcess.Accordion

An Accordion Content-Element for [Neos CMS](https://www.neos.io/).


## Installation

    composer require webexcess/accordion


## Compatibility and Maintenance


| Neos Version | Package Version | Maintained |
|--------------|-----------------|------------|
| 3.x          | 1.x             | YES        |

For Neos 2.2 LTS check out the package [Dotpulse/Accordion](https://packagist.org/packages/dotpulse/accordion).

## Integration

CSS

	@import "WebExcess.Accordion/Resources/Private/Scss/Accordion/Accordion";

JS

	import Accordion from 'WebExcess.Accordion/Resources/Private/Javascripts/Accordion';
	window.onload = function() {
		Accordion('.accordion');
	};

Or use the pre-built public resources accordion.min.css and accordion.min.js

--

by [webexcess GmbH](https://webexcess.ch/)
