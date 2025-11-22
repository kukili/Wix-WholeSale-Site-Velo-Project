# Wix-WholeSale-Site-Velo-Project
Wix Velo Code Project for WholeSale System is created also by using the ChatGPT and Claude AI systems.
The system idea is the parse of the product count designated in the name of the product which is defined in the WIX Products Media through WIX Administration panel.
For example, if the name of the product contains "(24 pieces x 12 $)", the Velo code behind any page designed in this reprository, parses via Regex and fetches the
particular pieces ratio (24 in the example), builds the "Product Count Ratio" in the button which is used to increase and decrease the product count before passing
to the cart of the system. Then the user who visits the e-commerce system internet page, can only decrease or increase the relevant product sales number in count of the 
ratio number parsed in the name of the relevant product defined through WIX Product Administration panel.

1-) "WIX MAIN PAGE PRODUCTS VELO CODE PAGE.txt" contains the code which controls the products of the site which is feeded by the WIX CMS of Stores DB.
    The data is presented in a four container repeater schema where each page contains the first sixteen products of the whole portfolio.

2-) "WIX PRODUCTS CART-JSW BACKEND SERVICES VELO CODE .txt" contains the code which controls the CART.JSW WIX Backend file that controls the cart services, is called by
    the codes in the "WIX MAIN PAGE PRODUCTS VELO CODE PAGE.txt" , "WIX MY FAVOURITE PRODUCT PAGE VELO CODE .txt" , "WIX PRODUCT SPECIAL PAGE VELO CODE.txt" .

3-) "WIX PRODUCT SPECIAL PAGE VELO CODE.txt" contains the code which controls the page presenting the each WIX product special information. 

4-) "WIX STORES-CATALOG ACCESS PRODUCTS-JSW BACKEND SERVICES.txt" contains the code which controls the "karmaPrimaryCat.jsw" WIX Backend file that controls the access
    procedures of the WIX CMS Stores DB data which is called by the code in the  "WIX MAIN PAGE PRODUCTS VELO CODE PAGE.txt" .

5-) "WIX PRODUCT SPECIAL LIGHTBOX PAGE VELO CODE.txt" contains the code which controls the lightbox page which controls the magnificaiton of the picture which is defined 
    in the product special page that is controlled by the codes, defined in the "WIX PRODUCT SPECIAL PAGE VELO CODE.txt" file.

    <img width="1399" height="408" alt="image" src="https://github.com/user-attachments/assets/a0bfff0a-8bda-4c1f-b9bb-18bb08a35080" />

 
