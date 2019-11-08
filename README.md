# department-listing-directory-page-part-2
The most important information when showcasing a department or directory is a mission statement, leadership biography, and pertinent contact information.

## Tutorial
For detailed instruction's, view Solodev's [How to Create a Department Listing or Directory Page (Part 2)](https://www.solodev.com/blog/web-design/how-to-create-a-department-listing-or-directory-page-part-2.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/q7svhze5/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="container pt-5 pb-5">
    <div class="row">
      <div class="col-md-8 col-xs-12">
        <h1 class="entry-title">Life Sciences</h1>
        <div class="breadcrumbs py-2">
          <a class="fileTrail" href="/">Home</a> <span class="fileTrailDividers"><i class="fa fa-angle-right"></i></span> 
          <a class="fileTrail" href="#">Departments</a> <span class="fileTrailDividers"><i class="fa fa-angle-right"></i></span> 
          <a class="fileTrail" href="#">Sciences</a> <span class="fileTrailDividers"><i class="fa fa-angle-right"></i></span> 
        <span class="fileTrailCurrent">Life Sciences</span>
        </div>
    <article>
      <div class="introduction super-introduction pb-4">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut tristique et egestas quis ipsum suspendisse ultrices gravida. Aliquam purus sit amet luctus venenatis lectus. Massa vitae tortor condimentum lacinia quis. Nulla facilisi morbi tempus iaculis. Est ante in nibh mauris cursus mattis. Feugiat pretium nibh ipsum consequat nisl.</p>
        <p>Turpis egestas pretium aenean pharetra magna ac placerat vestibulum. Tempor orci eu lobortis elementum nibh tellus molestie nunc non. Vestibulum rhoncus est pellentesque elit ullamcorper dignissim cras. Velit aliquet sagittis id consectetur. Interdum varius sit amet mattis vulputate enim nulla aliquet porttitor. Pretium nibh ipsum consequat nisl vel pretium lectus. Adipiscing tristique risus nec feugiat in.
        </p>
      </div><!-- .introduction -->
    </article>
      
    <div class="author-info pt-4 pb-4">
      <div class="row">
        <div class="avatar col-sm-3 col-xs-12"><img src="images/team_lifesciences.jpg" class="img-responsive" alt="department icon"></div>
          <div class="col-sm-9 col-xs-12">
            <h2>Jacquelyn Li</h2>
            <p class="p1"><span class="s1">Jacquelyn has been with LunarXP since the beginning of the program.</span></p>
          </div>
        </div>
      </div><!-- .author-info -->
    </div>             
      
     <aside class="col-lg-3 col-lg-offset-1 col-md-4 col-xs-12 marginBottom40">
       <ul class="contact-info">
         <li><i class="w-25p fa fa-user-circle-o pr-2"></i><p><strong class="text-uppercase">Jacquelyn Li</strong><br><em>Life Sciences</em></p></li>
         <li><i class="w-25p fa fa-envelope-o pr-2"></i> <a href="mailto:jacquelyn.li@lunarxp.com">jacquelyn.drake@lunarxp.com</a></li>
         <li><i class="w-25p fa fa-mobile pr-2"></i> <a href="tel:(800) 000-0000">(800) 000-0000</a></li>
         <li><i class="w-25p fa fa-map-marker pr-2"></i>400 N. Rose Ave - Orlando, FL</li>
         <li><i class="w-25p fa fa-clock-o pr-2"></i>9:00am - 5:00pm</li>
       </ul>
      </aside>
    </div><!-- row -->
</div><!-- container -->
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
```
