# OSSM v2.x Board AIO Motor Head Mod
![](Images/Renders/Primary.png)

## Summary    
This is a modification for the Default OSSM Body Motor Head that houses the v2.x Reference Board as part of the Motor Head.  
This turns the OSSM electronics into a self-contained unit; Just add power and a remote.  
This replaces the Middle and Cover of a Default setup, with an ***optional*** matching Bottom.  


To be used in a [PitClamp Mini](https://github.com/armpitMFG/PitClamp-Mini) setup.

**I'm considering this an experimental print.**  
The JST-PH 4 pin header will be in close proximity to the motor pulley. 
I believe I have included enough clearance for a comfortable margin of safety if you remove slack from your cables.  
If this makes you nervous, wait for a fully contained remix that may never come.   

### Capacitor size support  
### Choose a cover based on what size capacitor you have
- Cover - Default
  - Up to 12mm diameter
- Cover - Extra Clearance
  - Up to 18mm diameter

 ### Requires a motor ring with cable passthru:  
- [PitClamp Mini - Ring - 57AIM - Default - 5mm Offset.stl](https://github.com/armpitMFG/PitClamp-Mini/blob/main/Files/Rings/PitClamp%20Mini%20-%20Ring%20-%2057AIM%20-%20Default%20-%205mm%20Offset.stl) ([.STEP](https://github.com/armpitMFG/PitClamp-Mini/blob/main/Files/Rings/STEP/PitClamp%20Mini%20-%20Ring%20-%2057AIM%20-%20Default%20-%205mm%20Offset.step))   

### [Print Files](Files/)  


### Bill Of Materials
    4x M3x10 (12 max)
    2x M3x15 (20 max)
    4x M3 Nuts
    Plus standard hardware for:
      OSSM Body
      PitClamp Mini Ring

### Assembly

Route the cable through the PitClamp Motor Ring Passthru, slide motor into place.  
Attach Middle to Base through Motor Ring like a normal assembly.  
Route JST-PH 4 pin through wire access hole, then power cables.  
Attach wires to Reference Board v2.x and put the board in place.  
Do cable routing to reduce slack, pinch points, etc.  
Secure the board using 2x M3x10.    
Attach your chosen Cover and secure using 2x M3x10 and 2x M3x15 with nuts in slots.  

### Updates
  - 09.14.2024 - v1.0 Release

![](Images/AIO_Holding.jpg)
![](Images/Renders/Secondary.png)

## Printing

**Recommend using preconfigured 3mf file - [OSSM - Body - 2.x AIO.3mf](Files/OSSM%20-%20Body%20-%202.x%20AIO.3mf)**

    0.2mm layer height
    Standard strength (5 wall) profile
    15% gyroid or crosshatch infill
    Tree/organic Supports ~4deg overhang setting
  
Supports required for:
  - OSSM - Body - 2.x AIO - Cover (any)
  - OSSM - Body - 2.x AIO - Middle

It's a lot of support, but it's a small part.  
Possibly can optimize some of this out in a future rev.  

I recommend using a raft on "OSSM - Body - 2.x AIO - Cover", this will help with support removal as well.

![](Images/Print/Print.png)  
