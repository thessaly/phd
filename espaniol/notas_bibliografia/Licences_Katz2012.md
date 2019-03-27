# Towards a Functional Licence for Open Hardware41Towards a Functional Licence forOpen Hardware

Compares TAPR and CERN OHL, proposes new non copyleft based on Apache license.

There are currently two main licences vying for serious consideration as open hardware licences.They are the TAPR1 Open Hardware License, and the CERN2 Open Hardware Licence. Both ofthese licences are intended to assert a form of copyleft on open hardware, the intention being that,as with free software, open hardware must be distributed in a way that guarantees availability ofthe underlying design documents, and provides the right to reuse, adapt and redistribute them, withthe same rule applied downstream as those designs and hardware based on them are re-distributed.

 An effective open hardwarelicence should address the full range of hardware (and frequently will also, incidentally, addressassociated software)
 
## The TAPR Open Hardware License

The TAPR Open Hardware License was drafted by John Ackermann, an attorney and radioamateur8, as a response to designers of electronics comprising the Tucson Amateur Packet RadioSystem. It is expressly intended to apply copyleft to hardware

The licence is expressly intended to be a contract (unlike the GPL, which was drafted to be a barelicence subject to conditions11). It primarily deals with design documentation (which includesCAD   files,   board   layouts   and   mechanical   drawings),   requiring   anyone   who   uses   designdocumentation of covered hardware to comply with the licence obligations, and specifically, tomake the design documentation (including any modifications to them) available to any recipient ofthe hardware (there are also obligations to attempt to pass details of the obligations back to theupstream licensors).

The licence provides that any software (including firmware) in the project is not covered by the licence, but is governedby whatever (generally open source) software licence is applicable to it12. There is also a non-commercial version of the TAPR License, but like the Creative Commons non-commercial option,this is neither a free nor open source licence.

## The CERN Open Hardware Licence
elsewhere??


## Issues

Copyleft is particularly problematic, given that the cost of circumvention forhardware is lower than for software, that no obvious legal mechanism exists to make copyleftconsistently applicable, and that the number of opportunities in the development and exploitationlifecycle for hardware for copyleft to impinge are much lower. 

- Using a piece of hardware, or transferring a piece of hardware fromone  person   to  another   does  not   potentially  contravene   any  intellectual   property   rights,  andtherefore does not require any licence on which copyleft-type requirements can impinge. Thismakes it difficult to effectively implement a copyleft licence for hardware which is effective, if thetrigger is to be distribution of the physical hardware.

It’s important to distinguish between the hardware itself and the associated design documents. Thedesign   documents   will   generally   be   subject   to   copyright,   and   reproduction,   adaptation   anddistribution of design documents to the public will therefore require a copyright licence. Thus anyappropriate document licence such as one of the Creative Commons licences or the GNU FreeDocumentation Licence can be applied, with copyleft adopted (or not) accordingly. 

For   a  copyleft   mechanism   to  work,   there   needs   to  be  a  clear   boundary,   such   that   certaininteractions between a copyleft piece of software (“CS”) and a non-copyleft piece of software(“NCS”) mean NCS can only be distributed subject to the copyleft licence, and certain otherinteractions allow NCS to be distributed free of the copyleft licence (but subject of course towhatever other licence, if any, may be required in respect of NCS).

- Boundaries: The types of interaction are much greater: would bolting a copyleft wheel to yourproprietary car mean that (assuming hardware copyleft is possible) you could not sell your old carwithout being able to provide the design document to the wheel, or the whole car?

New CERN OHL: Tying the copyleft to the design documentation also helps as regards incorporation of sub-assemblies into larger assemblies. If the copyleft only applies at file-level, it becomes more akin toMozilla-style weak copyleft, and is more easily manageable.

### economic argument

Hardware is different. For any piece of hardware, there will already be a cost involved in sourcingthe raw materials. Assembling atoms is much more expensive than assembling bits. The costdifferential, therefore, is likely to be much smaller in proportion

Copyleft relies on this gulf between the cost of replication and the cost of circumvention. Wherethe cost differential is smaller, the incentive for the replicator to comply with the copyleft licencerather than go to the effort of reverse-engineering, is similarly smaller. 

Once the replicator has created its own version of the hardware after the reverse-engineeringprocess, it will then be free and clear to exploit and license that as it sees fit (and less likely tocontribute back to the community than it would have been had the original designs been availableto it under a non-copyleft licence)


## Solderpad license

Apache 2.0 explicitly deals with patents, trademarks and copyright. The main change in theSolderpad licence has been to extend the rights licensed by incorporating a new definition of“Rights”, used typically where reference to copyright alone was used, which is intended to sweepup, alongside copyright, all other relevant rights, such as design rights, semiconductor topography(mask) rights and database rights. A slightly controversial addition to clause 2 (Grant of License)provides that the licence also permits doing “...anything in relation to the Work as if the Rights didnot exist” as an additional permission (still subject to the other conditions). The idea is that if thescope of intellectual property is increased from jurisdiction, then this will be picked up in thedefinition of “Rights”, but also related rights will be dealt with in this sweeping up clause. 

Andrew Back kindly offered to host the modified Apache licence on Solderpad35, “a place to share,discover and collaborate on electronic projects”, and consequently, the name “Solderpad HardwareLicence” was adopted. 
