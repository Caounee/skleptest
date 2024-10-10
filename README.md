# :boom: <a id="top"> skleptest.pl - exploratory testing of the web application [Jira] </a> :boom:

My tests of a sample website. I grouped the tests into several sets: <i> • [homepage](#homepage) • [menu](#menu) • [shopping cart and ordering process](#shopping_cart_and_ordering_process) • [user account](#user_account) • [product sorting](#product_sorting) • [product pages](#product_pages) • [search](#search). I found a lot of bugs, which I included in my portfolio. </i>

* type of tests: exploratory testing
• tools: Jira, Monosnap

✔️ [screenshots of bug reports on Google Drive](https://drive.google.com/drive/folders/1HZiAgsz2lYCKehnEDEZRamY82VIiPgc_?usp=sharing)

## :sparkles: Testing application address:
* https://skleptest.pl/

## :sparkles: Test assumptions

###  Tester's first name:

* Manuela
  
### Date and time of test execution:

* 14-31.08.2023 (9:00 - 16:00)
* 04-13.09.2023 (10:00 – 15:00)
  
### Environment:

* Windows 10 Pro 64-bit
* Google Chrome version 115, 116
  
### Summary of tools used:

* Jira - bug reporting
* Monosnap – screenshots

## :sparkles: Conclusion

### Tested application elements:

*	<b> homepage </b> - usability, functionality, overall appearance assessment, links, footer, display of products on the website
* <b> menu </b> - menu tabs, links, checking subpages from the menu
* <b> cart and ordering process </b> - adding products to the cart, removing and changing the quantity of products, the ordering process
* <b> user account </b> - account management functions
* <b> product sorting </b>
* <b> product pages </b> - product descriptions, photos
* <b> search </b> - checking the search function

### Evaluation:

* The <b> homepage </b> is easy to use and friendly for users. However, there are some problems that affect the overall rating of the application. Some issues make it harder to shop, and the lack of product pictures means we don't know what the product looks like, so we won't buy it. Some links don't work.
* Not all <b> menu </b> cards contain the right things on the page. When you look through the menu, it's easy to notice many mistakes.
* There are problems with managing products in the <b> shopping cart </b>. The checkout page is confusing for the user.
* The <b> user account </b> page is hard to understand. You can't manage your account.
* The <b> product sorting </b> by price doesn't work.
* On the <b> product pages </b>, some of them don't have pictures, and the buttons for looking at pictures don't work. Besides a few mistakes, the product page looks nice.
* The <b> search </b> function has a few visual errors.

## :sparkles: Bugs:

### <a id="homepage"> ✔ Homepage </a> [[🔼 scroll up 🔼](#top)]


* <b> SK-1 </b> - Invalid tab highlighting in navigation menu (two tabs highlighted)
![SK-1](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-1.jpg)

* <b> SK-2 </b> - Display and positioning issues with "Black Top" product due to missing product image
![SK-2](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-2.jpg)

* <b> SK-3 </b> - Inconsistent products display - presence of ratings and uneven text alignment
![SK-3](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-3.jpg)

* <b> SK-4 </b> - Display and positioning issues with "Blue Sweater" product due to missing product image
![SK-4](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-4.jpg)

* <b> SK-5 </b> - Invalid price in "Sale" section
![SK-5](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-5.jpg)

* <b> SK-6 </b> - Products incompatibility with the "High Heel Shoes" section
![SK-6](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-6.jpg)

* <b> SK-7 </b> - Typo in the word "Catergries" in the menu tab
![SK-7](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-7.jpg)

* <b> SK-8 </b> - Product incompatibility with the "All Black Tops" section
![SK-8](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-8.jpg)

* <b> SK-9 </b> - Lack of redirection after clicking the Email address
![SK-9](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-9.jpg)

* <b> SK-10 </b> - Invalid "Shop Now" button link next to "2016 Autumn Collection"
![SK-10](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-10.jpg)

* <b> SK-11 </b> - Invalid "Learn More" button link next to "2016 Autumn Collection"
![SK-11](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-11.jpg)

* <b> SK-12 </b> - Non-functioning "View cart" button after adding product to cart
![SK-12](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-12.jpg)

* <b> SK-13 </b> - Malfunctioning product scroll arrows on page
![SK-13](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-13.jpg)

* <b> SK-14 </b> - Incorrect redirect from the "Buy Now" button in the "Save up to 50% on our black tops" section
![SK-14](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-14.jpg)

* <b> SK-15 </b> - Incorrect redirect from the "Buy Now" button in the "Save up to 50% on our high heels" section
![SK-15](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-15.jpg)
___
### <a id="menu"> ✔ Menu </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-16 </b> - Header text misalignment on the "Most Wanted" page
![SK-16](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-16.jpg)

* <b> SK-17 </b> - Centering text on the "Most Wanted" page
![SK-17](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-17.1.jpg)

* <b> SK-18 </b> - Header text misalignment on category tab pages from the "Catergries" menu
![SK-18](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-18.jpg)

* <b> SK-19 </b> - No highlighting of the selected tab in the "Catergries" menu
![SK-19](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-19.jpg)

* <b> SK-20 </b> - Incorrect singular form in the "Blouse" category tab in the "Catergries" navigation menu
![SK-20](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-20.jpg)

* <b> SK-21 </b> - No category "Belts" in the "All" tab of the "Catergries" menu 	
![SK-21](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-21.jpg)

* <b> SK-22 </b> - Centering text on the "Catergries" tabs
![SK-22](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-22.1.jpg)

* <b> SK-23 </b> - Incorrect page number selection
![SK-23](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-23.jpg)

* <b> SK-24 </b> - Incorrect page number selection
![SK-24](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-24.jpg)

* <b> SK-25 </b> - Display and positioning issues with "Visual M. T-Shirt" product due to missing product image
![SK-25](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-25.jpg)

* <b> SK-26 </b> - Inconsistent products display in the "Shirts" tab - presence of ratings and uneven text alignment
![SK-26](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-26.jpg)

* <b> SK-27 </b> - Products incompatibility with the "Shoes" category
![SK-27](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-27.jpg)

* <b> SK-28 </b> - Inconsistent products display in the "Shoes" tab - presence of ratings and uneven text alignment
![SK-28](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-28.jpg)

* <b> SK-29 </b> - Product incompatibility with the "Tops" category
![SK-29](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-29.jpg)

* <b> SK-30 </b> - Product incompatibility with the "Blouse" category
![SK-30](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-30.jpg)

* <b> SK-31 </b> - Inconsistent products display in the "Jeans" tab - presence of ratings and uneven text alignment
![SK-31](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-31.jpg)

* <b> SK-32 </b> - Incorrect content in "About Us" tab
![SK-32](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-32.jpg)

* <b> SK-33 </b> - Invalid tab highlighting in navigation menu (two tabs highlighted) in "About Us" page
![SK-33](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-33.jpg)

* <b> SK-34 </b> - Misaligned navigation in "Contact" tab
![SK-34](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-34.jpg)

* <b> SK-35 </b> - Problem with displaying the map, which results in stretching the page in the "Contact" tab
![SK-35](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-35.jpg)

* <b> SK-36 </b> - Unable to contact via the form on the "Contact" page when all fields are filled out
![SK-36](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-36.jpg)

* <b> SK-37 </b> - The appearance of a rectangle when attempting to submit the form on the "Contact" page
![SK-37](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-37.jpg)

* <b> SK-38 </b> - Unable to contact through the form on the "Contact" page when only the required fields are filled out
![SK-38](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-38.jpg)

* <b> SK-39 </b> - Misaligned navigation and incorrect display in "Blog" tab
![SK-39](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-39.jpg)

* <b> SK-40 </b> - Incompatibility in displaying posts in the "Blog" tab
![SK-40](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-40.jpg)

* <b> SK-41 </b> - Duplicate search bar on the "Blog" page
![SK-41](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-41.jpg)

* <b> SK-42 </b> - Different text spacing in the blog menu on the right
![SK-42](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-42.jpg)

* <b> SK-43 </b> - Incorrect number of displayed comments for the posts
![SK-43](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-43.2.jpg)

* <b> SK-44 </b> - Incorrect redirect after clicking on the author of the comment
![SK-44](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-44.jpg)

* <b> SK-45 </b> - Shifted checkbox on the comment submission form
![SK-45](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-45.jpg)
___
### <a id="shopping_cart_and_ordering_process"> ✔ Shopping cart and ordering process </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-46 </b> - The cross button on the shopping cart page is not working
![SK-46](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-46.jpg)

* <b> SK-47 </b> - After changing the quantity of the product, making another quantity change doesn't work
![SK-47](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-47.jpg)

* <b> SK-48 </b> - The non-functioning coupon code addition button
![SK-48](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-48.jpg)

* <b> SK-49 </b> - Unreadable checkout page
![SK-49](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-49.jpg)

* <b> SK-50 </b> - Non-functioning order print button
![SK-50](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-50.jpg)

* <b> SK-51 </b> - Incorrect default quantity for adding products to cart
![SK-51](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-51.jpg)
___
### <a id="user_account"> ✔ User account </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-52 </b> - Error when attempting registration with a long email address
![SK-52](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-52.jpg)

* <b> SK-53 </b> - Unreadable user account page
![SK-53](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-53.jpg)

* <b> SK-54 </b> - Invalid content on the user account details page
![SK-54](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-54.jpg)
___
### <a id="product_sorting"> ✔ Product sorting </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-55 </b> - No action after clicking "Sort by price" button
![SK-55](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-55.jpg)
___
### <a id="product_pages"> ✔ Product pages </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-56 </b> - Header text misalignment on products pages
![SK-56](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-56.jpg)

* <b> SK-57 </b> - Non-functioning buttons in the enlarged view on the product page
![SK-57](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-57.jpg)

* <b> SK-58 </b> - The "Add to cart" button on the products pages is not working
![SK-58](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-58.jpg)

* <b> SK-59 </b> - Centering text on the products page
![SK-59](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-59.1.jpg)
___
### <a id="search"> ✔ Search </a> [[🔼 scroll up 🔼](#top)]

* <b> SK-60 </b> - Different text spacing between text in search results
![SK-60](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-60.2.jpg)

* <b> SK-61 </b> - There is no spacing from the next element after the search bar
![SK-61](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-61.2.jpg)

* <b> SK-62 </b> - The button has a different height compared to the search bar
![SK-62](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-62.2.jpg)

* <b> SK-63 </b> - The page stretches when entering long text in the search bar
![SK-63](https://raw.githubusercontent.com/Caounee/skleptest/images/SK-63.2.jpg)
