---
Make:
  bottom:
    template: printing.md
    stl-file: models/bottom_v1.3.stl
    stlname: bottom_v1.3.stl
    material: PLA
    weight-qty: 50g
  rack legs:
    template: printing.md
    stl-file: models/Rack_Leg_21_Units.stl
    stlname: Rack_Leg_21_Units.stl
    material: PLA
    weight-qty: 60g
  stuff shelf:
    template: printing.md
    stl-file: models/Stuff_Shelf_1.0.stl
    stlname: Stuff_Shelf_1.0.stl
    material: PLA
    weight-qty: 50g
---

# Construct the and populate the rack

{{BOM}}

[M4x10mm countersunk screws]: parts/Hardware.yaml#CskScrew_M4x10mm_SS
[M4x10mm cap screws]: parts/Hardware.yaml#CapScrew_M4x10mm_SS

## Attach the legs to the bottom{pagestep}

* Get the [bottom]{make, qty:1, cat:printed} and the four [rack legs]{make, qty:4, cat:printed} that you printed earlier.
* Get an [3mm Allen key](parts/metric_allen_keys.md){qty:1, cat:tool} ready
* Use four [M4x10mm countersunk screws]{qty:4} to attach a leg to each corner of the bottom.

![](images/RackAssembly1.jpg)
![](images/RackAssembly2.jpg)

## Add the NUC and Netgate shelves {pagestep}

* Lightly screw two [M4x10mm cap screws]{qty:2, cat:mech} into the top two holes of the [Assembled NUC Shelf](nuctall_shelf.md){make, qty:1, cat: prev} until they first start to bite.
* Check the screws are not protruding through the back of the shelf-front
* Slide the shelf over the legs and down to the bottom of the rack
* Don't tighten  the screws up yet!

![](images/RackAssembly3.jpg)

* Repeat the same process with the [Assembled Netgate Shelf](netgate_shelf.md){make, qty:1, cat: prev} and two more [screws][M4x10mm cap screws]{qty:2, cat:mech}.


![](images/RackAssembly4.jpg)
![](images/RackAssembly5.jpg)

## Mount the Omni on top of the rack {pagestep}

* Take the [Assembled Omni Shelf](omnicharge_shelf.md){make, qty:1, cat: prev} and place it on top of the rack so the screen on the omni face the front of the rack.
* Use four [M4x10mm countersunk screws]{qty:4} to attach the shelf to the four legs of the rack

![](images/RackAssembly6.jpg)

## Mount the Patch Panel and Switch {pagestep}

* Slide the [Assembled Patch panel](patch_panel.md){make, qty:1, cat: prev} into the rack  as high as it will go.
* Use two [M4x10mm cap screws]{qty:2, cat:mech} to secure it in place.

![](images/RackAssembly7.jpg)

* Now slide the [Assembled UniFi Switch Shelf](switch_shelf.md){make, qty:1, cat: prev} underneath the patch pannel.
* Use two [M4x10mm cap screws]{qty:2, cat:mech} to secure it in place.

![](images/RackAssembly8.jpg)

## Raise the NUC and Netgate shelves {pagestep}

* Slide both the Netgate and the NUC shelved up as high as they will go.
* Tighten the screws in these shelves to hold them into the rack.

![](images/RackAssembly9.jpg)

## Insert the remaining shelves {pagestep}

* Insert the final four shelves into the remain space in the following order (from top to bottom)
    * [Assembled USB Power Shelf](usb_shelf.md){make, qty:1, cat: prev}
    * [Assembled SSD shelf](ssd_shelf.md){make, qty:1, cat: prev}
    * [Assembled Raspberry Pi Shelf](pi_shelf.md){make, qty:1, cat: prev}
    * [Stuff Shelf]{make, qty:1, cat: printed}
* Secure each in place with two [M4x10mm cap screws]{qty:8, cat:mech} 

![](images/RackAssembly10.jpg)
![](images/RackAssembly11.jpg)
![](images/RackAssembly12.jpg)

## Insert the remaining screws {pagestep}

* Finally fill the remaining holes in the front of the shelves with [M4x10mm cap screws]{qty:16, cat:mech}.

![](images/RackAssembly13.jpg)



