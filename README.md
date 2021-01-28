# COMP-303-A7
Assignment Instructions:

Area 1 - Basic Domain Objects
- A Menu shall comprise multiple menu items. It shall be possible to add and remove items from the menu.
- The information for every menu item shall include a food type category (e.g., drinks, snacks, mains), a name (e.g., "coffee"), a price (e.g., $2.50), and a set of zero or more dietary categories (vegetarian, vegan, gluten free, etc.).
- It shall be possible to obtain from the menu well-defined subsets of menu items by filtering on their price, food type or any combination of dietary category.

Area 2 - Special Domain Objects
- Certain menu items can be sizeable. A sizeable item should come in three sizes (small, medium, large). The small and large versions should have a corresponding negative/positive price adjustment.
- It shall be possible to create combo items (e.g., beer and chips). Combos shall have a discounted (e.g., 10% off the normal total price). The size of the discount may vary from one combo to the next.
- It shall be possible to put some items on special (e.g., chips are 10% off this week). Combo items can also be put on special, which further discounts their price.
- For any item, it shall be possible to obtain a String-typed description of the item that includes all relevant information. The name of the item should always come first, the price, last, and any other information (e.g., its size, whether it's on special), shall come in the middle.

Area 3 - Notification
- Whenever there is a change to the menu, the menu displays shall be updated accordingly to display the description of all items.
- The items within a panel shall be displayed either in alphabetical order of description or in increasing order of price. This setting does not need to be available in the GUI, but it shall be possible to change this option through a clearly labelled constant in the code.

Area 4 - Configurations
- Different subsets of items shall be displayed on the three menu panel. By default, drinks on the left, mains in the center, and snacks on the right.
- It shall be possible to configure which subset of the menu items shall appear on each panel through the writing of a configuration in the code. An example of a different configuration would be all items in the center, the ten cheapest items on the right, and the combo items on the right. The structure of the code should make it possible to add new configurations.
- The user shall be able to choose between three different configurations using the user interface. It should be possible to change which configurations the user can choose (if there are more than three) by customizing the source code.

My team's solution:
- Utilized observer pattern (for notification) and implemented Java GUI
