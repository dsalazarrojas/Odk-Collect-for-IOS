# GIC Collect 1.0.14

[GIC Collect examples](https://github.com/dsalazarrojas/Odk-Collect-for-IOS/tree/master/examples)

# Download the app from the apple store

[https://apps.apple.com/mx/app/gic-collect/id1485932698](https://apps.apple.com/mx/app/gic-collect/id1485932698)

### Logic Building Blocks

The following building blocks work

- Variables
- Expressions
- Calculation
- Required
- Default values
- Restriction and Message
- Read-only questions
- Conditional showing questions
- Groups of questions
- Repeating questions
- Filtering options in select questions

### Markdown

This is the current status of the markdown implementation.

The following markdown tags work at label, hint and options:

- Headings
- Font colors
- Choices label formatting
- Cursive text
- New Lines
- Emphasis bold
- Emphasis italic
- Emphasis bold and italic
- Underline italic
- Monospace
- Clickable link
- Bullets in a title
- A combination of several formatting
- Hint formatting
- Blockquotes
- Nested blockquotes
- Unordered lists
- Local Image
- Remote image
- Quick url and email


### Metadata

The following metadata work, except those in italics and in parentheses and depending on your device and carrier some might not be recordable (\*)

- start
- end
- today
- deviceid (\*)
- subscriberid (\*)
- simserial (\*)
- phonenumber (\*)
- username
- *(email, audit)* 

### Form Operators and Functions

GIC collect operators and functions currently working. All work except those in *italics* and in parentheses:

 - Math operators: +, -, \*, div, mod
 - Comparison operators:  =, !=, >, >=, <, <=
 - Boolean operators: and, or
 - Path operators: ., ..
 - Control flow: if, position, (*once*)
 - Select questions: selected, selected-at, count-selected, (*jr:choice-name*)
 - Repeat groups: indexed-repeat, count, max, min, sum. (*count-non-empty*)
 - Strings: regex, contains, starts-with, ends-with, substr, substring-before, substring-after, string-length, translate, normalize-space
 - Combining strings: concat, join
 - Converting to and from strings: boolean-from-string, string
 - Math: round, int, number, digest
 - Calculation: pow, log, log10, abs, sin, cos, tan, asin, acos, atan, atan2, sqrt, exp, exp10, pi
 - Date and time: today, now
 - Converting dates and time: decimal-date-time, date, decimal-time
 - Formatting dates and times for display: format-date, format-date-time
 - Geography: area, distance
 - Utility: random, randomize, uuid, boolean, not, checklist, weighted-checklist, coalesce, true, false

### Widgets

This is the current status of the widgets implementation.

The following widgets and appearances work, but those in italics and in parentheses ignore appearance flags.

- text: no appearance, numbers, thousands-sep, url, *(ex:change.uw.android.BREATHCOUNT, printer:org.opendatakit.sensors.ZebraPrinter)*
- integer: no appearance, thousands-sep, *(ex:change.uw.android.BREATHCOUNT)*
- decimal:  no appearance, thousands-sep, *(ex:change.uw.android.BREATHCOUNT)*, bearing
- range: integer no appearance, decimal no appearance, integer vertical, decimal vertical, picker, range
- image: no appearance, new, selfie, selfie new, draw, annotate, signature
- barcode: no apperance
- audio: no appearance
- video: no appearance, new-front
- *file: (no appearance)*
- date no-calendar, ethiopian, coptic, islamic, persian, no appearance, month-year, year,  *(bikram-sambat, myanmar)*
- time: no-calendar, *(no appearance)*
- dateTime: no-calendar, *(no appearance)*
- geoPoint: no appearance, placement-map, maps
- geoTrace: no appearance
- geoShape: no appearance
- *osm: (no appearance)*
- select\_one: no appearance, minimal, quick, search, autocomplete
- select\_one with images: no appearance, compact, compact-2, quickcompact, quickcompact-2, *(image-map, likert)*
- select\_multiple: no appearance, autocomplete
- select\_multiple with images: no appearance, compact, compact-2, minimal, *(image-map)* 
- select \_one: *(label, list-nolabel, list)*
- select \_multiple: *(label, list-nolabel, list)*
- *rank: (no appearance)*
- trigger: no appearance


[What's new](https://dsalazarrojas.github.io/Odk-Collect-for-IOS/What's%20new.html)
[All current features](https://dsalazarrojas.github.io/Odk-Collect-for-IOS/GIC%20Collect%20features.html)
[Contact us](https://dsalazarrojas.github.io/Odk-Collect-for-IOS/Contact-Us.html)
[Privacy Policy](https://dsalazarrojas.github.io/Odk-Collect-for-IOS/Privacy-Policy.html)
[Training Course](https://dsalazarrojas.github.io/Odk-Collect-for-IOS/GIC%20Collect%20for%20IOS%20Compatible%20with%20ODK%20Training%20Course.html)

