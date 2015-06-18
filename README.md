# iopc
IOT platform as a container.

- checkout steps:
  1. git clone git@github.com:YuanYuLin/iopc.git
  2. git submodule init
  3. git submodule update

- build steps:
  * usage:
     ./buildscripts/build_system.py [buildroot] [project config] [output_name] [action]

  * show help: 
      ./buildscripts/build_system.py buildsystem/buildroot-2014.11 buildcfgs/ArmV6/RaspberryPi/bsp/project_configs.ini RaspberryBSP HELP

  * show menuconfig:
      ./buildscripts/build_system.py buildsystem/buildroot-2014.11 buildcfgs/ArmV6/RaspberryPi/bsp/project_configs.ini RaspberryBSP MENUCONFIG

  * build project
      ./buildscripts/build_system.py buildsystem/buildroot-2014.11 buildcfgs/ArmV6/RaspberryPi/bsp/project_configs.ini RaspberryBSP BUILD_PROJECT

