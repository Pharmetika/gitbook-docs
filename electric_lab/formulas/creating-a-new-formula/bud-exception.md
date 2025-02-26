# BUD Exception

## Synopsis

A formula can include both bulk ingredients (i.e., ingredients in ElectricLab) and formulas marked with 'add as ingredient', also referred to as sub-formulas or compounded components. BUD Exception can be used for formulas containing compounded ingredient components (i.e., sub-formulas) whose BUD should not be considered when determining the formula's BUD.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcZhv6kIV-xEElrbL8zri5zDRjMe5E_PmRlkZbl0tAgwF8mI011Qczaf-otMbp5Ajb8PYF63NTckiOrTggTbkDfM4mct_5saN8Vuw0Le2jD7o0baVJ18TW0_wJHUqJxJQBrq3FDWwT1r3OlrV4rfGIcb7zJ?key=B7SPq71ZAfZ9fNSxLWqaQw" alt=""><figcaption></figcaption></figure>

## Selecting BUD Exceptions for Formula-Ingredients

* When creating a formula-ingredient profile that will be used in a formula, select the BUD Exception option if applicable.
* A warning will appear when the formula-ingredient marked BUD exception is scanned in a formula, as a reminder of the BUD exception. &#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeqyt7oyakXUy8DPDoxGJK1W0msC5jQA1SpFpXHvDq7KgsiBM8xCCOtn62tevFQwcUXbZXDNoDr2WjrLu5kCP0T5IizGN6Fj7AofcBbtjRCfe8PTt_wBOc-33bzyl9Kjew8xsKogbFAmM072yXm5uqh0K5S?key=B7SPq71ZAfZ9fNSxLWqaQw" alt=""><figcaption></figcaption></figure>

## There are two common scenarios encountered when using a formula-ingredient as an ingredient:

1. If a formula contains a formula-ingredient that DOES NOT have a BUD exception then the formula-ingredient’s BUD **WILL** be used when determining what the BUD of a compounded formula lot will be.

* For example, a formula contains 3 ingredients and 1 formula-ingredient (w/o BUD exception).
  * The formula generally has a stability span of 180 days
  * The 3 ingredients have expiration dates much more than 180 days from now.
  * The formula-ingredient lot used has a BUD of 120 days.
  * In this example, the formula lot will have a 120 day BUD when compounded

2. If a formula contains a formula-ingredient that DOES have a BUD exception then the formula-ingredient’s BUD **WILL NOT** be used when determining what the BUD of a compounded formula lot will be.

* For example, a formula contains 3 ingredients and 1 formula-ingredient (with BUD exception).
  * The formula generally has a stability span of 180 days
  * The 3 ingredients have expiration dates much more than 180 days from now.
  * The formula-ingredient lot used has a BUD of 1 day.
  * In this example, the formula lot will have a 180 day BUD when compounded
