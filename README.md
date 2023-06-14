# platform-radxazero
Volumio platform files for Radxa Zero (Amlogic S905Y2) and Radxa Zero 2 (A311D) SBCs

Platform files are created using the armbian build system for kernel, u-boot, armbian-firmware and specific Volumio settings in armbianEnv.txt (read by the geeric Armbian boot script for meson64 devices).

<sub>

|Date|Author|Change
|---|---|---|
20230514|gkkpch|initial with Radxa Zero
20230607||Added Radxa Zero2
20230614||Modified radxa zero and zero2 dts to enable SPDIF
|||Created corresponding audio routing settings with a modified,  board-specific asound.state


