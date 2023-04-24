# VendingMachineSample

### You need to design a Vending Machine which:
- Contains multiple products and accepts coins of 50 cents, 1 EURO, 2 EURO to buy them.
- The available products are ENERGY DRINK (2 EUR), WATER (1 EUR), CHOCOLATE BAR (1.5 EUR), PROTEIN BAR (2.50 EUR).
- You can buy products by putting coins into the machine. The machine has a display to show the amount of money added.
- After selecting a product you:
  - Will get the product if there is enough money in the machine
  - Will see an error if there is not enough money, no product must be given to the user and the needed money should be displayed
- After paying out a product, the machine needs to calculate the change for the user and return the remaining coins.
  - E.g. if a user puts in 2 EUR and buys a chocolate bar, the returned exchange must be 50 cents.
- The last feature is to cancel a product. If a user puts in money but decides to not buy a product. Then the full money needs to be returned.
- Bonus if there is time left: Think about better error handling and more features. A bonus feature is that the vending machine keeps track of the available change. Think about admin features for the vending machine provider.
