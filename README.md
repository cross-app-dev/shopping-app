# Shopping App

## Author(s)
Wael Showair
  
## Description
This mobile/web app enables the users to create lists of items that you want to buy daily. There are two lists in the current version of the application:
- Picked-items list: Which contains list of items that have been already purchased.
- Shopping list : Which contains list of items that would be purchased.
The app handles device orientation by showing both lists properly for portrait mode as well as landscape mode.

It supports current features:
1. Add new item to the list.
2. Remove an item from the list.
3. Move items back and forth picked-items list and shopping list.

## Instruction for using the app
- To Add new item: Fill the text field then press Add button.
- To Move an item from one list to another: Press the checkbox button that is located next to that item.
- To completely delete an item: Press the remove button that is located at the end of that item.

## Software implementaion:
There are two js objects:
**1- utilities**: Which provides some generic functionalities like getting current device height or forming listviews for a given list.
```javascript
utilities.getContentHeight();
utilities.getUlHtmlTag();
```
**2- shopping**: Which contains the core functionalities of the app like creating listviews, set listeners for a given listview
```javascript
shopping.listViewCreate();
shopping.updateListViewListeners();
```
