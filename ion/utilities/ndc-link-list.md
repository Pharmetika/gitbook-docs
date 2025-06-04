# NDC Link List

Your pharmacy can use NDC links to associate identical or substitutionary products to one another. You might use an NDC link in any of the following scenarios:

* You use two identical formulas.
* You have a 503b product that can be alternatively fulfilled using a compounded product.
* You created a new formula to replace an existing one, and you want to use your product inventory for the existing formula prior to switching over to the new formula.

When you link two NDCs together, you designate a primary product and a linked product. The primary product is the ordered product, and the linked product is the product that can be substituted for the primary product if needed.

To associate primary and linked products, complete these steps:\


1. To get started, download the existing list by following the path **Utilities > NDC Link List** and clicking **Download List**. If you haven’t yet created a link list, clicking **Download List** creates a template file for you to use.&#x20;
2.  In the file, add two rows for each product link you want to create. In the first row, enter the NDC of the primary product in both the **Primary Code** and the **Linked NDC** columns. In the second row immediately below the first row, enter the NDC of the primary product in the **Primary Code** column and the NDC of the linked product in the **Linked NDC** column. When you are finished, each set of rows for a link should look like this:\


    | **Primary Code**                               | **Linked NDC**                                 | **Description (optional)**                                 |
    | ---------------------------------------------- | ---------------------------------------------- | ---------------------------------------------------------- |
    | <mark style="color:orange;">99000778899</mark> | <mark style="color:orange;">99000778899</mark> | <mark style="color:orange;">Example primary product</mark> |
    | <mark style="color:orange;">99000778899</mark> | <mark style="color:blue;">99000776655</mark>   | <mark style="color:blue;">Example linked product</mark>    |
3. Open the **Configure NDC Links** activity by following this path: **Utilities > NDC Link List**.
4. Upload your .CSV file in the **Upload your custom NDC list below** section.
