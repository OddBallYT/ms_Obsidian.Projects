### Root Item Data Structure

##### Variables
name (String) : the item's name
description (String) : the item's description
sprite (SpriteFrames) : the sprite of the item
stack_size (int) : the item's max stack size
value (float) : the value in currency of the item
##### Methods
\_hold : base hold method for the item. Will be the basic hold method, that most items use
\_use : base use method for the item, empty as basic items will have no use in themselves
