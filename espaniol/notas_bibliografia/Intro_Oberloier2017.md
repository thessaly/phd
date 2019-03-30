# General Design Procedure for Free and Open-SourceHardware for Scientific Equipment

One  of  the  primary  enabling  innovations  that  provide  the  opportunity  for  distributedmanufacturing of open-source hardware-based [26] scientific equipment is the 3D printing capabilitiesof the self-replicating rapid prototyper (RepRap) project [27].  RepRap 3D printers have been usedto provide high-quality educational experiences for students in a wide range of disciplines in theclassroom [28,29] and have become scientific platforms themselves [30].  A maturing network ofpeer-production [31] and 3D printing file repositories [32] provides both time and cost savings withinscientific labs [33]. Combining 3D printing with off-the-shelf components and open-source electronics(e.g., the Arduino prototyping platform) has enabled the automation of scientific equipment.

 This procedure ismade up of design steps, which are activities that have to be performed to come to a fully definedproduct [34,35], and follow a set of design principles, which are the general rules leading the cognitiveactivity of design in the appropriate direction [36].
 
## General procedure
 
The generalized procedure contains five steps and encompasses six design principles:
 
### 1.Evaluate existing similar scientific tools for their physical functions and base the design of the FOSH design off of replicating the physical effects, not pre-existing designs. If necessary, evaluate a proof of concept.

 Literature review must be undertaken before a new open hardware device is to be designed.This literature review should ensure that there have not been other open-source designs for the samedevice as well as detail how similar devices are fabricated for commercial applications. In both casesthe fundamental concepts that are targeted are the physical steps that the device must perform as wellas determining the metrics of success.
 
 If a literature review reveals that a solution already exists, build off of what has been done, addingimprovements or refinements.
 
 Generate an as-simple-as-possible proof ofconcept. If there are even small signs of success, the design may be worth pursuing.
 
### 2.Design, involving the following design principles:

    a.Use only free and open-source software tool chains and open hardware for the fabrication of the device.
 
Use  free  and  open-source  software  design  tools  where  possible  in  the  initial  design  (e.g.,open-source  CAD  packages  such  as  OpenSCAD,  FreeCAD,  or  Blender).   
FOSS shouldbe used for all software whenever possible.     
The fabrication equipment used to make the targeted device should run free and open-source firmware and should when possible be FOSHitself (e.g., a RepRap 3D printer). If that is not feasible, then low-cost and/or widely-used software packages and hardware should be favored. This is to ensure the widest possible accessibility of your designs for remixing by others.
 
    b.Attempt to minimize the number and type of parts and the complexity of the tool.
    
In  order  to  support  maintenance,  upgrading,  repair,  and  end  of  life  disassembly  [41]  andrecycling [42],  attempt to minimize the number and type of parts (e.g.,  use all the same type offastener) and the complexity of the tool overall.  Minimize dissimilar materials when unnecessaryand reduce the part count

    c.Minimize the amount of material and the cost of production.

eliminating non-functional bulk to designs, and, in 3D printed designs, minimizing infillpercentage to fulfill mechanical requirements.
    
    d.Maximize the use of components that can be distributed digitally manufactured from using widespread and accessible tools such as the RepRap 3D printer.

The use of distributed digital manufacturing using widespread and accessible tools such as theRepRap 3D printer and open PCB mills [47] help to reduce both the environmental impact as well as reduce the economic costs of production [48–51]. Lead times can also be reduced, as well asimproving maintainability.
    
    e.Create parametric designs with pre-designed components, which enable design customization.
    
By making parametric designs rather than solving a specific case, all future cases can also be solvedwhile enabling future users to alter the core variables to make the device useful for them
The creation of parametric tools allows a large degree of flexibility to the user. Properly parametrized3D model designs will allow users to alter critical dimensions for their purposes.In some cases, it will alsoallow models to be reformatted such that they could be manufactured with a wide and unforeseeablerange of tools.

    f.All components that are not easily and economically fabricated with existing open hardwareequipment in a distributed fashion should be chosen from off-the-shelf parts, which arereadily available throughout the world.
    
All customized parts are designed to be digitally manufactured, but often times less expensivecomponents can be found that are mass manufactured (e.g., pipes, tubes, screws, etc.). These shouldbe sourced so they are as widely available as possible throughout the world. Using off the shelf partsallow research labs to stock a minimum of parts, which are widely used. This, once again, reduces thelead time, which speeds up research

### 3.Validate the design for the targeted function(s).

In order for the FOSH tool to be used in the scientific community, it must be validated using aclear and transparent procedure and have a low-cost, effective method of calibration. Again, wheneverpossible, one should use other digitally manufactured open hardware tools and FOSS to complete thevalidation and calibration.

### 4.Document  the  design,   manufacture,   assembly,   calibration,   and  operation  of  the  devicemeticulously. This should include the raw source of the design (e.g., computer aided design files(CAD)), not only the files used for production (e.g., stereolithography files (STL)).

Documentation must actively assist a non-specialist with recreating the hardware.  The OpenSource Hardware Association (OSHWA) has extensive guidelines for properly documenting andreleasing open-source designs [53]. I

- Share design files in the most universal type.
- Include a fully detailed bill of materials, including prices and sourcing information.
- If software is involved, make sure the code is clear and understandable to a layman.
- Include  many  photos  such  that  nothing  is  obscured;   these  can  be  used  as  a  referencewhile manufacturing.
- In the methods section, the entire manufacturing process must be detailed, as these are instructionsfor users to replicate the design.
- Share on many file hosting sites (see step 5 below), but also be sure to specify a license, this givesusers information on what fair use of the design constitutes.

### 5.Share all of the documentation in the open-access literature

In order for FOSH to proliferate, designs must be shared aggressively just to raise awareness of the existence of the option.  
All of the documentation for a project can be shared on the Open Science Framework, which is set up to take any type of file andhandle large datasets.
Software can be shared on sites like GitHub or SourceForge,  and should include  proper  documentation  on  the  inner  workings  of  the  code,  as  well  as  a  brief  summary.
The 3D designs can be shared on sites set up by government scientific funders like the NIH 3DPrint Exchange or open-source companies like Ultimaker’s YouMagine or MyMiniFactory as well asother repositories. 
Circuit designs can be shared on sites like the Open Circuit Institute [55].

Designers should consider spreading designs to as many hosting sites as possible, as this willonly increase exposure. Regardless of the site, it is important to engage with the community, buildingpersonal  rapport.   Building  a  reputation  for  intelligence,  reliability,  and  helpfulness  will  bolsterconfidence in your designs and increase usage.
