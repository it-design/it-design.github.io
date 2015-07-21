---
layout: styleguide
title: "Cards"
type: components
styleguide: famousfootwear
---

# {{ page.title }}
Cards are used to highlight product, reviews, various UI (like modals), and other forms of content.

The specific properties of a card are:

- White background
- 2px border radius
- Must have a drop shadow
- They can be any height or width


##Distance
Cards are meant to highlight our product and content as tangible items. This is why the size and drop shadow of a card are so important. For a card to be resting on the background of the device (desktop or mobile), it should have a subtle drop shadow. Whereas a card closer to the user (like a modal) will have a more pronounced drop shadow blur to emphasize that distance.

The drop shadow values for these two states are:

- **Resting:** box-shadow: 0px 1px 3px 0px rgba(6,16,48,0.20);
- **Distant:** box-shadow: 0px 1px 8px 0px rgba(6,16,48,0.20);

![Cards](../../../assets/famousfootwear/images/components-cards.png "Cards Example")

<small>The card on the left is close to the canvas, whereas the card on the right is farther away (thus it is larger and the shadow is more pronounced)</small>


##Example
The most prominent use of cards on famous.com can be found on the results pages where all products are wrapped in a card view.

![Product Card](../../../assets/famousfootwear/images/components-cards-product.png "Product Card Example")

<small>The card on the left is the standard results card found on the Famous Footwear site. The card on the right is what that card COULD look like if a user hovered over it.</small>
