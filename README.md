# How to build Ivan Miranda's CNC machine

This guide goes through all the steps of building Ivan Miranda's 3d-printed CNC machine and is a complement to Ivan's Youtube-videos:

1. Original video: [https://www.youtube.com/watch?v=_atw3e0nIrg](https://www.youtube.com/watch?v=_atw3e0nIrg)
2. Updates with geared stepper motors etc: [https://www.youtube.com/watch?v=qpjf5D3WngY](https://www.youtube.com/watch?v=qpjf5D3WngY)
3. Updating to metal parts: [https://www.youtube.com/watch?v=RDnGvhdGFEY](https://www.youtube.com/watch?v=RDnGvhdGFEY)

It follows the first and second video quite strict, while only using the added vertical beams from the third video.

## License
The following license is included when buying Ivan Miranda's blueprints of the CNC machine:

```
Everything that is in these files that I produced myself, apart from reselling the files, is allowed.
You can print and sell parts, sell machines, sell courses to build the machine. Modify the parts and post 
them for free, as long as you don’t sell the files and keep this license on everything you make with the 
files and credit me, we’re good. No DRM or anything, you are even allowed to repost the files as long as 
they’re kept free. Why buy this then? To support me and keep me encouraged to do more projects like this. 
```

Ivan does an amazing job putting these DIY builds together. I've posted his STL-files in this repository to simplify the build, but PLEASE buy his blueprints here: [https://ivanmiranda.com/products/3d-printed-cnc](https://ivanmiranda.com/products/3d-printed-cnc). It's only $25 and helps him to continue build and share his awesome projects.

## Parts
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

### 3d-printed parts
All the parts below needs to be 3d-printed. The tables include links to the STL-files.

#### Left side plates

| Item no. | Type                             | Amount | Image                                                                                            | STL link                                                                                                | Used for          |
|----------|----------------------------------|--------|--------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|-------------------|
| SP_001   | Left side plate                  | 1      | ![left_plate](./images/3dprinted_parts/side_plates/left/left_plate.jpg)                                           | [LEFT\_PLATE.stl](./stl_files/side_plates/left/LEFT_PLATE.stl)                                          | Lock bridge beams |
| SP_002   | Left side plate upper front clip | 1      | ![left_plate_upper_front_clip](./images/3dprinted_parts/side_plates/left/left_plate_upper_front_clip.jpg)         | [LEFT\_PLATE\_UPPER\_FRONT\_CLIP.stl](./stl_files/side_plates/left/LEFT_PLATE_UPPER_FRONT_CLIP.stl)     | Lock bridge beams |
| SP_003   | Left side plate lower front clip | 1      | ![left_plate_lower_front_clip](./images/3dprinted_parts/side_plates/left/left_plate_lower_front_clip.jpg)         | [LEFT\_PLATE\_LOWER\_FRONT\_CLIP.stl](./stl_files/side_plates/left/LEFT\_PLATE\_LOWER\_FRONT\_CLIP.stl) | Lock bridge beams |
| SP_004   | Left side plate back clip        | 1      | ![left_plate_back_plate_back_clip](./images/3dprinted_parts/side_plates/left/left_plate_back_plate_back_clip.jpg) | [LEFT\_PLATE\_BACK\_CLIP.stl](./stl_files/side_plates/left/LEFT_PLATE_BACK_CLIP.stl)                    | Lock bridge beams |

#### Right side plate

| Item no. | Type                              | Amount | Image                                                                                      | STL link                                                                                               | Used for          |
|----------|-----------------------------------|--------|--------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------|
| RP_001   | Right side plate                  | 1      | ![right_plate](./images/3dprinted_parts/side_plates/right/right_plate.jpg)                                   | [RIGHT\_PLATE.stl](./stl_files/side_plates/right/RIGHT_PLATE.stl)                                      | Lock bridge beams |
| RP_002   | Right side plate upper front clip | 1      | ![right_plate_upper_front_clip](./images/3dprinted_parts/side_plates/right/right_plate_upper_front_clip.jpg) | [RIGHT\_PLATE\_UPPER\_FRONT\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_UPPER_FRONT_CLIP.stl) | Lock bridge beams |
| RP_003   | Right side plate lower front clip | 1      | ![right_plate_lower_front_clip](./images/3dprinted_parts/side_plates/right/right_plate_lower_front_clip.jpg) | [RIGHT\_PLATE\_LOWER\_FRONT\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_LOWER_FRONT_CLIP.stl) | Lock bridge beams |
| RP_004   | Right plate back clip.jpg         | 1      | ![right_plate_back_plate_back_clip](./images/3dprinted_parts/side_plates/right/right_plate_back_clip.jpg)    | [RIGHT\_PLATE\_BACK\_CLIP.stl](./stl_files/side_plates/right/RIGHT_PLATE_BACK_CLIP.stl)                | Lock bridge beams |

#### Router

| Item no. | Type             | Amount | Image                                                              | STL link                                                          | Used for                    |
|----------|------------------|--------|--------------------------------------------------------------------|-------------------------------------------------------------------|-----------------------------|
| RO_001   | Carriage         | 1      | ![carriage](./images/3dprinted_parts/router/carriage.jpg)                 | [CARRIAGE.stl](./stl_files/router/CARRIAGE.stl)                   | Lock router in place        |
| RO_002   | Router bracket   | 1      | ![router_bracket](./images/3dprinted_parts/router/router_bracket.jpg)     | [ROUTER\_BRACKET.stl](./stl_files/router/ROUTER_BRACKET.stl)      | Lock router in place        |
| RO_003   | Vaccum funnel    | 1      | ![vaccum_funnel](./images/3dprinted_parts/router/vaccum_funnel.jpg)       | [VACUUM\_FUNNEL.stl](./stl_files/router/VACUUM_FUNNEL.stl)        | Lock vaccum close to router |
| RO_004   | Vertical slider  | 1      | ![vertical_slider](./images/3dprinted_parts/router/vertical_slider.jpg)   | [VERTICAL\_SLIDER.stl](./stl_files/router/VERTICAL\_SLIDER.stl)   | Vertical slider for router  |
| RO_005   | Z motor mount    | 1      | ![z_motor_mount](./images/3dprinted_parts/router/z_motor_mount.jpg)       | [Z\_MOTOR\_MOUNT.stl](./stl_files/router/Z_MOTOR_MOUNT.stl)       | Mount z motor to carriage   |
| RO_006   | Vaccum hose ring | 1      | ![vaccum_hose_ring](./images/3dprinted_parts/router/vaccum_hose_ring.jpg) | [VACUUM\_HOSE\_RING.stl](./stl_files/router/VACUUM_HOSE_RING.stl) | Lock vaccum to carriage     |

#### Belt tensioners

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

### Other parts
All the parts below needs to be bought or cut out.

#### Nuts

| Type    | Amount | Image                                  | Used for                               |
|---------|--------|----------------------------------------|----------------------------------------|
| M3 nuts | X      | ![m3_nuts](./images/parts/nuts_M3.jpg) | X                                      |
| M6 nuts | X      | ![m6_nuts](./images/parts/nuts_M6.jpg) | X                                      |
| M8 nuts | X      | ![m8_nuts](./images/parts/nuts_M8.jpg) | X                                      |

#### Screws

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

#### Washers

| Type            | Amount | Image                                                                    | Used for                               |
|-----------------|--------|--------------------------------------------------------------------------|----------------------------------------|
| M3              | X      | ![m3_washers](./images/parts/washers_M3.jpg)                             | X                                      |
| 10mm, 20mm, 2mm | X      | ![10_mm_20_mm_2_mm_washers](./images/parts/washers_10_mm_20_mm_2_mm.jpg) | X                                      |

#### Beams
All beams where cut out from 30mm x 30 mm (2 mm thick) aluminium profiles using a miter saw.

| Type              | Amount | Image                                                                  | Used for                               |
|-------------------|--------|------------------------------------------------------------------------|----------------------------------------|
| Vertical 80 mm    | 8      | ![beams_vertical_80_mm](./images/parts/beams_vertical_80_mm.jpg)       | X                                      |
| Front/Back 677 mm | 4      | ![beams_front_back_677_mm](./images/parts/beams_front_back_677_mm.jpg) | X                                      |
| Right/Left 900 mm | 4      | ![beams_right_left_900_mm](./images/parts/beams_right_left_900_mm.jpg) | X                                      |
| Bridge 803 mm     | 3      | ![beams_bridge_803_mm](./images/parts/beams_bridge_803_mm.jpg)         | X                                      |

#### Threaded rods

| Type      | Amount | Image                                                                | Used for                               |
|-----------|--------|----------------------------------------------------------------------|----------------------------------------|
| M5 140 mm | 2      | ![M5_140_mm_threaded_rod](./images/parts/threaded_rod_M5_140_mm.jpg) | Keep bridge beams together             |
| M8 12 mm  | 8      | ![M8_120_mm_threaded_rod](./images/parts/threaded_rod_M8_120_mm.jpg) | Keep upper and lower frames together   |
| M8 717 mm | 4      | ![M8_717_mm_threaded_rod](./images/parts/threaded_rod_M8_717_mm.jpg) | Keep frames together                   |

#### Others

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

## Build the CNC machine
This section covers how all the parts is put together to build the CNC machine. 

All the measurements, distances etc can be found in the main project Fusion 360 CAD design that is included when buying Ivan's blueprints. The blueprints can be bought here for just \$25: [https://ivanmiranda.com/products/3d-printed-cnc](https://ivanmiranda.com/products/3d-printed-cnc)

### Build the main frame

#### Cut out holes in the 900 mm profiles
The main frame consists of two separate frames, the lower and the upper frame. The two frames are keep everything together using threaded rods, washers and nuts. To enable the threaded rods to slide through the aluminium profiles, holes needed to be drilled.

First, a marker was used to indicate where all the holes were going. This was done by using a set square and a penn. A bradawl and a hammer were then used to make indentations at the center of the holes.

![holes_main_frame_1](./images/build/frame/holes_main_frame_1.jpg)

A 9 mm drill-bit and a bench drill was used to drill the holes.

![holes_main_frame_1](./images/build/frame/holes_main_frame_2.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_3.jpg)

To be able to access the nuts and tight them with a socket wrench, some holes (facing outwards) needed to be enlarged. This was done by first marking all the holes that should be enlarged.

![holes_main_frame_1](./images/build/frame/holes_main_frame_4.jpg)

A step drill was then used to enlarge the holes holes to 20 mm. A tip is to measure the size of your socket wrench and keep the holes as small as possible, while you're still able to tight the nuts. To be able to see which step you're aiming for on the step drill, attach a small piece of masking tape on the step above.

![holes_main_frame_1](./images/build/frame/holes_main_frame_5.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_6.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_7.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_8.jpg)

Smooth out the rought edges with a round metal file.

![holes_main_frame_1](./images/build/frame/holes_main_frame_9.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_10.jpg)

![holes_main_frame_1](./images/build/frame/holes_main_frame_11.jpg)

#### Attach rails to 900 mm profiles

Before the upper and lower frames were assembled, two 600 mm rails were attached to the longer 900 mm aluminium profiles of the upper frame. They need to be attached to the sides facing outwards and be attached above the three vertical beams (connecting the lower and upper frame). A tip is to place all the profiles as they should go to make sure that you're attaching the rails to the correct faces (see the red boxes on the below image).

![rails_main_frame_1](./images/build/frame/rails_main_frame_1.jpg)

![rails_main_frame_0](./images/build/frame/rails_main_frame_0.jpg)

Three 3d-printed support tools were used to center the rails on the profiles. A 57 mm wood block were cut out and used to attach the rails at the same distance from the ends. The rails were then clamped to the profiles.

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

#### Assemble upper and lower frames

The frames were interlocked using the longer 717 mm M8 threaded rods, (10mm, 20mm, 2mm) washers and M8 lock nuts.

The profiles were first placed in their correct place and clamps were used to keep the profiles aligned. I used jointed spanner to lock everything in place, but you can also use two socket wrenches. Just make sure that the bits fit into the drilled holes.

![assemble_frames_1](./images/build/frame/assemble_frames_1.jpg)

![assemble_frames_3](./images/build/frame/assemble_frames_3.jpg)

![assemble_frames_2](./images/build/frame/assemble_frames_2.jpg)

![assemble_frames_4](./images/build/frame/assemble_frames_4.jpg)

![assemble_frames_5](./images/build/frame/assemble_frames_5.jpg)

![assemble_frames_6](./images/build/frame/assemble_frames_6.jpg)

![assemble_frames_7](./images/build/frame/assemble_frames_7.jpg)

#### Interlock upper and lower frames

All the aluminium profiles were first placed in their correct place. The horizontal aluminium bridge beams and clamps were then used to align the frames on top of each other.

![assemble_frames_9](./images/build/frame/assemble_frames_9.jpg)

![assemble_frames_10](./images/build/frame/assemble_frames_10.jpg)

The 120 mm M8 threaded rods, (10mm, 20mm, 2mm) washers and M8 lock nuts were then used to interlock the upper and lower frames, with the 80 mm vertical aluminium profiles in between.

![assemble_frames_8](./images/build/frame/assemble_frames_8.jpg)

![assemble_frames_12](./images/build/frame/assemble_frames_12.jpg)

![assemble_frames_11](./images/build/frame/assemble_frames_11.jpg)

![assemble_frames_13](./images/build/frame/assemble_frames_13.jpg)

#### Attach side plates

![assemble_side_plates_1](./images/build/frame/assemble_side_plates_1.jpg)

![assemble_side_plates_2](./images/build/frame/assemble_side_plates_2.jpg)

![assemble_side_plates_3](./images/build/frame/assemble_side_plates_3.jpg)

![assemble_side_plates_4](./images/build/frame/assemble_side_plates_4.jpg)

![assemble_side_plates_5](./images/build/frame/assemble_side_plates_5.jpg)

![assemble_side_plates_6](./images/build/frame/assemble_side_plates_6.jpg)

![assemble_side_plates_7](./images/build/frame/assemble_side_plates_7.jpg)

![assemble_side_plates_8](./images/build/frame/assemble_side_plates_8.jpg)

#### Attach motors on side plate

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_1.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_2.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_3.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_4.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_5.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_6.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_7.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_8.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_9.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_10.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_11.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_12.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_13.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_14.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_15.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_16.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_17.jpg)

![attach_side_plate_motors_1](./images/build/frame/attach_side_plate_motors_18.jpg)

#### Attach tensioners and belt

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

![attach_tensioners_and_belts_12](./images/build/frame/attach_tensioners_and_belts_12.jpg)

![attach_tensioners_and_belts_13](./images/build/frame/attach_tensioners_and_belts_13.jpg)

![attach_tensioners_and_belts_14](./images/build/frame/attach_tensioners_and_belts_14.jpg)

![attach_tensioners_and_belts_15](./images/build/frame/attach_tensioners_and_belts_15.jpg)

![attach_tensioners_and_belts_16](./images/build/frame/attach_tensioners_and_belts_16.jpg)

![attach_tensioners_and_belts_17](./images/build/frame/attach_tensioners_and_belts_17.jpg)

![attach_tensioners_and_belts_18](./images/build/frame/attach_tensioners_and_belts_18.jpg)

![attach_tensioners_and_belts_19](./images/build/frame/attach_tensioners_and_belts_19.jpg)

![attach_tensioners_and_belts_20](./images/build/frame/attach_tensioners_and_belts_20.jpg)

![attach_tensioners_and_belts_21](./images/build/frame/attach_tensioners_and_belts_21.jpg)

![attach_tensioners_and_belts_22](./images/build/frame/attach_tensioners_and_belts_22.jpg)

![attach_tensioners_and_belts_23](./images/build/frame/attach_tensioners_and_belts_23.jpg)

![attach_tensioners_and_belts_24](./images/build/frame/attach_tensioners_and_belts_24.jpg)

![attach_tensioners_and_belts_25](./images/build/frame/attach_tensioners_and_belts_25.jpg)

![attach_tensioners_and_belts_26](./images/build/frame/attach_tensioners_and_belts_26.jpg)

![attach_tensioners_and_belts_27](./images/build/frame/attach_tensioners_and_belts_27.jpg)

![attach_tensioners_and_belts_28](./images/build/frame/attach_tensioners_and_belts_28.jpg)

![attach_tensioners_and_belts_29](./images/build/frame/attach_tensioners_and_belts_29.jpg)

![attach_tensioners_and_belts_30](./images/build/frame/attach_tensioners_and_belts_30.jpg)

![attach_tensioners_and_belts_31](./images/build/frame/attach_tensioners_and_belts_31.jpg)

![attach_tensioners_and_belts_32](./images/build/frame/attach_tensioners_and_belts_32.jpg)

![attach_tensioners_and_belts_33](./images/build/frame/attach_tensioners_and_belts_33.jpg)

![attach_tensioners_and_belts_34](./images/build/frame/attach_tensioners_and_belts_34.jpg)

![attach_tensioners_and_belts_35](./images/build/frame/attach_tensioners_and_belts_35.jpg)

![attach_tensioners_and_belts_36](./images/build/frame/attach_tensioners_and_belts_36.jpg)

![attach_tensioners_and_belts_37](./images/build/frame/attach_tensioners_and_belts_37.jpg)

![attach_tensioners_and_belts_38](./images/build/frame/attach_tensioners_and_belts_38.jpg)

![attach_tensioners_and_belts_39](./images/build/frame/attach_tensioners_and_belts_39.jpg)

![attach_tensioners_and_belts_40](./images/build/frame/attach_tensioners_and_belts_40.jpg)

![attach_tensioners_and_belts_41](./images/build/frame/attach_tensioners_and_belts_41.jpg)

#### Attach rails to beams

![attach_rails_to_beams_1](./images/build/frame/attach_rails_to_beams_1.jpg)

![attach_rails_to_beams_2](./images/build/frame/attach_rails_to_beams_2.jpg)

![attach_rails_to_beams_3](./images/build/frame/attach_rails_to_beams_3.jpg)

![attach_rails_to_beams_4](./images/build/frame/attach_rails_to_beams_4.jpg)

![attach_rails_to_beams_5](./images/build/frame/attach_rails_to_beams_5.jpg)

![attach_rails_to_beams_6](./images/build/frame/attach_rails_to_beams_6.jpg)

![attach_rails_to_beams_7](./images/build/frame/attach_rails_to_beams_7.jpg)

![attach_rails_to_beams_8](./images/build/frame/attach_rails_to_beams_8.jpg)

![attach_rails_to_beams_9](./images/build/frame/attach_rails_to_beams_9.jpg)

![attach_rails_to_beams_10](./images/build/frame/attach_rails_to_beams_10.jpg)

![attach_rails_to_beams_11](./images/build/frame/attach_rails_to_beams_11.jpg)

![attach_rails_to_beams_12](./images/build/frame/attach_rails_to_beams_12.jpg)

![attach_rails_to_beams_13](./images/build/frame/attach_rails_to_beams_13.jpg)

![attach_rails_to_beams_14](./images/build/frame/attach_rails_to_beams_14.jpg)

![attach_rails_to_beams_15](./images/build/frame/attach_rails_to_beams_15.jpg)

#### Attach tensioners to beams

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


#### Attach beams to side plates

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_1.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_2.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_3.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_4.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_5.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_6.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_7.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_8.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_9.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_10.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_11.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_12.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_13.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_14.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_15.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_16.jpg)

![attach_beams_to_side_plates_1](./images/build/frame/attach_beams_to_side_plates_17.jpg)


#### Attach bearings, acme nut and rails to carriage

![assemble_carriage_1](./images/build/frame/assemble_carriage_1.jpg)

![assemble_carriage_2](./images/build/frame/assemble_carriage_2.jpg)

![assemble_carriage_3](./images/build/frame/assemble_carriage_3.jpg)

![assemble_carriage_4](./images/build/frame/assemble_carriage_4.jpg)

![assemble_carriage_5](./images/build/frame/assemble_carriage_5.jpg)

![assemble_carriage_6](./images/build/frame/assemble_carriage_6.jpg)

![assemble_carriage_7](./images/build/frame/assemble_carriage_7.jpg)

![assemble_carriage_8](./images/build/frame/assemble_carriage_8.jpg)

![assemble_carriage_9](./images/build/frame/assemble_carriage_9.jpg)

![assemble_carriage_10](./images/build/frame/assemble_carriage_10.jpg)

![assemble_carriage_11](./images/build/frame/assemble_carriage_11.jpg)

![assemble_carriage_12](./images/build/frame/assemble_carriage_12.jpg)

![assemble_carriage_13](./images/build/frame/assemble_carriage_13.jpg)

#### Attach acme rod and blocks

![assemble_carriage_14](./images/build/frame/assemble_carriage_14.jpg)

![assemble_carriage_15](./images/build/frame/assemble_carriage_15.jpg)

![assemble_carriage_16](./images/build/frame/assemble_carriage_16.jpg)

![assemble_carriage_17](./images/build/frame/assemble_carriage_17.jpg)

![assemble_carriage_18](./images/build/frame/assemble_carriage_18.jpg)

![assemble_carriage_19](./images/build/frame/assemble_carriage_19.jpg)

![assemble_carriage_20](./images/build/frame/assemble_carriage_20.jpg)

![assemble_carriage_21](./images/build/frame/assemble_carriage_21.jpg)

#### Attach Z motor mount and X axis cable chain

![assemble_carriage_22](./images/build/frame/assemble_carriage_22.jpg)

![assemble_carriage_23](./images/build/frame/assemble_carriage_23.jpg)

![assemble_carriage_24](./images/build/frame/assemble_carriage_24.jpg)

![assemble_carriage_25](./images/build/frame/assemble_carriage_25.jpg)

![assemble_carriage_26](./images/build/frame/assemble_carriage_26.jpg)

![assemble_carriage_27](./images/build/frame/assemble_carriage_27.jpg)

![assemble_carriage_28](./images/build/frame/assemble_carriage_28.jpg)

![assemble_carriage_29](./images/build/frame/assemble_carriage_29.jpg)

![assemble_carriage_30](./images/build/frame/assemble_carriage_30.jpg)

![assemble_carriage_31](./images/build/frame/assemble_carriage_31.jpg)

![assemble_carriage_32](./images/build/frame/assemble_carriage_32.jpg)

![assemble_carriage_33](./images/build/frame/assemble_carriage_33.jpg)

![assemble_carriage_34](./images/build/frame/assemble_carriage_34.jpg)

![assemble_carriage_35](./images/build/frame/assemble_carriage_35.jpg)

![assemble_carriage_36](./images/build/frame/assemble_carriage_36.jpg)

![assemble_carriage_37](./images/build/frame/assemble_carriage_37.jpg)

![assemble_carriage_38](./images/build/frame/assemble_carriage_38.jpg)

![assemble_carriage_39](./images/build/frame/assemble_carriage_39.jpg)

![assemble_carriage_39](./images/build/frame/assemble_carriage_39_0.jpg)

![assemble_carriage_40](./images/build/frame/assemble_carriage_40.jpg)

![assemble_carriage_41](./images/build/frame/assemble_carriage_41.jpg)

![assemble_carriage_42](./images/build/frame/assemble_carriage_42.jpg)

![assemble_carriage_43](./images/build/frame/assemble_carriage_43.jpg)

![assemble_carriage_44](./images/build/frame/assemble_carriage_44.jpg)

![assemble_carriage_45](./images/build/frame/assemble_carriage_45.jpg)

![assemble_carriage_46](./images/build/frame/assemble_carriage_46.jpg)

![assemble_carriage_47](./images/build/frame/assemble_carriage_47.jpg)

![assemble_carriage_48](./images/build/frame/assemble_carriage_48.jpg)

![assemble_carriage_49](./images/build/frame/assemble_carriage_49.jpg)

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

![assemble_carriage_61](./images/build/frame/assemble_carriage_61.jpg)
