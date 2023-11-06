# RT685 SuperMonkey- Hardware #

This repo has the PCB design data for the SuperMonkey that is based upon the i.MXRT685 in a VFBGA176 package.  This design was created to show a minimal configuration example of the i.MXRT685 using QSPI flash on FlexSPI port A.    Each PCB revision is in its own folder.  I typically always keep copies of all revisions in one repo so I can have access to multiple CCA versions at one time (instead of branches for each PCB/CCA).   Branches are used for development and merged into master when boards are sent out.

The SuperMonkey is in a prototype state.   Use at your own risk.

### Latest Revision - Navigation ###

The revisions is are PCB Rev B1 and PCB Rev C. 

Rev C is a new formfactor with more pins and integrated OCTAL PSRAM

The design files are in Altium v21 format.




### History/Notes

#### PCB REV B:

- 1st official prototype.   Rev A was dispositioned.

#### PCB REV B:

- 1st official prototype.   Rev A was dispositioned.

#### PCB REV B1:

- Minor Fix to the I2C PMIC Interface
- Font Fixes

#### PCB REV C:

- New Form Factor MK-76 PGA
- No Onboard flash.  Octal PSRA<>
