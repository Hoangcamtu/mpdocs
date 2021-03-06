# Automatic Related Products

## Overview

[Magento 2 Automatic Related Products](https://www.mageplaza.com/magento-2-automatic-related-products/) (ARP) is a tool that helps admins establish links between new products easily. In brief, ARP is a recommendation tool, similar to [Who Bought This Also Bought](https://www.mageplaza.com/magento-2-who-bought-this-also-bought/) or [Frequently Bought Together](https://www.mageplaza.com/magento-2-frequently-bought-together/), but more additional outstanding features, and give more rules as well as managements in the backend.


## Download & Install

You can download from the following resouces:

- [Mageplaza](https://www.mageplaza.com/magento-2-automatic-related-products/)
- [Magento Marketplace](https://marketplace.magento.com/mageplaza-module-automatic-related-products.html)
- [How to Install](https://www.mageplaza.com/install-magento-2-extension/)

## How to configue

Login to Magento Admin, choose ``Marketing > Automatic Related Products``

![ARP1](https://i.imgur.com/TlpDp0X.png)

Follow our given guide below to complete Automatic Related Products configuration which includes
* Manage Rules
  * Manage Rules on Product Page
  * Manage Rules on Category Page
  * Manage Rules on Shopping Page
* Configuration
  
### 1. Configuration

From the Admin Panel, go to ``Stores > Settings > Configuration > Mageplaza Extensions > Automatic Related Products``

![ARP2](https://i.imgur.com/rOYaVnW.png)

* In the **Enable Automatic Related Products** field, choose “Yes” to enable the extension.

### 2. Manage Rules on Product Page
This section allows you to install the Related Product Block in your desired Product Page. Product pages that meet this rule, the Related Product Block will be displayed.

To create a new Rule on Product Page, go to ``Marketing  > Automatic Related Products > Manage Rules``. In the Add Rule section, select Product Page

![ARP3](https://i.imgur.com/n0AtHY8.png)

#### a. Rule Information

* In the **Statistic** page where the Rule is applied, the Product selection from the Block of ARP along with the percentage between the Product selection and the Page entry

![ARP4](https://i.imgur.com/Msywy2I.png)

![ARP5](https://i.imgur.com/htzfwAi.png)

* In the **Rule Information** field

![ARP6](https://i.imgur.com/nH0mjXG.png)

  * **Rule Name** field is where you name the rule. The rule name will be displayed on the Grid in Manage Rules Page and visible only with admins. This is a required field so there will be an error message if you leave it blank.
  
  * **Where to Display**  is where you specify where the block is located in the Product Page 
  
    * **Replace Related Products**: The new block will replace  the Magento's default Related Product Block
    
    * **Replace Upsell Products**: The new block will replace  the Magento's default Upsell Products Block
    
    * **Before native related products**: Auto Related Product block displays above the Magento's Related Product block
    
    * **After native related products**: Auto Related Product block displays below the Magento's Related Product block
    
    * **Before upsell products**: Auto Related Product block displays above  the Magento's Related Product Block
    
    * **After upsell products**: Auto Related Product block displays below  the Magento's Related Product Block
    
    * **Above Content**: Auto Related Product block displays above the Content of the Product Page
    
    * **Below Content**: Auto Related Product block displayed under the Content of the Product Page

    * **Floating Left Bar**
    
    * **Floating Right Bar**
    
    
* **Manually**: Admins can adjust the position to show the ARP Block according to the guide. With the guide is Manually, ARP only works on the Product List Page and Product Detail Page

![ARP7](https://i.imgur.com/8yIqfqM.png)

  * In the **Status** field: choose "Active" to enable the rule.  
  * In the **Store View** field you can select the store view where the Rule applies on.
  * In the **Customer Group** field: The rule is only applicable to customers who in  the selected group
  * In the **From** field is where you select the starting date of the Rule applied to the Product Page. You can either select by calendar or directly enter the date In the **To** field is where Select the ending date the Rule is applied. You can either select by calendar or directly enter the date
  * In the **Priority** field
    * This is the field where you enter the priority of the rule. The higher priority (smaller number) rule will be applied to Product Page
    * Priority won’t impede the application of multiple rules on a product page. Higher priority blocks will be ordered first.
    * In case there are multiple rules with the same priority, the rule with  smaller ID will be applied.
    * Priority doesn’t affect to Parent Rule and Child Rule
    
#### b. Products to Meet Conditions

* **Configure Conditions**
  * This is where you select the conditions for pages. Only product pages which match the setup conditions, the new rule will be displayed
  * You can add, remove conditions by clicking on + or x
  * You can change the true/false of the condition by clicking the bold text

![ARP7](https://i.imgur.com/7IKRX23.png)

* **Preview Products**
After saving the conditions, you can get a Product List. Click on ``Preview Product`` to display the products that meet the conditions.

![ARP8](https://i.imgur.com/0sw92Ya.png)

#### c. Products to Show

* **Block configuration**

![ARP11](https://i.imgur.com/ROY93nD.png)

  * The **Block name** field is where you can name the block which is displayed in the frontend. If you don’t want to have it named, leave it blank.
  * In the **Product Layout** field: There are two modes. You can choose the Slider mode or the Grid mode
  * In the **Display mode** fields: There are two Display Style that you could choose.
    * **Ajax Display**: The ARP block is loaded after the page loads, and it will take a while to display in the Frontend. This option is useful for loading speed of page
    * **Block Display**: ARP block will be loaded when loading page and display as soon as the page is loaded. This option helps improve SEO for the page. And this style does not support A / B Testing Rule
  * In the **Limit number of products** field: Enter the maximum number of products displayed in a block.. If you leave it blank or set 0, all of products in the Product List will be displayed
  * In the **Display "Out-of-stock" products** field: select “No” to not display Out-of-Stock products in the Auto Related Product block.
  * In the **Product order** field: choose how to sort products in the block
    * **Bestseller**: more purchased products will be displayed first.
    * **Lowest Price**: products displaying based on low to high price
    * **Highest Price**: products displaying based on high to low price
    * **Newest**: newer products added will be displayed first
    * **Random**: products are selected randomly from the Product List
  * In the **Display additional information** field: choose additional information or/and buttons displayed under products in the block, include Price, Review Information, Add to Cart, Add to WishList, Add to Compare buttons.
  * In the **Add Product** field:
    * Choose an available related type of products to set for the block (Related Products, Up-sell Products, Cross-sell Products)
    * Each of product page can have different related product blocks which you can configure them in here.
    * How to configure Related, Up-sell, Cross-sell Product document can be found [here](https://www.mageplaza.com/blog/how-to-add-and-remove-related-products-magento-2.html)
  * In the **Do not Display Product in** field: Eliminate the products which are added to Cart or WishList out of ARP block 
  
* **Condition**
  * **Setting**: 
    * Choose Products which are displayed in ARP block. Only Products which are match with the condition here are displayed in block
    * You can add, remove condition by clicking on + or x
    * You can change the condition of the condition by clicking bold
    
![ARP10](https://i.imgur.com/lOviiJD.png)

  * **Preview Products**: After saving the condition, we get a Product List. Click on **PREVIEW PRODUCTS** to display the products that match the condition. Products are displayed in Block


#### d. A/B Testing

* A/B testing doesn't apply to [Block Display](http://docs.mageplaza.com/automatic-related-products/index.html#i-configuration)
* After a parent rule (an original rule) is generated, a child rule can be created by clicking Add A/B Testing.You can edit the this child rule in the same way to set up parent rules.

![ARP11](https://i.imgur.com/c5uPGcT.png)

* When two rules are simultaneously active, these two rules will be applied alternately in Product Page.
* If one of the two rules is inactive, the other rule will work normally
* After the A/B Testing Rule is created, the Statistic section will be changed to sum up the views, clicks, and CTR rates of two rules.

![ARP12](https://i.imgur.com/2I5bZ03.png)

* In the **Parent Rule** section of the A/B Testing: it will indicate which of the two links is the Parent - Child. From the Parent Rule you can go to this section to quickly switch to the Child Rule by clicking on the Child Rule Link

![ARP13](https://i.imgur.com/3frYphJ.png)

* Also in the Child Rule there is a Parent button to quickly switch to Parent Rule

![ARP14](https://i.imgur.com/xSCFup8.png)

### 3. Manage Rules on Category Page
This section allows you to install the Related Product Block in the Category Page that you desire. For category pages that satisfy this rule, the Related Product Block will be displayed in the selected location

Headings in the Rule Category Page are quite similar to the Rule Product Page, we will only point different places out for you in this guide.

#### a. Rule Information

In Rule information, the only difference is about Location. There are 5 Location options to display the Block in Category Page. In 

![ARP15](https://i.imgur.com/J0mXNC3.png)

* **Sidebar Top**: Related Products Block is displayed at the top of Sidebar
* **Sidebar Bottom**: Related Products Block is displayed at the bottom of Sidebar
* **Above Content**: Related Product Block is displayed on top of Content in Category Page
* **Below Content**: Related Product Block is displayed below Content in Category Page
* **Manual**: It is entirely similar to Product Rule

#### b. Products to Meet Conditions

* By Conditions, you can select the Category Page you want the Rule to be applied to, you cannot select as many conditions as the Product Page.

![ARP16](https://i.imgur.com/ApF3UKv.png)

* There’s no Preview Product here (Because this is choose Category)

#### c. Products to Show
* Action Page of Category Rule doesn't have *Add Product item* as in Product Page Rule.
* For the rest, it's similar to Action section of Product Page. Click [here](https://docs.mageplaza.com/automatic-related-products/index.html#action) to refer.

#### d. A/B Testing
Completely Similar to A/B Testing of the Product Page. Click [here](https://docs.mageplaza.com/automatic-related-products/index.html#a-b-testing) to refer.

### 4. Manage Rules on View Cart Page
This section allows you to install the Related Product Block in your desired View Cart Page. When the View Cart Page fulfills the Rule, the Related Product Block will be displayed in the selected position.

Headings in the Rule Shopping Page are quite similar to the Rule Product Page, we will only guild you the diferences. 

#### a. Rule Information

In the Rule Information, the only different is about Location. There are 6 Location options to display the Block in Category Page, it lacks 3 options relating to Related Product compare to Product Rule

![ARP17](https://i.imgur.com/D1Xsob4.png)

#### b. Products to Meet Conditions

You can select the same conditions as the Product Page. Furthermore, you can set additional conditions for Total Items in the Cart, Total Price and Total Volume of Products.

![ARP18](https://i.imgur.com/eHd1UQ4.png)

#### c. Products to Show
* Action Page of Shopping Cart Page Rule doesn't have *Add Product* as in Product Page Rule.
* For the rest, it's similar to Action section of Product Page. lick [here](https://docs.mageplaza.com/automatic-related-products/index.html#action) to refer.

#### d. A/B Testing
Completely Similar to A/B Testing of the Product Page. Click [here](https://docs.mageplaza.com/automatic-related-products/index.html#a-b-testing) to refer.

### 5. Manange Rules on One Page Checkout
* ARP compatible with the Mageplaza OSC extension, the admin needs to set OSC to display ARP on the Frontend.
* The settings are quite similar to other rules

### 6. How to reject ARP extension in a specific Product Detail
* Choose `Catalog > Product > Edit Product` which admin does not want to adopt  ARP extension
* Choose **Related Products, Up-Sells, and Cross-Sells**
* Enable  **Manually Setup Auto Related Products**
* Save Products
This function makes the ARP extension not to work on this product. The Related Products which are displayed in Frontend will be based on the Related of Product with the design after Core

### 7. How to set the Where to display = (Manually) 
Firstly, the Admin needs to set the Rule with Where to Display = Manually and set store view = All Store Views, and then can customize the ARP block in the following ways. Otherwise, the Frontend will display both Widgets and Rules

#### a. Create Widget
* **Step 1**: Select the Type
  * Choose `Content > Elements > Widgets > Add Widget`
  * In the Setting section, choose `Type = ARP Product List`, degisn any theme

![ARP19](https://i.imgur.com/jGsFtn3.png)

  * Choose the `Continue` button

* **Step 2**: Set up Widget
  * In the Storefront Properties section:
      * Enter the name of Widget and StoreView display
      * At Layout Update, choose the Widget display page in Display on, after that choose the display position for Widget on that page in the Container section
      * Need to select Display on = Category if you want to custom the Category Rule and select Display on = Product if you want to custom the Product Rule. If not, the Rule will not be display

![ARP20](https://i.imgur.com/oyt9f9q.png)

  * In the Widget Option section, choose the Rule Name that you want

![ARP21](https://i.imgur.com/wqEQSf7.png)

![ARP22](https://i.imgur.com/Gj7drW1.png)

  * Choose Save to finish creating Widget
* **Step 3**: Check in Frontend

#### b. Insert ARP in CMS Static Block
* **Step 1**: Insert the ARP into the CMS Static Block
  * Select `Content > Elements > Blocks > Edit / Add New CMS Static Block` that you want to add ARP
  * In Content of CMS Static Block, there are 2 ways to add ARP
      * Option 1: Select `Insert Widget> Widget Type = ARP Product List> Select Rule Name> Click Insert Widget`

![ARP24](https://i.imgur.com/8NG2hXZ.gif)

  * Option 2: Click on `Show / Hide Editor`, then paste the following code directly into Content. You can change rule_id to the ID of the rule that you want to insert
      
```
{block class = "Mageplaza \ AutoRelated \ Block \ Widget \ ProductList" rule_id = "1"}}
```

![ARP25](https://i.imgur.com/FPhlh2T.png)

  * Select `Save` to save the change

* **Step 2**: Check the Frontend

#### c. Insert the code into the .phtml file
This way you can insert anywhere you want, you just only need to know the location of the .phtml file
```
$objectManager = \Magento\Framework\App\ObjectManager::getInstance(); 
$productList= $objectManager->create("Mageplaza\AutoRelated\Block\Widget\ProductList")->setRuleId(1)->toHtml(); 
echo $productList;
```



    











  
  
    
  


