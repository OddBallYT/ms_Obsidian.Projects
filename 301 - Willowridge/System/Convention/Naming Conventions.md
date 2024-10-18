* **Files**
	* **Autoload**: PascalCase
	* **Blueprint**: PascalCase
	* **Component**: snake_case
	* **JSON**: *same as resource*
	* **Resource Structure**: SCREAMING_CASE
		* **Resource**: Pascal_Snake_Case
	* **Scene**: SCREAMING_CASE
	* **Script**: *matches convention of respective node*
* **Members**
	* **Classes**: PascalCase
	* **Constants**: SCREAMING_CASE
	* **Enums**: PascalCase
		* **Enum Values**: SCREAMING_CASE
	* **Methods**: snake_case
	* **Signals**: snake_case
	* **Variables**: snake_case
#### Underscores
* Leading Underscore
	* overrides
	* private methods
	* private variables
* Trailing Underscore
	* container nodes
#### Naming Convention
Files are named from general to specific. For example: RES_ITEM_GEAR : RES (type) > ITEM (parent class) > GEAR (name)

###### Type Prefixes
* BLP : blueprint
* CMP : component
* RES : resource