*This document is a work-in-progress and has no official affiliation with any of the institutions mentioned. *Do not quote from this document*  

This document was created to document changes in the digital preservation policy and guidelines at AFC, specifically by creating time-stamped, multi-authored documentation. The AFC DAM's hire in 7/2015 precipiated the need to create documentation of processes as *they were, as they had been previously, and as they would be during her tenure.*

During the first 6 months, the DAM made necessary processing changes in order to complete in-progress or stalled projects, including the Field Projects digitization, the Civil Rights Oral History Collection, and other examples that required immediate decisions to keep a usable workflow for vendors and external partner organization. The near-loss of valuable content exposed the dangers of loose documentation practicers during years of major staff turnover. This document should help impede this_

**Sampling of Policies/Guidelines**
[Yale University:](http://www.library.yale.edu/iac/DPC/revpolicy2-19-07.pdf)  
[SCAPE project  
[York University:[(https://digital.library.yorku.ca/tags/digital-preservation-policy)  
[New Zealand]  
[National Library of Austrailia:](http://www.nla.gov.au/policy-and-planning/digital-preservation-policy)  

**American Folklife Center, Library of Congress**  
*"'American folklife' means the traditional expressive culture shared within the various groups in the United States: familial, ethnic, occupational, religious, regional; expressive culture includes a wide range of creative and symbolic forms such as custom, belief, technical skill, language, literature, art, architecture, music, play, dance, drama, ritual, pageantry, handicraft; these expressions are mainly learned orally, by imitation, or in performance, and are generally maintained without benefit of formal instruction or institutional direction."*  
-the American Folklife Preservation Act law (P.L. 94-201), 1976).

**Digital Preservation**  
Digital preservation is the whole of the activities and processes involved in the physical and intellectual protection and technical stabilization of digital resources through time in order to reproduce authentic copies of these resources. 

Digital preservation decisions are made on the basis of this Policy, the Library's Strategic Plan, the digital resources’ enduring value and the feasibility of the digital resources’ preservation. When possible, decisions about the need for preservation are made at the time of creation, acquisition, or licensing of digital resources. 

Preservation of digital resources may include any actions necessary to preserve continued access to the digital material, ensure its authenticity, mitigate and/or reverse the effects of hardware and software obsolescence and media decay. This Policy recognizes that the maintenance and the reliable long-term access to digital resources are supported by a preservation planning function, research (monitoring) about technology that supports a repository and the requirements of the designated community it serves, as well as outreach and education regarding policies, procedures and best practices for digital resources. 

**Levels of Digital Preservation**  
AFC recognizes that not all collections require or mandate the same amount of processing, staff time, and resources. 
In the initial assessment, each accession of a collection should be evaluated and designated a tier level of 1-3 to indicate, very roughly, the resources required for the collection. Difficulty (a score of "3") would indicate major preservation actions needed because of corrupt or obsolete file types; older physical carriers (floppy disks), a large collection size, complicated or unclear rights, and a high-priority (mandated collection or grant funded collection, for example) project. All of these factors combined would require much more resources.
[Emory University SAA-ERS post:](https://saaers.files.wordpress.com/2016/01/waugh_tieredapproachtoprocessing_ersblog.png)

AFC recognizes there also are occasions for *no preservation,* in which we cannot accept responsibility for collections. This may be because the collection files were corrupted, or appropriate authorization for preservation actions were not established. AFC can preserve a limited number of supported formats, and can provide limited support to less known, less-adopted, and proprietary formats. 

**Frequency of Policy Review**  
This policy will be reviewed bi-annually to assure timely updates to reflect the maturing of the technology by the relevant body. 

**Authenticity**  
The mutable nature of digital resources opens the possibility for unauthorized and undetectable changes. Confidence in the authenticity of digital resources over time is particularly crucial owing to the ease with which alterations can be made. From the moment that digital resources are created or acquired, AFC undertakes protective procedures to prevent, discover, and correct loss or corruption of digital resources. In addition, supporting evidence, ideally in the form of metadata, must be provided to enable users to evaluate the authenticity of all preserved digital resources. 

AFC can only guarantee digital files when they are transferred with the known fixity of each file. Bagger (or a CLI tool, like mdsum) must be used prior to file transfer to validate that the files have transferred w/out introducing change or error. If the files are not bagged before transfer, we will not be able to provide proof that the files have been transferred to the archive. File corruption can happen for any number of reasons, including hardware failures in hard drives, network failures, and operator (human) failures.

Yale University Library employs both SHA1 and MD5 algorithms upon ingest.
Harvard University - MD5 required with deposit via SFTP to validate
AFC very strongly requests a minimum of an MD5 algorithm in order to validate ingest to repository. When fixity is not created by donor, AFC staff will create a manifest of fixity values before ingest, to validate in ingesting to the repository.  

**Metadata** 
Preservation metadata includes a number of different types of metadata: administrative (used in managing information resources including rights and permissions), technical (describing hardware and software needed to maintain an information object) and structural (identifying the relationships between objects such as part of, dependent upon that form intellectual entities. Particular attention is paid to the documentation of digital provenance (metadata documenting the history of the object and any actions taken to maintain and provide access), and of relationships among different objects within preservation repositories (vs. relationships between resources, i.e., structural metadata). The preservation process must be able to understand, take in, and maintain metadata submitted with the digital resource while creating its own metadata to manage the preservation of that resource.




Pre-conditiong (but even in these cases, better to ingest, pre-processing and then alter)
-adding and correcting the file extension
-excluding problematic characters

-all changes must be reversible
“All changes must have a “system-based provenance note that clearly describes the change that has been made to the file.”


*Validation**
Before ingesting processed collections into the repository, it is necessary that we ensure they are valid and well-formed.


