# Responsive Image Gallery (Using Flexbox)

We'll be creating a responsive, repeating grid (image gallery) with flexbox.

# Grid

We have to make sure before starting to include some sort of reset, or at least set box-sizing: border-box and margin: 0 to the body. (More about all that, if you’re not sure.) Now we can get started on the grid.

In this repo, we'll be delving into creating flexbox galleries for multiple devices: tablet, phone, and desktop.

We'll start by putting everything inside a generic container. The grid class will be the flex wrapping container. For mobile, everything will be on column, hence it doesn't need to be defined as flex yet.

Inside that, we'll make a cell and place an image inside of that. We'll make the cell responsive by putting a max-width on it.

Moreover, the image should be a block level element.
