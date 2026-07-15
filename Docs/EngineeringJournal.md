July 14th-
  This will be an informal way for me to log my progress and changes on this project. The goal is to put into words what I need to do for each sub-project, how to do it, and how long it actually took me to do.
  This will also be a good way for me to track where I go wrong and mistakes not to do in the future.

  Today I created this repository, and make sections for every part of the project, broken down into its respective folders; a folder for electronics, for materials, for CAD designs, etc...
  I have also divided every part of the project into digestable phases, each building off the last. A blueprint will help ease the amount of times I have to backtrack due to poor planning.
  The workflow is given below:

Phase 0: Requirements and Dimensions
* Figure out how big everything is, Will save you a headache later with redesigning
* Target speed (10 mph? 20 mph?)
* Battery voltage (2S, 3S?)
* Motor size
* Wheel diameter
* Desired suspension travel
* Overall wheelbase
* Ground clearance

Phase 1: Drivetrain
* Choose motor
* Choose gear ratio
* Design gearbox
* Design differential
* Design axles

Phase 2: suspension and steering
* Front double wishbone, or Spring suspension?
* rear suspension
* Steering knuckles
* Servo linkage
* Ackermann steering geometry
* Bearings
* Hub desgins

Phase 3: Chassis
* Bettery mount
* Electronics tray
* Motor mount
* differential mount
* Servo mount
*Suspention mounting points

Phase 4: Wheels
* Look into inexpensive rubber or O-rings
* Rim
* hub
* Tire interface

Phase 5: Assembly
* This is where you test every CAD part thus far. If anything collides then it wont work irl
* Test things like:
* Suspension travel
* steering angle
* gear meshing
* wheel interface
* Driveshaft alignment

Phase 6: Electronics
* L298N / design own MOSFET H-Bridge
* Test power supply
* Add PWM
* Add breaking

* Electronics needed are:
* DC Motor
* Servo
* Battery supply
* Arduino nano (2)*****
* ESP32 (2)

Phase 7: Firmware
* PWM
* Steering
* Read steering and throttle

Phase 8: Body Design
* Design own, and make a replica of a nice one

I will also be putting this under ProjectPLan.md, but in case this changes I will also store it here.
With a bit of calculations, I determined that in order for a 25 MPH max speed, I need about 18,000 RPM from the motor with a 125mm diameter wheel. Buying a 20,000 RPM motor may grant me some more speed, or smaller wheel size in the future.
Upon further inspection a LiPo 3S would be a suitable power supply. Only problem would be the current, so I should be weary of that in the future.

The next step to work on should be the transmission, differential, then suspension.
