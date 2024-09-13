Custom Armour Template

How does this work
It uses the new features added in 24w36a which allows you to add custom models and also custom item texures without using custom_model_data.

How to spawn the copper armour
Here are the commands to spawn the armour:

Helmet
/give @s minecraft:iron_helmet[minecraft:item_name="'Copper Helmet'", item_model="custom.armour:copper_helmet", equippable={slot:head, model:'custom.armour:copper'}]

Chestplate
/give @s minecraft:iron_chestplate[minecraft:item_name="'Copper Chestplate'", item_model="custom.armour:copper_chestplate", equippable={slot:chest, model:'custom.armour:copper'}]

Leggings
/give @s minecraft:iron_leggings[minecraft:item_name="'Copper Leggings'", item_model="custom.armour:copper_leggings", equippable={slot:legs, model:'custom.armour:copper'}]

Boots
/give @s minecraft:iron_boots[minecraft:item_name="'Copper Boots'", item_model="custom.armour:copper_boots", equippable={slot:feet, model:'custom.armour:copper'}]

How to create your own
1. Change copper.json and it's contents to your armour!
2. Replace the humanoid and humanoid_leggings to your textures!
3. Change the item textures to yours!
4. Use .replace.bat and replace copper to your armour!
5. Modify the commands in this file to spawn your custom armour!