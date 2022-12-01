

```
I think this will also work...You can use the \n to do a new line so that it is not one long string...
    {action_respond_info("Print_Start Macro Inputs:\n"
                         "BED = %d\n" 
                         "EXTRUDER = %d\n" 
                         "CHAMBER = %d\n"
                         "FL_SIZE == %s\n"
                         "material = %s\n"
                         "Z_Adjust = %.3f\n" 
                         "nozzle = %.2f"\n
                         "filament_name = %s\n" % 
                         (BED, EXTRUDER, CHAMBER, FL_SIZE, material, z_adjust, nozzle, filament_name))}
```


## General

- https://docs.vorondesign.com/community/howto/Takuya/Klicky_Probe_AutoZ_Alternative.html

- CANBUS WHEN CW2
    - GOOD https://github.com/cruiten/Voron-Related/tree/main/CANbus/Documentation/Umbilical
    - https://github.com/Alexander-T-Moss/Voron-Stuff/tree/main/Mods/%23%20SB2040%20Cooling/STLs
    - https://github.com/allenrowand/voron_mods/tree/main/v2.4
    - https://www.printables.com/model/279739-voron-can-bus-z-chain-move
    - https://github.com/maz0r/klipper_canbus/blob/main/controller/monster8v2.md
    - https://github.com/maz0r/klipper_canbus/blob/main/toolhead/ebb36-42_v1.1.md
    - https://www.teamfdm.com/forums/topic/672-how-to-use-can-toolhead-boards-connected-directly-to-octopus-octopus-pro-on-canboot/
    - https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/LoCoCNC/Strain_Relief_w_Microfit
    - https://github.com/MotorDynamicsLab/LDOVoron2/blob/main/STLs/beefy_raspberry_bracket.stl
    - https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/Electronics_Bay/pcb_din_clip_x3.stl
    - https://github.com/MotorDynamicsLab/LDOVoron2/blob/main/STLs/toolhead_breakout_pcb_bracket.stl
    - https://www.teamfdm.com/files/file/601-bowden-tube-guide/
    - https://github.com/KayosMaker/CANboard_Mounts
    - https://github.com/majarspeed/Misc-Voron/tree/main/StealthBurner%20Umbilical%20cover
    - https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Minsekt/Rear_Umbilical
    - https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/CW2_SB2040_CAN_Umbilical
    - canbus and SB/CWw2 stuff https://github.com/kejar31/VoronMods/tree/main/CB-C2
        - need a fan https://dfh.fm/products/sunon-mf20100v1-1000u-a99-2010-axial-fan?_pos=1&_sid=d08833795&_ss=r
    - Rear cable mount
        - https://github.com/hartk1213/MISC/blob/main/Voron%20Mods/Archived/Voron2.4_umbilical_strain_relief(OLD)/STL/A_Drive/%5Ba%5D_pigtail_cable_cover.stl
        - https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/CW2_SB2040_CAN_Umbilical/STLs
- Macro ideas
    - https://github.com/zellneralex/klipper_config/tree/master
- ~~FINISH ELLIS TUNING~~
- ~~Mainsail timelapse~~
    - ~~https://www.youtube.com/watch?v=n-BVPidUDLI ~~
    - ~~add to super slicer~~
    - ~~Printer Settings -> Custom G-code -> Before layer change Gcode -> TIMELAPSE_TAKE_FRAME~~
- KlipperScreen?
    - https://klipperscreen.readthedocs.io/en/latest/
- Filament sensor
    - https://www.amazon.com/dp/B07Z97582P/?coliid=I278JGHS5OD8M7&colid=3T6GGJW7T3YSG&psc=1&ref_=lv_ov_lig_dp_it
    - https://www.printables.com/en/model/231626-bigtreetech-smart-filament-sensor-sfs-bracket-for-/files
    - https://www.teamfdm.com/files/file/417-exhaust-cover-sfs/
- Nice screen, what mods to mount it?
    - https://www.amazon.com/BIGTREETECH-Screen-Display-800x480-Raspberry/dp/B08FD2YZ23/ref=sr_1_3?crid=10KRTBYWNXMOD&keywords=tft50&qid=1667860109&sprefix=tft50%2Caps%2C67&sr=8-3&ufe=app_do%3Aamzn1.fos.18ed3cb5-28d5-4975-8bc7-93deae8f9840
    - cheaper still! https://www.aliexpress.us/item/3256801084054417.html
    - Find the case with the cutout on the bottom for brightness
    - https://www.teamfdm.com/files/file/31-btt-pitft50-v2-mount/
- ~~C920 webcam~~
  - ~~https://www.teamfdm.com/files/file/275-c920-mount/~~
  - ~~Mount under z rail https://media.discordapp.net/attachments/710952853514223617/1031599846202822697/20221016_174843.jpg~~



## TO PRINT
- clips?
    - https://github.com/v6cl/My-Voron2.4-Customs/blob/main/InteriorStuff/Panel_Locker/v2_Thin%20Locker/Thin_Locker_5.5mm.stl
- nozzle holding skirt
  - https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/README.md

## TO BUILD

# Parts URLs
- https://kb-3d.com/store/inserts-fasteners-adhesives/288-5x10x1mm-shim-ring-washer-pack-of-50-din988-1634423113147.html
- Extrusion nuts
    - https://www.dold-mechatronik.de/Standard-connector-20-I-type-groove-5-incl-Mounting-kit
- Build plates
    - https://www.filamentone.com/products/ultistik-premium-powder-coated-ultem-pei-build-plate-355-x-355-voron-sovol-sv03
- Brushes
    - https://www.aliexpress.us/item/2251832866802617.html?spm=2114.12010615.8148356.2.315e106dfzI86U&gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US
    - https://www.amazon.com/uxcell%C2%AE-Length-Plastic-Handle-Bristle/dp/B00X9HY5D4
    - https://www.amazon.com/gp/product/B092HWQG69/
- Tubing
    - https://west3d.com/products/capricornus-ptfe-tube-1-9mm-teflonto
    - https://west3d.com/products/bowden-ptfe-tube-4mm-od-2-5mm-id
- Igus cables direct
    - https://www.igus.com/product?artNr=CF10-05-04
- HiWin rails
    - https://magicphoenix.xyz/product/hiwin-mgn12h-rail-z1pm/
    - https://magicphoenix.xyz/product/magicphoenix-mgn9h-rail440c-sus/?cgkit_search_word=mgn9
- Other rails
    - https://west3d.com/products/west3d-printing-mgn12h-1r-300-350-400-linear-rails-with-carriages?variant=42096413376724
    - fabreeko HBs
- Good fans
    - https://www.digikey.com/en/products/detail/orion-fans/OD4010-24HB01A/2621114
