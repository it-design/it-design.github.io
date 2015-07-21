---
layout: styleguide
title: "Text Fields and Forms"
type: components
styleguide: famousfootwear
---

# {{ page.title }}
Input fields share a similar format as buttons in order to maintain consistency throughout the experience. For Famous Footwear’s needs, there are two kinds of inputs: text fields and drop downs.


##Text Fields
Text fields continue the lighting structure seen in cards where each field shows an inset shadow to highlight an area for the user to interact with.

	CSS 
     height: 38px;
     background: #FFFFFF;
     border: 1px solid #E6E6E6;
     box-shadow: inset 0px 5px 1px 0px #FBFBFB;
     border-radius: 5px;

The field name is always displayed about the input field and is smaller (14px) than the copy inside the text field (16px) to make it easier for the user to see what they are inputting.

![Text Field](../../../assets/famousfootwear/images/components-fields-forms-field.png "Text Field")

Below is an example of a filled out text field.

![Text Field Example](../../../assets/famousfootwear/images/components-fields-forms-example.png "Text Field Example")


##Drop Downs
Drop downs share a similar styling to text field, except for the location of the inset shadow. To emphasize a tappable interaction for touch devices, the inset shadow is located at the bottom of the field.

![Drop Down Example](../../../assets/famousfootwear/images/components-fields-forms-dropdown-example.png "Drop Down Example")


##Put it all together
You can see what a form can look like with all the elements put together below.

![Form Example](../../../assets/famousfootwear/images/components-fields-forms-form-example.png "Form Example")

<small>This form has a heading, text field, drop down, button, and card components</small>
