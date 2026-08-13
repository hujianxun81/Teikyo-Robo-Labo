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

### 2.1 Default settings

| | Value |
|---|---|
| Material | Inslogic PETG Pro (verification) → Inslogic PA12-CF (final) |
| Walls | 3 → 2 |
| Top / bottom solid layers | 6 → 4 each |
| Infill | 15–20 %, gyroid |

Do not raise infill above ~20 % on flat plates. Stiffness in bending comes from the top and bottom skins — add solid layers instead, it is lighter and stiffer.

PA12-CF must be dried before printing.

### 2.2 Per-part orientation

| Part | Orientation on bed | Notes |
|---|---|---|
| `rear-axle-carrier-left/right.step` | Wall-plate face down | Bearing bore axis vertical → round bore |
| `steering-knuckle-left/right.step` | Bearing bore axis vertical | Matches the fit gauge |
| `steering-deck-lower/upper.step` | Donut lying flat | Relief slot must flex in-plane |

Parts with thin walls around a press fit (e.g. the MR117 seat) should get 3–4 walls locally instead of 2.

### 2.3 Bearing bores

Calibrated with `cad/test-coupons/bearing-fit-gauge.step` on this printer.
Re-run the gauge if the printer, nozzle, or filament changes.

| Bearing | Nominal OD | Bore in model | Lead-in chamfer |
|---|---|---|---|
| MR117ZZ | 11.00 mm | **⌀11.10** | 0.4–0.5 mm × 45° |
| MR74ZZ | 7.00 mm | **⌀7.10** | 0.4–0.5 mm × 45° |

Without the chamfer the bearing has to be hammered in. Shoulders stay square — no fillet, or the bearing will not seat flat.

### 2.4 Rod ends

Ball ⌀4.8 mm, stud ⌀2.7 mm. Socket clearance calibrated with `cad/test-coupons/rod-end-fit-gauge.step`.

| Socket bore | Fit | Use |
|---|---|---|
| ⌀5.0 | Press fit, smooth rotation | Default |
| ⌀5.1 | Easier fit, still retains | Positions removed often |
