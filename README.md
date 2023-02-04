Marlin update for X2
M997

sudo dfu-util -a 0 -s 0x8000000:leave -D firmware.bin


EEPROM backup:
Recv: echo:  G21    ; Units in mm (mm)
Recv: 
Recv: echo:; Filament settings: Disabled
Recv: echo:  M200 S0 D1.75
Recv: echo:; Steps per unit:
Recv: echo: M92 X80.12 Y80.12 Z402.00 E445.00
Recv: echo:; Maximum feedrates (units/s):
Recv: echo:  M203 X300.00 Y300.00 Z50.00 E60.00
Recv: echo:; Maximum Acceleration (units/s2):
Recv: echo:  M201 X2000.00 Y2000.00 Z100.00 E10000.00
Recv: echo:; Acceleration (units/s2): P<print_accel> R<retract_accel> T<travel_accel>
Recv: echo:  M204 P800.00 R10000.00 T2000.00
Recv: echo:; Advanced: B<min_segment_time_us> S<min_feedrate> T<min_travel_feedrate> J<junc_dev>
Recv: echo:  M205 B20000.00 S0.00 T0.00 J0.03
Recv: echo:; Home offset:
Recv: echo:  M206 X0.00 Y0.00 Z0.00
Recv: echo:; Auto Bed Leveling:
Recv: echo:  M420 S1 Z10.00
Recv: echo:  G29 W I0 J0 Z-0.02276
Recv: echo:  G29 W I1 J0 Z-0.06007
Recv: echo:  G29 W I2 J0 Z-0.01530
Recv: echo:  G29 W I3 J0 Z0.01953
Recv: echo:  G29 W I4 J0 Z0.00460
Recv: echo:  G29 W I0 J1 Z0.04938
Recv: echo:  G29 W I1 J1 Z0.00958
Recv: echo:  G29 W I2 J1 Z0.02450
Recv: echo:  G29 W I3 J1 Z-0.02525
Recv: echo:  G29 W I4 J1 Z-0.06007
Recv: echo:  G29 W I0 J2 Z0.04938
Recv: echo:  G29 W I1 J2 Z0.00958
Recv: echo:  G29 W I2 J2 Z0.00460
Recv: echo:  G29 W I3 J2 Z0.00460
Recv: echo:  G29 W I4 J2 Z-0.04764
Recv: echo:  G29 W I0 J3 Z0.05684
Recv: echo:  G29 W I1 J3 Z0.04938
Recv: echo:  G29 W I2 J3 Z0.01455
Recv: echo:  G29 W I3 J3 Z0.01455
Recv: echo:  G29 W I4 J3 Z-0.02525
Recv: echo:  G29 W I0 J4 Z0.16381
Recv: echo:  G29 W I1 J4 Z0.12898
Recv: echo:  G29 W I2 J4 Z0.12898
Recv: echo:  G29 W I3 J4 Z0.09167
Recv: echo:  G29 W I4 J4 Z0.02699
Recv: echo:; PID settings:
Recv: echo:  M301 P14.58 I1.14 D46.57
Recv: echo:  M304 P62.75 I9.39 D279.43
Recv: echo:; Z-Probe Offset (mm):
Recv: echo:  M851 X27.25 Y-12.80 Z-1.07
