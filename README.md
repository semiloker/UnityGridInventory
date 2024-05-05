# UnityGridInventory
<p>
Unity Grid Inventory System
</p>

It's a simple grid style Inventory for your unity project.
<p>
  Space - spawn random item
  R - rotate item 
  LMB - drag item
  RMB - delete item
</p>
You can change slot size in InventorySettings.cs
<p>
On default settings, slot size = 96, 96
</p>

And i want to do my inventory like 6x9 grid, we need to change width and height in rect transform (in backpack [6x9]): 
<p>
  Width -  6x96 = 576
  Height -  9x96 = 864
</p>
<p>
  ![Screenshot 2024-05-05 132939](https://github.com/semiloker/UnityGridInventory/assets/146450267/56b77349-f6f5-4bdc-967b-6cbe45fc42b6)
  </p>

For items, u need to add ItemData 
<p>
  ![Screenshot 2024-05-05 133048](https://github.com/semiloker/UnityGridInventory/assets/146450267/aaf68c58-0363-499b-9c33-77050ac4f305)
</p>

and change the settings as you need 
<p>
  ![Screenshot 2024-05-05 133152](https://github.com/semiloker/UnityGridInventory/assets/146450267/86c2c6db-8ca2-4728-bf61-91dd447b2819)
</p>

Add the data of the items we created previously to the “Inventory” script
<p>
  ![image](https://github.com/semiloker/UnityGridInventory/assets/146450267/319106de-a8b9-486f-b7cc-5b0a3874a1ba)
</p>

<p>
Finish!
</p>
<p>
  ![Screenshot 2024-05-05 132045](https://github.com/semiloker/UnityGridInventory/assets/146450267/5cb5647d-38e6-494f-b1cb-a2ff9f77b8b0)
</p>
