- 0.2.0-220 RC1
- 0.2.2-225 [attempt] dyn lpf fix
- 0.2.3-226 smart dterm smoothing [added]
- 0.2.3-227 osd issue fix
- 0.2.4-228 minor dterm smoothing improvement marinus suggestion
- 0.2.5-229 [acro-mode worked] adding witchcraft from raceflight
- 0.2.6-230 full PID controller for the level code (preliminary)
- 0.2.6-231 fix dterm for angle
- 0.2.6-232 adding horizon code in the settings
- 0.2.7-233 separate witchcraft per axis
- 0.2.8-234 changing the mixer for brushed quads
- 0.2.9-237 dual pids on level mode (like silverware does it)
- 0.2.10-238  adding FF to the angle code
- 0.2.11-239  adding beebrain_lite target and feedforward in angle change
- 0.2.12-240  removing dyn gyro adding spi_sfhss
- 0.2.12-241  fixing horizon mode to work with the new angle code
- 0.2.12-242  Merge branch 'loutwice_test' into Main
- 0.2.12-243  support for NewBeeDrone FC
- 0.2.12-252  Merge pull request #70 from Olaf-FPV/Main (180 degree arm)
- 0.2.12-258  external i
- 0.2.12-259  Merge pull request #70 from Olaf-FPV/Main
- 0.2.13-244  cinematic_setpoint (fix angle ff value (multiplier was way to high))
- 0.2.13-245  fixing code from NBD to support other targets
- 0.2.13-264  Adding Target MadChiller/KaioPride
- 0.2.13-265  Update target.h MadChiller/KaioPride
- 0.2.13-266  Update target.h MadChiller/KaioPride
- 0.2.14-246  update to cinematic setpoint/f angle
- 0.2.15-247  fixing horizon properly this time, making cinematic setpoint a set value
- 0.2.16-248  update horizon mode, update kalman, update acc update rate
- 0.2.17-249  make Dshot 600 default
- 0.2.18-250  [Acro-Mode fixed] 2.17 combine gyro and acc
- 0.2.20-253  0.2.20 revert the complimentary filter [0.2.20](https://github.com/emuflight/EmuFlight/commit/856650e558a123e633912732f29d5554364574a1)
- 0.2.21-254  0.2.21 slight change to dterm calc (like the old days) [0.2.21](https://github.com/emuflight/EmuFlight/commit/219a6a3f53e29a267063ae7877fd49774899d0de)
- 0.2.22-255  update FF to use the iDT instead of pidfrequency [0.2.22](https://github.com/emuflight/EmuFlight/commit/359e767e7d6cd279bc63e5db364b7f4c62a8db25)
- 0.2.23-256  [Known good] spa per axis, acrotrainer removed [0.2.23](https://github.com/emuflight/EmuFlight/commit/8db96683dc3ad0c3a4e9bb421139975c66577e5f)
- 0.2.24-260  [experimental/bug] 0.2.24 (added a min/max motor change) (first w/ 1.44msp number but no msp change)
- 0.2.25-261  [experimental iTerm Calcs v1]
- 0.2.26-262  [experimental iTerm Calcs v2 / fixed bug, but horrible drift] 0.2.26
- 0.2.27-263  [revert iTerm Calcs] 0.2.27 fix the dang bugs
- 0.2.28-267  0.2.28 gyro average filter added [works on helio] ["GyroCraft"]
- 0.2.28-268  0.2.29 getting all filters to work with helio fc [not working helio]
- 0.2.29-269  [gyro average filter, helio, but not working] Update version.h
- 0.2.30-270  Added: LPF per axis, dterm lpf2, smart_dterm_smooth per axis, remove yaw lpf, remove dterm notch
- 0.2.30-271  fixing silly targets
- 0.2.31-272  QuickFlash is an idiot helio works on this (2020 Feb 08)
- 0.2.32-273  Removed r_weight, made static; removed the motor min/max changes; added sharpness for helio imuf. first  w/ v2fonts.
- 0.2.33-274  better defaults smart_dterm_yaw=0, witchcraft_yaw=0 [0.2.33](https://github.com/emuflight/EmuFlight/commit/ae4b3901d0002ecd17c2eb8cce1f4fdc07e2953c)
- 0.2.34-275  increasing max value for IMUF Sharpness as well as imuf 227 [0.2.34](https://github.com/emuflight/EmuFlight/commit/dbfca3c25c022d1e71c234cc88a2b37393bca2f5)
- 0.2.35-276  msp updates, change to vbat pid compensation, now it only effects pterm [0.2.35](https://github.com/emuflight/EmuFlight/commit/4e9f735e95b8da62fa2fd519def32716b7a06ff4)
- 0.2.36-278 Make angle mode better. [0.2.36 ](https://github.com/emuflight/EmuFlight/commit/3a1e2c391a2e17ebe7733f03175a645c10732966)
- 0.2.37-282 pre-sharpness imuf compatibility. [0.2.37](https://github.com/emuflight/EmuFlight/commit/905afd4a63ee391bb11b6d80f48ba589e15c5a82)
- 0.2.38-292 Sharpness all FC. [0.2.38](https://github.com/emuflight/EmuFlight/commit/6f2d6d363f65bfc9a29e2265bf081028797d1916)
- 0.2.38-294 add a form of sharpness for regular fc. [0.2.38](https://github.com/emuflight/EmuFlight/commit/2cd825c30d57e79fdccc55e5de43df303c30533c)
- 0.2.39 (squish of all)  tylercorleone/vbat_compensation_throttle_comp_fix , .vbatLpfPeriod=35
- 0.2.40 squich of gyro-fix, cineamtic removal and dynamic notch? 
