# KripSimpleAPI
How to use KripSimpleAPI
---
Put KripSimpleAPI.java in the same folder as the main .java file of your mod (and api for 1.20.4)
 
 # _**If you want an item, then write this in the main .java file of your mod:**_
 ```KripSimpleAPI.registerItem("example_item", ItemGroup.MISC);```

 # _**If you want an block:**_

 ```KripSimpleAPI.registerBlock("example_block", Material.STONE, ItemGroup.BUILDING_BLOCKS);```

 # _**If you want an group**_

 ```ItemGroup newGroup = KripSimpleAPI.createItemGroup("Example Group", example_Item);```
 

# _**If you want a register item in group**_

```KripSimpleAPI.registerItem("example_item", newGroup);```

---

*P.S.*

 (Example Group - name)

 (example_item - item on preview your group)


*P.S.S.*

Of course you can change the group and material of the block/item/

and change item and name of the group 

and id block or item
