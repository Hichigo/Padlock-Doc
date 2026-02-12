# Changelog

## **1.1.1 - 08-09-2019**

### Changed

* Columns with symbols (_**SM\_ColumnSymbols**_) now count from top to bottom.

### **Fixed**

* Fixed bug on **BP\_ColumnLock** with random symbol.

## **1.1.0 - 26-02-2019**

### **New**

* Added mesh columns
* From the lock inherited a new blueprint for **BP\_ColumnLock**
* A door has been added which shows how you can hang more than one lock on the door
* New variables:
  * bUseAnimationPadlockLoop
  * NumberOfSymbolsOnMesh
  * bVerticalInput

### **Changed**

* The character is replaced by a character with switching from the first / third person
* This ([https://youtu.be/oGKDVFvpeto](https://youtu.be/oGKDVFvpeto)) is no longer relevant, now works with any character, the only thing you need to do is transfer the control from **BP\_Player**
* **Map\_Demo** map has been slightly modified, **BP\_ColumnLock** and **BP\_DoorWithTwoLock** have been added to the map
