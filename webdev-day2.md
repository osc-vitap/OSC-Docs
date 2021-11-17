# CSS - Flexible Box, Position, Grid, Media query

## Flexible Box
The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.

<details>
<summary>Basics and terminology</summary>

    + Since flexbox is a whole module and not a single property, it involves a lot of things including its whole set of properties. Some of them are meant to be set on the container (parent element, known as “flex container”) whereas the others are meant to be set on the children (said “flex items”). When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it. Everything we do with flexbox refers back to these axes, so it is worth understanding how they work from the outset.

    + The main axis is defined by flex-direction, which has four possible values: "row, row-reverse,column,column-reverse" should you choose row or row-reverse, your main axis will run along the row in the inline direction.

    +main-start | main-end – The flex items are placed within the container starting from main-start and going to main-end.

    + main size – A flex item’s width or height, whichever is in the main dimension, is the item’s main size. The flex item’s main size property is either the ‘width’ or ‘height’ property, whichever is in the main dimension.

    + cross axis – The axis perpendicular to the main axis is called the cross axis. Its direction depends on the main axis direction.

    + cross-start | cross-end – Flex lines are filled with items and placed into the container starting on the cross-start side of the flex container and going toward the cross-end side.

    +cross size – The width or height of a flex item, whichever is in the cross dimension, is the item’s cross size. The cross size property is whichever of ‘width’ or ‘height’ that is in the cross dimension.
</details>

<details>
<summary>Properties applied to flex items</summary>

    + To have more control over flex items we can target them directly. We do this by way of three properties:
        flex-grow
        flex-shrink
        flex-basis
    
</details>

<details>
<summary>Alignment, justification and distribution of free space between items</summary>

    + A key feature of flexbox is the ability to align and justify items on the main- and cross-axes, and to distribute space between flex items. Note that these properties are to be set on the flex container, not on the items themselves

    + The align-items property will align the items on the cross axis

    + The justify-content property is used to align the items on the main axis, the direction in which flex-direction has set the flow. The initial value is flex-start which will line the items up at the start edge of the container, but you could also set the value to flex-end to line them up at the end, or center to line them up in the centre.

    + 
</details>
<br>
<br>  

[In depth alignments guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container)

[In depth Flex box properties](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#flexbox-properties)  

[Please follow this link to learn more about Controlling Ratios of Flex Items on the Main Axis](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax)  

