
# SilverCSS - CSS Grid Framework

SilverCSS is a no-BS simplistic 12-grid CSS framework. It is built with flexbox and its functionality can be extended. Each column is 60px wide with 20px gutters.

[Example](https://shivamsaigupta.github.io/silvercss-framework/example/)

## Integration
SilverCSS is not hosted on a CDN as of now. You will have to download `silvercss.css` and then link it to your HTML.
    
    <head>
    ...
    <link rel="stylesheet" href="../silvercss.css" />
    </head>

If you want to extend SilverCSS, we encourage you to download `silvercss.scss`. It will be easier for you to edit the Sass file.

## Container

Create div with class `container` to utilize our container component. The container is a 960px wide container meant to be the holder for all your elements.

Create a div with class `row` then add divs with class `col` to create a grid.
Example:

    <body>
    <div class="container">
      <div class="row">
        <div class="col-3"></div>
        <div class="col-6"></div>'
        <div class="col-3"></div>
      </div>
    </div>
  </body>

This will create a row with the first column occupying 3/12th the space, the second column occupying 6/12th of the space and the last column occupying 3/12th of the space.
      </nav>

## Contributors

@shivamsaigupta

Contribution encouraged!
