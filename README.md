# HotD
Hanger of the Dispossessed (BattleTech Game Mods)

Repositor for BattleTech/MechWarrior models & mods.
Models are all based on original artwork from PGI & HBS.
(Working on license before uploading content)


Note on 3d printing:
None of my files for 3d printing are truely cleaned and optimized for 3d printing.  I just don't have the time
to clean them up properly to be proper whole meshes without gaps.
STL files with _cleaned on them are properly fixed meshes. (Rare)
STL files with _reinforces are typically what I have to print with.  Those I've taken the PGI models and exported
them into Windows 3D Builder (the 3mf file).  I let 3D Builder repair the models and then save them a STL file.
I then use Cura to slice them (0.05 layer height) and look for major voids, gaps, detatched parts, or parts that 
just won't print. I then go back to 3D Builder and position cubes, spheres, and cylindars to reinforce the print.
I then re-export, and re-slice in Cura until I'm satisfied the 'Mech will print well enough.
I was using a 0.02mm nozzle on my Robo 3D R1+ FDM printer.
I'm now using an AnyCubic Photon DLP Resin printer and loving that.


Note on 3d printing scale:
I'll try to keep the 3mf & STL files in 6mm or N-Scale, equivilent to comercial miniatues.
I like to print mine a little smaller at about 5mm scale.  So some of the files might be off.
I use 30mm + tonnage/10 as a general guide, adjusting individual 'Mechs as they need.
The smaller size fits on 1.75" heroscape tile with my trees: https://www.thingiverse.com/thing:2852387

Also note on 3d printing:
The antennas need to be beefed up as they will break off.  I typically just print as is and reaplace them post print 
with one of the long cylindrical printing supports I remove.


Typical File & Folder layout:
BattleMechs
  <Mech Name>
    Textures (folder)                           Adjusted & Recompiled PGI textures for Mech
      chassis_body_diffuse.png
      chassis_body_normal.png
      ...
      chassis_mask_v1_base.png
      ...
      chassis_weapon_diffuse.png
      ...
    chassis.max                                 3ds Max scene with all textured models, projectors, originals
    chassis.fbx                                 export of 3ds Max scene
    chassis_model-xxx.3mf                       Working file for 3d printing with supports (6mm Scale)
    chassis_model-xxx_reinforeced.stl           Quickie reinforcements for 3d printing
    chassis_model-xxx_cleaned.stl               Properly cleaned-up for 3d printing
    Notes.txt                                   Notes to self, status, todo, etc
  <Mech Name>
    Textures
      ...
    chassis.max
    chassis.fbx
    chassis_model-xxx.3mf
    chassis_model-xxx_reinforeced.stl
    chassis_model-xxx_cleaned.stl
    Notes.txt                                   Notes, status, todo, etc
  <Mech Name>
    ...