# This is the home of Project Revolution

Ever been frustrated with most OSes for Linux friendly handhelds being just Linux with a custom DE?

Here comes the Project Revolution

## Goals:
- Lightning fast bootup to menu, 5 seconds at most from reset vector
- Entirely custom userspace, tailored for handheld gaming
- Transparent handling of emulation ROMs, through retroarch
- Be as usable as it is possible. Battle PSP for its usability
- Match or even outperform other OSes
- Track recent upstream kernel and u-boot(with falcon mode)
- Conserve power when not gaming, yet allow the games to use full power of device when needed
- Utilize mainline kernel drivers when possible

- Implement hardware accelerated media playback for as long battery life as it is possible(https://github.com/R-ARM/Rmedia)
- Custom, extensible yet simple menu program(https://github.com/R-ARM/Rmenu)
- Compatibility with native Linux ports based on SDL2 and GLFW with as little changes as possible

- SDK for easy program development
