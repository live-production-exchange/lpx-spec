# How we use audio with different languages

LPX does not create bespoke language tags.
Audio language tagging is a standard method for identifying human languages in internet-based media standardised in IETF BCP47.  

An example where Welsh is cy taken from ISO 639,
"language": "cy",

A best practice is recommended using two letter codes based on ISO 639 in conjunction with ISO 3166 country code for regional variants.
An example where Welsh is cy taken from ISO 639 in conjunction with ISO 3166 country code for regional variants.
"language": "cy-GB",

A good reference resource is http://www.lingoes.net/en/translator/langcode.htm

Additional resource links are: https://en.wikipedia.org/wiki/ISO_639#Two-letter_code_space https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes https://en.wikipedia.org/wiki/IETF_language_tag

And:
https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry


IETF BCP47
Type: language
Subtag: cy
Description: Welsh
Added: 2005-10-16
Suppress-Script: Latn

Newsml from IPTC:
},
        "language": {
          "title": "Language",
          "description": "The human language used by the content. The value should follow IETF BCP47.",
          "type": "string"
