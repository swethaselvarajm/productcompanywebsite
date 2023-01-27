# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```

home.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BERTIE BOTT'S DELICACIES</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/temp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">BERTIE BOTT'S DELICACIES</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us :</h1>
          <img src="/static/img/temp.png" alt="Building" />
          <div class="contenttext">
            We 'Bertie Bott's Delicacies' are over a multi-year-old brand that has appreciated notoriety for being the most choice high-quality chocolates and jellies
            around the World.

          <br/>

            Longing for something phenomenal? If it’s not too much trouble attempt our delicious "normal" jelly beans that are mixed with creepy,crazy 
            flavours in a 20-flavor magical medley,which keeps tasters guessing whether they will get a tasty or tricky flavor with every bite.Some of the tasty 
            flavors include Marshmallow,Cherry,Cinnamon and Blueberry.These are paired with gross flavors like Vomit,Soap, and Earwax as well as odd flavors like
            Sausage,Grass, and Black Pepper for a fun and risky experience.Each 1.2-ounce box is the perfect serving size for kids or the young at heart.Give them 
            out as party flavors at your child's next birthday party or use them as a stocking stuffers for a fun-filled christmas morning.At ‘BERTIE BOTT'S 
            DELICACIES’,everybody—from our chocolatiers to our in-shop chocolate epicureans—is constantly enlivened to remove you from the customary.

            <br/>

            We source premium-quality fixings from around the globe and pick nearby alternatives at whatever point conceivable. We never trade off on quality, and 
            you wager you can taste it. It was properly said that a fair eating regimen implies chocolate in two hands. Everybody has an alternate palette,
            particularly with regards to chocolate and jellies.Regardless of what kind of jelly treat you are fantasizing over today, ensure you are getting an
            eminent portion of our varied blend of jellies, only made only for you. 
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 BERTIE BOTT'S DELICACIES, Developed by Swetha.S
      </div>

 products.html

      <!DOCTYPE html>
<html lang="en">
  <head>
    <title>BERTIE BOTT'S DELICACIES</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/temp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Delicacies We Offer :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b1.png" alt="product image">
                  </div>
                  <div class="itemname">Bubble-gum</div>
                  <div class="itemprice">Price: Rs.500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b2.png"  alt="product image">
                  </div>
                  <div class="itemname">Sausage</div>
                  <div class="itemprice">Price: Rs.350.00</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b3.png"  alt="product image">
                  </div>
                  <div class="itemname">Chocolate</div>
                  <div class="itemprice">Price: Rs.550.00</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b4.png"  alt="product image">
                  </div>
                  <div class="itemname">Coconut</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b5.png"  alt="product image">
                  </div>
                  <div class="itemname">Strawberry</div>
                  <div class="itemprice">Price: Rs.450.00</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b6.png"  alt="product image">
                  </div>
                  <div class="itemname">Vomit</div>
                  <div class="itemprice">Price: Rs.450.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b7.png"  alt="product image">
                  </div>
                  <div class="itemname">Cheese</div>
                  <div class="itemprice">Price: Rs.650.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/b8.png"  alt="product image">
                  </div>
                  <div class="itemname">Pepper</div>
                  <div class="itemprice">Price: Rs.200.00</div>
              </div>
             
          </div>
          </div>  
          </div>
      <div class="footer">
        Copyright &#169; 2021 BERTIE BOTT'S DELICACIES, Developed by Swetha.S
      </div>
    </div>
  </body>
</html>
      
people.html

      <!DOCTYPE html>
<html lang="en">
  <head>
    <title>BERTIE BOTT'S DELICACIES</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/temp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Board Of Directors :</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d2.png" alt="People">
                  </div>
                  <div class="itemname">Ms.Emma Watson</div>
                  <div class="itemprice">Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d1.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Daniel Radcliffe</div>
                  <div class="itemprice">Co-Founder </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d3.png" alt="People">
                  </div>
                  <div class="itemname">Mr. Rupert Grint</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d4.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Tom Felton</div>
                  <div class="itemprice"> Joint-Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d5.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Robert Pattinson</div>
                  <div class="itemprice"> CEO </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/d6.png" alt="People">
                  </div>
                  <div class="itemname">Mr.Henry Cavill</div>
                  <div class="itemprice"> Chief Technical Officer </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; BERTIE BOTT'S DELICACIES, Developed by Swetha.S
      </div>
    </div>
  </body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>BERTIE BOTT'S DELICACIES</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/temp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1>
          <img src="/static/img/c1.png" alt="Building" />
          <div class="contenttext">
            Saveetha Nagar, Sriperumbadur Taluk, Kanchipuram - Chennai Rd, Chennai, Tamil Nadu- 602105
          </div>
          <h1>Phone:</h1>
          <div class="contenttext">
              Ms.Shruthika(HR):6382159898<br/>
              Mr.Sanjay(Assistant HR):6383945689
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              Sales:sales@bertiebottsdelicacies.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 BERTIE BOTT'S DELICACIES, Developed by Swetha.S
      </div>
    </div>
  </body>
</html>

layout.css

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: pink;
  color:black;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px black;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/temp.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px ;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: pink;
}

.menuitem a {
  text-decoration: none;
  color: #000000;
}

.content {
  display: block;
  width: 100%;
  background-color: black;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}
.homecontent h2{
  text-align: left;
}
.contenttext {
  text-align: justify;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color:white;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: white;
}
.productitem .itemprice {
  display: block;
  color: white;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #59ccdbf1;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: black;
}

```

## OUTPUT:
![OUTPUT](./out7.png)
![OUTPUT](./out8.png)
![OUTPUT](./out9.png)
![OUTPUT](./out10.png)

## HTML Validator

![HTML Validator](./valid1.png)

### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
