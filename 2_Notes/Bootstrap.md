# Bootstrap

Bootstrap is the CSS Framework which help us to create websites with the writing less and less CSS.

We can use already styled components by just including bootstrap in your html file and by **using bootstrap classes**.

### Colors in Bootstrap
- Blue : `text-primary`
- Grey : `text-secondary`
- Green : `text-sucess`
- Red : `text-danger`
- Black : `text-dark`
- Light Grey : `text-muted`

### Color with Background
- Orange color with black background : `text-warning bg-dark`

- Teal color with black background : `text-info bg-dark`

- White color with black background : `text-light bg-dark`

- Orange color with black background : `text-warning bg-dark`

- Orange color with black background : `text-warning bg-dark`

### Alerts in Bootstrap
Alerts are the alert boxes which most of the websites use for their alerts.

alert : `alert`

And We can customize our colors of our alerts by simply adding one more class like `alert alert-primary` next class will work for the **color** of the alert.

### Buttons in Bootstrap

**Types of Buttons in Bootstrap**

- **Normal Buttons** : Normal buttons with class **`btn`** are the simple buttons with the text and styling as per the class **`btn btn-primary`** we are providing.

- **Outline Buttons** : Same as the normal buttons **`btn`** with the class for styling and outline with the class **`btn btn-outline-primary`** which will have hover effect.

- **Button-Sizes** : We can just handle the sizes of button with the extra class like:
    
    - **Small** : `btn btn-primary btn-sm`.
    - **Normal** : By default its  size is normal.
    - **Large** : `btn btn-primary btn-lg`

Colors can be applied for all the buttons by the `btn-color` class.

### Bootstrap Cards
You Dont need to create cards by your own,You can just copy paste cards and edit its content and image.

### Image slider in bootstrap (Carousel)
**Carousel's** is the image slider provided by bootstrap by just simply copy pasting the component for our image slider and there are various crousel's are available and we can use it accordingly as per our requirement.

##  Grid system in Bootstrap 

***(Most-Important class of the bootstrap)***

### Containers In Bootstrap

- **.container** - which sets a max-width at each responsive - breakpoint 

- **.container-fluid** - which is width: 100% at all breakpoints

- **.container-{breakpoint}** - which is width: 100% until the specified breakpoint


### Grid in bootstrap

**Bootstrap have 12 columns in a row.**

- **.row** - We can create row

- **.column** - We can create column inside that row

Bootstrap will automatically grasp the rows and columns automatically.

We can use the columns or cover the columns like colspan by simply adding classes like **col-3** it will cover 3 columns in a row.

### Responsive layout in bootstrap

We can make our layout responsive by just simply manipulating classes and handling their values of column widths on various types of devices.

Devices as per its size and its classes as follows : 

- Extra Small Devices : **Mobiles - xs(<576px)** - **`.col-`**

- Small Devices : **sm(≥576px)** - **`.col-sm`**

- Medium Devices : **md(≥768px)** - **`.col-md-`**

- Large Devices : **lg(≥992px)** - **`.col-lg-`**

- Extra Large Devices : **xl(≥1200px)** - **`.col-xl-	`**

- Extra Extra Large Devices : **xxl(≥1400px)** - **`.col-xxl-`**

### Bootstrap Modal
Bootstrap modal is nothing but the alert box with features and we can use that by simply copy pasting the component and modifying it.


### Bootstrap Jumotron
Jumbotron is the hero text of the website and we can refer the bootstrap docs for it.

### Bootstrap components

**We have multiple components in bootstrap.**

Maybe it will even increase in future just learn them accordingly as per your need. 

### Margins and Paddings in Bootstrap

We can give margins and paddings in bootstrap itself as follows : 

- **m** : Margin
- **p** : Padding

**Sides for margin and paddings in bootstrap :**

- **t** : Top
- **b** : Bottom
- **s** : Start (Left)
- **e** : End (Right)
- **x** : Left and Right Both
- **y** : Top and Bottom Both
- **blank** : for classes that set a `margin` or `padding` on all 4 sides of the element

**Sizes for margin and padding**

- **0** - for classes that eliminate the margin or padding by setting it -to 0
- **1** - (by default) for classes that set the margin or padding to     $spacer * .25
- **2** - (by default) for classes that set the margin or padding to     $spacer * .5
- **3** - (by default) for classes that set the margin or padding to     $spacer
- **4** - (by default) for classes that set the margin or padding to     $spacer * 1.5
- **5** - (by default) for classes that set the margin or padding to     $spacer * 3
- **auto** - for classes that set the margin to auto

### Flexbox in Bootstrap

We can make any component display flex with only bootstrap as mentioned below.

- d-flex : display flex
- justify-contnet-center : make justify content center
- align-contnet-center : make align content center

### Order of items in bootstrap

We can change the orders of div's in the same container by using : 

**order-md-1** - It will set the order as per the devices we gave or it will aply to the current device size.

