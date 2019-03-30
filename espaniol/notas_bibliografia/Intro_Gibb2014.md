# Building open source hardware
## 5. The Design Process: How to Get from Nothing to Something

![waterfall model of product development](../notas_bibliografia/wozniak.png)

### Design phase
The design phase is just the flow of going back and forth between generating and testing ideas thatnaturally occurs while building something. Designing is often done on paper or in a computersimulation, and prototyping is always physical. The design process is always iterative, but it’s not achicken–and–egg scenario. Your first design input is always your formal definition. Every successiveprototype you build (whether it works or not) is considered a design output. The way you iterateduring the design phase is by checking whether your prototype meets the requirements listed in yourproduct definition. This often–neglected step is called testing (or sometimes validation andverification). 

Many details can be worked out on paper or during the initial design phase, such as whether aspecific type of amplifier IC (integrated circuit) is readily available in the volumes you’ll need tobuy. As mentioned earlier, however, a lot of different design inputs will inevitably crop up duringyour design phase that may impact your product, but that you won’t learn about until after you’ve builtthe first prototype and either tested it yourself or given it to someone to try out.

At this point, you should also recognize why some form of formal testing is a gatekeeping item initerating through the design process. Whether it’s a manufacturing test, a circuit performance test, a
unit stress test, an interoperability test, or a user experience beta test, the only way to discover theshortcomings and limitations of your design is to see how well it works in all the ways you intend forpeople to use it. It should also be clear that it’s not just users you have to worry about—you also needto beta test your production line

1. Most projects start with bread–boarding bits andpieces together to make a proof of concept. The hardware doesn’t have to be small, perfect, ormanufacturable at this point: You just want to prove your circuit works and to determine which partsyou need to build it.

2. Once you have that first proof of concept made, the next step is to move your design from thebench–top into CAD software so that you can make a PCB. This workflow is the same no matterwhich program you’re using (e.g., Eagle, Cadence, Altium).

3. First: select your parts—and I mean, really select your parts. For anything critical (likemicrocontrollers or any nongeneric component), you should have both a manufacturer part numberand a vendor part number for the specific part you’re using. For generic parts you can buyanywhere, you can cheat and just specify the part as “MLCC Capacitor, Footprint: 0603, Value: 10nF.” Next, make sure you have each of those parts correctly entered into your part library. For extracredit, have a physical sample of the part on hand and use it to confirm that both the schematicsymbol and the part PCB footprint are correct. 

4. Once your have a part in your library, you can place it in your schematic. In the schematic captureprocess, focus on reproducing the logical design of your bread–board circuit. While you’re addingcomponents to your parts library and schematic, you should also be adding them to a separatedocument called your bill of materials (BOM). Once the schematic is complete and you’ve passedthe design review, you can start the PCB layout (in the same CAD program). All of these filesshould be shared as your source files for making open source hardware

    You’ll want to conclude this phase with a layout review. Ifyou do not work at a company with a formal design review process, ask a friend in your field toreview your board or make friends with your local hackerspace. 
    
5. Finally, to get to your next prototype and have your ultimate design output, you’ll need to generateGerbers (board fabrication files that describe the layout of your board layers in a vector format).

6. Your Gerber package (also called “artwork” or “PCB prints”) will include a file for each physicallayer of the board design. For a two–layer PCB, typical files are as follows: top copper (sometimescalled the component–side copper); bottom copper (sometimes called the solder–side copper); topand bottom solder mask; top and bottom silkscreen; and top and bottom solder paste mask. The NCdrill file contains the center coordinates for drill holes and the dimensions for each drill. 

Each iteration of the design cycle should generate a new “version” of your design,  this information is collected in a design history file.


### Release phase
Once your design meets all of your critical requirements, you can launch into the release phase.During release, you start with your final preproduction prototype that’s practically perfect in everyway, and test it to the point where you have decided that you are ready to commit—that is, this exactversion of the product is what you will sell to customers. Once you’re in release, change ist verboten.All you should do during this phase is double–check the technical and ephemeral details for yourproject one last time and make sure that this version of your design is the one. This process may seem tedious, but the release phase isyour last critical check to make sure you’ve caught everything before you commit a huge amount oftime and money to go to manufacturing.



## 6. Making a derivative

Derivative:  A derivative is open source hardware that has been altered or modified but isbased on an original design by another person or company.

Clone or Copy: A clone or copy is an open source hardware product that has been directlycopied and conforms with the Open Source Hardware Definition because it does not infringeon the trademarks of other companies.

Counterfeit: With a counterfeit piece of open source hardware, the trademark has beencopied onto a clone or derivative piece of hardware and does not abide by the Open SourceHardware Definition because the trademark is not owned by the person or company creatingthe derivative. Proper attribution does not include copying trademarks. Copying trademarksis illegal.

Derivatives may come from:

(1) The function of the deviceis altered; 

(2) the form of the device is modified; 

(3) the change is economic, with the creator sellingthe same product at a different—usually lower—price point; or 

(4) the change enables a better designfor manufacture (DFM), making it easier to manufacture or supply parts. 

Even if your project no longer reflects any of the original design, you still maywant to reference that previous versions were based on so–and–so’s contraption so that people do notfeel left behind or forgotten

- PCB layout software: Fritzing, Kicad, Eagle
- 3D printing software: Blender, OpenSCAD

Schematic
BOM
Board layout
README
Assembly guide
3d printing files
Code

## 7. Personal fabrication in digital age

### 3D Printing
The purest of these digital fabrication processes are the various forms of 3D printing. These turndigital design into physical objects by gradually adding material in the desired locations, allowing fora wide range of possible geometries. The term 3D printing encompasses a broad range of machines,from personal plastic printers costing a few hundred dollars to industrial machines that sinter metaland cost hundreds of thousands of dollars. Different machines work with different materials and offerdifferent resolutions and tolerances. The materials may have different strengths, optical properties,appearances, finishing possibilities, and so on. Depending on the object being fabricated, some or allof these characteristics may be crucial to creating a useable result. In designing and sharing objectsfor 3D printing, therefore, it’s important to specify not just their geometries, but also the requiredtolerances, materials, and other characteristics—most of which are less easily captured in digitalform. In addition, many 3D-printing processes need some form of manual post-processing, such asremoval of support material, finishing, or curing. These require an operator with appropriateknowledge and skill—and can create variations from one print to the next, even with the same file andmachine. Finally, 3D printing technology is evolving and diversifying rapidly. For all these reasons,it’s important not to think of 3D printing as a way to automatically create things from information, butrather as a material process with specific qualities and affordances.

### Milling and Cutting
Other fabrication processes work by cutting or removing pieces of a larger stock material. Lasercutters cut 2D shapes out of plywood, cardboard, acrylic, and other flat materials. Vinyl cutters do thesame, but with a knife that cuts through thin materials like paper or adhesive-backed vinyl. The water-jet cutter handles stronger and thicker materials like wood, metal, and glass, cutting with a stream ofhard particles in a powerful jet of water. CNC (computer-numeric control) machines, like mills orrouters, work in three (or more) dimensions, removing material from solid blocks of stock with avariety of cutting bits. They are often capable of very precise operations, albeit only within specificaxes of movement. Compared with 3D printers, these cutting and milling tools have the advantage ofbeing able to work with a variety of existing materials, including natural ones with complex structuresthat are difficult or impossible to replicate with the homogenous stock of most 3D printers. They aremore limited in the geometries they can produce, however, and often require more steps in fabricatingor assembling the parts.

In addition to specifying the geometry of the design itself, it’s important to be explicit about thenature of the stock material and the characteristics of the cutting process. Whether two parts press-fittightly together, slip past each other, or don’t fit at all depends as much on the precise thickness of thestock (which can vary even across nominally equivalent materials) and the thickness of the cut as onthe shape in the file. Some constructions may be infeasible to achieve given the tolerances of aparticular machine. (Laser cutters may yield slightly different cut thicknesses on different sides oftheir working area; water-jet cutters can give rough, nonvertical edges, for example.) Traditionalengineering drawings often capture the required tolerances for various surfaces and the material to beused. A quickly created CAD file used for a prototype and then thrown up on a webpage may not.Parts might be sanded, glued, pounded together, or otherwise tweaked in ways not reflected in thedesign files. Generating tool paths for a CNC machine is a complex process with a significant impacton the form and finish of the resulting object; this complexity may not be possible to capture in a waythat can be easily shared with others, particularly if they are using a different machine. Finishing andassembling parts created with CNC devices requires careful craft, which might be difficult tocommunicate or learn. All of these factors need to be kept in mind when designing or sharing a digitalfile for someone else to replicate.

### Other Fabrication Machines
A variety of other digital fabrication processes exist, each with its own affordances and constraints.For example, a host of machines are available for working with soft materials: CNC embroiderymachines apply custom designs to fabric, knitting machines generate colors and constructions basedon digital files, and Jacquard looms are possibly the oldest digital fabrication machines in existence.Industrial production uses a variety of automated machines, including robot arms and other adaptableparts of an assembly line. Furthermore, as digital fabrication becomes more established, more peopleare creating their own machines for custom purposes of various kinds.

### Printed Circuit Boards and Electronics
The production of printed circuit boards (PCBs) can also be considered a digital fabrication process—and a relatively mature one. Digital designs are etched from copper or other materials using aphotographic process, then covered with an isolating layer and text and other annotations. While theprocesses for creating circuit boards in this way are generally toxic and the automated systems fordoing so are expensive, many services will produce PCBs on demand for individual customers withsmall or nonexistent minimums and standard specifications and tolerances. (As a board’sspecifications get more demanding, however, costs can increase, sometimes dramatically.) Circuitboards can also be manually etched or milled on a CNC machine, processes that are more directlyaccessible to individuals but also less robust and precise. While some circuits are sensitive to theprecise characteristics of circuit board’s substrate or the exact tolerances of the fabrication process, agreat many can be shared with relative confidence that they will work when made on a differentmachine from a different provider.

In reproducing circuits, then, the main difficulties are typically getting the necessary parts andassembling them. While vast quantities of components are available to individuals—and manydistributors specifically target hobbyists—advanced parts with specific functionality may not beaccessible. These may be simply impossible to purchase, require an extended procurement processthat makes replication infeasible, or be difficult or impossible to assemble with the processesavailable. As parts are optimized for size and automated assembly, they become harder forindividuals to work with. Even easier-to-solder parts rely on manual skill and the knowledge totroubleshoot problems. Different electronic components may be available or preferred in differentlocations. Parts may go out of stock, become obsolete, or cease being made altogether. All of thesefactors mean that while making a PCB may be a robust and accessible process, much work must bedone to ensure that individuals are able to replicate a complete electronic circuit for themselves. (It’salso worth noting that while the problem may be worse for electronic components, other materials—such as plywood or 3D printer stock—are also industrial products and may not be availableeverywhere or all the time.

### Access to Fabrication
Access to digital fabrication processes comes in a variety of forms. Some machines, particularly 3Dprinters and vinyl cutters, are being targeted at individual consumers via low-cost, Easy-to-usemodels. Local workshops, whether at schools, libraries, community centers, or commercial locations,provide access to larger, messier, and more expensive machines. They also offer opportunities forpeople to learn how to use the machines and can provide a community of like-minded individuals.Online services offer an alternative for those without local, hands-on access. They can provide alarger variety of processes and materials than those found in a single workshop and obviate the needto learn to operate the machines directly. On the downside, the time required for parts to be producedand shipped—and the lack of direct control over the process—can make it harder to iterate and refinedesigns when using an online service. Additionally, online services generally involve higher per-partprices than direct machine access, since they need to cover the cost of the machines, labor, andinfrastructure required to support the service.

## 8. Manufacturing 

The manufacturing of your product is thefact that manufacturing is likely to be the most costly part of all hardware design and distribution

You can choose to DIY manufacture or select a trustedcontract manufacturer (CM) to build your product for you. 

If you have chosen a reputable CM to work with, it will more than likely do a great job of sourcing all your bill of materials (BOM) components for you.Understand, however, that the CM will be providing this service at an additional cost to you. Also, beprepared to hear its ideas for how your design can be improved to better optimize your product forefficiency gains when being built with the manufacturer’s production processes.

In contrast, making the decision to set up your own supply network and provide your CM withinventory can deliver some very tangible benefits, including some significant cost savings. Be aware,however, that this route will require a lot of hard work spent contacting potential suppliers toestablish a network for procuring the components needed for your design.

> Seeed studio
> Seeed Studio, an open source hardware company located in Shenzhen, is alsoaccelerating the maker movement by helping people in mainly three aspects. First, thecompany makes technologies accessible to makers by providing corresponding openhardware modules for makers to build projects. Second, it helps makers turn ideasinto products by providing Agile manufacturing services, including sourcing, design,cutting costs, and logistics, among others. Last but not least, Seeed Studio has helpedspread the culture by building the first maker space in Shenzhen, thereby providing aphysical space and platform for cross-field cooperation; as well as bringing MakerFaire to Shenzhen, and encouraging communication between makers within China andabroad.

If you decide to try your hand at manufacturing your own product and owning every aspect of thatdesign, five critical manufacturing focal points must be given serious consideration as yourproduction plans take shape: 

- Design for manufacturability 
- Equipment selection and implementation 
- Supply chain/purchasing 
- Resource planning and scheduling 
- Testing and quality control

When designing for manufacturing there are also dozens of other design tradeoffs to consider (see Appendix D for the full list): 

- Performance of the part versus requirements of the design. 
- Can we swap plated through hole (PTH) parts for surface-mount device (SMD) parts forease of manufacturing? 
- Consider size, cost, availability, minimum order quantity (MOQ), among other factors. 
- New parts: do you have a vendor for the new parts? Setting up vendors and getting stock cantake time. Are there long lead times? Are there shortages? MOQs? Is end of life (EOL) aconcern?

Testing can be a time-consuming process, but is anabsolute must. It becomes more important the less refined your assembly processes are. Although it isquite difficult to be absolutely perfect (as defined by a single defective product never getting into acustomer’s hands), your product’s reputation depends on making every reasonable effort possible tominimize the number of undesirable experiences that your customers have with your product
