* Item_Resource
	* Data structure of the base item
	* Holds data related to specific items
* Item_Node
	* Loads Item_Resource, by referencing GlobalItemList at runtime to manage method calls
* Item_UI_Node
	* Loads Item_Node and uses data to populate ui elements (sprite)
* Slot_UI_Node
	* Item_UI_Node made as a child of Slot_UI_Node
	* Has methods to help with pick and put to and from the slot
* Local_Inventory_Node
	* Initializes a grid of Slot_UI_Nodes based on the capacity of the inventory
* Global_Inventory_Node
	* Manages inventory functionality (drag/drop) to allow for cross-inventory item placements