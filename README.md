# UnityGridInventory
Unity Grid Inventory System

It's a simple grid style Inventory for your unity project.

Space - spawn random item
R - rotate item 
LMB - drag item
RMB - delete item

You can change slot size in InventorySettings.cs
On default settings, slot size = 96, 96

And i want to do my inventory like 6x9 grid, we need to change width and height in rect transform (in backpack [6x9]): 
Width -  6x96 = 576
Height -  9x96 = 864

![Screenshot 2024-05-05 132939](https://github.com/semiloker/UnityGridInventory/assets/146450267/56b77349-f6f5-4bdc-967b-6cbe45fc42b6)

For items, u need to add ItemData 
![Screenshot 2024-05-05 133048](https://github.com/semiloker/UnityGridInventory/assets/146450267/aaf68c58-0363-499b-9c33-77050ac4f305)

and change the settings as you need 
![Screenshot 2024-05-05 133152](https://github.com/semiloker/UnityGridInventory/assets/146450267/86c2c6db-8ca2-4728-bf61-91dd447b2819)

Add the data of the items we created previously to the “Inventory” script
![image](https://github.com/semiloker/UnityGridInventory/assets/146450267/319106de-a8b9-486f-b7cc-5b0a3874a1ba)

Finish!

![Screenshot 2024-05-05 132939](https://github.com/semiloker/UnityGridInventory/assets/146450267/15f380a6-e54b-4b8d-b676-a15ff71b5b6f)
