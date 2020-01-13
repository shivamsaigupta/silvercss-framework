
# SilverCSS - CSS Grid Framework

SilverCSS is a no-BS simplistic 12-grid CSS framework. It is built with flexbox and its functionality can be extended. Each column is 60px wide with 20px gutters.

## Container

Create div with class `container` to utilize our container component. The container is a 960px wide container meant to be the holder for all your elements.

Create a div with class `row` then add divs with class `col` to create a grid.
Example:

    <body>
    <div class="container">
      <div class="row">
        <div class="col-4"></div>
        <div class="col-8"></div>'
        <div class="col-4"></div>
      </div>
    </div>
  </body>

This will create a row with the first column occupying 4/12th the space, the second column occupying 8/12th of the space and the last column occupying 4/12th of the space. 

    <body>
    <div class="container">
      <div class="row">
        <div class="col"></div>
        <div class="col"></div>'
        <div class="col"></div>
        <div class="col"></div>
      </div>
    </div>
  </body>

This will create a row with 4 columns occupying equal space. We will get an equivalent layout if we replace `col` with `col-3` .  Each column in this case will have 240px space (inclusive of gutters).

## Button

The framework also has button styling. To utilize, use class `btn` , `btn-light` or `btn-sm`.

## Navbar

The SilverCSS framework also provides a `navbar` class that can be used to easily create navbars. To utilize `navbar` correctly, you must use `nav-item` and `nav-link` inside `navbar`. 

    <nav class="navbar">
        <div class="nav-item"><a href="#" class="nav-link">Home</a></div>
        <div class="nav-item"><a href="#" class="nav-link">About</a></div>
        <div class="nav-item"><a href="#" class="nav-link">Services</a></div>
        <div class="nav-item"><a href="#" class="nav-link">Career</a></div>
        <div class="nav-item"><a href="#" class="nav-link">Contact</a></div>
      </nav>
