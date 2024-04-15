---
Tags: shelf
Make:
  Raspberry Pi Shelf:
    template: printing.md
    stl-file: models/RPi_4B_Shelf_v1.3.stl
    stlname: RPi_4B_Shelf_v1.3.stl
    material: PLA
    weight-qty: 50g
---

# The Pi Shelf

## Assembling the Pi Shelf

{{BOM}}

[M2.5x6mm cap screws]: parts/Hardware.yaml#CapScrew_M2.5x6mm_SS

## Position the Raspberry Pi {pagestep}

* Take the [Raspberry Pi Shelf]{make, qty:1, cat:printed} you printed earlier

![](images/PiShelfAssembly1.jpg)

* Position the [Raspberry Pi 4B](parts/RPi_4B.md){qty:1, cat:net} on the shelf so that the ports align with the large hole

![](images/PiShelfAssembly2.jpg)


## Secure the Raspberry Pi {pagestep}

* Adjust the Raspberry Pi so that the 4 lugs on the tray align with the 4 holes in the PCB
* Using four [M2.5x6mm cap screws]{qty:4} and a [2mm Allen key](parts/metric_allen_keys.md){qty:1, cat:tool}, secure the pi to the shelf.

![](images/PiShelfAssembly3.jpg)
