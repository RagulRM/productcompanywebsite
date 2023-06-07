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

## OUTPUT:
### sample.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Levi's</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/images.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>Levi's</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/images.jpg" alt="logo" />
          <div class="contenttext">
           Levi Strauss & Co. is one of the world's largest brand-name apparel companies and a global leader in jeanswear. The company designs and markets jeans, casual wear and related accessories for men, women and children

           Levi Strauss & Co., world’s largest maker of pants, noted especially for its blue denim jeans called Levi’s (registered trademark). Its other products include tailored slacks, jackets, hats, shirts, skirts, and belts, and it licenses the manufacture of novelty items.
            <br />
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Levi's developed by Ragul R
      </div>
    </div>
  </body>
</html>
```
### product.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Levi's</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/images.jpg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>Levi's</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/P1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Men's 511 Blue Slim Fit Jeans</div>
                  <div class="itemprice">Price: Rs:4,259.00 </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/P2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Levi's Men's Slim Fit Jacket</div>
                  <div class="itemprice">Price: Rs:2,599.00 </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/P3.jpg" alt="product image">
                  </div>
                  <div class="itemname">LEVI'S MEN'S COURTRIGHT SNEAKERS</div>
                  <div class="itemprice">Price: Rs:3,265.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P4.jpg" alt="product image">
                </div>
                <div class="itemname">WOMEN'S SOLID SHIRT COLLAR SHIRT</div>
                <div class="itemprice">Price: Rs:2,277.00</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P5.jpg" alt="product image">
                </div>
                <div class="itemname">Levi's Men's Wallet</div>
                <div class="itemprice">Price: Rs:1,039.00</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/P6.jpg" alt="product image">
                </div>
                <div class="itemname">LEVI'S MEN'S WORDMARK METAL KEEPER BELT</div>
                <div class="itemprice">Price: Rs:1,039.00 </div>
            </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023  Levi's developed by Ragul R.
      </div>
    </div>
  </body>
</html>
```
### people.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Levi's</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/images/images.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>Levi's</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/Ragul.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Ragul R (Founder)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/Kothai.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Kothai K (CEO)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/Shanmathi.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Shanmathi S (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/nethraa.png" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Nethraa J (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/Mithra.png" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Mithra (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/Prithvi.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Prithviraj (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Levi's developed by Ragul R
      </div>
    </div>
  </body>
</html>
```
### contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Levi's</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>Levi's</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:6A,Thirumangalaam main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;9934567789</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <li><b>&emsp;Shop Manager Number:</b>7010586334</li>
                        <li><b>&emsp;Email Id:</b>&emsp;Levi's@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;Levi's@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Levi's developed by Ragul R
      </div>
    </div>
  </body>
</html>

```
### layout.css
```css
*{
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  body {
    background-color: black;
    color: red;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: black;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color:  black;
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
    color:  black;
  }
  
  .menuitem a {
    text-decoration: none;
    color: black;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: white;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: black;
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
  
  .contenttext {
    text-align: justify;
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
  }
  .productitem .itemprice {
    display: block;
  }
  
  .footer {
    display: block;
    width: 100%;
    height: 40px;
    background-color: black;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: red;
  }
```
### contact.css
```css
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  body {
    background-color:black;
    color: black;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-size: 100% 100%;
    margin: -100px 0px 0px 0px;
    padding-top: 150px;
    color: white;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: red;
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
    color: black;
  }
  
  .menuitem a {
    text-decoration: none;
    color: black;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color:white;
    font-size: 20px;
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
  
  .contenttext {
    text-align: justify;
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
  }
  .productitem .itemprice {
    display: block;
  }
  
  .footer {
    display: block;
    width: 100%;
    height: 40px;
    background-color: gray;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: black;
  }
```
## Output
### Home Page:
![ex07 1](https://github.com/RagulRM/productcompanywebsite/assets/121609342/fda684e8-30f2-427f-9caf-56395d87cb0a)
### Product Page:
![ex07 2](https://github.com/RagulRM/productcompanywebsite/assets/121609342/315e705e-87b9-43b2-ace5-06e265ad5451)
### People Page:
![ex07 3](https://github.com/RagulRM/productcompanywebsite/assets/121609342/63a552cd-669c-4bca-af0b-90a0c4d560e4)
![ex07 4](https://github.com/RagulRM/productcompanywebsite/assets/121609342/eb34033b-21c9-4655-a5ac-ea8a9b794766)
![ex07 5](https://github.com/RagulRM/productcompanywebsite/assets/121609342/144863cf-666d-4aff-8ea5-d02b99b069f3)
![ex07 6](https://github.com/RagulRM/productcompanywebsite/assets/121609342/2d11c3f0-9a17-42b2-ab0c-236535418673)
![ex07 7](https://github.com/RagulRM/productcompanywebsite/assets/121609342/1fea79fb-685b-463c-8ab2-b94327e7bd2e)
![ex07 8](https://github.com/RagulRM/productcompanywebsite/assets/121609342/5e3bb688-a40a-4c2e-b675-7749fadf07a5)
### Contact Page
![ex07 9](https://github.com/RagulRM/productcompanywebsite/assets/121609342/48ea9810-81a3-48eb-94af-f34e0fcf337f)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
