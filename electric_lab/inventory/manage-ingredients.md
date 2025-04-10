# Manage Ingredients

To search for an ingredient, type in the name of the ingredient. To search by a part of the ingredient name, enter % and then the search terms. For example, to find petrolatum white, you can type “petrolatum white” or “%white”.

For new ingredients, click the **+New** button on the right side to add the ingredient.

<figure><img src="../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

## Adding a New Ingredient

1. In the **Ingredient Description** field, enter the name of the ingredient. Make sure to verify the spelling.
2. In the **Code** field, enter a short code, such as “E2” for estradiol. This is a required field.
3. In the **Units** field, select the units from the dropdown menu. Frequently-used units include grams, mL, each, or capsules. The units must remain consistent throughout the system. If you enter olive oil in mL, do not enter a unit of liters in another place. The scales weigh in grams, so kg would not be appropriate as the unit of measure for ingredients weighed using scales.
4. In the **Primary NDC** field, enter the NDC you have in stock or the one you use most frequently. This information is used in the ION dispensing system to determine the schedule of the ingredient, so verify that you are using an accurate NDC. If there is no NDC and you want the ingredient sent to the dispense system (for example, for pricing the compound), enter a unique numeric identifier of 11 digits or fewer. If you do not need the ingredient in the dispense system, such as for an ingredient not used for billing, leave the primary NDC blank.
5. Click the refresh button for the **Primary NDC** field (A). This step is important to make sure controlled substance ingredients are linked to the appropriate substance in the **Linked Substance** field for dispensing in ION (B).&#x20;

<figure><img src="../.gitbook/assets/Refreshing NDC for linked substance.png" alt=""><figcaption></figcaption></figure>

6. In the **Cost Basis** field, enter the acquisition cost in a per unit format. Remember to use the unit you selected from the dropdown menu in the **Units** field.
7. If the ingredient is considered hazardous as defined by USP <800>, select the **Hazardous** checkbox. For more information, refer to the CDC's list of hazardous drugs: [https://www.cdc.gov/niosh/docs/2016-161/pdfs/2016-161.pdf](https://www.google.com/url?q=https://www.cdc.gov/niosh/docs/2016-161/pdfs/2016-161.pdf\&sa=D\&source=editors\&ust=1716828712668033\&usg=AOvVaw0wuuuZ2Ggj0hlESmvQG0Hm)
8. If the ingredient is an active pharmaceutical ingredient, select the **Active** checkbox. Active pharmaceutical ingredients are not checked for excipients, bases, etc.
9. If the ingredient is to be tracked, but its expiration date should not be used in determining the BUD of the finished preparation, select the **Consumable** checkbox. An example of a consumable ingredient is sterile tubing.
10. If the ingredient has activity that can vary from lot to lot, select the **Has Activity Factor** checkbox.
11. If the ingredient has pack stats, select the **Has pack stat** checkbox. For more information about using pack stats, refer to the [Pack Stat Module](pack-stat-module/) documentation.

## Manufacturers

{% hint style="info" %}
Make sure you double check all manufacturer information for accuracy before saving.&#x20;
{% endhint %}

1. Select the manufacturer from the available options. Click the **+Add** button.
2. In the **Code** field, scan the barcode of the container.
3. In the **NDC/UPC** field, enter the NDC. If the NDC is not available, select the UPC option from the dropdown menu and scan the UPC. If neither the NDC nor the UPC are available, select **Other** and enter the desired information. &#x20;
4. Click the **+** symbol to add the entered information.
5. Repeat this process for adding other manufacturers or package sizes.&#x20;
6. Click **Save** at the top right to add the ingredient.

<figure><img src="../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>
