# BP\_Lock

## **General**

* **Collision Box Extent** (Vector3D): Vector that sets the size Collision Box.
* **Collision Box Location** (Vector3D): Vector that sets the location Collision Box.
* **Main Mat Ref** (Material): The main material of the lock.
* **bUseAnimationPadlockLoop** (bool): If _True_ then starts the loop (mesh) animation on the lock.

## **Symbols**

* **Password** (String array): The password need to enter. Add as many symbols as indicated in the variable “_**Length Password**_”.
* **Player Digit Password** (Integer array): Here are stored the indexes of symbols that the player enters. Length must be equal “_**Length Password**_”.
* **Random Symbols** (Bool): Starting symbols are set randomly, otherwise they will be set according to the indices from “_**Player Digit Password**_” suchwise you can set the initial symbols manually.
* **Symbols List** (Structure array from String array): An array of character arrays is used to verify the password if the “_**Symbol Password**_” is set to _True_.
* **Symbol Password** (Bool): If set to _True_, then the password will be of letters or mixed (letters and numbers).
* **Length Password** (Integer): Password length. This amount will be created “_**SM\_Symbol**_” (StaticMesh).

## **Spring Arm**

* **Spring Arm Length** (Float): The distance from the lock to the camera when the password is entered.
* **Spring Arm Rotation** (Rotator): Rotating the camera around the lock.

## **Meshes**

* **Materials Symbol** (Material array): Materials with characters for each “_**SM\_Symbol**_”. Quantity must match the “_**Length Password**_”.
* **Start Symbol Location** (Vector3D): Location from which will be created “_**SM\_Symbol**_”.
* **Offset Symbol Location** (Vector3D): Offset each new “_**SM\_Symbol**_”.
* **SM\_Symbol** (Static Mesh): Created procedurally in _Construction script_.
* **Rotate Mesh Symbol** (Rotator): Rotates “_**SM\_Symbol**_”, for example, if the lock is vertical or another device.
* **Duration Switch Symbol** (Float): The time for which the symbol will switch.
* **NumberOfSymbolsOnMesh** (int): The number of characters on “_**SM\_Symbol**_” and on the basis of this variable is calculated the angle of rotation.

## **Input**

* **bVerticalInput** (bool): If _True_ control is convenient for vertical “_**SM\_Symbol**_”, and if _False_ for horizontal.
