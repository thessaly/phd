# Collaboration in Open-Source Hardware:Third-Party Variations on the Arduino Duemilanove

This paper explores the   nature   of  such  open-source   hardware   collaboration through  a  prominent  example,  the  Arduino microcontroller development   platform.
We find that its  structure  differs  substantially  from  that  of  open-source software,   emphasizing  multiple  alternatives  from  small-scale  partnerships  rather  than  centralized  public  processes. 

Open-source  hardware  can  also  be  seen  as  an  example  or enabler  of  technological appropriation  [2]  and  user-driven innovation  [9]. 
By  providing  design  files  for  others  to modify and build  from,  it  allows them  to adapt technology to  their   own  circumstances  or   needs.     
This   blurs  the division between producer  and consumer in ways similar  to those discussed in the theories of Eglash and von Hippel.

## Arduino variations

The  differences  between  the  variations  and  the  original Arduino    hardware   can    be    grouped   into   five    major categories:

- aesthetics: e.g.  PCB color  and shape,  component  layout, and additional LEDs.•}

- form  factor:  e.g.  four  of  the  variations  can  be  inserted into a solderless breadboard.

- assembly:  five  of   the   variations  come   as   kits  to  be soldered  together  by  the  end  user,  using  larger  through hole components instead of surface mount parts

- processor:  three  variations  include  a  different  processor than that used on the standard Arduino board.

- other  functional  variations:  e.g.  omission  of  on-board USB connectivity, alternative power connections.  

Some of these don't   lend  themselves   to contribution back to the  original design because they reflect a  different  (and  incompatible) approach  than  that taken by the Arduino hardware.   
Still,  together  they provide a  useful range of products to the Arduino community.

## Motivations

The   motivations   for   many   of   the   Arduino  derivatives stemmed  from  functional  requirements  for  the  hardware itself, cost, educational exercise, feedback from users.   

Much of  the  development of the Arduino variants  was done privately   by   select   collaborators.

Some  of  the  teams  were  distributed,  communicating through emails,  others collaborate   with   wiki   and dropbox  [file  sharing].

Development     of     the     variations     involved     different prototyping processes.

 Some  of  the  developers  started  from  the  original Arduino  design  files  in  creating  their  variations;  others simply recreated them  from  scratch using the  originals  as a reference.
 None  of the  projects make  regular  public  use  of a  software version  control  system. 
 
 The  design  files  for  the  Arduino  variants  tended  to  be published,  if  at  all,  only  when  they  were  finished  and  the board had been produced. As a result,  the boards have  very few  public  versions  (to date).   
 
 In  all  but  two  of  the  cases  (the  LilyPad  Arduino  and  the Freeduino),   the   Arduino   variations   were   designed   and developed  by the  same  people  or  company  that  eventually made   and  sold  the   boards.   
 
## Collaboration structure and influences

This is  an ecosystem  of  many  small  groups  or  companies  providing alternative  offerings  within  a  product  space.     
Individual products  undergo  few  iterations;  instead,  their  designs  are used  as  the  basis  for  new  alternative  variations.    

In  this model,   open-source   collaboration   means   increasing   the number  of  choices  offered  to  users  rather  than  improving the  functionality  of  a  single,  central  option.   
This  may  be partially  a  result  of  the  relatively  simple  design  of  the Arduino  hardware  but it also reflects the  nature  of  physical products.

Aspects of oshw that promote  the  decentralized  collaboration  structure:

a) Agreeing on the components to use  in a  hardware  design is critical   to   enabling   collaboration   between   developers (e.g. surface-mount   components vs through-hole components).

It's   difficult   for someone  to make  or test a  change  to  the  design of  a  board if  it requires  them  to  first acquire  a new set  of  components or   redesign   large   portions   of   the   circuit   to   use   the components   they   already   have.

b) The constraints of manufacturing make it more  difficult and costly  to  test  design  revisions,  limiting  the  frequency  of iteration  and  the  ability  to  integrate  modifications  from many  contributors.  

This need to invest financial resources in the development process may encourage  someone  to make  and sell   their   own   version   of   the   hardware,   rather   than contribute  improvements  back  to  a  product  in  which  they have  no  monetary  stake.   

c) Hardware   doesn't  have   mature tools  or  techniques  for  tracking  and  integrating  changes using free  or low-cost tools.   While existing version control systems  can  be  used  for  hardware  designs,  they  simply store   subsequent   versions   of   a   file   without  providing mechanisms  for   understanding   the   differences   between them.

