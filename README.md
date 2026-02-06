# NeRmo2

## Introduction
This project contains MuJoCo xml model files for NeRmo. 

`test.ipynb` (not finished) contains some information about the model, including:
* Minor revisions of legacy model
* Joints, sensors and actuators of the model

## Project structure
📦 project/
├── 📁 archive_t1_legs/                 # legacy leg structure
│   ├── 📄 front_leg_t1_exp.xml
│   ├── 📄 front_leg_t1_large.xml
│   ├── 📄 front_leg_t1_v1.xml
│   ├── 📄 front_leg_t1_v2.xml
│   ├── 📄 rear_leg_t1_exp.xml
│   ├── 📄 rear_leg_t1_v1.xml
│   └── 📄 rear_leg_t1_v2.xml
├── 📁 leg_fl_assets/                   # assets for front left leg 
│   ├── 📄 fl_asset_exp.xml             # joints and sites
│   ├── 📄 fl_sensor_actuator.xml       # sensors and actuators on joints
│   └── 📄 fl_tendon.xml                # useless, since current leg has no tendon
├── 📁 leg_fr_assets/
│   ├── 📄 fr_asset_exp.xml
│   ├── 📄 fr_sensor_actuator.xml
│   └── 📄 fr_tendon.xml
├── 📁 leg_rl_assets/
│   ├── 📄 rl_asset_exp.xml
│   ├── 📄 rl_sensor_actuator.xml
│   └── 📄 rl_tendon.xml
├── 📁 leg_rr_assets/
│   ├── 📄 rr_asset_exp.xml
│   ├── 📄 rr_sensor_actuator.xml
│   └── 📄 rr_tendon.xml
├── 📁 meshes_new_leg/                  # stl files for current leg
│   ├── 📄 foot.stl
│   ├── 📄 hip.stl
│   ├── 📄 servo_horn.stl
│   ├── 📄 thigh_down.stl
│   ├── 📄 thigh_up.stl
│   └── 📄 thigh_up_m.stl
├── 📁 mouse_stl/                       # stl files for current body
│   ├── 📄 actuator.stl
│   ├── 📄 actuator_frame.stl
│   ├── 📄 actuator_schraube.stl
│   ├── 📄 battery.stl
│   ├── 📄 battery_frame.stl
│   ├── 📄 board_down.stl
│   ├── 📄 board_mid.stl
│   ├── 📄 board_up.stl
│   ├── 📄 cam.stl
│   ├── 📄 cam_glass.stl
│   ├── 📄 head_fix.stl
│   ├── 📄 head_main.stl
│   ├── 📄 hip.stl
│   ├── 📄 neck_wing_orange.stl
│   ├── 📄 nose_black.stl
│   ├── 📄 pcb.stl
│   ├── 📄 pcb_assembly.stl
│   ├── 📄 pcb_board.stl
│   ├── 📄 pcb_mpu_grey.stl
│   ├── 🖼️ ref.png
│   ├── 🖼️ reflection.png
│   ├── 📄 schraube.stl
│   ├── 📄 schraube_leg_connect.stl
│   ├── 📄 schraube_small.stl
│   ├── 📄 spine.stl
│   ├── 📄 spine_actuator_pan.stl
│   ├── 📄 spine_actuator_pan_2.stl
│   ├── 📄 spine_front.stl
│   ├── 📄 tail_connect.stl
│   └── 🖼️ white_nylon.png
├── 📁 stl-meshes/                      # more stl files ...
│   ├── 📁 tail/
│   │   ├── 📄 servo_horn_tail.stl
│   │   ├── 📄 t1.stl
│   │   ├── 📄 t10.stl
│   │   ├── 📄 t11.stl
│   │   ├── 📄 t12.stl
│   │   ├── 📄 t13.stl
│   │   ├── 📄 t14.stl
│   │   ├── 📄 t15.stl
│   │   ├── 📄 t16.stl
│   │   ├── 📄 t17.stl
│   │   ├── 📄 t18.stl
│   │   ├── 📄 t19.stl
│   │   ├── 📄 t2.stl
│   │   ├── 📄 t3.stl
│   │   ├── 📄 t4.stl
│   │   ├── 📄 t5.stl
│   │   ├── 📄 t6.stl
│   │   ├── 📄 t7.stl
│   │   ├── 📄 t8.stl
│   │   ├── 📄 t9.stl
│   │   └── 📄 tail_main.stl
│   ├── 📄 fully_body_static_spine.stl
│   ├── 📄 head_bracket.stl
│   ├── 📄 head_main.stl
│   ├── 📄 hip.stl
│   ├── 📄 hip_zeroed.stl
│   ├── 📄 leg_fl_l1.stl
│   ├── 📄 leg_fl_l3.stl
│   ├── 📄 leg_fl_l4.stl
│   ├── 📄 leg_fr_l1.stl
│   ├── 📄 leg_fr_l3.stl
│   ├── 📄 leg_fr_l4.stl
│   ├── 📄 leg_rl_l1.stl
│   ├── 📄 leg_rl_l3.stl
│   ├── 📄 leg_rl_l4.stl
│   ├── 📄 leg_rr_l1.stl
│   ├── 📄 leg_rr_l3.stl
│   ├── 📄 leg_rr_l4.stl
│   ├── 📄 leg_servo_l.stl
│   ├── 📄 leg_servo_r.stl
│   ├── 📄 m2_horn.stl
│   ├── 📄 m2_rl.stl
│   ├── 📄 main_chest.stl
│   ├── 📄 main_l.stl
│   ├── 📄 main_rl.stl
│   ├── 📄 reel_small.stl
│   ├── 📄 spine_t1.stl
│   ├── 📄 spine_t1_zeroed.stl
│   ├── 📄 spine_t2.stl
│   ├── 📄 spine_t2_zeroed.stl
│   ├── 📄 spine_t3.stl
│   ├── 📄 spine_t3_zeroed.stl
│   ├── 📄 spine_t4.stl
│   ├── 📄 spine_t4_zeroed.stl
│   └── 📄 Tail_Unit.stl
├── 📁 tail_assets/                     # assets of tail
│   ├── 📄 tail.xml
│   ├── 📄 tail_new.xml                 # current structure in use
│   ├── 📄 tail_no_stl.xml
│   ├── 📄 tail_sensor_actuator.xml
│   ├── 📄 tail_stl_assets.xml
│   ├── 📄 tail_tendon.xml
│   └── 📄 tail_tendon_new.xml          # current file in use
├── 📁 test_environment/
│   ├── 📄 maze_path_tendon.xml
│   ├── 📄 maze_setup.xml
│   ├── 📄 straight_line.xml
│   ├── 📄 turn_test_2m.xml
│   └── 📄 turn_test_tendon.xml
├── 📎 .gitignore
├── 📄 basic_scene.xml
├── 📄 dynamic_4l.xml
├── 📄 left_leg_stl_assets.xml          # assets for left leg
├── 📖 README.md
├── 📄 right_leg_stl_assets.xml         # assets for right leg
└── 📄 test.ipynb


## Reference
[RL_Nermo](https://github.com/zhenshan-bing/RL_Nermo)
