Demo: https://baby-eboost-demo.myshopify.com/

Password: 1234

# BABY SHOPIFY THEME

## STANDARD SECTIONS

+ Recently Viewed
+ Countdown
+ Free style
+ Products tabs
+ Instagram
+ Icon with text
+ Featured product
+ Featured collection
+ Video
+ Contact Form
+ Email signup
+ Newsletter popup
+ Collapsible content
+ Multirow
+ Multicolum
+ Collage
+ Slideshow
+ Image banner
+ Image with text
+ Rich text
+ Quick order list
+ Collection list
+ Blog posts
+ Announcement Bar

## USE SETTING MENU

![BABY Screenshot](docs/baby-shopify-theme-menu.jpg)


### Add color for top level

1. Go to Online Store -> Themes -> Customize button
2. Sections -> Header  Sections -> Add block -> Color Menu
![BABY Screenshot](docs/Baby-Eboost-Demo-·-Customize-baby-·-Shopify-menu04.png)
3. Select color -> Select url match url that you would like to show color
![BABY Screenshot](docs/Baby-Eboost-Demo-·-Customize-baby-·-Shopify-menu03.png)
![BABY Screenshot](docs/Baby-Eboost-Demo-·-Customize-baby-·-Shopify-menu02.png)


### Add color for 1 level

You only need add an image for collection after it will be shown here

### Add icon for 2 level

1. Go to Online Store -> Themes -> Customize button
2. Sections -> Header  Sections -> Add block -> Icon
3. Upload an icon 
4. Select url match url that you would like to show icon
![BABY Screenshot](docs/Baby-Eboost-Demo-·-Customize-baby-·-Shopify-menu01.png)


## USE PROGRESS SHIPPING (both cart drawer and cart page)

![BABY Screenshot](docs/baby-shopify-theme.jpg)


1. Go to Online Store -> Themes -> Customize button
2. Settings -> Progress Bar Shipping -> check Enable Progress Bar shipping to turn on it
3. Add total price, messages for free shipping

![BABY Screenshot](docs/baby-shopify-theme-progress-config.jpg)


## USE COUNTDOWN ON PRODUCT DETAIL PAGE

To enbable countdown on product detail page. We need follow step by step below:

![BABY Screenshot](docs/baby-shopify-theme-countdown.jpg)


1. Go to Online Store -> Themes -> Customize button -> Settings
2. Expand Product cards -> click Enable Countdown? to enable this featured



3. Select option 
	- Use for all products -> If you chose this option After that go to step 4 
	- Use for different product -> If you chose this option. After that go to step 5
4. Add a deal time with a format like "2025/12/25 22:11:00". This time must be greater than the current time.

5. Go to Content->Metaobjects-> Manage definitions

![BABY Screenshot](docs/Baby-Eboost-Demo-·-Metafield-definitions-·-Shopify.png)

6. Go to Products -> click Add definition button on top right 

![BABY Screenshot](docs/Baby-Eboost-Demo-·-Metafield-definitions-·-Shopify-config.png)

7. Create a metafield

```bash

Namespace: custom
Key: countdown

```
![BABY Screenshot](docs/Baby-Eboost-Demo-·-Product-metafield-definitions-·-Edit-countdown-·-Shopify.png)


8. Go to  products -> Select product that you would like to show count down

9. Add a deal time for this product. This time must be greater than the current time.

![BABY Screenshot](docs/Baby-Eboost-Demo-·-Products-·-Selling-Plans-Ski-Wax-·-Shopify.png)


## SETTING TO SHOW WISHLIST


1. Go to Online Store -> Themes -> Customize button -> Settings

2. Expand Product cards -> click "Enable Wishlist?" to show wishlist icon on card product and product detail page

![BABY Screenshot](docs/baby-shopify-theme-config.jpg)

3. Go to Sections -> Header section -> check "Enable Header Wishlist" 

![BABY Screenshot](docs/Baby-Eboost-Demo-·-Customize-baby-·-Shopify-wishlist-header.png)

3.  Go to Online Store -> Pages -> Create wishlist page

```bash

URL and handle: wish-list
Theme template: wishlist

```

![BABY Screenshot](docs/Baby-Eboost-Demo-·-Wishlist-·-Shopify.png)

## HOME PAGE

![BABY Screenshot](docs/HOME.png)


## COLLECTION PAGE

![BABY Screenshot](docs/PLP.png)

 
##  PRODUCT DETAIL PAGE

 ![BABY Screenshot](docs/PDP.png)


##  CART PAGE

 ![BABY Screenshot](docs/CART.png)

## Bugs/Feature Requests & Contribution

Please do open a pull request on GitHub should you want to contribute, or create an issue.

## License
[BSD-4-Clause](http://directory.fsf.org/wiki/License:BSD_4Clause) - Do as you wish 👍
