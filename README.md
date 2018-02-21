# Responsive Image Gallery (Using Flexbox)

We'll be creating a responsive, repeating grid (image gallery) with flexbox.

# Grid

We have to make sure before starting to include some sort of reset, or at least set box-sizing: border-box and margin: 0 to the body. (More about all that, if you’re not sure.) Now we can get started on the grid.

# Mobile

In this repo, we'll be delving into creating flexbox galleries for multiple devices: tablet, phone, and desktop.

We'll start by putting everything inside a generic container. The grid class will be the flex wrapping container. For mobile, everything will be on column, hence it doesn't need to be defined as flex yet.

Inside that, we'll make a cell and place an image inside of that. We'll make the cell responsive by putting a max-width on it.

Moreover, the image should be a block level element.

This pretty much wraps it up for mobile devices.

# Tablet

We'll be choosing 600px as the width to start showing the mid-screen view. We want the images to show up in rows of two now.

The grid wrapping container is defined as a flex element, which will wrap in the direction of a row (horizontal). Since we now want the images to show up in rows of two columns, I’m going to set the width to 50%.

# Desktop

For desktops, we'll be using 1000px and we'll display the images in rows of three.

# Margins

So far we don't have any padding or spacing between the images and it doesn't look that good. Therefore, we'll be making some adjustments in adding space between all the images.

First, we'll add a margin around the cell for all screen sizes. Then edit the width of the cells on their respective sizes. See the commit along with this ReadME file in order to see the corresponding changes to the CSS file.
