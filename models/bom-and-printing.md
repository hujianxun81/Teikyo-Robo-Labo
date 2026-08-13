# Bill of Materials & Printing

## 1. Purchased parts

CAD for every item below lives in `vendor-models/`. The **Mounted on** column says where each one ends up on the car.

### Chassis

| Part | Qty | Model / SKU | CAD file | Mounted on | Link |
|---|---|---|---|---|---|
| Motor | 1 | Hobbywing QuicRun Fusion Pro Elite | `motor-quicrun-fusion-pro.step` | Chassis | https://www.hobbywing.com/en/products/quicrun-fusion-pro-elite |
| Steering servo | 1 | YANTRS 0427 AS-MGX-E | `servo-as-mgx-e.step` | Chassis, ahead of front axle | https://yantrs.cn/products/yantrs-helical-1-8-1-10-rc-40kg-climbing-car-racing-car-high-torque-waterproof-brushless-servo-%E7%9A%84%E5%89%AF%E6%9C%AC |
| Battery | 1 | FULLYMAX 3S 11.1 V 1000 mAh 70C | `battery-3s-1000mah.step` | Chassis, battery bay | https://www.fullymaxbattery.com/china-3s-1000mah-lipo-battery-11-1v-70c-fpv-drone-helicopter-rc-model-battery-for-rc-car-35910738.html |
| Power switch board | 1 | MOSFET high-current switch | `power-switch-board.step` | Chassis | https://item.taobao.com/item.htm?id=761933378076&mi_id=0000alAN-XYrRSmAFEfxlQoHM2mqXHMpbJpDYXINHWatipE&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |
| Y harness | 1 | Parallel battery lead | `y-harness.step` | Chassis, Power switch board | https://detail.tmall.com/item.htm?id=40903043930&mi_id=00002qwayTatY_29CtMr2TTscj7L_Z29epVH1KwdpRxt85A&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj&skuId=4281671717614 |
| Front wheels | 2 | Losi LOS41049 | `wheel-front-los41049.step` | Front axle | https://www.losi.com/product/losi-wide-body-rib-front-mounted-tires-white-2-mini-b/LOS41049.html |
| Rear wheels | 2 | Losi LOS41017 | `wheel-rear-los41017.step` | Rear axle | https://www.losi.com/product/losi-taper-pin-fr-mounted-white-2-mini-b/LOS41017.html |

### Tier 2

| Part | Qty | Model / SKU | CAD file | Mounted on | Link |
|---|---|---|---|---|---|
| LiDAR | 1 | YDLIDAR 4ROS | `lidar-ydlidar-4ros.step` | Tier 2 deck | https://category.yahboom.net/products/ydlidar-4ros?srsltid=AfmBOoo2HZNwg6TdYKnXCDHRvT45DeGlSHpiZdEB1jrmj9uY1cf8DHAe |
| DC-DC converter | 1 | GODSEND GOD60-18S12B3R2-TS | `dcdc-god60.step` | Tier 2 deck | https://item.taobao.com/item.htm?id=521952280662&mi_id=0000ib9_cBgtVdxzw1rIUO0q0MgNP1V0pMRXQ4xXKIFxrkU&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |
| Cooling fan | 1 | FB Cr03 | `fan-fb-cr03.step` | Tier 2 deck, no fan mount | https://detail.tmall.com/item.htm?id=777437560260&mi_id=0000uskYcyfIi_wGhHkCKC-jiQb8M3dy7pPehpBIqbLHju0&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |

### Tier 3

| Part | Qty | Model / SKU | CAD file | Mounted on | Link |
|---|---|---|---|---|---|
| SBC (host) | 1 | NVIDIA Jetson Orin Nano Super | `sbc-jetson-orin-nano-super.step` | Tier 3 deck | https://www.hzhytech.com/AI-product/pd_232 |
| MCU board | 1 | Yahboom ROS Control Board V3.0 | `mcu-yahboom-ros-v3.step` | Tier 3, on camera mount | https://category.yahboom.net/collections/stm32/products/ros-driver-board |
| Depth camera | 1 | ORBBEC Gemini 336L | `depth-camera-gemini-336l.step` | Tier 3, on camera mount | https://www.orbbec.com/products/stereo-vision-camera/gemini-336l/ |
| USB hub | 1 | MixedSignal Lab SmartUSBHub 4CH | `usb-hub-4ch.step` | Tier 3 deck, front | https://item.taobao.com/item.htm?id=687666588208&mi_id=0000AQjDHCJD3i6aUUdQFNH-HVYHG1cEr1cQ-O5BXWzUMdk&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |
| LiDAR UART bridge | 1 | Silicon Labs CP210x | `uart-bridge-cp210x.step` | Tier 3 deck, bottom | https://item.taobao.com/item.htm?id=521952280662&mi_id=0000ib9_cBgtVdxzw1rIUO0q0MgNP1V0pMRXQ4xXKIFxrkU&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |

### Tier 2–3 interconnect brackets

| Part | Qty | Model / SKU | CAD file | Mounted on | Link |
|---|---|---|---|---|---|
| Display | 1 | DFRobot DFR0486 | `display-dfr0486.step` | Display mount | https://www.dfrobot.com/product-1576.html |
| Button | 1 | DFRobot DFR0991 | `button-dfr0991.step` | Button + ToF mount | https://www.dfrobot.com/product-2634.html |
| ToF rangefinder | 1 | DFRobot SEN0628 | `tof-sensor-sen0628.step` | Button + ToF mount | https://www.dfrobot.com/product-2999.html |
| Main switch | 1 | Zave KND-1-DF007-R2 | `power-switch-knd1.step` | Switch + voltmeter mount | https://detail.tmall.com/item.htm?id=825164395808&mi_id=0000xCIGe_TRUi4g2JMwBJvc6YGcwi-hVw9EwjE5p3OEmO0&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |
| Voltmeter | 1 | CEDAR OLED micro voltmeter | `voltmeter-oled.step` | Switch + voltmeter mount | https://item.taobao.com/item.htm?id=1010575171136&mi_id=0000SFygwo6W1HUDgC8PwKaxZ0DQlemV6nqgqU2O0H455R8&spm=tbpc.boughtlist.suborder_itemtitle.1.13112e8dTJKrkj |

### Bearings & fasteners

| Part | Qty | Spec | Used in | Link |
|---|---|---|---|---|
| Bearing | 2 | MR117ZZ, ⌀11 × 7 × 3 mm | Rear axle carriers, inner | https://www.amazon.co.jp/dp/B07ZPVT411?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1 |
| Bearing | 2 | MR74ZZ, ⌀7 × 4 × 2.5 mm | Rear axle carriers, outer | https://www.amazon.co.jp/dp/B07NXPL9GL?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1 |
| Bearing | 4 | MR74ZZ, ⌀7 × 4 × 2.5 mm | Steering knuckles, 2 each | https://www.amazon.co.jp/dp/B07NXPL9GL?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1 |
| Screws | — | M3 | Throughout | https://www.amazon.co.jp/dp/B0742DDLQ1?ref=ppx_yo2ov_dt_b_fed_asin_title |

---

## 2. Printing

### 2.1 Profiles

|                           | PETG (verification)                        | PA12-CF (final)                      |
| ------------------------- | ------------------------------------------ | ------------------------------------ |
| Filament                  | Inslogic PETG Pro                          | Inslogic PA12-CF                     |
| Nozzle diameter           | 0.4 mm, Tungsten Carbide Nozzle, High Flow | **0.6 mm, hardened steel, Standard** |
| Layer height              | 0.2 mm                                     | 0.3 mm                               |
| Walls                     | 3                                          | **2**                                |
| Top / bottom solid layers | 6 / 6                                      | **4 / 4**                            |
| Infill                    | 15–20 % gyroid                             | 15–20 % gyroid                       |
| Nozzle temp               | 240 °C                                     | **270 °C** (first layer 275 °C)      |
| Bed temp                  | 65 °C (Texture PEI Plate)                  | **90 °C** (Engineering Plate)        |
| Chamber                   | —                                          | **50 °C, exhaust fan OFF**           |
| Max volumetric speed      | default                                    | **8 mm³/s** (≈ 43 mm/s effective)    |

Wall counts differ because the nozzle does: 3 × 0.42 mm ≈ 2 × 0.62 mm ≈ 1.25 mm of wall either way; Same for the solid layers: 6 × 0.2 = 4 × 0.3 = 1.2 mm of skin.

Do not raise infill above ~20 % on flat plates. Bending stiffness comes from the top and bottom skins; at 4 mm thickness the core contributes under 0.5 %. Add solid layers instead — lighter and stiffer per gram.

PA12-CF is roughly twice the flexural modulus of PETG at 83 % the density, so a plate can be about 20 % thinner for the same stiffness (4.0 mm PETG ≈ 3.2 mm PA12-CF, and 34 % lighter).

### 2.2 PA12-CF setup

Getting this material to stick took several attempts. All of the following matter:

| Step             | Detail                                                       |
| ---------------- | ------------------------------------------------------------ |
| Dry the filament | 85 °C for 12 h **before** printing, then keep it in the dryer and feed through PTFE. Drying while printing does not remove water, it only maintains. |
| Wash the plate   | Use Isopropyl alcohol to remove finger oil from the textured surface. |
| Glue             | Preheat plate to 60 °C, apply Magigoo PA thinly, let it dry to a film. |
| Bed temperature  | **90 °C** on the Engineering Plate. The 60–70 °C in the TDS assumes a Textured PEI Plate; the Engineering Plate is designed for a higher range and adheres poorly at 65 °C. |
| Chamber          | 50 °C, and make sure the chamber exhaust fan is off or it defeats the heater. |
| Brim             | 8 mm outer brim, **gap 0**. A gap means the brim is not anchoring anything. 5 mm is enough for small parts. |

Other slicer settings that were needed:

| Setting                             | Value                                                      | Why                                                          |
| ----------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------ |
| Part cooling fan                    | 0 % on normal layers                                       | Cooling is what causes warping in nylon                      |
| Overhang / bridge fan               | 40 %                                                       | Needed so top skins don't sag into the infill                |
| Cooling overhang threshold          | 50 %                                                       | At 0 % it flags ordinary outer walls as overhangs and blows on them |
| First layer speed                   | 20 mm/s (infill 30 mm/s)                                   | Only speed that isn't capped by the volumetric limit, and it drives adhesion |
| Acceleration                        | normal 3000, outer wall 2000, travel 5000, first layer 500 | High acceleration knocks marginally-attached parts loose     |
| First layer line width              | 0.68 mm                                                    | More contact area with the plate                             |
| Elephant foot compensation          | 0                                                          | It shrinks the first layer, which is the opposite of what we want |
| **Auto circular hole compensation** | **OFF**                                                    | Would silently resize every bore and invalidate the calibration below |
| **X-Y size compensation**           | **0**                                                      | Same reason                                                  |
| Seam position                       | Random on structural parts                                 | Aligned seams stack into a vertical weak line                |

The purge line at the front of the plate is disabled — the `G130 ... L40 E12 D4` line in the machine start G-code is commented out. It was being dragged into the part. Safe to disable because every part is printed with a brim, so any under-extrusion at the start lands on the brim. Re-check this after a Bambu Studio update.

### 2.3 Per-part orientation

| Part                           | Orientation                | Notes                                                        |
| ------------------------------ | -------------------------- | ------------------------------------------------------------ |
| `rear-axle-carrier-left/right` | Wall-plate face down       | Bearing bore axis vertical → round bore. 3 walls locally: the MR117 seat wall is only ~1.3 mm |
| `steering-knuckle-left/right`  | Bearing bore axis vertical | Matches the fit gauge orientation                            |
| `steering-deck-lower/upper`    | Flat                       | Integral ball sockets at both ends                           |

### 2.4 Fit calibration

**Re-run the gauges whenever the material *or* the nozzle diameter changes.** The offset
below is not material shrinkage — it is nearly constant across bore sizes, which means it
comes mostly from extrusion width.

| Feature                 | Nominal | PETG @0.4 | PA12-CF @0.6 |
| ----------------------- | ------- | --------- | ------------ |
| MR117ZZ seat            | ⌀11.00  | 11.10     | **11.40**    |
| MR74ZZ seat             | ⌀7.00   | 7.10      | **7.40**     |
| Ball socket (ball ⌀4.8) | —       | 5.00      | **5.45**     |

Gauges: `cad/test-coupons/bearing-fit-gauge-*.step`, `rod-end-fit-gauge-*.step`

Notes:

- Every bearing seat gets a **0.4–0.5 mm × 45° lead-in chamfer**. Without it the bearing has to be driven in with a hammer.
- Bearing shoulders stay square. No fillet, or the bearing will not seat flat.
- **Spherical cavities need about 0.15 mm more compensation than a cylindrical bore of the same size** (0.45 vs 0.30 here). The upper hemisphere is an unsupported dome that droops inward as it prints. Apply this to any ball socket, not just rod ends.
