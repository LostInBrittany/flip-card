The objective of the `<flip-card>` element is to propose a Polymer implementation of the flip-card
UI pattern using CSS 3D transforms.

In order to use `<flip-card>` you must have a browser supporting CSS 3D transforms.

## Example ##

    <flip-card>
      <front>Hi mate!</front>
      <back>Bye mate!</back>
    </flip-card>

## Options ##

A `width` and and `height` attributes can be added to the `<flip-card>` element to
define card dimensions. Dimensions by default are 250x250 px.
A `status` attribute ca be used to recover and/or force the status from the outside
of the element. Valid status are `showFront` and `showBack` 

