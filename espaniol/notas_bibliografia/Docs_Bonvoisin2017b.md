# Best Practices of Open Source Mechanical Hardware

The type of information you may want to share depends on your motivation to go open source:

1. Is  your  motivation  to  demonstrate  your  customers  how  good  your  product  is  designed? Then put  particular  emphasis  on  publishing  detailed  and  commented  design  files.  See  section  “enable others to study your product”.

2. Do  you  want  your  innovative  product  to  be  manufactured by  others  so  it  can  be  rapidly  adopted  worldwide?  Then  put  particular  emphasis  on  publishing  clear  assembly  instructionsand a parts list. See section “enable others to make your product”.

3. Do  you  want  to  use  open  source  as  a  means  to  improve  your  product  by  receiving  feedback  from others  to  or  by even letting  them  take  part  in  your  product  development  project?  Then put particular emphasis on publishing documents others can edit and tell potential contributors what you expect from them. See section “enable others to contribute to your design”

Note  that  the  maturity  of  your  product  also  influences  the  content and the  level  of  detail  of  your  product documentation. If you are still at an early design phase, you may have only some description of  the  product  concept  and  requirements  in  the  form  of  sketches  and  text.  If  your  product  is  fully  defined,  you  may  have  complete CAD  drawings  and  a stable parts  list.  But  independent  from  the  maturity of your design, the general rule of thumb is to share the information you have at the time you have it. 

## 1- Enable others to study your product

Share  your  design  files  in  their  original format,  that  is,  in  the  format  in  which  you  created  them.  Even  better  is  to  use  free  and  open-source software  applications  and  open  file  formats.

Alternatively,  you  can  share  your  design  files  in  export  file  formats  such  as  STL,  PDF  or  PNG.  Exporting  your  original  files  in  those  formats  will  however  inevitably  lead  to  loss  of  information.  

In any case you may: 

- share  these  files  in  a  design  repository  to  allow  others  to  browse  your  files  online  (e.g.  GitHub);
- give the possibility to download packaged files with one click;
- clearly separate original design files and exports by labelling them accordingly.

## 2- Enable others to replicate your product

### Share a parts list

A well-made and clear parts list (also termed as bill of materials [BOM] in engineering jargon) is an essential  document  for  those  who  want  to  replicate  your  product.  This  document  will  help  them  understand which parts they have to source or manufacture before assembling your product.

A BOM may contain the following information for each part/component of your product:

- Name of the part: a short denomination allowing to quickly identifying its function. 
- Reference  designation:  This  is  a  unique reference  code  linking  the  parts  list  and  your  technical  documentation.  With  this  code,  the  maker  will  know  which  component  refers  to  which CAD file.  Reference designation and name of the part may eventually be the same, as long as the reference designation is unique and unambiguous.   
- Photo  or  illustration:  Putting  a  photo  next  to  the  textual  reference  of  each  part  will  help  getting a quick overview of your parts list. This will allow someone to search more efficiently for parts in the parts list. 
- Exact specifications: these are precise descriptions of the characteristics the part will have to fulfil,  including  the  metrics  and  the  units  of  measure,  preferably  in  SI  units.  Avoid  vague  descriptions  such  as  "you  will  need  20  small  bolts,  10  large  ones,  a  good  battery  and  a  long  wire".  This information may be insufficient to find the appropriate components and to reliably reproduce   the   functionality   of   your   product.   
- Quantity: that is, how many of such parts are necessary. You may also indicate whether some extra parts should be bought as a precautionary measure, in case the assembly of your product goes wrong.
- Procurement  information:  that  is,  where  the  parts  can  be  ordered.  A  list  with  possible  suppliers will help makers of your product to save time. In the best case, you can recommend a supplier by providing a direct URL hyperlink to the part on the supplier’s website. S tating an alternative procurement option can make sense as well.
- Cost:  it  may  be  of  interest  to  know  the  cost of  each  part  in  order  to  calculate  the  total  procurement  costs  of  the  product.  You  can  either  provide  estimates or  alternatively  make  references to market prices and provide URL hyperlinks to one or more suppliers.

### Share assembly instructions

Text:  A good instructional text finds the balance between richness of details and clarity. It should be detailed enough and mistake-proof,  but  not  filled  with  unnecessary  information  that  could lead  to  confusion.Concise  language  is  essential  if  you  want  to  reach  a  wide  audience  of  readers,  so  you  may  want  to  minimize unnecessary technical jargon

Illustrations: Illustrating  assembly  instructions  makes  them  more  clear  and  vivid.  There  are  at  least  two  kinds  of  illustrations you can provide images or videos/gifs.

## 3- Enable others to contribute to your design

If you want to profit from collective intelligence to improve your product and build a community that actively  participates  in  your  product  development  project,  there  are  at  least  two  things  you  may  consider: sharing editable information and publishing a contributing guide. 

### Share editable information

Publishing  non-editable  files  represents  a  barrier  to  potential  contributions.  Sharing export CAD formats  like  PDF  or  STL may enable  your  community  to  study  your  design.  Yet,  those  formats  are  hardly  editable  and  they  may  not  bear  all  information  you  had  in  your  original  CAD  format  (e.g.  parameters and constraints). In  contrast, sharing  CAD  files  in  their  original  processing  format  would  allow others to access the entire information, to modify it and to make modifications. 

There are at least two ways you can share editable information:  
- through editable files your community members can download/upload.
- through a Web 2.0 environment allowing online edition (e.g. a wiki).

### Publish a contribution guide

If you want to build a community of co-designers, you may communicate publicly (i.e. make an open call)  that interested  persons  are highly welcome  to  join  and  contribute  in  the  product  development.

State explicitly that people are welcomed and explain them **what** they can do. For example: 

- take on already identified tasks/issues; 
- define new tasks/issues, for example by giving improvement suggestions or reporting bugs;
- contribute to the documentation regarding product assembly or usage; 
- help expressing product requirements; 
- leave comments;
- support your project financially.

After  letting  potential  contributors  know  what  they  can  do,  you  may  want  to  explain  them  **how**  they can contribute:

- Collaborative design tools: 
    - Where can the contributors find the files they need? 
    - Which tools should they use? 
    - How can they register?
    - How can they let others know what part of the project they are working on?

- The design process:  
    - How can contributors make or suggest modifications? 
    - How are contributions evaluated and integrated?  
    - What rules and guidelines should be followed when contributing to the project?

- The design rationale: 
    - Why is your product the way it is? 
    - Why you made the specific choices you did.

- The team
    - Who is involved in the project and how?  
    - Which skills are currently needed in your project?

Finally,  you  may  want  to  explain  potential  contributors  **why** they  should  contribute:    

- Tell them what your vision is. 

- People  may  be  motivated  by  fun,  the  desire  to  learn  new  skills  or  to  create  a  better  product,  social  aspects,  networking,  career  development  and  even  competition  or  rewards.  You  could  make  use  of  this  and  tell  your  potential  contributors  the  benefits  they  can  expect  from  contributing. 

    - fields in which they can improve their skills and gain additional knowledge
    - explaining/showing the fun that you are having and that they can expect
    - emphasize  the  aspects  of  community  building  and  the  collective  spirit in your project
    
## Checklist: how open is your hardware?

1. design files are published
2. assembly instructions are published
3. a BOM is published
4. a contribution guide is published
5. the published CAD files are in editable format
6. the published assembly instructions are in editable format
7. the published BOM is in editable format
8. the specified license allows commercial use

