# Best CAD Practices
This is a living document. The goal is to record the "Best" CAD practices so that it is easier to stay up to date and compare your CAD practices with what's "standard" 

# Example Document Setup
The current "best" setup is a multi-document setup that references each other. 

- Framework Document
    - Inside this document, you have the KrayonCad Assembly in which you create the framework for your robot design.
    - MasterSketch Part Studio
        - This is where your core-geometry for all of your subsystems is done.  It should contain the master sketches of all your mechanisms.
- Elevator Document
    - Within this document, you have a Part Studio for each stage of your elevator, in which you can create part studios for your First-Stage Tubes and your mounting plates and derive in your Core Geometry from the Master Sketch. From there, those parts go into a rigid First Stage Sub-Assembly. You should repeat this for your second stage, and in your Main Elevator Assembly, you import (depicted with red arrows) your rigid SubAssemblies and mate them to be able to move like any elevator would. 

- Intake, Drivetrain, and Climber Document
    - This is the more traditional way of doing documents, with no separate subassemblies, and you have one part studio for creating parts, and a single assembly for assembling the subsystems. You should derive (depicted with a blue arrow) your core-geometry from the Master Sketch.

- Master Document
    - In here, you import all of your subsystem assemblies into a single document. 

![](../img/cad-examples/FLOWCHART_1.webp)

*Example of Multi Document Setup*


# Sub Document Setup

Within Each Document, you should have a part studio and assembly attached to it. The goal is to have only 1 part studio and 1 assembly, although depending on your load times you may want to split (such as camera mounts).

![](/img/cad-examples/part-studio.webp)

Note how there's only 1 part studio and 1 assembly. 

# Master Sketch Practices
Utilize Layering to prevent confusing, have a sketch for each mechanism if possible. 

Utilize colored sketches to define subassemblies 
# Feature Tree Practices

Derive applicable master sketches into part studio
Derive Applicable 

# Assembly Practices 

# Why Optimize?

