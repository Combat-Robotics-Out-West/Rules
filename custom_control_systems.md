# Custom Control System Guidelines

This describes some guidelines to help get a custom control system approved. Meeting every guideline in this document does not guarantee your system will be approved.

Approvals will be balanced based on a few factors, including but not limited to:
 - Builder Experience
 - System Testing 
    - Particularly testing in active combat
 - System documentation and clarity
 - Bot dangerousness

C.R.O.W. supports innovation and development, so when possible we will work with builders to get custom systems approved, but we cannot guarantee the availability of time or resources.

## General Rules
Any custom system must comply with all rules, no exceptions will be given. This particularly applies to failsafing correctly (stop all motors when transmitter power/signal is lost).

Builders should take great care to ensure that their code can't get stuck or crash in such a way as to prevent failsafing.

## Frequency
Any system should be capable of using more than one frequency to prevent collisions with other robots. Digital spread spectrum or frequency hopping is preffered.

Builders should remember Australian laws about allowed frequencies and transmission power.


## Connection Timeliness
Robot combat events run on a tight schedule, and we do not have time for connection difficulties. We recommend builders engineer their systems to connect reliably and quickly, without contacting the robot once its powered up (which happens before the transmitter is turned on).

Typically if connections take longer than 30s you may forfeit a fight. If connection drops out mid match causing a loss, this will never be grounds for a replay.

## Interference
Systems that unintentionally cause interference with other radios will not be approved. If this is confirmed half way through an event, results may be reversed if it is deemed the interference was a major factor.

## Wifi and Bluetooth
While these can form the basis of safe and effective communication systems, they are typically not particularly suitable, and care should be taken if choosing to base a system off them. It is unlikely that a robot with a spinner controlled by wifi or bluetooth will be approved.