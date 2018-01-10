# Activity-1
In this exercise, you'll practice using the flex-box layout to manipulate the distribution of elements on your page. You'll implement different layouts for small, medium, and large screen sizes. The HTML content is already present, so you'll all work in the `css/style.css` file.

This is the layout for small screens:

![small screen layout](imgs/small-screens.png)

This is the desired layout for medium screens (>768px):

![medium screen layout](imgs/medium-screens.png)

This is the desired layout for large screens (>992px):

![large screen layout](imgs/large-screens.png)



**Flexbox Container**

Your flexbox container should have the following CSS properties:

- Set some initial properties by assigning it a minimum height of `200px`, and a border that is `1px solid black`
- Set the `display` to `flex` to initiate the flexbox layout
- Set the `align-items` property such that it _centers_ elements **vertically** (I suggest you also experiment with properties like `stretch`, `flex-end`, and `flex-start` to see what they do)

**Flexbox Items**

The items (immediate children) in your flexbox container should have the following styles:
- Set the padding to `20px`
- Have each item take up `100%` of the width by default (but _don't_ use the `width` property...)

**Item Content**

Set the items with the class `content` to have the following styles. Also, think about what advantages are provided by wrapping this content with the `flex-column` divs.
- Set the background color to `tomato`
- Align text in the center
- Set the font-size to `4rem`
- Set the height to `100%`

**Media Queries**

Write the media queries that impose the following styles:
- On medium screens (>=768px), have the flexbox items each take up 50% of the flexbox
- On large screens (>=992px) have the flexbox items take up 25% of the flexbox

See `complete` branch for answers.
