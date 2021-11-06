# Bootstrap Grids

Bootstrap's grid system is built with flexbox and allows up to 12 columns across the page.

If you do not want to use all 12 columns individually, you can group the columns together to create wider columns:

The grid system is responsive, and the columns will re-arrange automatically depending on the screen size.

## Bootstrap Grid Classes
### Bootstrap 5 grid system has six classes

<ul>
    <li> .col- (extra small devices - screen width less than 576px) </li>
    <li> .col-sm- (small devices - screen width equal to or greater than 576px)</li>
    <li> .col-md- (medium devices - screen width equal to or greater than 768px) </li>
    <li> .col-lg- (large devices - screen width equal to or greater than 992px) </li>
    <li> .col-xl- (xlarge devices - screen width equal to or greater than 1200px) </li>
    <li> .col-xxl- (xxlarge devices - screen width equal to or greater than 1400px) </li>
</ul>

The classes above can be combined to create more dynamic and flexible layouts.


<!-- Control the column width, and how they should appear on different devices -->
<div class="row">
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
</div>
<div class="row">
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
  <div class="col-*-*"></div>
</div>

Create a row (<div class="row">). Then, add the desired number of columns (tags with appropriate .col-*-* classes)
The first star (*) represents the responsiveness: sm, md, lg, xl or xxl
the second star represents a number, which should add up to 12 for each row

<!-- Or let Bootstrap automatically handle the layout -->
<div class="row">
  <div class="col"></div>
  <div class="col"></div>
  <div class="col"></div>
</div>

instead of adding a number to each col, let bootstrap handle the layout, to create equal width columns: two "col" elements = 50% width to each col
three cols = 33.33% width to each col
Four cols = 25% width, etc
You can also use .col-sm|md|lg|xl|xxl to make the columns responsive.