# Wix-WholeSale-Site-Velo-Project
Wix Velo Code Project for WholeSale System
The system idea is the parse the product count designated in the nmae of the product which is defined in the WIX Products Media through WIX Administration panel.
For example, if the name of the product contains "(24 pieces x 12 $)", the Velo code behind any page designed in this reprository, parses via Regex and fetches the
particular pieces ratio (24 in the example), builds the "Product Count Ratio" in the button which is used to increase and decrease the product count before passing
to the cart of the system. Then the user who visits the e-commerce system internet page, can only decrease or increase the relevant product count in count of the 
ratio number parsed in the name of the relevant product defined through WIX Product Administration panel.
