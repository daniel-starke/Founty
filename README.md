Founty
======

A toy fountain.

About
-----

I made this as my entry to the Snapmaker contest gifts for kids with my Snapmaker 2.0 A350.  
A print and assembly description is given here together with the FreeCAD project file in the hope that other get inspired to make their own version of it. Or just have fun with it :)  
I decided to put it into an Github repository to track changes and collect improvements on it. Let's see how well that works.

**Unfortunately, the used pump mechanism of the current version does not work ☹️.** Maybe someone knows how to fix this.

Print
-----

The parts can be mashed in the `Mesh Design` workspace of FreeCAD to the desired resolution and exported to STL for printing. I used Cura to slice the files at 0.2mm layer height with a 0.4mm diameter nozzle and 3.5mm gyroid infill if not stated different. PETG is used as filament as it was designed to be used in water. Use the recommended print orientation as shown below.

Note that PETG tends to stringing. I used the stock hotend components and have done E-step calibration and linear acceleration calibration but not retraction calibration. Polylite PETG printed quite well at 240°C and 70°C build plate temperature.


<img src="img/LowerFrameCut.JPG" alt="LowerFrameCut" width="50%" height="50%"/>

`LowerFrameCut`


<img src="img/UpperFrame.JPG" alt="UpperFrame" width="50%" height="50%"/>

`UpperFrame`


<img src="img/Turn,Pump.JPG" alt="Turn,Pump" width="50%" height="50%"/>

`Turn`, `PumpThreadCut` (42h print)


<img src="img/Holder.JPG" alt="Holder" width="50%" height="50%"/>

`Holder`


<img src="img/AdapterLock.JPG" alt="AdapterLock" width="50%" height="50%"/>

`AdapterLock`


<img src="img/Washers.JPG" alt="Washers" width="50%" height="50%"/>

`PumpBottomWasher`, `TurnBottomWasher`, `TurnTopWasher` (print in sequence)


<img src="img/Shafts.JPG" alt="Shafts" width="50%" height="50%"/>

`TurnShaftPrintGroup`, `PumpShaft` (0.12mm layer height, tree supports touching build plate)


<img src="img/AdapterLockCut.JPG" alt="AdapterLockCut" width="50%" height="50%"/>

`AdapterLockCut`


<img src="img/Whale.JPG" alt="Whale" width="50%" height="50%"/>

`WhaleFinalCut` (0.3mm layer height, tree supports touching build plate, support eraser for mouth and eyes)


<img src="img/Locks.JPG" alt="Locks" width="50%" height="50%"/>

`TurnLock`, `PumpLock`, `MainLockLeft`, `MainLockRight`, `MainLockPipe` (print in sequence)

Assembly
========

No glue is needed. Everything is assembly with snap-fits. Just follow the steps below and paint it with acrylic colors to your liking at the end.

1. Attach the `AdapterLockCut` to the `WhaleFinalCut` using `MainLockLeft`, `MainLockRight` and `MainLockPipe`.

  <img src="img/Step1.JPG" alt="Step1" width="50%" height="50%"/>

2. Insert `PumpShaft` in `Holder` and both together into the assembled `AdapterLockCut`.

  <img src="img/Step2.JPG" alt="Step2" width="50%" height="50%"/>

3. Attach the `UpperFrame`.

  <img src="img/Step3.JPG" alt="Step3" width="50%" height="50%"/>

4. Insert `AdapterLock` and turn it to lock it.

  <img src="img/Step4.JPG" alt="Step4" width="50%" height="50%"/>

5. Insert `TurnShaftPrintGroup` into `UpperFrame`.

  <img src="img/Step5.JPG" alt="Step5" width="50%" height="50%"/>

6. Add `PumpBottomWasher` and `TurnBottomWasher` to `LowerFrameCut`.

  <img src="img/Step6.JPG" alt="Step6" width="50%" height="50%"/>

7. Add `Turn` and `PumpThreadCut` to it. Add `TurnTopWasher` to `Turn`.

  <img src="img/Step7.JPG" alt="Step7" width="50%" height="50%"/>

8. Put both halves together. Make sure the ends of `PumpShaft` and `TurnShaftPrintGroup` are sticking out.

  <img src="img/Step8.JPG" alt="Step8" width="50%" height="50%"/>

9. Attach `TurnLock` to `TurnShaftPrintGroup` and `PumpLock` to `PumpShaft`.

  <img src="img/Step9.JPG" alt="Step9" width="50%" height="50%"/>

Done.

<img src="img/FinalAssembly.JPG" alt="FinalAssembly" width="50%" height="50%"/>
