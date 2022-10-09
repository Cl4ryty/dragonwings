# How to assemble the keyboard

Read the FULL instructions BEFORE starting the assembly and also fully read those for each step when you reach that part to avoid mistakes due to incomplete understanding.

## 1. Make sure you have all the parts and tools required.
For the complete keyboard you need:

- parts: dragonwings kit (or otherwise acquired equivalent parts) containing:
    - dragonwings pcb & backplate
    - 30 pink choc switches (linear 20gf)
    - 30 MCC keycaps
    - Pro Micro
    - 5 through hole rubber feet, 5mm diameter (search for glass table top spacers)
    - 1 UNC 1/4" hex nut
    - 7 M2x5mm standoffs
    - 14 M2x4mm screws
    - 1 SMD button, 5x5x2mm
    - 30 SMD diodes (1N4148W, SOD-123)

- tools:
    - small cross tip screwdriver
    - soldering iron (with small enough tip to solder the SMD components)
    - solder
    - fireproof mat/table to solder on
    - tweezers for holding the diodes (and button) into place while soldering
    - hot glue gun and hot glue to fixate the insert tripod mount and prevent the shorting the ProMicro
    - optional:
        - sharp knife to cut away excess glue
        - soldering wick or pump in case you need to remove excess solder

I would recommend to at least check if the ProMicro is working before soldering it on, as this can be quickly tested by connecting it to a computer and saves a lot of work in case it is defective.  
Also, please make sure to only solder in a well ventilated area as soldering fumes can be toxic, especially when using leaded solder.

## 2. Start by soldering the SMD components.
IMPORTANT: Make sure to place the diodes in the correct orientation, the line on the diode has to be on the same side as on the marking on the PCB (on the left side).

Importantly, the button should be soldered before soldering the microcontroller, otherwise it will be hard to do so. Additionally, you are probably more focused at this point, thus making it a bit easier to deal with the small components and you will be glad to move on to the switches and controller after getting the "hard" part out of the way.

If you have never soldered SMD components before, you should probably look at a tutorial first, so do that and then come back to this guide.  
Personally, I found that putting some solder on one pad, then using tweezers to hold the diode in the right place with one hand while using the soldering iron in the other to remelt the solder to secure that side and then soldering the other pad, to be very effective.  
Just make sure not to accidentally get solder under the diode which might create a short and you should be fine. It doesn't have to look perfect, no one will see it under the back plate anyways.  
You can use the same technique for the button, it just has two more legs to solder in the end and that you have to line up correctly in the beginning.


## 3. Solder the microcontroller and the switches
IMPORTANT: Make sure to place the controller in the correct orientation, so that it is on the top side of the keyboard (the side with the dragonwings lettering) but with its components facing down and the USB port away from the lettering.

While it does not matter in which order you solder these, you might not want to put too much strain on the controller by heating it up too much soldering all the pins at once, so it makes sense to start with the controller, taking some breaks to let it cool down a bit and soldering some switches in the meantime.  
The easiest way to do this is probably to push all switches in before starting to solder them as the board will then lie flat on a surface. I also found it easiest to solder the legs to the controller separately and then solder that to the PCB. Though as the switches are taller than the controller, you will have to put something below it (use something that can take some heat) to keep it in place at least until you have soldered some pins.



## 4. Screw the standoffs to the top PCB

## 5. Glue in the hex nut
Place the backplate on an even surface with the inner side (without the dragonwings lettering) facing up.  
Push the hex nut all the way in so that it touches the surface and is thus flush with the outside of the PCB.  
Put some hot glue around the nut to secure it in place, then cover all the still exposed parts while making sure not to fill up the threaded part. Do not use too much hot glue as you might otherwise have problems fitting this part between the plates and also in between the microcontrollers legs. Although it is also possible to use a lot of glue and then cut the excess with a sharp knife (be careful not to cut yourself in the process though). You probably want to check the fit several times during this, which is why the standoffs should be attached in step 4.

## 6. Screw the plates together

## 7. Push the rubber feet into the holes in the back plate

## 8. Put the keycaps on the switches

## Congratulations! You are now done with the assembly of the keyboard!
