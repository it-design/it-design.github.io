---
layout: styleguide
title: "Typography"
type: style
styleguide: famousfootwear
---

# {{ page.title }}
Typography can enhance a brand's identitiy and personality. Below are the fonts that Famous Footwear uses for their digital experiences.

## Archer
Archer is Famous Footwear’s core brand font largely used for titles and headings

### Usage
As a block serif, Archer is difficult to read at smaller sizes - especially on mobile. For this reason Archer is not used at any size smaller than 20px, and is used for title, headings, and price points.

**NOTE:** Consult Joe Ebeler, Brett Banning, or AJ Manker if you are planning on using Archer as a web font on the desktop or mobile site. Famous Footwear has a licensed agreement with Hoefler & Co. to use Archer only on a Famous Footwear domain.

[Download Archer](https://www.dropbox.com/sh/muzubb8268sp0vz/AAAmWr8-Ii2GIi6971M1D-2Da?dl=0){: .btn-download}

10.6 MB 

![Archer Font](../../../assets/famousfootwear/images/style-typography-font-archer.png "Archer Font")

### Weights
Famous Footwear focuses on four specific Archer weights. Famous Footwear is only licensed to use *Medium, Medium Italic, Semibold, and Semibold Italics* for the web as a web font.

![Archer Weights](../../../assets/famousfootwear/images/style-typography-weights-archer.png "Archer Weights")

### Numbers
If using Archer for numbers (such as price points) use the small caps, or LF, version of the font so that all numbers maintain a consistent baseline. 

![Archer Numbers](../../../assets/famousfootwear/images/style-typography-weights-archer-numbers.png "Archer Numbers")

<hr>

## DIN
For marketing assets, DIN is used as a headline/title font. DIN is being used less and less for the desktop and mobile experiences since it is such a bold and heavy font. Because of this, DIN is used sparingly in page and UI design.

[Download DIN](https://www.dropbox.com/sh/g5zpj0wiouh6q53/AACslBOqQVAbdjK3dVPXJJy4a?dl=0){: .btn-download}

146 KB

![DIN Font](../../../assets/famousfootwear/images/style-typography-font-din.png "DIN Font")

### Weights
DIN 1451 STD only has one weight - Engschrift. With that being said, the only time DIN is used is when it’s in all caps.

<hr>

## Helvetica Neue
Helvetica Neue is a great versatile font. For all experiences (marketing assets, mobile and desktop layout, and UI purposes) Helvetica Neue is used for body copy, button text, disclaimers, captions, and various other UI pieces. 

Helvetica Neue comes pre-installed on all Apple computers.

![Helvetica Neue Font](../../../assets/famousfootwear/images/style-typography-font-helvetica-neue.png "Helvetica Neue Font")

### Weights
For Helvetica Neue we use the following weights: *Regular, Italic, and Bold*.

![Helvetica Neue Weights](../../../assets/famousfootwear/images/style-typography-weights-helvetica-neue.png "Helvetica Neue Weights")

<hr>

## CSS Font Stack
As with life, there are no assurances that a user will be able to see our beautiful hand crafted fonts across every device they view our site on. Below are the fallbacks for each font.

{% highlight css %}
/* For Archer */
font-family: "Archer", "Helvetica Neue", Helvetica, Arial, sans-serif;

/* For DIN */
font-family: "DIN", "HelveticaNeue-CondensedBold", "HelveticaNeueBoldCondensed", "HelveticaNeue-Bold-Condensed", "Helvetica Neue Bold Condensed", "HelveticaNeueBold", "HelveticaNeue-Bold", "Helvetica Neue Bold", Helvetica, Arial, sans-serif;

/* For Helvetica Neue */
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
{% endhighlight %}
