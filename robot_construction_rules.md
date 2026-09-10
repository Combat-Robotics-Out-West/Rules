
# Robot Construction Specifications

Combat Robotics Out West September 2026 version

**DISCLAIMER: ANY and all ambiguities, loopholes you want to exploit, concerns or questions should be taken up with the organizers**

## 1. General
1. All participants build and operate robots at your own risk. Combat robotics is inherently dangerous. There is no amount of regulation that can encompass all the dangers involved. Please take care to not hurt yourself or others when building, testing and competing.

2. If you have a robot or weapon design that does not fit within the categories set forth in these rules or is in some way ambiguous or borderline, please contact the event organizer. Safe innovation is always encouraged, but surprising the event staff with your brilliant exploitation of a loophole may cause your robot to be disqualified before it ever competes.

3. Each event has safety inspections. It is at the organisers sole discretion that your robot is allowed to compete. As a builder you are obligated to disclose all operating principles and potential dangers to the inspection staff.

## 2. Critical Safety Rules
Failure to comply with any of the following rules could result in expulsion or worse, injury and death.

1. Radios that do not operate using spread spectrum technology may not be turned on at or near events for any purpose without obtaining the appropriate frequency clip or explicit permission from the event.
   - Custom radio systems are not advised as safety of such systems cannot be assessed by event organizers. If you wish to use your own radio system please clear this with the event organizer.
  
2. Proper activation and deactivation of robots is critical. Robots must only be activated in the arena, testing areas, or with expressed consent of the event and its safety officials.

3. All robots must be able to be FULLY deactivated, which includes power to drive and weaponry, **in under 15 seconds by a manual disconnect**. Examples include a link or power switch. This must be accessible from outside the robot, without obstruction by the weapon. Power switches or equivalents must be rigidly mounted to the robot as to not become inaccessible after a fight.

4. All robots not in an arena or official testing area must be raised or blocked up in a manner so that their wheels or legs cannot cause movement if the robot were turned on. Runaway bots are VERY
dangerous.

5. Locking devices: Moving weapons that can cause damage or injury must have a **clearly visible** locking device in place **at all times** when not in the arena. Locking devices must be painted in neon orange or another high visibility color. Locking devices must be clearly capable of stopping, arresting or otherwise preventing harmful motion of the weapon.

6. Weapon locking pins **must be in place** when weapon power is applied during a robot’s power-on procedure. This includes **all** powered
weapons regardless of the power source or weight class.

7. Robots may not be touched once powered on unless it is to remove the weapon pin/lock or minor repositioning.

8. It is expected that all builders will follow basic safety practices during work on the robot at your pit station. Please be alert and aware of
your pit neighbors and people passing by.

## 3. Weight Classes.
C.R.O.W. events currently support the following weight classes. 

| **Rolling**   | **Shufflers** | **Non-Wheeled** |
| ------------- | ------------- | --------------- |
| 150g          | 225 g         | 300 g           |
| 150g Plastic  | 225 g         | 300 g           |

See Section 5 for definitions of non-wheeled robots and shufflers. 

Robots must show that at least half of the weight bonus applied for is used in moving parts of the locomotion mechanism, not including motors or off-the-shelf gearboxes. Flying/Hovering robots do not have to show this.

It is reccommended to confirm with the event beforehand if you intend on applying for a weight bonus.

## 4. Plastic Class
The spirit of this class is to have an easy entry point for new builders and to encourage creative designs by limiting materials to accesible and cheap materials, including those commonly used in 3D printers. These materials typically don't have strength characteristics common in the standard classes.

While damage is expected in these classes, it is requested that builders remember the spirit of the class. Excessively tough or damaging robots may be requested to change class to the open league

Robots deemed to be violating the spirit of the class can be banned at will at any point through an event.

### Allowed Materials
 - PLA
 - PLA+
 - ABS
 - PET
 - PET-G
 - Acrylic
 - Cardboard
 - MDF
 - Plywood
 - Cheap Recycled Goods

Other materials may be permitted if the follow the class intent, confirm with organisers before the event.

### Materials allowed for weapons
These materials can only be used for weapons
- Foam

### Material Exemptions
All exempt materials may not be used as armor, impactors, or structural features.

 - Decorations
 - Grippy Material for wheel tread or tracks, e.g.
   - O-rings
   - Silicons
   - Rubbers
   - Resins
 - Ropes, Springs and Elastics
   - For use in actuators or power transmission only
  
### Hardware
Hardware should be off the shelf standardised components, typically less than 5aud each, available from common hardware stores or online vendors. Highly specialised components, such as uncommon materials, sizes or tolerances are not allowed.

Hardware includes:
 - Fasteners
   - Bolts
   - Nuts
   - Screws
   - Washers
 - Heat Set Inserts
 - Bearings
 - Bushings


### Components
Any off the shelf or custom electronics are allowed. Off the shelf motors and gearboxes are permitted, but cannot be modified for performance gains.


### Abuses
Abuse of the exemptions will not be tolerated.

Abuses include but aren't limited to: 
 - Building overly armoured robots
 - Building overly tough robots
 - Building overly destructive robots
 - Using exmpt materials as ballast

## 5. Mobility
1. All robots must have easily visible and controlled mobility in order to compete. Methods of mobility include but are not limited to:
   - Rolling
     - Examples Include:
        - Wheels
        - Tracks
        - Bristle Bots
        - Gyro Walkers
        - Torque Walkers
        - Melty brains
   - Shufflers
      - Examples Include:
        - CAM operated linkeges
        - Hovercraft
   - Non-wheeled / Walking: 
      - Non-wheeled robots have no rolling elements in contact with the floor and no continuous rolling or cam operated motion in contact with the floor, either directly or via a linkage. Motion is "continuous" if continuous operation of the drive motor(s) produces continuous motion of the robot. To obtain the non-wheeled weight bonus the locomotion mechanism must have at least two non-continuous degrees of freedom.
      - Examples Include:
        - Flying robots
        - Multi axis servo legs


2. To demonstrate mobility, robots must be able to drive from one corner of the arena, to the opposite corner and return within 20 seconds. Exemptions may be granted on a case-by-case basis.

## 6. Robot control requirements
1. The communication system must stop all motion in the robot (drive and weapons), when the transmitter loses power or signal are required.

2. Every robot must use an approved protocol. Currently approved off the shelf are:
 - AFHDS 2A
 - ELRS
 - DSMX

3. Custom systems may be approved on a case by case basis. See [custom_control_systems.md](custom_control_systems.md) for guidance

## 7. Autonomous/Semi-Autonomous Robots
Any robot that moves, seeks a target, or activates weapons without human control is considered autonomous. If your robot is autonomous you are required to contact the event before registration. 

1. Autonomous robots must have a clearly visible light for each autonomous subsystem that indicates whether or not it is in autonomous mode, e.g. if your robot has two autonomous weapons it should have two "autonomous mode" lights (this is separate from any power or radio indicator lights used).

## 8. Batteries and Power
1. The only permitted batteries are ones that cannot spill or spray any of their contents when damaged or inverted. This means that standard automotive and motorcycle wet cell batteries are prohibited. Examples of batteries that are permitted: 
    - LiPo
    - LIon
    - LiFe
    - NiCads
    - NiMh
    - Dry cells
    - AGM

If your design uses a new type of battery, or one you are not sure about please contact the event you're planning to attend.

2. All onboard voltages above **48 Volts** are not allowed. (It is understood that a charged battery's initial voltage state is above their nominal rated value)

3. All electrical power to weapons and drive systems (systems that could cause potential human bodily injury) must have a manual disconnect that can be activated within **15 seconds** without endangering the person turning it off. (E.g. No body parts in the way of weapons or pinch points.) Shutdown must include a **manually** operated mechanical method of disconnecting the main battery power, such as a switch or removable link. Relays may be used to control power, but there must also be a mechanical disconnect. Please note that complete shutdown time is specified in section 2.3.

4. All efforts must be made to protect battery terminals from a direct short and causing a battery fire.

5. Robot frames are not wires. No electrical connections should be made to the frame.

6. All Robots must have a light easily visible from the outside of the robot that shows its main power is activated.

## 9. Rotational Weapons

1. Spinning weapons that can contact the outer arena walls or floor during normal operation must be pre-approved by the event. (Contact with an inner arena curb, or containment wall is allowed and does not require prior permission.)

2. There are no tip speed limits for both of the 150g classes.

3. Spinning weapons must come to a full stop within **60 seconds** of the power being removed, or the radio transmitter being turned off using a self-contained braking system.

## 10. Springs and flywheels
1. Any flywheel or spring or similar energy storing device must not be spinning or storing energy in any way unless inside the arena or testing area.

2. There must be a way of generating and dissipating the energy from the device remotely under the robot's power.

3. All springs, flywheels, and similar kinetic energy storing devices must fail to a non-energy storing state on loss of radio contact or power.

## 11. Tethered Projectiles
1. Tethered projectiles must have a tether or restraining device that stops the projectile and is no longer than 0.5 meter.

## 12. Forbidden Energy Sources

The following are not allowd:
 - Pneumatics
 - Hydraulics
 - Internal Combustion Engines (ICE)
 - Fuels
   - This includes anything intended to burn. Intentional fires are not allowed.

## 13. Forbidden Weapons and Materials
The following weapons and materials are absolutely forbidden from use:

1. Weapons designed to cause invisible damage to the other robot. This includes but is not limited to:
   - Electrical weapons
   - RF jamming equipment
   - EMF fields from permanent or electro-magnets that affect another robot's electronics.

2. Entangling Weapons or defenses: these are weapons or defenses that can reasonably be expected to stop drive train and/or weapon motion
by being wrapped around rotating parts. This includes:
   - Nets
   - Tape
   - String

3. Weapons or defenses that that can reasonably be expected to stop combat completely of both (or more) robots.

4. Weapons that require significant cleanup, or in some way damages the arena to require repair for further matches. This includes but is not limited to:
   - Liquid weapons. Additionally a bot may not have liquid that can spill out when the robot is superficially damaged
   - Foams and liquefied gasses
   - Powders, sand, ball bearings and other dry chaff weapons
   - Weapons that excessively damage the floor or external walls of the arena

5. Un-tethered Projectiles (see tethered projectile description in section 11)

6. Heat and fire are forbidden as weapons. This includes, but is not limited to the following:
   - Heat or fire weapons
   - Flammable liquids or gases
   - Explosives or flammable solids such as:
     - Gunpowder
     - Cartridge Primers
     - Military Explosives

7. Light and smoke based weapons that impair the viewing of robots by an Entrant, Judge, Official or Viewer. You are allowed to physically engulf your opponent with your robot however. Weapons banned under this category includes, but is not limited to the following:
    - Smoke weapons
    - Lights such as external lasers above 'class I' and bright strobe lights which may blind the opponent.

8. Hazardous or dangerous materials are forbidden from use anywhere on a robot where they may contact humans, or by way of the robot being damaged (within reason) contact humans. Contact the event you plan to attend if you have a question.


