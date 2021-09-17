This guide goes through all the steps of building Ivan Miranda's 3d-printed CNC machine and is a complement to Ivan's Youtube-videos:

1. Original video: [https://www.youtube.com/watch?v=_atw3e0nIrg](https://www.youtube.com/watch?v=_atw3e0nIrg)
2. Updates with geared stepper motors etc: [https://www.youtube.com/watch?v=qpjf5D3WngY](https://www.youtube.com/watch?v=qpjf5D3WngY)
3. Updating to metal parts: [https://www.youtube.com/watch?v=RDnGvhdGFEY](https://www.youtube.com/watch?v=RDnGvhdGFEY)

It follows the first and second video quite strict, while only using the added vertical beams from the third video.

# Table of content
.....

# License
The following license is included when buying Ivan Miranda's blueprints of the CNC machine:

```
Everything that is in these files that I produced myself, apart from reselling the files, is allowed.
You can print and sell parts, sell machines, sell courses to build the machine. Modify the parts and post 
them for free, as long as you don’t sell the files and keep this license on everything you make with the 
files and credit me, we’re good. No DRM or anything, you are even allowed to repost the files as long as 
they’re kept free. Why buy this then? To support me and keep me encouraged to do more projects like this. 
```

Ivan does an amazing job putting these DIY builds together. I've posted his STL-files in this repository to simplify the build, but PLEASE buy his blueprints here: [https://ivanmiranda.com/products/3d-printed-cnc](https://ivanmiranda.com/products/3d-printed-cnc). It's only $25 and helps him to continue build and share his awesome projects.

# Parts (bill of materials)
The following chapter goes through all the parts needed to build the CNC machine. There are two sub-sections:

* `3d-printed parts` - All parts that you need to 3d-print
* `Other parts` - All the parts that you need to buy

Each table includes:

* `Item no.` - Item number used to identify the part later in the guide
* `Type` - Name of the part
* `Amount` - Number of units needed
* `Image` - Image of the part
* `(STL link)` - Link to the stl-file if there is any
* `Used for` - Where it's used in the CNC machine

## 3d-printed parts
All the parts below needs to be 3d-printed. The tables include links to the STL-files.

### Left side plates

| Item no. | Type                             | Amount | Image                                                                                            | STL link                                                                                                | Used for          |
|----------|----------------------------------|--------|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------|
| SP_001   | Left side plate                  | 1      | ![left_plate](./images/3dprinted_parts/side_plates/left/left_plate.jpg)                                           | [LEFT\_PLATE.stl](./stl_files/side_plates/left/LEFT_PLATE.stl)                                          | Lock bridge beams |
| SP_002   | Left side plate upper front clip | 1      | ![left_plate_upper_front_clip](./images/3dprinted_parts/side_plates/left/left_plate_upper_front_clip.jpg)         | [LEFT\_PLATE\_UPPER\_FRONT\_CLIP.stl](./stl_files/side_plates/left/LEFT_PLATE_UPPER_FRONT_CLIP.stl)     | Lock bridge beams |
| SP_003   | Left side plate lower front clip | 1      | ![left_plate_lower_front_clip](./images/3dprinted_parts/side_plates/left/left_plate_lower_front_clip.jpg)         | [LEFT\_PLATE\_LOWER\_FRONT\_CLIP.stl](./stl_files/side_plates/left/LEFT\_PLATE\_LOWER\_FRONT\_CLIP.stl) | Lock bridge beams |
| SP_004   | Left side plate back clip        | 1      | ![left_plate_back_plate_back_clip](./images/3dprinted_parts/side_plates/left/left_plate_back_plate_back_clip.jpg) | [LEFT\_PLATE\_BACK\_CLIP.stl](./stl_files/side_plates/left/LEFT_PLATE_BACK_CLIP.stl)                    | Lock bridge beams |

### Right side plate

| Item no. | Type                              | Amount | Image                                                                                      | STL link                                                                                               | Used for          |
|----------|-----------------------------------|--------|--------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------|
| RP_001   | Right side plate                  | 1      | ![right_plate](./images/3dprinted_parts/side_plates/right/right_plate.jpg)                                   | [RIGHT\_PLATE.stl](./stl_files/side_plates/right/RIGHT_PLATE.stl)                                      | Lock bridge beams |
| RP_002   | Right side plate upper front clip | 1      | ![right_plate_upper_front_clip](./images/3dprinted_parts/side_plates/right/right_plate_upper_front_clip.jpg) | [RIGHT\_PLATE\_UPPER\_FRONT\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_UPPER_FRONT_CLIP.stl) | Lock bridge beams |
| RP_003   | Right side plate lower front clip | 1      | ![right_plate_lower_front_clip](./images/3dprinted_parts/side_plates/right/right_plate_lower_front_clip.jpg) | [RIGHT\_PLATE\_LOWER\_FRONT\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_LOWER_FRONT_CLIP.stl) | Lock bridge beams |
| RP_004   | Right plate back clip.jpg         | 1      | ![right_plate_back_plate_back_clip](./images/3dprinted_parts/side_plates/right/right_plate_back_clip.jpg)    | [RIGHT\_PLATE\_BACK\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_BACK_CLIP.stl)                | Lock bridge beams |

### Router

| Item no. | Type             | Amount | Image                                                              | STL link                                                          | Used for                    |
|----------|------------------|--------|--------------------------------------------------------------------|-------------------------------------------------------------------|-----------------------------|
| RO_001   | Carriage         | 1      | ![carriage](./images/3dprinted_parts/router/carriage.jpg)                 | [CARRIAGE.stl](./stl_files/router/CARRIAGE.stl)                   | Lock router in place        |
| RO_002   | Router bracket   | 1      | ![router_bracket](./images/3dprinted_parts/router/router_bracket.jpg)     | [ROUTER\_BRACKET.stl](./stl_files/router/ROUTER_BRACKET.stl)      | Lock router in place        |
| RO_003   | Vaccum funnel    | 1      | ![vaccum_funnel](./images/3dprinted_parts/router/vaccum_funnel.jpg)       | [VACUUM\_FUNNEL.stl](./stl_files/router/VACUUM_FUNNEL.stl)        | Lock vaccum close to router |
| RO_004   | Vertical slider  | 1      | ![vertical_slider](./images/3dprinted_parts/router/vertical_slider.jpg)   | [VERTICAL\_SLIDER.stl](./stl_files/router/VERTICAL\_SLIDER.stl)   | Vertical slider for router  |
| RO_005   | Z motor mount    | 1      | ![z_motor_mount](./images/3dprinted_parts/router/z_motor_mount.jpg)       | [Z\_MOTOR\_MOUNT.stl](./stl_files/router/Z_MOTOR_MOUNT.stl)       | Mount z motor to carriage   |
| RO_006   | Vaccum hose ring | 1      | ![vaccum_hose_ring](./images/3dprinted_parts/router/vaccum_hose_ring.jpg) | [VACUUM\_HOSE\_RING.stl](./stl_files/router/VACUUM_HOSE_RING.stl) | Lock vaccum to carriage     |

### Belt tensioners

| Item no. | Type                    | Amount | Image                                                                                                        | STL link                                                                                                       | Used for               |
|----------|-------------------------|--------|--------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|------------------------|
| BT_001   | Y axis left back clip   | 1      | ![y_axis_left_back_clip](./images/3dprinted_parts/belt_tensioner/y_axis_left/y_axis_left_back_clip.jpg)      | [Y\_AXIS\_LEFT\_BACK\_CLIP.stl](./stl_files/belt_tensioner/y_axis_left/Y_AXIS_LEFT_BACK_CLIP.stl)              | Lock left y-axis belt  |
| BT_002   | Y axisleft front clip   | 1      | ![y_axis_left_front_clip](./images/3dprinted_parts/belt_tensioner/y_axis_left/y_axis_left_front_clip.jpg)    | [Y\_AXIS\_LEFT\_FRONT\_CLIP.stl](./stl_files/belt_tensioner/y_axis_left/Y_AXIS_LEFT_FRONT_CLIP.stl)            | Lock left y-axis belt  |
| BT_003   | Y axis left tensioner   | 1      | ![y_axis_left_tensioner](./images/3dprinted_parts/belt_tensioner/y_axis_left/y_axis_left_tensioner.jpg)      | [Y\_AXIS\_LEFT\_BELT\_TENSIONER.stl](./stl_files/belt_tensioner/y_axis_left/Y_AXIS_LEFT_BELT_TENSIONER.stl)    | Lock left y-axis belt  |
| BT_004   | Y axis right back clip  | 1      | ![y_axis_right_back_clip](./images/3dprinted_parts/belt_tensioner/y_axis_right/y_axis_right_back_clip.jpg)   | [Y\_AXIS\_RIGHT\_BACK\_CLIP.stl](./stl_files/belt_tensioner/y_axis_right/Y_AXIS_RIGHT_BACK_CLIP.stl)           | Lock right y-axis belt |
| BT_005   | Y axis right front clip | 1      | ![y_axis_right_front_clip](./images/3dprinted_parts/belt_tensioner/y_axis_right/y_axis_right_front_clip.jpg) | [Y\_AXIS\_RIGHT\_FRONT\_CLIP.stl](./stl_files/belt_tensioner/y_axis_right/Y_AXIS_RIGHT_FRONT_CLIP.stl)         | Lock right y-axis belt |
| BT_006   | Y axis right tensioner  | 1      | ![y_axis_right_tensioner](./images/3dprinted_parts/belt_tensioner/y_axis_right/y_axis_right_tensioner.jpg)   | [Y\_AXIS\_RIGHT\_BELT\_TENSIONER.stl](./stl_files/belt_tensioner/y_axis_right/Y_AXIS_RIGHT_BELT_TENSIONER.stl) | Lock right y-axis belt |
| BT_007   | X axis back clip        | 1      | ![x_axis_back_clip](./images/3dprinted_parts/belt_tensioner/x_axis/x_axis_back_clip.jpg)                     | [Y\_AXIS\_X\_AXIS\_BACK\_CLIP.stl](./stl_files/belt_tensioner/x_axis/X_AXIS_BACK_CLIP.stl)                     | Lock x-axis belt       |
| BT_008   | X axis front clip       | 1      | ![x_axis_front_clip](./images/3dprinted_parts/belt_tensioner/x_axis/x_axis_front_clip.jpg)                   | [Y\_AXIS\_X\_AXIS\_FRONT\_CLIP.stl](./stl_files/belt_tensioner/x_axis/X_AXIS_FRONT_CLIP.stl)                   | Lock x-axis belt       |

## Other parts
All the parts below needs to be bought or cut out.

### Nuts

| Type    | Amount | Image                                  | Used for                               |
|---------|--------|----------------------------------------|----------------------------------------|
| M3 nuts | X      | ![m3_nuts](./images/parts/nuts_M3.jpg) | X                                      |
| M6 nuts | X      | ![m6_nuts](./images/parts/nuts_M6.jpg) | X                                      |
| M8 nuts | X      | ![m8_nuts](./images/parts/nuts_M8.jpg) | X                                      |

### Screws

| Type     | Amount | Image                                                 | Used for                               |
|----------|--------|-------------------------------------------------------|----------------------------------------|
| M3 10 mm | X      | ![m3_10_mm_screws](./images/parts/screw_M3_10_mm.jpg) | X                                      |
| M3 16 mm | X      | ![m3_16_mm_screws](./images/parts/screw_M3_16_mm.jpg) | X                                      |
| M3 20 mm | X      | ![m3_20_mm_screws](./images/parts/screw_M3_20_mm.jpg) | X                                      |
| M3 25 mm | X      | ![m3_25_mm_screws](./images/parts/screw_M3_25_mm.jpg) | X                                      |
| M5 20 mm | X      | ![m5_20_mm_screws](./images/parts/screw_M5_20_mm.jpg) | X                                      |
| M5 30 mm | X      | ![m5_30_mm_screws](./images/parts/screw_M5_30_mm.jpg) | X                                      |
| M5 60 mm | X      | ![m5_60_mm_screws](./images/parts/screw_M5_60_mm.jpg) | X                                      |
| M6 70 mm | X      | ![m6_70_mm_screws](./images/parts/screw_M6_70_mm.jpg) | X                                      |
| M8 80 mm | X      | ![m8_80_mm_screws](./images/parts/screw_M8_80_mm.jpg) | X                                      |

### Washers

| Type            | Amount | Image                                                                    | Used for                               |
|-----------------|--------|--------------------------------------------------------------------------|----------------------------------------|
| M3              | X      | ![m3_washers](./images/parts/washers_M3.jpg)                             | X                                      |
| 10mm, 20mm, 2mm | X      | ![10_mm_20_mm_2_mm_washers](./images/parts/washers_10_mm_20_mm_2_mm.jpg) | X                                      |

### Beams
All beams where cut out from 30mm x 30 mm (2 mm thick) aluminium profiles using a miter saw.

| Type              | Amount | Image                                                                  | Used for                               |
|-------------------|--------|------------------------------------------------------------------------|----------------------------------------|
| Vertical 80 mm    | 8      | ![beams_vertical_80_mm](./images/parts/beams_vertical_80_mm.jpg)       | X                                      |
| Front/Back 677 mm | 4      | ![beams_front_back_677_mm](./images/parts/beams_front_back_677_mm.jpg) | X                                      |
| Right/Left 900 mm | 4      | ![beams_right_left_900_mm](./images/parts/beams_right_left_900_mm.jpg) | X                                      |
| Bridge 803 mm     | 3      | ![beams_bridge_803_mm](./images/parts/beams_bridge_803_mm.jpg)         | X                                      |

### Threaded rods

| Type      | Amount | Image                                                                | Used for                               |
|-----------|--------|----------------------------------------------------------------------|----------------------------------------|
| M5 140 mm | 2      | ![M5_140_mm_threaded_rod](./images/parts/threaded_rod_M5_140_mm.jpg) | Keep bridge beams together             |
| M8 12 mm  | 8      | ![M8_120_mm_threaded_rod](./images/parts/threaded_rod_M8_120_mm.jpg) | Keep upper and lower frames together   |
| M8 717 mm | 4      | ![M8_717_mm_threaded_rod](./images/parts/threaded_rod_M8_717_mm.jpg) | Keep frames together                   |

### Others

| Item no. | Type                             | Amount | Image                                                          | Used for                   |
|----------|----------------------------------|--------|----------------------------------------------------------------|----------------------------|
| OT_001   | NEMA17 1:19 geared stepper motor | 3      | ![NEMA17_geared](./images/parts/NEMA17_geared.jpg)             | Move X & Y axis            |
| OT_002   | NEMA17 stepper motor             | 1      | ![NEMA17_no_gears](./images/parts/NEMA17_no_gears.jpg)         | Move Z axis                |
| OT_003   | HTD5M 4 meter belt               | 1      | ![HTD5M_belt](./images/parts/HTD5M_belt.jpg)                   | Belt to move X & Y axis    |
| OT_004   | HTD5M 12 teeth pulley            | 3      | ![HTD5M_pulley](./images/parts/HTD5M_pulley.jpg)               | Pulleys to move X & Y axis |
| OT_005   | 2GT belt 300 mmm                 | 1      | ![2GT_belt_300_mm](./images/parts/2GT_belt_300_mm.jpg)         | Belt to move Z axis        |
| OT_006   | 2GT 16 teeth pulley              | 1      | ![2GT_pulley_16_teeth](./images/parts/2GT_pulley_16_teeth.jpg) | Pulley to move Z axis      |
| OT_007   | 2GT 60 teeth pulley              | 1      | ![2GT_pulley_60_teeth](./images/parts/2GT_pulley_60_teeth.jpg) | Pulley to move Z axis      |
| OT_008   | Acme threaded rod 300 mm (8x8mm) | 1      | ![acme_threaded_rod](./images/parts/acme_threaded_rod.jpg)     | To move Z axis             |
| OT_009   | Acme threaded rod nut            | 1      | ![acme_nut](./images/parts/acme_nut.jpg)                       | To move Z axis             |
| OT_010   | KFL08 rod bearing                | 2      | ![KFL08_rod_bearing](./images/parts/KFL08_rod_bearing.jpg)     | To move Z axis             |
| OT_011   | MGN12H rail 600 mm               | 4      | ![MGN12H_rail_600_mm](./images/parts/MGN12H_rail_600_mm.jpg)   | To move X & Y axis         |
| OT_012   | MGN12H rail 200 mm               | 2      | ![MGN12H_rail_200_mm](./images/parts/MGN12H_rail_200_mm.jpg)   | To move Z axis             |
| OT_013   | MGN12H block                     | 12     | ![MGN12H_rail_block](./images/parts/MGN12H_rail_block.jpg)     | To move all axis           |
| OT_014   | Cable chain 1 meter              | 2      | ![cable_chain_1000_mm](./images/parts/cable_chain_1000_mm.jpg) | Encapsulate cables         |
| OT_015   | 698zz bearing                    | 18     | ![698zz_bearing](./images/parts/698zz_bearing.jpg)             | Ilders for HTD5M belt      |

# Build the CNC machine
This section covers how all the parts is put together to build the CNC machine. 

All the measurements, distances etc can be found in the main project Fusion 360 CAD design that is included when buying Ivan's blueprints. The blueprints can be bought here for just \$25: [https://ivanmiranda.com/products/3d-printed-cnc](https://ivanmiranda.com/products/3d-printed-cnc)

## Main frame

### Cut out holes in the 900 mm profiles
The main frame consists of two separate frames, the lower and the upper frame. The two frames are kept together using threaded rods, washers and nuts. To enable the threaded rods to slide through the aluminium profiles, holes needed to be drilled.

First, a sharpie was used to indicate where all the holes were going. This was done by using a set square and a penn. A bradawl and a hammer were then used to make indentations at the center of the holes.

![holes_main_frame_1](./images/build/frame/holes_main_frame_1.jpg)

A 9 mm drill-bit and a bench drill was used to drill the holes straight through the profiles.

![holes_main_frame_1](./images/build/frame/holes_main_frame_2.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_3.jpg)

To be able to access the nuts and tight them with a socket wrench, some holes (facing outwards) needed to be enlarged. A sharpie was used to mark all the holes that needed to be enlarged.

![holes_main_frame_1](./images/build/frame/holes_main_frame_4.jpg)

A step drill was then used to enlarge the holes holes to 20 mm. A tip is to measure the size of your socket wrench and keep the holes as small as possible, while you're still able to tighten the nuts. To be able to see which step you're aiming for on the step drill, attach a small piece of masking tape on the step above.

![holes_main_frame_1](./images/build/frame/holes_main_frame_5.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_6.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_7.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_8.jpg)

The edges were finally smoothed out using a round metal file.

![holes_main_frame_1](./images/build/frame/holes_main_frame_9.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_10.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_11.jpg)

### Rails to 900 mm profiles

Before the upper and lower frames were assembled, two 600 mm MGN12H rails were attached to the 900 mm aluminium profiles of the **upper** frame. They were attached to the sides facing outwards and above the three 80 mm vertical beams (connecting the lower and upper frame). A tip is to place all the profiles as they should go to make sure that you're attaching the rails to the correct faces (see the red boxes on the image below). Also, be very careful when removing the MGN12H blocks from the rails.

![attach_rails_to_beams_2](./images/build/frame/attach_rails_to_beams_2.jpg)

![rails_main_frame_1](./images/build/frame/rails_main_frame_1.jpg)

![rails_main_frame_0](./images/build/frame/rails_main_frame_0.jpg)

Three 3d-printed support tools were used to center the rails on the profiles. A 57 mm wood block were cut out and used to attach the rails at the same distance from the end of the profiles. The rails were then clamped to the profiles.

![rails_main_frame_2](./images/build/frame/rails_main_frame_2.jpg)

![rails_main_frame_3](./images/build/frame/rails_main_frame_3.jpg)

![rails_main_frame_4](./images/build/frame/rails_main_frame_4.jpg)

![rails_main_frame_5](./images/build/frame/rails_main_frame_5.jpg)

A bradawl and a hammer were then used to make indentations at the center of the holes. Cutting fluid were applied and a 2 mm drill was used to drill all the holes.

![rails_main_frame_6](./images/build/frame/rails_main_frame_6.jpg)

![rails_main_frame_7](./images/build/frame/rails_main_frame_7.jpg)

![rails_main_frame_8](./images/build/frame/rails_main_frame_8.jpg)

![rails_main_frame_9](./images/build/frame/rails_main_frame_9.jpg)

![rails_main_frame_10](./images/build/frame/rails_main_frame_10.jpg)

![rails_main_frame_11](./images/build/frame/rails_main_frame_11.jpg)

Cutting fluid was then applied once more on the drilled holes and a M3 drill tap was used to create threads in the holes.

![rails_main_frame_12](./images/build/frame/rails_main_frame_12.jpg)

![rails_main_frame_13](./images/build/frame/rails_main_frame_13.jpg)

Finally, the rails were attached using 20 mm M3 screws.

![rails_main_frame_14](./images/build/frame/rails_main_frame_14.jpg)

![rails_main_frame_15](./images/build/frame/rails_main_frame_15.jpg)

![rails_main_frame_16](./images/build/frame/rails_main_frame_16.jpg)

![rails_main_frame_17](./images/build/frame/rails_main_frame_17.jpg)

### Assemble upper and lower frames

The two frames were assembled using the longer 717 mm M8 threaded rods, (10mm, 20mm, 2mm) washers and M8 lock nuts.

The profiles were first placed in their correct place and clamps were used to keep the profiles aligned. I used two jointed spanners (one one each side) to lock everything in place, but you can also use two socket wrenches. Just make sure that the bits fit into the drilled holes.

![assemble_frames_1](./images/build/frame/assemble_frames_1.jpg)

![assemble_frames_3](./images/build/frame/assemble_frames_3.jpg)

![assemble_frames_2](./images/build/frame/assemble_frames_2.jpg)

![assemble_frames_4](./images/build/frame/assemble_frames_4.jpg)

![assemble_frames_5](./images/build/frame/assemble_frames_5.jpg)

![assemble_frames_6](./images/build/frame/assemble_frames_6.jpg)

![assemble_frames_7](./images/build/frame/assemble_frames_7.jpg)

### Interlock upper and lower frames

The upper and lower frames and the 80 mm vertical aluminium beams were first layed out in their correct place. The 803 mm horizontal bridge beams and clamps were then used to align the frames on top of each other.

![assemble_frames_9](./images/build/frame/assemble_frames_9.jpg)

![assemble_frames_10](./images/build/frame/assemble_frames_10.jpg)

The 120 mm M8 threaded rods, (10mm, 20mm, 2mm) washers and M8 lock nuts were then used to interlock the upper and lower frames, with the 80 mm vertical aluminium profiles in between.

![assemble_frames_8](./images/build/frame/assemble_frames_8.jpg)

![assemble_frames_12](./images/build/frame/assemble_frames_12.jpg)

![assemble_frames_11](./images/build/frame/assemble_frames_11.jpg)

![assemble_frames_13](./images/build/frame/assemble_frames_13.jpg)

### Side plates to upper frame

Before attaching the side plates, the MGN12H blocks were added back onto the rails, two on each side. Be careful when sliding them onto the rails, there are multiple small bearing balls that easily fall out of the blocks.

The left and right side plates where then attached to the blocks using 20 mm M3 screws. Make sure to attach the plates on the correct side (see images below).

![assemble_side_plates_1](./images/build/frame/assemble_side_plates_1.jpg)

![assemble_side_plates_2](./images/build/frame/assemble_side_plates_2.jpg)

I had to redesign the left side plate and reprint it later in the build (after the images were taken). Therefore, the left side plate seen in the upcoming images look a bit different than the one used (see next image for the left side plate used).

![assemble_side_plates_3](./images/build/frame/assemble_side_plates_3.jpg)

![assemble_side_plates_4](./images/build/frame/assemble_side_plates_4.jpg)

![assemble_side_plates_5](./images/build/frame/assemble_side_plates_5.jpg)

![assemble_side_plates_6](./images/build/frame/assemble_side_plates_6.jpg)

![assemble_side_plates_7](./images/build/frame/assemble_side_plates_7.jpg)

![assemble_side_plates_8](./images/build/frame/assemble_side_plates_8.jpg)

### Y-axis motors, idlers and pulleys to side plates

Each idler were made up out of one 60 mm fully threaded M8 screw, 3 698zz bearings and 4 (10 mm x 8 mm x 2 mm) washers (1 closest to the idler blocker and 3 closest to the side plate). Two idlers were then attached to each side plate using two M8 nuts. Make sure that the bearings are spinning freely.

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_1.jpg)

![attach_side_plate_motors_2](./images/build/frame/attach_side_plate_motors_2.jpg)

As I designed and added the idler blocker later on in the build, some of the images doesn't have it and they also have 3 washers instead of 1 washer closest to the screw head. I left these images anyways in the guide so you can see how it looks when you attach the idlers, but please ignore the wrong number of washers. Also ignore all the other things around the idlers in the upcoming 2 images, they are taken later on in the build.

![attach_side_plate_motors_3_0](./images/build/frame/attach_side_plate_motors_3_0.jpg)

![attach_side_plate_motors_3_1](./images/build/frame/attach_side_plate_motors_3_1.jpg)

Should be idler blockers and a different number of washers in the upcoming images.

![attach_side_plate_motors_3](./images/build/frame/attach_side_plate_motors_3.jpg)

![attach_side_plate_motors_4](./images/build/frame/attach_side_plate_motors_4.jpg)

![attach_side_plate_motors_5](./images/build/frame/attach_side_plate_motors_5.jpg)

![attach_side_plate_motors_6](./images/build/frame/attach_side_plate_motors_6.jpg)

![attach_side_plate_motors_7](./images/build/frame/attach_side_plate_motors_7.jpg)

To attach the stepper motors to the side plates, the 4 M3 screws locking the gear box to the motor were removed. Save these as they will be used later on to attach the power supply and Arduino.

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_8.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_9.jpg)

The stepper motors were then inserted into the large holes on the side plates, facing inwards. 4 40 mm M3 screws and 4 M3 washers were used to lock each stepper motor to the side plates (I forgot to add the washers in the images below, therefore they're not visible). The motors should be attached so that the cables are facing in the direction of the two bridge beams (i.e. the longer vertical surface of the side plates).

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_10.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_11.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_12.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_13.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_14.jpg)

The HTD5M timing pulleys were attached to the motor shaft using set screws.

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_15.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_16.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_17.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_18.jpg)

### Y-axis belt tensioners and end-stop mounts

Fixed belt tensioners were attached to the longer aluminium profiles of the upper frame using M5 screws. When aligning the fixed belt tensioners, make sure that the "belt opening" is pointing in the direction of the rails (one fixed belt tensioner for each rail). Similar to before, a bradawl and a hammer were used to make indentations at the center of the holes. Cutting fluid were applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap.

![attach_tensioners_and_belts_12](./images/build/frame/attach_tensioners_and_belts_12.jpg)

![attach_tensioners_and_belts_13](./images/build/frame/attach_tensioners_and_belts_13.jpg)

![attach_tensioners_and_belts_14](./images/build/frame/attach_tensioners_and_belts_14.jpg)

![attach_tensioners_and_belts_15](./images/build/frame/attach_tensioners_and_belts_15.jpg)

![attach_tensioners_and_belts_16](./images/build/frame/attach_tensioners_and_belts_16.jpg)

![attach_tensioners_and_belts_17](./images/build/frame/attach_tensioners_and_belts_17.jpg)

![attach_tensioners_and_belts_18](./images/build/frame/attach_tensioners_and_belts_18.jpg)

The belt tension sliders were attached on the opposite side of the fixed belt tensioners, ontop of the aluminium profile. To get them aligned at the exact same place on both sides, a 100 mm distance was cut out and a flat support was clamped to the inner side of the profile. The same drill and tap size were used as for the fixed belt tensioners (4mm drill, M5 drill tap). Make sure that the belt tension sliders are pointing outwards.

![attach_tensioners_and_belts_19](./images/build/frame/attach_tensioners_and_belts_19.jpg)

![attach_tensioners_and_belts_20](./images/build/frame/attach_tensioners_and_belts_20.jpg)

![attach_tensioners_and_belts_21](./images/build/frame/attach_tensioners_and_belts_21.jpg)

![attach_tensioners_and_belts_22](./images/build/frame/attach_tensioners_and_belts_22.jpg)

![attach_tensioners_and_belts_23](./images/build/frame/attach_tensioners_and_belts_23.jpg)

![attach_tensioners_and_belts_24](./images/build/frame/attach_tensioners_and_belts_24.jpg)

![attach_tensioners_and_belts_25](./images/build/frame/attach_tensioners_and_belts_25.jpg)

![attach_tensioners_and_belts_26](./images/build/frame/attach_tensioners_and_belts_26.jpg)

![attach_tensioners_and_belts_27](./images/build/frame/attach_tensioners_and_belts_27.jpg)

The end-stop mounts were then attached to the same side as the belt tension sliders using M5 screws, facing outwards and aligned with the rails. 

![attach_tensioners_and_belts_1](./images/build/frame/attach_tensioners_and_belts_1.jpg)

![attach_tensioners_and_belts_2](./images/build/frame/attach_tensioners_and_belts_2.jpg)

![attach_tensioners_and_belts_3](./images/build/frame/attach_tensioners_and_belts_3.jpg)

![attach_tensioners_and_belts_4](./images/build/frame/attach_tensioners_and_belts_4.jpg)

![attach_tensioners_and_belts_5](./images/build/frame/attach_tensioners_and_belts_5.jpg)

![attach_tensioners_and_belts_6](./images/build/frame/attach_tensioners_and_belts_6.jpg)

![attach_tensioners_and_belts_7](./images/build/frame/attach_tensioners_and_belts_7.jpg)

![attach_tensioners_and_belts_8](./images/build/frame/attach_tensioners_and_belts_8.jpg)

![attach_tensioners_and_belts_9](./images/build/frame/attach_tensioners_and_belts_9.jpg)

![attach_tensioners_and_belts_10](./images/build/frame/attach_tensioners_and_belts_10.jpg)

![attach_tensioners_and_belts_11](./images/build/frame/attach_tensioners_and_belts_11.jpg)

The belt tensioners were loosely attached to the belt tension sliders using fully threaded M8 screws, M8 locknuts and (20mm x 10mm x 2mm) washers.

![attach_tensioners_and_belts_28](./images/build/frame/attach_tensioners_and_belts_28.jpg)

![attach_tensioners_and_belts_29](./images/build/frame/attach_tensioners_and_belts_29.jpg)

### Y-axis HTD5M belts

The HTD5M belt was first inserted into one of the fixed belt tensioners using a flat screw driver. It was then stretched along the aluminium profile, below the first idler, around the timing pulley, below the second idler and all the way to the belt tensioner.

![attach_tensioners_and_belts_30](./images/build/frame/attach_tensioners_and_belts_30.jpg)

![attach_tensioners_and_belts_31](./images/build/frame/attach_tensioners_and_belts_31.jpg)

![attach_tensioners_and_belts_32](./images/build/frame/attach_tensioners_and_belts_32.jpg)

![attach_tensioners_and_belts_33](./images/build/frame/attach_tensioners_and_belts_33.jpg)

![attach_tensioners_and_belts_34](./images/build/frame/attach_tensioners_and_belts_34.jpg)

A scissor was used to cut the belt at an appropriate length. The loose end was then inserted into the belt tensioner using a flat screw driver and the belt was stretched by tightning the M8 locknut.

![attach_tensioners_and_belts_35](./images/build/frame/attach_tensioners_and_belts_35.jpg)

![attach_tensioners_and_belts_36](./images/build/frame/attach_tensioners_and_belts_36.jpg)

![attach_tensioners_and_belts_37](./images/build/frame/attach_tensioners_and_belts_37.jpg)

![attach_tensioners_and_belts_38](./images/build/frame/attach_tensioners_and_belts_38.jpg)

![attach_tensioners_and_belts_39](./images/build/frame/attach_tensioners_and_belts_39.jpg)

Make sure that the belt is not too loose and not too tight.

![attach_tensioners_and_belts_40](./images/build/frame/attach_tensioners_and_belts_40.jpg)

![attach_tensioners_and_belts_41](./images/build/frame/attach_tensioners_and_belts_41.jpg)

Repeat on the other side.

### Rails to bridge beams

The last two 600 mm MGN12H rails were attached to two of the 803 mm aluminium bridge beams (used for the X-axis). First, the MGN12H blocks were carefully removed from the rails.

![attach_rails_to_beams_1](./images/build/frame/attach_rails_to_beams_1.jpg)

![attach_rails_to_beams_2](./images/build/frame/attach_rails_to_beams_2.jpg)

The same 100 mm distance used to align the belt tension sliders were used to align the rails. Because they will be off center by 3 mm, make sure that you later attach the bridge beams to the side plates in a way so the rails line up. 

The same 3d-printed support tools used to align the rails on the 900 mm aluminium profiles were used here as well. Everything was clamped into position. A bradawl and a hammer were used to make indentations and a 2 mm drill and a M3 drill tap was used to make the screw holes.

![attach_rails_to_beams_3](./images/build/frame/attach_rails_to_beams_3.jpg)

![attach_rails_to_beams_4](./images/build/frame/attach_rails_to_beams_4.jpg)

![attach_rails_to_beams_5](./images/build/frame/attach_rails_to_beams_5.jpg)

![attach_rails_to_beams_6](./images/build/frame/attach_rails_to_beams_6.jpg)

![attach_rails_to_beams_7](./images/build/frame/attach_rails_to_beams_7.jpg)

![attach_rails_to_beams_8](./images/build/frame/attach_rails_to_beams_8.jpg)

![attach_rails_to_beams_9](./images/build/frame/attach_rails_to_beams_9.jpg)

![attach_rails_to_beams_10](./images/build/frame/attach_rails_to_beams_10.jpg)

![attach_rails_to_beams_11](./images/build/frame/attach_rails_to_beams_11.jpg)

The rails were finally attached using 20 mm M3 screws and the rail blocks were gently slided back onto the rails.

![attach_rails_to_beams_12](./images/build/frame/attach_rails_to_beams_12.jpg)

![attach_rails_to_beams_13](./images/build/frame/attach_rails_to_beams_13.jpg)

![attach_rails_to_beams_14](./images/build/frame/attach_rails_to_beams_14.jpg)

![attach_rails_to_beams_15](./images/build/frame/attach_rails_to_beams_15.jpg)

### X-axis tensioner and end-stop mount to lower bridge beam

The fixed tensioner and end-stop mount were attached to the lower bridge beam in the same fashion as on the 900 mm aluminium profiles, using M5 screws. When aligning the fixed tensioner, make sure that the "belt opening" is pointing in the direction of the rail. A bradawl and a hammer were used to make indentations at the center of the holes. Cutting fluid were applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap.

![attach_tensioners_to_beams_1](./images/build/frame/attach_tensioners_to_beams_1.jpg)

![attach_tensioners_to_beams_2](./images/build/frame/attach_tensioners_to_beams_2.jpg)

![attach_tensioners_to_beams_3](./images/build/frame/attach_tensioners_to_beams_3.jpg)

![attach_tensioners_to_beams_4](./images/build/frame/attach_tensioners_to_beams_4.jpg)

![attach_tensioners_to_beams_5](./images/build/frame/attach_tensioners_to_beams_5.jpg)

![attach_tensioners_to_beams_6](./images/build/frame/attach_tensioners_to_beams_6.jpg)

![attach_tensioners_to_beams_7](./images/build/frame/attach_tensioners_to_beams_7.jpg)

![attach_tensioners_to_beams_8](./images/build/frame/attach_tensioners_to_beams_8.jpg)

![attach_tensioners_to_beams_9](./images/build/frame/attach_tensioners_to_beams_9.jpg)

![attach_tensioners_to_beams_10](./images/build/frame/attach_tensioners_to_beams_10.jpg)

![attach_tensioners_to_beams_11](./images/build/frame/attach_tensioners_to_beams_11.jpg)

![attach_tensioners_to_beams_12](./images/build/frame/attach_tensioners_to_beams_12.jpg)

### Bridge beams to side plates

All three bridge beams were then inserted into the slots on the side plates. Make sure that the two beams with the rails are on top of each other, with the rails pointing outwards. Also, make sure that you insert them in the correct orientation, so that the rails are lined up (due to the rails being 3 mm off center).

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_1.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_2.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_3.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_4.jpg)

When the bridge beams were aligned, the blockers were placed in their correct place and a sharpie was used to mark the center of the holes to be drilled. Similar to before, a bradawl and a hammer were used to make indentations at the center of the holes.

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_5.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_6.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_7.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_8.jpg)

A 7 mm drill bit was used to drill the holes. As these holes were going straight through the profiles, a bench drill was used for precision. A metal file was used to remove all excess metal around the holes.

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_9.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_10.jpg)

The bridge beams were then inserted into the slots on the side plates once more, along with all the blockers. A 140 mm threaded M5 rod was inserted through the bottom two beams and a 60 mm M5 screws was inserted through the top bridge beam. It was all tightened using M5 nuts.

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_11.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_12.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_13.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_14.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_15.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_16.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_17.jpg)

### Rod bearings to carriage

Before attaching the carriage to the bridge beams, two KFL08 rod bearings were attached on the top and the bottom of the carriage (inside) using 20 mm M5 screws and M5 locknuts. A tip is to temporarily use the acme rod (used in an upcoming step) to vertically align the two bearings.

![assemble_carriage_1](./images/build/frame/assemble_carriage_1.jpg)

![assemble_carriage_2](./images/build/frame/assemble_carriage_2.jpg)

![assemble_carriage_3](./images/build/frame/assemble_carriage_3.jpg)

![assemble_carriage_4](./images/build/frame/assemble_carriage_4.jpg)

![assemble_carriage_5](./images/build/frame/assemble_carriage_5.jpg)

### Carriage to bridge beams

The carriage was attached to the four MGN12H blocks on the bridge beams, using 25 mm M3 screws.

![attach_carriage_to_beams_1](./images/build/frame/attach_carriage_to_beams_1.jpg)

![attach_carriage_to_beams_2](./images/build/frame/attach_carriage_to_beams_2.jpg)

![attach_carriage_to_beams_3](./images/build/frame/attach_carriage_to_beams_3.jpg)

![attach_carriage_to_beams_4](./images/build/frame/attach_carriage_to_beams_4.jpg)

### X-axis motor, idlers and pulley to carriage

Each idler were made up out of one 60 mm fully threaded M8 screw, 3 698zz bearings and 4 (10 mm x 8 mm x 2 mm) washers (1 closest to the idler blocker and 3 closest to the side plate). Two idlers were then attached to each side plate using two M8 nuts. Make sure that the bearings are spinning freely.

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_1.jpg)

![attach_side_plate_motors_2](./images/build/frame/attach_side_plate_motors_2.jpg)

As I designed and added the idler blocker later on in the build, some of the images doesn't have it and they also have 3 washers instead of 1 washer closest to the screw head. I left these images anyways in the guide so you can see how it looks when you attach the idlers, but please ignore the wrong number of washers. Also ignore all the other things around the idlers in the upcoming image, they are taken later on in the build.

![attach_idlers_motor_to_carriage_3](./images/build/frame/attach_idlers_motor_to_carriage_2.jpg)

Should be idler blockers and a different number of washers in the upcoming images.

![attach_idlers_motor_to_carriage_3](./images/build/frame/attach_idlers_motor_to_carriage_3.jpg)

![attach_idlers_motor_to_carriage_4](./images/build/frame/attach_idlers_motor_to_carriage_4.jpg)

![attach_idlers_motor_to_carriage_5](./images/build/frame/attach_idlers_motor_to_carriage_5.jpg)

To attach the stepper motor to the carriage, the 4 M3 screws locking the gear box to the motor were removed.

![attach_idlers_motor_to_carriage_6](./images/build/frame/attach_idlers_motor_to_carriage_6.jpg)

![attach_idlers_motor_to_carriage_7](./images/build/frame/attach_idlers_motor_to_carriage_7.jpg)

![attach_idlers_motor_to_carriage_8](./images/build/frame/attach_idlers_motor_to_carriage_8.jpg)

The stepper motor was then inserted into the large hole on the carriage, facing towards the bridge beams/idlers. 4 40 mm M3 screws and 4 M3 washers were used to lock the stepper motor onto the carriage. The motor should be attached so that the cables are facing upwards.

![attach_idlers_motor_to_carriage_9](./images/build/frame/attach_idlers_motor_to_carriage_9.jpg)

![attach_idlers_motor_to_carriage_10](./images/build/frame/attach_idlers_motor_to_carriage_10.jpg)

![attach_idlers_motor_to_carriage_11](./images/build/frame/attach_idlers_motor_to_carriage_11.jpg)

The HTD5M timing pulley was attached to the motor shaft using set screws.

![attach_idlers_motor_to_carriage_12](./images/build/frame/attach_idlers_motor_to_carriage_12.jpg)

![attach_idlers_motor_to_carriage_13](./images/build/frame/attach_idlers_motor_to_carriage_13.jpg)

### X-axis HTD5M belt

The HTD5M belt was first inserted into the fixed belt tensioner using a flat screw driver. It was then stretched along the aluminium profile, below the first idler, around the timing pulley, below the second idler and all the way to the other side.

The belt was cut at an appropriate length and inserted into the belt tensioner using a flat screw driver.

![attach_x_axis_belt_1](./images/build/frame/attach_x_axis_belt_1.jpg)

![attach_x_axis_belt_2](./images/build/frame/attach_x_axis_belt_2.jpg)

![attach_x_axis_belt_3](./images/build/frame/attach_x_axis_belt_3.jpg)

![attach_x_axis_belt_4](./images/build/frame/attach_x_axis_belt_4.jpg)

![attach_x_axis_belt_5](./images/build/frame/attach_x_axis_belt_5.jpg)

The belt tensioner was then attached to the side plate using a fully threaded M8 screw, a M8 locknut and a (20mm x 10mm x 2mm) washer. The M8 screw in the image is not fully threaded as I lost the one I was suppose to use and had to use another one, so please ignore :)

![attach_x_axis_belt_6](./images/build/frame/attach_x_axis_belt_6.jpg)

![attach_x_axis_belt_7](./images/build/frame/attach_x_axis_belt_7.jpg)

Make sure that the belt is not too loose and not too tight.

![attach_x_axis_belt_8](./images/build/frame/attach_x_axis_belt_8.jpg)

### Acme nut and rails to carriage slider

An acme nut was inserted from the outside, into the the center hole at the top of the vertical carriage slider. It was locked in place using 4 25 mm M3 screws.

![assemble_carriage_6](./images/build/frame/assemble_carriage_6_0.jpg)

![assemble_carriage_6](./images/build/frame/assemble_carriage_6.jpg)

![assemble_carriage_7](./images/build/frame/assemble_carriage_7.jpg)

![assemble_carriage_8](./images/build/frame/assemble_carriage_8.jpg)

The two smaller 200 mm MGN12H rails were then attached to the back of the vertical carriage slider. First, the MGN12H blocks were carefully removed from each rail. After that, the rails were screwed in place on the back of the vertical carriage slider using 20 mm M3 screws. The MGN12H blocks were then slided back on and each end were blocked using tape. 

![assemble_carriage_9](./images/build/frame/assemble_carriage_9.jpg)

![assemble_carriage_10](./images/build/frame/assemble_carriage_10.jpg)

![assemble_carriage_11](./images/build/frame/assemble_carriage_11.jpg)

![assemble_carriage_12](./images/build/frame/assemble_carriage_12.jpg)

![assemble_carriage_13](./images/build/frame/assemble_carriage_13.jpg)

### Acme rod and vertical slider to carriage

To attach the vertical slider to the carriage, 25 mm M3 screws were first inserted into the holes on the carriage. You might need to "open up" the holes using a narrow tool (depending on the direction you 3d-printed the carriage).

![assemble_carriage_17](./images/build/frame/assemble_carriage_17.jpg)

![assemble_carriage_18](./images/build/frame/assemble_carriage_18.jpg)

![assemble_carriage_19](./images/build/frame/assemble_carriage_19.jpg)

The acme rod was then inserted through the two KFL08 rod bearings and the acme nut, and the set screws on the bearings were tightened.

![assemble_carriage_14](./images/build/frame/assemble_carriage_14.jpg)

![assemble_carriage_15](./images/build/frame/assemble_carriage_15.jpg)

![assemble_carriage_16](./images/build/frame/assemble_carriage_16.jpg)

The vertical slider was finally attached to the carriage by attaching the 25 mm M3 screws to the MGN12H blocks on the vertical slider.

![assemble_carriage_20](./images/build/frame/assemble_carriage_20.jpg)

![assemble_carriage_21](./images/build/frame/assemble_carriage_21.jpg)

### Z motor mount and X-axis cable chain

The first step was to find a good length of the X-axis cable chain. To simplify this process, the X-axis belt was removed to easier move the carriage along the X-axis.

![assemble_carriage_22](./images/build/frame/assemble_carriage_22.jpg)

The Z motor mount and the X-axis cable chain mount were then assembled using 3 25 mm M4 screws, 3 M4 nuts and 3 (8mm x 4mm x 0.5mm) washers.

![assemble_carriage_23](./images/build/frame/assemble_carriage_23.jpg)

![assemble_carriage_24](./images/build/frame/assemble_carriage_24.jpg)

![assemble_carriage_25](./images/build/frame/assemble_carriage_25.jpg)

![assemble_carriage_26](./images/build/frame/assemble_carriage_26.jpg)

![assemble_carriage_27](./images/build/frame/assemble_carriage_27.jpg)

![assemble_carriage_28](./images/build/frame/assemble_carriage_28.jpg)

![assemble_carriage_29](./images/build/frame/assemble_carriage_29.jpg)

![assemble_carriage_30](./images/build/frame/assemble_carriage_30_1.jpg)

They Z motor mount was then attached to the carriage using 2 80 mm M8 screws, 2 M8 nuts and 2 (20mm x 10mm x 2mm) washers. The vaccum mount was also inserted and attached to the right-side M8 screw. Please ignore the timing pulley attached to the acme rod in some of the images, it will be attached in a later step.

![assemble_carriage_30](./images/build/frame/assemble_carriage_30.jpg)

![assemble_carriage_31](./images/build/frame/assemble_carriage_31.jpg)

![assemble_carriage_32](./images/build/frame/assemble_carriage_32.jpg)

![assemble_carriage_33](./images/build/frame/assemble_carriage_33.jpg)

![assemble_carriage_34](./images/build/frame/assemble_carriage_34.jpg)

![assemble_carriage_35](./images/build/frame/assemble_carriage_35.jpg)

A 1 meter cable chain were then clamped to the cable chain mount and to the back-side bridge beam. The carriage was then moved as far to the sides as possible. It's important that the chain doesn't touch any of the side plates when moved. In my case, I had to remove 3 links from the cable chain to get a good length of the chain.

![assemble_carriage_36](./images/build/frame/assemble_carriage_36.jpg)

![assemble_carriage_37](./images/build/frame/assemble_carriage_37.jpg)

![assemble_carriage_38](./images/build/frame/assemble_carriage_38.jpg)

![assemble_carriage_39](./images/build/frame/assemble_carriage_39_0.jpg)

![assemble_carriage_39](./images/build/frame/assemble_carriage_39.jpg)

The Z motor mount and cable chain mount were then disassembled and the cable chain was properly attached to the cable chain mount using 2 25 mm M4 screws, 2 M4 nuts and 2 (8mm x 4mm x 0.5mm) washers.

![assemble_carriage_40](./images/build/frame/assemble_carriage_40.jpg)

![assemble_carriage_41](./images/build/frame/assemble_carriage_41.jpg)

![assemble_carriage_42](./images/build/frame/assemble_carriage_42.jpg)

![assemble_carriage_43](./images/build/frame/assemble_carriage_43.jpg)

The Z motor mount and cable chain mount were then assembled again and attached to the carriage in the same fashion as before.

![assemble_carriage_44](./images/build/frame/assemble_carriage_44.jpg)

![assemble_carriage_45](./images/build/frame/assemble_carriage_45.jpg)

![assemble_carriage_46](./images/build/frame/assemble_carriage_46.jpg)

![assemble_carriage_47](./images/build/frame/assemble_carriage_47.jpg)

The carriage was move all the way to the right side plate and the cable chain was clamped to the back-side bridge beam.

![assemble_carriage_48](./images/build/frame/assemble_carriage_48.jpg)

![assemble_carriage_49](./images/build/frame/assemble_carriage_49.jpg)

A bradawl and a hammer were used to make indentations at the center of the two holes. Cutting fluid was applied and a 3 mm drill was used to drill the holes, followed by a M4 drill tap. The cable chain was then attached to the bridge beam using 2 25 mm M4 screws.

![assemble_carriage_50](./images/build/frame/assemble_carriage_50.jpg)

![assemble_carriage_51](./images/build/frame/assemble_carriage_51.jpg)

![assemble_carriage_52](./images/build/frame/assemble_carriage_52.jpg)

![assemble_carriage_53](./images/build/frame/assemble_carriage_53.jpg)

![assemble_carriage_54](./images/build/frame/assemble_carriage_54.jpg)

![assemble_carriage_55](./images/build/frame/assemble_carriage_55.jpg)

![assemble_carriage_56](./images/build/frame/assemble_carriage_56.jpg)

![assemble_carriage_57](./images/build/frame/assemble_carriage_57.jpg)

![assemble_carriage_58](./images/build/frame/assemble_carriage_58.jpg)

![assemble_carriage_59](./images/build/frame/assemble_carriage_59.jpg)

![assemble_carriage_60](./images/build/frame/assemble_carriage_60.jpg)

Finally, the X-axis belt was reattached and tightened.

![assemble_carriage_61](./images/build/frame/assemble_carriage_61.jpg)

### Y-axis cable chain

The Y-axis cable chain was attached using two supports. The first support (with screw holes to attach the cable chain) was clamped to the left side of the lower frame and aligned with the last vertial beam. A bradawl and a hammer were used to make indentations at the center of the two holes. Cutting fluid was applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap. The support was then attached to the lower frame using 2 20 mm M5 screws.


![assemble_cable_support_y_axis_1](./images/build/frame/assemble_cable_support_y_axis_1.jpg)

![assemble_cable_support_y_axis_2](./images/build/frame/assemble_cable_support_y_axis_2.jpg)

![assemble_cable_support_y_axis_3](./images/build/frame/assemble_cable_support_y_axis_3.jpg)

![assemble_cable_support_y_axis_4](./images/build/frame/assemble_cable_support_y_axis_4.jpg)

![assemble_cable_support_y_axis_5](./images/build/frame/assemble_cable_support_y_axis_5.jpg)

The second support was only attached to the lower frame for the cable chain to rest on. I aligned and attached it at the center between the second and third vertical beam. Make sure that it does not go below the bottom frame!

In the same way as the first support, a bradawl and a hammer were used to make indentations at the center of the two holes. Cutting fluid was applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap. The support was then attached to the lower frame using 2 20 mm M5 screws.

![assemble_cable_support_y_axis_6](./images/build/frame/assemble_cable_support_y_axis_6.jpg)

![assemble_cable_support_y_axis_6](./images/build/frame/assemble_cable_support_y_axis_6_1.jpg)

![assemble_cable_support_y_axis_7](./images/build/frame/assemble_cable_support_y_axis_7.jpg)

![assemble_cable_support_y_axis_8](./images/build/frame/assemble_cable_support_y_axis_8.jpg)

![assemble_cable_support_y_axis_9](./images/build/frame/assemble_cable_support_y_axis_9.jpg)

![assemble_cable_support_y_axis_10](./images/build/frame/assemble_cable_support_y_axis_10.jpg)

![assemble_cable_support_y_axis_11](./images/build/frame/assemble_cable_support_y_axis_11.jpg)

The Y-axis cable chain was then attached to the left side plate and lower frame support using 4 25 mm M4 screws, 4 M4 nuts and 4 (8mm x 4mm x 0.5mm) washers.

![assemble_cable_support_y_axis_12](./images/build/frame/assemble_cable_support_y_axis_12.jpg)

![assemble_cable_support_y_axis_13](./images/build/frame/assemble_cable_support_y_axis_13.jpg)

![assemble_cable_support_y_axis_14](./images/build/frame/assemble_cable_support_y_axis_14.jpg)

![assemble_cable_support_y_axis_15](./images/build/frame/assemble_cable_support_y_axis_15.jpg)

![assemble_cable_support_y_axis_16](./images/build/frame/assemble_cable_support_y_axis_16.jpg)

![assemble_cable_support_y_axis_17](./images/build/frame/assemble_cable_support_y_axis_17.jpg)

### Z stepper motor, pulleys and belt

The NEMA17 stepper motor was attached to the Z-axis motor mount using 4 10mm M3 screws and 4 M3 washers. Make sure that the motor cable connector is pointing in the same direction as the opening of the X-axis cable chain.

The smaller GT2 timing pulley was then attached to the motor shaft and the larger GT2 timing pulley was attached to the acme rod. Both were locked in place using set screws. Make sure that they line up. 

![attach_z_stepper_pulleys_belt_1](./images/build/frame/attach_z_stepper_pulleys_belt_1.jpg)

![attach_z_stepper_pulleys_belt_2](./images/build/frame/attach_z_stepper_pulleys_belt_2.jpg)

![attach_z_stepper_pulleys_belt_3](./images/build/frame/attach_z_stepper_pulleys_belt_3.jpg)

![attach_z_stepper_pulleys_belt_4](./images/build/frame/attach_z_stepper_pulleys_belt_4.jpg)

![attach_z_stepper_pulleys_belt_5](./images/build/frame/attach_z_stepper_pulleys_belt_5.jpg)

![attach_z_stepper_pulleys_belt_6](./images/build/frame/attach_z_stepper_pulleys_belt_6.jpg)

The GT2 timing belt was looped around both timing pulleys and stretched. Before tightning the M3 screws and locking the motor into place, make sure that the belt is not too loose and not too tight. 

![attach_z_stepper_pulleys_belt_7](./images/build/frame/attach_z_stepper_pulleys_belt_7.jpg)

![attach_z_stepper_pulleys_belt_8](./images/build/frame/attach_z_stepper_pulleys_belt_8.jpg)

![attach_z_stepper_pulleys_belt_9](./images/build/frame/attach_z_stepper_pulleys_belt_9.jpg)

![attach_z_stepper_pulleys_belt_10](./images/build/frame/attach_z_stepper_pulleys_belt_10.jpg)

### Extend and solder stepper motor cables

All 4 stepper motors (x2 Y-axis, x1 X-axis and x1 Z-axis) get their power and movement instructions from the Arduino + CNC shield that in a later step will be attached in the small electronic box. Therefore, the stepper motor cables needed to be extended to reach through the cable chains all the way to the front of the machine, where the small electronic box will be located.

AWG22 cables of matching colors were used when increasing the length of the stepper motor cables. The same process was used for all the motors:

1. The amount of cables needed to reach all the way to the electronic box was approximated and cut. Make sure to have an extra ~300 mm of cables from the point where the cables exits the Y-axis cable chain, as this will be needed to reach the small electronic box.
2. The ends of the stepper cables and the AWG22 cables were stripped using a wire stripper.
3. The colors of the stepper cables and the AWG22 cables were matched up and the stripped ends of the cables were twisted around each other.
4. The twisted cables where then locked in a steady position by a "third hand".
5. Soldering grease was applied to the twisted cables and the cables were soldered together.
6. 4 shrinking tubes (one per cable) were shrunk around the now soldered twisted cables, covering the soldering.
7. A handful of larger shrinking tubes were shrunk around all 4 wires to keep them together.
8. Finally, the cables were marked using tape and a penn, indicating which stepper motor the cables belonged to. This is important as it will help a lot later on, when the stepper motors are connected to the Arduino.

#### Y-axis 1

The extended cables of the first Y-axis stepper motor were cut at a length so that they reached through the lower front bridge beam (see red arrow on the next image) and through the Y-axis cable chain going to the front of the CNC machine.

![solder_steppers_y_axis_1](./images/build/frame/solder_steppers_y_axis_1.jpg)

![solder_steppers_y_axis_2](./images/build/frame/solder_steppers_y_axis_2.jpg)

![solder_steppers_y_axis_3](./images/build/frame/solder_steppers_y_axis_3.jpg)

![solder_steppers_y_axis_4](./images/build/frame/solder_steppers_y_axis_4.jpg)

![solder_steppers_y_axis_5](./images/build/frame/solder_steppers_y_axis_5.jpg)

![solder_steppers_y_axis_6](./images/build/frame/solder_steppers_y_axis_6.jpg)

![solder_steppers_y_axis_7](./images/build/frame/solder_steppers_y_axis_7.jpg)

![solder_steppers_y_axis_8](./images/build/frame/solder_steppers_y_axis_8.jpg)

![solder_steppers_y_axis_9](./images/build/frame/solder_steppers_y_axis_9.jpg)

![solder_steppers_y_axis_10](./images/build/frame/solder_steppers_y_axis_10.jpg)

![solder_steppers_y_axis_10_1](./images/build/frame/solder_steppers_y_axis_10_1.jpg)

#### Y-axis 2

The extended cables of the second Y-axis stepper motor were cut at a length so that they reached through the Y-axis cable chain going to the front of the CNC machine.

![solder_steppers_y_axis_11](./images/build/frame/solder_steppers_y_axis_11.jpg)

![solder_steppers_y_axis_12](./images/build/frame/solder_steppers_y_axis_12.jpg)

![solder_steppers_y_axis_13](./images/build/frame/solder_steppers_y_axis_13.jpg)

![solder_steppers_y_axis_14](./images/build/frame/solder_steppers_y_axis_14.jpg)

![solder_steppers_y_axis_15](./images/build/frame/solder_steppers_y_axis_15.jpg)

![solder_steppers_y_axis_16](./images/build/frame/solder_steppers_y_axis_16.jpg)

![solder_steppers_y_axis_17](./images/build/frame/solder_steppers_y_axis_17.jpg)

![solder_steppers_y_axis_18](./images/build/frame/solder_steppers_y_axis_18.jpg)

![solder_steppers_y_axis_19](./images/build/frame/solder_steppers_y_axis_19.jpg)

![solder_steppers_y_axis_20](./images/build/frame/solder_steppers_y_axis_20.jpg)

#### X-axis

I ran out of AWG22 cables when soldering the X-axis stepper motor cables, therefore you will see different type of cables in the upcoming images. Because of this, I had to insert the shrinking tubes before I soldered the cables. Please disregard this and follow the previous instructions.

The extended cables of the X-axis stepper motor were cut at a length so that they reached up and behind the Z-axis stepper motor, through the X-axis cable chain and through the Y-axis cable chain to the front of the CNC machine.

![solder_steppers_x_axis_1.jpg](./images/build/frame/solder_steppers_x_axis_1.jpg)

![solder_steppers_x_axis_2.jpg](./images/build/frame/solder_steppers_x_axis_2.jpg)

![solder_steppers_x_axis_3.jpg](./images/build/frame/solder_steppers_x_axis_3.jpg)

![solder_steppers_x_axis_4.jpg](./images/build/frame/solder_steppers_x_axis_4.jpg)

![solder_steppers_x_axis_5.jpg](./images/build/frame/solder_steppers_x_axis_5.jpg)

![solder_steppers_x_axis_6.jpg](./images/build/frame/solder_steppers_x_axis_6.jpg)

![solder_steppers_x_axis_7.jpg](./images/build/frame/solder_steppers_x_axis_7.jpg)

![solder_steppers_x_axis_8.jpg](./images/build/frame/solder_steppers_x_axis_8.jpg)

#### Z-axis

The non-geared NEMA17 motor used for the Z-axis had a removable cable, in contrast to the 1:19 geared NEMA17 motors that had non-removable cables. The first step was therefore to connect the cables to the NEMA17 motor and cut of the connector on the other side using a scissor. Otherwise, the same procedure was followed as for the other motors.

The extended cables of the Z-axis stepper motor were cut at a length so that they reached through the X-axis cable chain and through the Y-axis cable chain to the front of the CNC machine.

![solder_steppers_z_axis_1.jpg](./images/build/frame/solder_steppers_z_axis_1.jpg)

![solder_steppers_z_axis_2.jpg](./images/build/frame/solder_steppers_z_axis_2.jpg)

![solder_steppers_z_axis_3.jpg](./images/build/frame/solder_steppers_z_axis_3.jpg)

![solder_steppers_z_axis_4.jpg](./images/build/frame/solder_steppers_z_axis_4.jpg)

![solder_steppers_z_axis_5.jpg](./images/build/frame/solder_steppers_z_axis_5.jpg)

![solder_steppers_z_axis_6.jpg](./images/build/frame/solder_steppers_z_axis_6.jpg)

![solder_steppers_z_axis_7.jpg](./images/build/frame/solder_steppers_z_axis_7.jpg)

![solder_steppers_z_axis_8.jpg](./images/build/frame/solder_steppers_z_axis_8.jpg)

![solder_steppers_z_axis_9.jpg](./images/build/frame/solder_steppers_z_axis_9.jpg)

![solder_steppers_z_axis_9.jpg](./images/build/frame/solder_steppers_z_axis_10.jpg)

### End-stops and end-stop cables

End-stoppers are important, as they do not only enable you to home the CNC machine, but they also limit the CNC machine from moving past what is physically possible. When the end-stoppers are triggered, an alarm is fired and the machine automatically stops.

The cables used for end-stops were 0.75 mm^2.

#### X-axis (max)

A microswitch was attached to the X-axis max end-stop mount using 2 10mm M3 screws.

![attach_endstoppers_x_axis_1](./images/build/frame/attach_endstoppers_x_axis_1.jpg)

![attach_endstoppers_x_axis_2](./images/build/frame/attach_endstoppers_x_axis_2.jpg)

![attach_endstoppers_x_axis_3](./images/build/frame/attach_endstoppers_x_axis_3.jpg)

![attach_endstoppers_x_axis_4](./images/build/frame/attach_endstoppers_x_axis_4.jpg)

The end-stop mount was then pushed against the backside of the top bridge beam, which enabled the end-stop to trigger on the Z-axis stepper motor. The X-axis (carriage) was then moved to its maximum position and the end-stop mount was positioned in a way so that the end-stop triggered just before the X-axis reached its maximum position.

Please ignore the flexible conduit/hose in the next two images, it will be added in an upcoming step.

![attach_endstoppers_x_axis_5](./images/build/frame/attach_endstoppers_x_axis_5.jpg)

![attach_endstoppers_x_axis_7](./images/build/frame/attach_endstoppers_x_axis_7.jpg)

The end-stop mount was then clamped to the upper bridge beam and a small drill (-2 mm) was used to carefully make indentations at the center of the holes. The end-stop mount was then removed. Cutting fluid was applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap. The end-stop mount was then attached to the upper bridge beam using 2 40 mm M5 screws.

![attach_endstoppers_x_axis_8](./images/build/frame/attach_endstoppers_x_axis_8.jpg)

![attach_endstoppers_x_axis_9](./images/build/frame/attach_endstoppers_x_axis_9.jpg)

![attach_endstoppers_x_axis_10](./images/build/frame/attach_endstoppers_x_axis_10.jpg)

![attach_endstoppers_x_axis_11](./images/build/frame/attach_endstoppers_x_axis_11.jpg)

![attach_endstoppers_x_axis_12](./images/build/frame/attach_endstoppers_x_axis_12.jpg)

![attach_endstoppers_x_axis_13](./images/build/frame/attach_endstoppers_x_axis_13.jpg)

![attach_endstoppers_x_axis_14](./images/build/frame/attach_endstoppers_x_axis_14.jpg)

![attach_endstoppers_x_axis_15](./images/build/frame/attach_endstoppers_x_axis_15.jpg)

![attach_endstoppers_x_axis_16](./images/build/frame/attach_endstoppers_x_axis_16.jpg)

One black and one red 0.75 mm^2 cable were cut out at a length so that they reached from the X-axis max end-stop to the right side plate, through the top bridge beam and through the Y-axis cable chain to the front of the CNC machine. A handful of shrinking tubes were shrunk around the cables to keep them together.

![attach_endstoppers_x_axis_17](./images/build/frame/attach_endstoppers_x_axis_17.jpg)

![attach_endstoppers_x_axis_18](./images/build/frame/attach_endstoppers_x_axis_18.jpg)

![attach_endstoppers_x_axis_19](./images/build/frame/attach_endstoppers_x_axis_19.jpg)

One end of the cables were taped together and inserted through the upper bridge beam to the side plate on the other side.

![attach_endstoppers_x_axis_20](./images/build/frame/attach_endstoppers_x_axis_20.jpg)

![attach_endstoppers_x_axis_21](./images/build/frame/attach_endstoppers_x_axis_21.jpg)

![attach_endstoppers_x_axis_22](./images/build/frame/attach_endstoppers_x_axis_22.jpg)

A flexible conduit/hose was then cut out and the other side of the cables were inserted through the conduit. The flexible conduit was then inserted ~50 mm into the upper bridge beam and the other side was attached to the outside of the upper bridge beam using cable ties.

![attach_endstoppers_x_axis_23](./images/build/frame/attach_endstoppers_x_axis_23.jpg)

![attach_endstoppers_x_axis_24](./images/build/frame/attach_endstoppers_x_axis_24.jpg)

![attach_endstoppers_x_axis_25](./images/build/frame/attach_endstoppers_x_axis_25.jpg)

The end of the cables were stripped and twisted. Two 2.8 mm spade connectors were then attached to the stripped cables using a plier. The red cable were then attached to C (Common terminal) pinout on the end-stop and the black cable was connected to the NO (Normally Open) pinout.

![attach_endstoppers_x_axis_26](./images/build/frame/attach_endstoppers_x_axis_26.jpg)

![attach_endstoppers_x_axis_27](./images/build/frame/attach_endstoppers_x_axis_27.jpg)

![attach_endstoppers_x_axis_28](./images/build/frame/attach_endstoppers_x_axis_28.jpg)

![attach_endstoppers_x_axis_29](./images/build/frame/attach_endstoppers_x_axis_29.jpg)

![attach_endstoppers_x_axis_30](./images/build/frame/attach_endstoppers_x_axis_30.jpg)

Finally, the open end of the cables were marked using tape and a penn, indicating which end-stop the cables belonged to. This is important as it will help a lot later on, when the end-stops are connected to the Arduino.

![attach_endstoppers_x_axis_31](./images/build/frame/attach_endstoppers_x_axis_31.jpg)

#### X-axis (min)

A microswitch was attached to the X-axis min end-stop mount using 2 10mm M3 screws.

![attach_endstoppers_x_axis_32_0](./images/build/frame/attach_endstoppers_x_axis_32_0.jpg)

![attach_endstoppers_x_axis_32_1](./images/build/frame/attach_endstoppers_x_axis_32_1.jpg)

![attach_endstoppers_x_axis_32_2](./images/build/frame/attach_endstoppers_x_axis_32_2.jpg)

One black and one red 0.75 mm^2 cable were cut out at a length so that they reached from the X-axis min end-stop, around the left side plate, through the Y-axis cable chain to the front of the CNC machine. A handful of shrinking tubes were shrunk around the cables to keep them together.

![attach_endstoppers_x_axis_32](./images/build/frame/attach_endstoppers_x_axis_32.jpg)

![attach_endstoppers_x_axis_33](./images/build/frame/attach_endstoppers_x_axis_33.jpg)

![attach_endstoppers_x_axis_34](./images/build/frame/attach_endstoppers_x_axis_34.jpg)

The end of the cables were stripped and twisted. Two 2.8 mm spade connectors were then attached to the stripped cables using a plier. The red cable were then attached to C (Common terminal) pinout on the end-stop and the black cable was connected to the NO (Normally Open) pinout.

The cables were initially strapped around the lower front bridge beam (seen in the first two images), but as it turned out it blocked the belt tensioner. So they were instead strapped around the M8 tensioner screw, using a cable tie. 

![attach_endstoppers_x_axis_36](./images/build/frame/attach_endstoppers_x_axis_36.jpg)

![attach_endstoppers_x_axis_37](./images/build/frame/attach_endstoppers_x_axis_37.jpg)

![attach_endstoppers_x_axis_38](./images/build/frame/attach_endstoppers_x_axis_38.jpg)

Finally, the open end of the cables were marked using tape and a penn, indicating which end-stop the cables belonged to.

![attach_endstoppers_x_axis_39](./images/build/frame/attach_endstoppers_x_axis_39.jpg)

#### Y-axis (max)

The Y-axis max end-stop mount was clamped to the inner side of the upper frame and a sharpie was used to indicate the center of the holes. Note that this end-stop mount can probably be redesigned to gain an extra ~10 mm of Y-axis movement, something I will probably do in the future.

![attach_endstoppers_y_axis_1](./images/build/frame/attach_endstoppers_y_axis_1.jpg)

![attach_endstoppers_y_axis_2](./images/build/frame/attach_endstoppers_y_axis_2.jpg)

![attach_endstoppers_y_axis_3](./images/build/frame/attach_endstoppers_y_axis_3.jpg)

![attach_endstoppers_y_axis_4](./images/build/frame/attach_endstoppers_y_axis_4.jpg)

A bradawl and a hammer were then used to make indentations at the center of the holes. Cutting fluid was applied and a 4 mm drill was used to drill the holes, followed by a M5 drill tap. The end-stop mount was then attached to the inside of the upper frame using 2 20 mm M5 screws.

![attach_endstoppers_y_axis_5](./images/build/frame/attach_endstoppers_y_axis_5.jpg)

![attach_endstoppers_y_axis_6](./images/build/frame/attach_endstoppers_y_axis_6.jpg)

![attach_endstoppers_y_axis_7](./images/build/frame/attach_endstoppers_y_axis_7.jpg)

![attach_endstoppers_y_axis_8](./images/build/frame/attach_endstoppers_y_axis_8.jpg)

![attach_endstoppers_y_axis_9](./images/build/frame/attach_endstoppers_y_axis_9.jpg)

![attach_endstoppers_y_axis_10](./images/build/frame/attach_endstoppers_y_axis_10.jpg)

![attach_endstoppers_y_axis_11](./images/build/frame/attach_endstoppers_y_axis_11.jpg)

![attach_endstoppers_y_axis_12](./images/build/frame/attach_endstoppers_y_axis_12.jpg)

One black and one red 0.75 mm^2 cable were cut out at a length so that they reached from the Y-axis max end-stop and through the 900 mm aluminium profile of the upper frame to the front of the CNC machine.

![attach_endstoppers_y_axis_13](./images/build/frame/attach_endstoppers_y_axis_13.jpg)

![attach_endstoppers_y_axis_14](./images/build/frame/attach_endstoppers_y_axis_14.jpg)

![attach_endstoppers_y_axis_15](./images/build/frame/attach_endstoppers_y_axis_15.jpg)

A microswitch was attached to the Y-axis max end-stop mount using 2 10mm M3 screws.

![attach_endstoppers_y_axis_17](./images/build/frame/attach_endstoppers_y_axis_17.jpg)

![attach_endstoppers_y_axis_18](./images/build/frame/attach_endstoppers_y_axis_18.jpg)

![attach_endstoppers_y_axis_19](./images/build/frame/attach_endstoppers_y_axis_19.jpg)

A flexible conduit/hose was then cut out and the cables were inserted through the conduit. The flexible conduit was then inserted ~50 mm into the 900 mm aluminium profile of the upper frame. The other side was bent around and attached to the outside of the upper frame using cable ties.

![attach_endstoppers_y_axis_20](./images/build/frame/attach_endstoppers_y_axis_20.jpg)

![attach_endstoppers_y_axis_21](./images/build/frame/attach_endstoppers_y_axis_21.jpg)

![attach_endstoppers_y_axis_22](./images/build/frame/attach_endstoppers_y_axis_22.jpg)

The end of the cables were stripped and twisted. Two 2.8 mm spade connectors were then attached to the stripped cables using a plier. The red cable were then attached to C (Common terminal) pinout on the end-stop and the black cable was connected to the NO (Normally Open) pinout.

![attach_endstoppers_y_axis_23](./images/build/frame/attach_endstoppers_y_axis_23.jpg)

![attach_endstoppers_y_axis_24](./images/build/frame/attach_endstoppers_y_axis_24.jpg)

Finally, the open end of the cables were marked using tape and a penn, indicating which end-stop the cables belonged to.

![attach_endstoppers_y_axis_16](./images/build/frame/attach_endstoppers_y_axis_16.jpg)

#### Y-axis (min)

A microswitch was attached to the Y-axis min end-stop mount using 2 10mm M3 screws.

![attach_endstoppers_y_axis_25](./images/build/frame/attach_endstoppers_y_axis_25.jpg)

![attach_endstoppers_y_axis_26](./images/build/frame/attach_endstoppers_y_axis_26.jpg)

![attach_endstoppers_y_axis_27](./images/build/frame/attach_endstoppers_y_axis_27.jpg)

One black and one red 0.75 mm^2 cable were cut out at a length so that they reached from the Y-axis min end-stop and to the front of the CNC machine.

The end of the cables were stripped and twisted. Two 2.8 mm spade connectors were then attached to the stripped cables using a plier. The red cable were then attached to C (Common terminal) pinout on the end-stop and the black cable was connected to the NO (Normally Open) pinout.

![attach_endstoppers_y_axis_28](./images/build/frame/attach_endstoppers_y_axis_28.jpg)

![attach_endstoppers_y_axis_29](./images/build/frame/attach_endstoppers_y_axis_29.jpg)

![attach_endstoppers_y_axis_30](./images/build/frame/attach_endstoppers_y_axis_30.jpg)

![attach_endstoppers_y_axis_31](./images/build/frame/attach_endstoppers_y_axis_31.jpg)

A flexible conduit/hose was cut out and the cables were inserted through the conduit. The flexible conduit was attached to the outside of the upper frame using cable ties.

![attach_endstoppers_y_axis_33](./images/build/frame/attach_endstoppers_y_axis_33.jpg)

![attach_endstoppers_y_axis_34](./images/build/frame/attach_endstoppers_y_axis_34.jpg)

![attach_endstoppers_y_axis_32](./images/build/frame/attach_endstoppers_y_axis_32.jpg)

![attach_endstoppers_y_axis_35](./images/build/frame/attach_endstoppers_y_axis_35.jpg)

#### Z-axis (max)

The main purpose of the Z-axis max end-stop is, apart from homing the machine, to limit the CNC machine from moving past what the length of the rails allow. As the MGN12H blocks contains a lot of small bearing balls, there's a high risk of them falling out if the blocks move past the rail.

To reduce the complexity and amount of cables, I chose not to include a Z-axis min end-stop, as you are likely to mill straight through your waste board before there's a risk of moving past the Z-axis min limit. But if you want to add a Z-axis min end-stop, just repeat the process in this section with the new switch flipped around.

First, the carriage was moved upwards to its maximum point, where the blocks are just about to move past the rails. The Z-axis end-stop trigger was then pressed against the outside of the vertical carriage slider and a sharpie was used to mark the center of the holes.

![attach_endstoppers_z_axis_1](./images/build/frame/attach_endstoppers_z_axis_1.jpg)

![attach_endstoppers_z_axis_2](./images/build/frame/attach_endstoppers_z_axis_2.jpg)

![attach_endstoppers_z_axis_3](./images/build/frame/attach_endstoppers_z_axis_3.jpg)

A 2.5 mm drill was used to drill the holes into the vertical carriage slider. A tip is to mark the drill depth needed using tape. The Z-axis end-stop trigger was then attached to the vertical carriage slider using 2 10 mm M3 screws.

![attach_endstoppers_z_axis_4](./images/build/frame/attach_endstoppers_z_axis_4.jpg)

![attach_endstoppers_z_axis_5](./images/build/frame/attach_endstoppers_z_axis_5.jpg)

![attach_endstoppers_z_axis_6](./images/build/frame/attach_endstoppers_z_axis_6.jpg)

![attach_endstoppers_z_axis_7](./images/build/frame/attach_endstoppers_z_axis_7.jpg)

A microswitch was pressed against the carriage and positioned and aligned to be triggered by the current state of the Z-axis end-stop trigger.

![attach_endstoppers_z_axis_8](./images/build/frame/attach_endstoppers_z_axis_8.jpg)

![attach_endstoppers_z_axis_9](./images/build/frame/attach_endstoppers_z_axis_9.jpg)

A 2.5 mm drill was used to drill the first hole into the carriage and the microswitch was attached to the carriage using 1 10 mm M3 screw. After the microswitch was locked into position, the second hole was drilled and the second 10 mm M3 screw was attached.

![attach_endstoppers_z_axis_10](./images/build/frame/attach_endstoppers_z_axis_10.jpg)

![attach_endstoppers_z_axis_11](./images/build/frame/attach_endstoppers_z_axis_11.jpg)

![attach_endstoppers_z_axis_12](./images/build/frame/attach_endstoppers_z_axis_12.jpg)

One black and one red 0.75 mm^2 cable were cut at a length so that they reached over the top bridge beam, through the X-axis cable chain and through the Y-axis cable chain to the front of the CNC machine. A handful of shrinking tubes were shrunk around the cables to keep them together.

![attach_endstoppers_z_axis_13](./images/build/frame/attach_endstoppers_z_axis_13.jpg)

![attach_endstoppers_z_axis_14](./images/build/frame/attach_endstoppers_z_axis_14.jpg)

![attach_endstoppers_z_axis_15](./images/build/frame/attach_endstoppers_z_axis_15.jpg)

The end of the cables were stripped and twisted. Two 2.8 mm spade connectors were then attached to the stripped cables using a plier. The red cable were then attached to C (Common terminal) pinout on the end-stop and the black cable was connected to the NO (Normally Open) pinout.

![attach_endstoppers_z_axis_16](./images/build/frame/attach_endstoppers_z_axis_16.jpg)

![attach_endstoppers_z_axis_17](./images/build/frame/attach_endstoppers_z_axis_17.jpg)

![attach_endstoppers_z_axis_18](./images/build/frame/attach_endstoppers_z_axis_18.jpg)

The cables were strapped around the M8 screw keeping the Z motor mount attached to the carriage, using a cable tie.

Finally, the open end of the cables were marked using tape and a penn, indicating which end-stop the cables belonged to.

![attach_endstoppers_z_axis_19](./images/build/frame/attach_endstoppers_z_axis_19.jpg)

![attach_endstoppers_z_axis_20](./images/build/frame/attach_endstoppers_z_axis_20.jpg)

### Stepper motor and end-stop cable management

To keep a nice structure of all the cables, cable socks and flexible conduits/hoses were used.

#### Y-axis steppers and X-axis end-stops

First, the cables from the right-side Y-axis stepper motor were inserted into a small flexible conduit and pushed through the lower bridge beam closest to the carriage.

![stepper_motor_cable_management_1](./images/build/frame/stepper_motor_cable_management_1.jpg)

![stepper_motor_cable_management_3](./images/build/frame/stepper_motor_cable_management_3.jpg)

![stepper_motor_cable_management_4](./images/build/frame/stepper_motor_cable_management_4.jpg)

The cables from the two Y-axis steppers and the two X-axis end-stops were bundled together into the same cable sock. 

![stepper_motor_cable_management_6](./images/build/frame/stepper_motor_cable_management_6.jpg)

![stepper_motor_cable_management_6_1](./images/build/frame/stepper_motor_cable_management_6_1.jpg)

![stepper_motor_cable_management_6_2](./images/build/frame/stepper_motor_cable_management_6_2.jpg)

![stepper_motor_cable_management_5](./images/build/frame/stepper_motor_cable_management_5.jpg)

![stepper_motor_cable_management_6_3](./images/build/frame/stepper_motor_cable_management_6_3.jpg)

To simplify pushing the cables through the cable chain, the cables were taped together, leaving no loose ends to get stuck in the chain. This was needed as the cables were longer than the cable sock (to reach all the way to the small electronic box in the front of the CNC machine).

A cable tie was used to close the entrence of the cable sock.

![stepper_motor_cable_management_6_4](./images/build/frame/stepper_motor_cable_management_6_4.jpg)

![stepper_motor_cable_management_6_5](./images/build/frame/stepper_motor_cable_management_6_5.jpg)

![stepper_motor_cable_management_6_6](./images/build/frame/stepper_motor_cable_management_6_6.jpg)

#### X-axis stepper, Z-axis stepper and Z-axis end-stop

First, the cables from the X-axis stepper motor were inserted into a flexible conduit. The conduit was then bent over the upper bridge beam, strapped to the vaccum mount and Z motor mount, and then pushed behind the Z-axis stepper motor.

![stepper_motor_cable_management_9](./images/build/frame/stepper_motor_cable_management_9.jpg)

![stepper_motor_cable_management_10](./images/build/frame/stepper_motor_cable_management_10.jpg)

![stepper_motor_cable_management_11](./images/build/frame/stepper_motor_cable_management_11.jpg)

![stepper_motor_cable_management_12](./images/build/frame/stepper_motor_cable_management_12.jpg)

The cables from the X-axis stepper, Z-axis stepper and the Z-axis end-stop were bundled together into the same cable sock. The cable sock was cut at a length so that it reached through the X-axis cable chain, around the left side-plate and through the Y-axis cable chain.

To simplify pushing the cables through the cable chains, the cables were taped together, leaving no loose ends to get stuck in the cable chains. This was needed as the cables were longer than the cable sock (to reach all the way to the small electronic box in the front of the CNC machine).

A cable tie was used to close the entrence of the cable sock.

![stepper_motor_cable_management_13](./images/build/frame/stepper_motor_cable_management_13.jpg)

![stepper_motor_cable_management_13_1](./images/build/frame/stepper_motor_cable_management_13_1.jpg)

![stepper_motor_cable_management_13_2](./images/build/frame/stepper_motor_cable_management_13_2.jpg)

![stepper_motor_cable_management_13_3](./images/build/frame/stepper_motor_cable_management_13_3.jpg)

![stepper_motor_cable_management_13_4](./images/build/frame/stepper_motor_cable_management_13_4.jpg)

![stepper_motor_cable_management_13_5](./images/build/frame/stepper_motor_cable_management_13_5.jpg)

![stepper_motor_cable_management_13_6](./images/build/frame/stepper_motor_cable_management_13_6.jpg)

![stepper_motor_cable_management_13_7](./images/build/frame/stepper_motor_cable_management_13_7.jpg)

![stepper_motor_cable_management_13_8](./images/build/frame/stepper_motor_cable_management_13_8.jpg)

A cable tie was used to strap the cable sock to the left side-plate.

![stepper_motor_cable_management_13_9](./images/build/frame/stepper_motor_cable_management_13_9.jpg)

### Connect main electronic box

**NOTE: THIS PART INCLUDES WIRING OF HIGH VOLTAGE ELECTRICITY THAT CAN BE LETHAL IF NOT DONE PROPERLY. THE COLORS OF THE CABLES CAN VARY DEPENDING ON REGION/COUNTRY AND YOUR COMPONENTS/PINOUT NUMBERS MIGHT LOOK DIFFERENT. BEFORE YOU CONNECT THE POWER CORD TO THE POWER OUTLET, YOU MUST CONSULT WITH A LICENSED ELECTRICIAN TO MAKE SURE THAT EVERYTHING IS PROPERLY WIRED AND THAT IT IS IN LINE WITH YOUR LOCAL LEGISLATIONS.**

The 200W power supply was attached to the back panel of the larger electronic box using the small M3 screws unscrewed from the geared stepper motors.

![connect_main_electronic_box_1](./images/build/frame/connect_main_electronic_box_1.jpg)

![connect_main_electronic_box_2](./images/build/frame/connect_main_electronic_box_2.jpg)

![connect_main_electronic_box_3](./images/build/frame/connect_main_electronic_box_3.jpg)

The C14 connector and the emergency stop switch were inserted into the holes on the front plate of the large electronic box.

![connect_main_electronic_box_4](./images/build/frame/connect_main_electronic_box_4.jpg)

![connect_main_electronic_box_5](./images/build/frame/connect_main_electronic_box_5.jpg)

![connect_main_electronic_box_6](./images/build/frame/connect_main_electronic_box_6.jpg)

A small brown wire was cut out and the ends were stripped and twisted. Two 4.8 mm spade connectors were then attached to the stripped wire using a plier. The space connectors were connected between **10** and **1A** on the back side of the C14 connector.

![connect_main_electronic_box_7](./images/build/frame/connect_main_electronic_box_7.jpg)

![connect_main_electronic_box_8](./images/build/frame/connect_main_electronic_box_8.jpg)

![connect_main_electronic_box_9](./images/build/frame/connect_main_electronic_box_9.jpg)

![connect_main_electronic_box_10](./images/build/frame/connect_main_electronic_box_10.jpg)

A longer brown wire was cut out to reach between **L** on the C14 connector and **13** on the emergency stop switch. The ends were stripped and twisted. A 4.8 mm spade connector was attached to the side connected to the C14 connector and a 6.3 mm space connector was attached to the side connected to the emergency stop switch. The spade connectors were then connected.

![connect_main_electronic_box_11](./images/build/frame/connect_main_electronic_box_11.jpg)

![connect_main_electronic_box_12](./images/build/frame/connect_main_electronic_box_12.jpg)

![connect_main_electronic_box_13](./images/build/frame/connect_main_electronic_box_13.jpg)

Two short and one longer blue wire were cut out at an appropriate length and the ends of the wires were stripped and twisted.

![connect_main_electronic_box_14](./images/build/frame/connect_main_electronic_box_14.jpg)

Two 4.8 mm spade connector were attached to one of the sides of each shorter wire and the other sides were inserted and locked into a 3-way Wago 221-413.

![connect_main_electronic_box_15](./images/build/frame/connect_main_electronic_box_15.jpg)

![connect_main_electronic_box_16](./images/build/frame/connect_main_electronic_box_16.jpg)

A 6.3 mm space connector was attached to one side of the longer blue wire and the other side were inserted and locked into the 3-way Wago 221-413.

I didn't have access to matching colors of all the spade connectors, so I followed the appropriate color scheme of the wires instead. So please ignore if there's a mismatch between the wire color and the spade connector color in the upcoming images.

![connect_main_electronic_box_17](./images/build/frame/connect_main_electronic_box_17.jpg)

The shorter blue wires were connected to **N** and **XX** on the C14 connector. The longer blue wire was connected to **23** on the emergency stop switch.

![connect_main_electronic_box_18](./images/build/frame/connect_main_electronic_box_18.jpg)

![connect_main_electronic_box_19](./images/build/frame/connect_main_electronic_box_19.jpg)

One brown and one blue wire were cut out to reach between the emergency stop switch and the power supply's input terminals. The ends of the wires were stripped and twisted. Two 6.3 mm space connectors were attached to one side of the wires and two ring terminals were attached to the other side. The blue wire's spade connector was connected to **24** on the emergency stop switch. The brown wire's spade connector was connected to **14** on the emergency stop switch.

![connect_main_electronic_box_20](./images/build/frame/connect_main_electronic_box_20.jpg)

![connect_main_electronic_box_21](./images/build/frame/connect_main_electronic_box_21.jpg)

![connect_main_electronic_box_22](./images/build/frame/connect_main_electronic_box_22.jpg)

A small green/yellow wire was cut out to reach between the C14 connector and the power supply's input terminals. The end of the wire was stripped and twisted, a 4.8 mm spade connector was attached to one side and a ring terminal was attached to the other side. The spade connector was then attached to **⏚** (ground) on the C14 connector.

![connect_main_electronic_box_23](./images/build/frame/connect_main_electronic_box_23.jpg)

![connect_main_electronic_box_24](./images/build/frame/connect_main_electronic_box_24.jpg)

The three ring terminals were then connected to the power supply's input terminals in the following way:

* Brown -> AC/L
* Blue -> AC/N
* Green/Yellow -> **⏚** (ground)

![connect_main_electronic_box_25](./images/build/frame/connect_main_electronic_box_25.jpg)

![connect_main_electronic_box_26](./images/build/frame/connect_main_electronic_box_26.jpg)

Power was connected to the C14 connector (read [this](#connect-main-electronic-box) note before connecting the power) and a multimeter was used to verify that the power supply outputted 12V. The multimeter was also used to verify that the C14 connector worked properly (cut power when using the switch) and that the emergency stop switch worked propertly (cut power when pushed. Also that it remains off when C14 connector is switched off and on again).

![connect_main_electronic_box_26](./images/build/frame/connect_main_electronic_box_24_1.jpg)

The emergency stop switch was attached to the front plate using two 20 mm M4 screws, two M4 nuts and two (9 mm, 4 mm, 1 mm) washers.

![connect_main_electronic_box_27](./images/build/frame/connect_main_electronic_box_27.jpg)

![connect_main_electronic_box_28](./images/build/frame/connect_main_electronic_box_28.jpg)

Shrink tubes were cut out at an appropriate length, one for each spade connector. Each spade connector was then temporarily removed and inserted into its shrink tube, before attached back again. The shrink tubes were then shrunk around all the spade connectors.

![connect_main_electronic_box_29](./images/build/frame/connect_main_electronic_box_29.jpg)

![connect_main_electronic_box_30](./images/build/frame/connect_main_electronic_box_30.jpg)

![connect_main_electronic_box_31](./images/build/frame/connect_main_electronic_box_31.jpg)

![connect_main_electronic_box_32](./images/build/frame/connect_main_electronic_box_32.jpg)

### Prepare power to steppers and connect fans and LED

To prepare the power for the stepper motors, one black and one red wire were cut out (approx. 300 mm long) to reach between the 12V terminals on the power supply and the small electronic box containing the Arduino and CNC shield. One side of each wire was then stripped and twisted, and ring terminals were attached. 

The red wire was connected to the **V+** and the black wire was connected to **V-**.

![connect_main_electronic_box_33](./images/build/frame/connect_main_electronic_box_33.jpg)

![connect_main_electronic_box_34](./images/build/frame/connect_main_electronic_box_34.jpg)

![connect_main_electronic_box_35](./images/build/frame/connect_main_electronic_box_35.jpg)

A 40x40 mm 12V fan was attached to the back side of the large electronic box's front panel, using 4 10 mm M3 screws. The fan was attached to blow air out of the box.

![attach_fans_led_1](./images/build/frame/attach_fans_led_1.jpg)

![attach_fans_led_2](./images/build/frame/attach_fans_led_2.jpg)

![attach_fans_led_3](./images/build/frame/attach_fans_led_3.jpg)

A 12V red LED was inserted into the small ~8 mm hole on the front of the large electronic box's front panel.

![attach_fans_led_4](./images/build/frame/attach_fans_led_4.jpg)

![attach_fans_led_5](./images/build/frame/attach_fans_led_5.jpg)

![attach_fans_led_6](./images/build/frame/attach_fans_led_6.jpg)

The second 40x40 mm 12V fan was attached to the back side of the small electronic box's front panel, using 4 10 mm M3 screws.

![attach_fans_led_7](./images/build/frame/attach_fans_led_7.jpg)

![attach_fans_led_8](./images/build/frame/attach_fans_led_8.jpg)

![attach_fans_led_9](./images/build/frame/attach_fans_led_9.jpg)

The loose wires of the two fans and the LED were stripped and twisted together, black together and red together. Then all three black wires were attached into the same ring terminal and all three red wires were attached into the same ring terminal.

![attach_fans_led_10](./images/build/frame/attach_fans_led_10.jpg)

![attach_fans_led_11](./images/build/frame/attach_fans_led_11.jpg)

![attach_fans_led_12](./images/build/frame/attach_fans_led_12.jpg)

The red wires were finally connected to the **V+** and the black wire was connected to **V-**.

![attach_fans_led_13](./images/build/frame/attach_fans_led_13.jpg)

The power was once more connected to the C14 connector (read [this](#connect-main-electronic-box) note before connecting the power) to verify that both fans were spinning and that the red LED was emitting light. 

### Install CNC software (grbl) on Arduino Uno

The software used in this project to control the CNC machine is called `grbl`. It's an open source and high performance g-code-parser and CNC milling controller that can run on a straight Arduino Uno. To be able to install the software on the Arduino, you will need a computer.

#### Install Arduino Software (IDE)
To be able to install `grbl` on the Arduino, the `Arduino Software (IDE)` needs to be installed on your computer. This program is used to upload code to the Arduino. Download the program from this website and follow the instructions: 

[https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

When starting the program, you should see something similar to this:

![install_software_1](./images/build/frame/install_software_1.jpg)

#### Install `grbl`
After installing the Arduino Software, the latest stable version of `grbl` was downloaded (as zip-format) from their official GitHub release page: 

[https://github.com/gnea/grbl/releases](https://github.com/gnea/grbl/releases)

After unzipping the file, you should see something similar to this in the folder:

![install_software_2](./images/build/frame/install_software_2.jpg)

Before `grbl` was loaded into the `Arduino Software (IDE)`, a minor adjustment had to be done to `grbl's` config file, `config.h`. The reason for this is because when `gbrl` released v1.1, it changed the pin used by the Z endstopper. If this isn't done, the Z endstopper won't be recognized by `grbl`. To tell `grbl` that we want to use the old way of accessing the Z endstopper, a specific variable in the `config.h` was commented out. 

The config `grbl/config.h` was opened in a text editor and the line were the variable `VARIABLE_SPINDLE` is set was commented out by adding two slashes (//) at the beginning of the line (see the last line):

```
// Enables variable spindle output voltage for different RPM values. On the Arduino Uno, the spindle
// enable pin will output 5V for maximum RPM with 256 intermediate levels and 0V when disabled.
// NOTE: IMPORTANT for Arduino Unos! When enabled, the Z-limit pin D11 and spindle enable pin D12 switch!
// The hardware PWM output on pin D11 is required for variable spindle output voltages.
// #define VARIABLE_SPINDLE // <-- THIS SHOULD BE COMMENTED OUT!!
```

Save `config.h`.

Now, open the `Arduino Software (IDE)` and click `Sketch > Include Library > Add .ZIP Library...` in the top menu:

![install_software_3](./images/build/frame/install_software_3.jpg)

You should see a pop-up similar to this:

![install_software_4](./images/build/frame/install_software_4.jpg)

Find the unzipped folder, open it and choose the folder `grbl`. After choosing the folder, you should see a text below the editor saying `Library added to your libraries. Check "Include library" menu`.

Next, connect the Arduino to your computer. It should fire up right away as it uses the computer as a power source.

![install_software_5](./images/build/frame/install_software_5.jpg)

![install_software_6](./images/build/frame/install_software_6.jpg)

![install_software_7](./images/build/frame/install_software_7.jpg)

To let the IDE know where to upload the software, we first need to set the correct serial port and board. To set the serial port, find the correct one under `Tools > Port > SOMETHINGSOMETHING (Arduino Uno)`.

![install_software_8](./images/build/frame/install_software_8.jpg)

To set the board, find "Arduino Uno" under `Tools > Board > Arduino Uno`.

![install_software_8_1](./images/build/frame/install_software_8_1.jpg)


To test if you've chosen the correct board and serial port, compile the template code by clicking on the check mark in the top left corner. When compiling is done, click the right-pointing arrow to upload the code to the Arduino. If successfull, you should see a text saying `Done uploading` below the editor.

![install_software_9](./images/build/frame/install_software_9.jpg)

![install_software_10](./images/build/frame/install_software_10.jpg)

It's now time to upload `grbl` to the Arduino. To do this, click `File > Open` in the top menu:

![install_software_11](./images/build/frame/install_software_11.jpg)

This should open a pop-up window. Find the downloaded folder and open `grbl/examples/grblUpload/grblUpload.ino`:

![install_software_12](./images/build/frame/install_software_12.jpg)

A new editor should pop-up:

![install_software_13](./images/build/frame/install_software_13.jpg)

Similar as before, compile the code by clicking on the check mark. When done, upload the code to the Arduino by clicking on the right-pointing arrow. This should only take a couple of seconds. `grbl` is now installed on the Arduino!


### Connect power to Arduino
