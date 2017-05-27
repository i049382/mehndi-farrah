# Mehndi by Farrah

## Portfolio Photos
```html
  <div class="col-xs-6 col-sm-3">
    <a href="#portfolioModal" class="thumbnail" data-toggle="modal" data-target="#portfolioModal" data-img-url="img/portfolio/mehndi_1.jpg">
      <img style="max-height:180px;height:180px; width:100%; object-fit:cover;" src="img/portfolio/mehndi_1_th.jpg" alt="Mehndi heart two hands">
    </a>
  </div>
```
1. Upload your new photo to the /img/portfolio folder. Ensure that you have the original photo and a thumbnail.
2. Copy the above html code for your new photos.
3. Paste the code in the portfolio section.
4. Change the name of the photo and the thumbnail.
5. Update the alt field, this is used to describe the photo.



## Review Template
```html
  <div class="item">
    <div class="testimonial">
      <div class="row">
        <img class="img-circle img-testimonial" src="img/about/bullet-logo.png" alt="...">
      </div>
      <div class="row" style="margin-top:10px;margin-left:20px;margin-right:20px;">
        <i class="fa fa-fw fa-star" aria-hidden="true"></i>
        <i class="fa fa-fw fa-star" aria-hidden="true"></i>
        <i class="fa fa-fw fa-star" aria-hidden="true"></i>
        <i class="fa fa-fw fa-star" aria-hidden="true"></i>
        <i class="fa fa-fw fa-star" aria-hidden="true"></i>
        <br>
        <<REVIEW>>
      </div>
      <div class="row" style="margin-top:10px"> <<CLIENT>>, <<MONTH>> <<YEAR>>, <<LINK>></div>
    </div>
  </div>
  ```
  
  1. By default bullet-log.png is used, if possible use a profile image.
  2. By default each review has 5 stars. Remove the necessary lines to give the appropriate number of stars.
  3. Enter the review, ensure that you overwrite ```<<REVIEW>>```
  4. Enter the customers first name only in ```<<CLIENT>>```
  5. Enter the month and year in ```<<MONTH>>``` ```<<YEAR>>``` respectively.
  6. If there is a link to the review, eg Etsy put it in the ```<<LINK>>``` placeholder, eg

     ```<a href="https://www.etsy.com/uk/shop/mehndibyfarrah#reviews">Etsy</a>```  
