## Installing on Debian
I have only tested this on Ubuntu 16.04 xenial LTS, in crosh. It is advised to update aptitude before running the install.sh file, if you don't want it updfated you will need to remove the first two line that update aptitude.

```
(xenial)root@localhost:/lerieui# sh install.sh
```

### Required Packages
* zip
* sass

## Grid
12 column repeating grid

### Sections
***Sections*** belong inside of ***Containers***.

CSS Class|Notes
---------|-----
two|Gives the developer two sections
three|Allows for a section to have three panels
four|Yep, there is now four panels.

### Panels
Panels hold your content, panels belong inside of sections.

```
<section>
	<panel>
		...
	</panel>
</section>
```

### Utilities
Helper classes for fonts, colors, and other stuff.

CSS Class|Notes
---------|-----
center-text|
bg-black|this creates a black background around an element, used mostly for demo purposes. 

### Colors

### Headers

### Footers

### HTML Document

### Navbars
The nav HTML tag sits inside of the container tag. Some helper classes

CSS Class|Notes
---------|-----
right|pulls the menu right
