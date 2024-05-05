# UnityGridInventory
<p>
  <ul>
Unity Grid Inventory System
  </ul>
</p>

It's a simple grid style Inventory for your unity project.
<p>
  <ul>
  Space - spawn random item
  <p>
  R - rotate item 
  </p>
  <p>
  LMB - drag item
  </p>
  <p>
  RMB - delete item
  </p>
    </ul>
</p>
You can change slot size in InventorySettings.cs
<p>
  <ul>
On default settings, slot size = 96, 96
    </ul>
</p>

And i want to do my inventory like 6x9 grid, we need to change width and height in rect transform (in backpack [6x9]): 
<p>
  <ul>
  Width -  6x96 = 576
  <p>
  Height -  9x96 = 864
    </p>
    </ul>
</p>
<p>
  
![Screenshot 2024-05-05 132939](https://github.com/semiloker/UnityGridInventory/assets/146450267/34a78854-c59a-4d8d-bf58-8316e8e0b315)

  </p>

For items, u need to add ItemData 
<p>
  ![Screenshot 2024-05-05 133048](https://github.com/semiloker/UnityGridInventory/assets/146450267/28b44cd2-4997-4bd5-aae2-c236ffbe1911)
</p>

and change the settings as you need 
<p>
  ![Screenshot 2024-05-05 133152](https://github.com/semiloker/UnityGridInventory/assets/146450267/8f81440c-6cdd-4bda-bba7-e946f3d54a6d)

</p>

Add the data of the items we created previously to the “Inventory” script
<p>
  ![Screenshot 2024-05-05 133346](https://github.com/semiloker/UnityGridInventory/assets/146450267/6a45950a-0a61-46f6-8f3e-4b6f135066ff)

</p>

<p>
Finish!
</p>
<p>
  ![Screenshot 2024-05-05 132045](https://github.com/semiloker/UnityGridInventory/assets/146450267/a994dd37-420d-4397-bd61-e2201af3f171)

</p>
