### H4 *This document is a work-in-progress,* This document does not imply consent, permission granted, or adoption by the organizations mentioned. Do not assume this draft is working policy.  ### H4

_This document was created to document changes in the digital preservation policy and guidelines at AFC, specifically by creating time-stamped, multi-authored documentation.
The AFC DAM's hire in 7/2015 precipiated the need to create documentation of processes as *they were, as they had been previously, and as they would be during her tenure.*

During the first 6 months, the DAM was told to prioritize making decisions for several projects including the Field Projects digitization, the issues surrounding the Civil Rights Oral History Collection, and other examples that required immediate decisions to keep a usable workflow for vendors and external partner organization. The near-loss of valuable content exposed the dangers of loose documentation practicers during years of major staff turnover. This document should help impede this_

**Sampling of Policies/Guidelines**
[Yale University:](http://www.library.yale.edu/iac/DPC/revpolicy2-19-07.pdf)
[SCAPE project]
[York University]
[New Zealand]

**American Folklife Center, Library of Congress**
"'American folklife' means the traditional expressive culture shared within the various groups in the United States: familial, ethnic, occupational, religious, regional; expressive culture includes a wide range of creative and symbolic forms such as custom, belief, technical skill, language, literature, art, architecture, music, play, dance, drama, ritual, pageantry, handicraft; these expressions are mainly learned orally, by imitation, or in performance, and are generally maintained without benefit of formal instruction or institutional direction." -excerpted from the American Folklife Preservation Act law (P.L. 94-201), 1976).

**Digital Preservation**
Digital preservation is the whole of the activities and processes involved in the physical and intellectual protection and technical stabilization of digital resources through time in order to reproduce authentic copies of these resources. 

Digital preservation decisions are made on the basis of this Policy, the Library's Strategic Plan, the digital resources’ enduring value and the feasibility of the digital resources’ preservation. When possible, decisions about the need for preservation are made at the time of creation, acquisition, or licensing of digital resources. 

Preservation of digital resources may include any actions necessary to preserve continued access to the digital material, ensure its authenticity, mitigate and/or reverse the effects of hardware and software obsolescence and media decay. This Policy recognizes that the maintenance and the reliable long-term access to Yale’s digital resources are supported by a preservation planning function, research (monitoring) about technology that supports a repository and the requirements of the designated community it serves is a core activity to preservation planning, as well as outreach and education regarding policies, procedures and best practices for digital resources. 


**Levels of Digital Preservation**
AFC recognizes that not all collections require or mandate the same amount of processing, staff time, and resources. 
In the initial assessment, each accession of a collection should be given a score  of 1-4 to indicate, very roughly, the processing difficulty and include: preservation actions needed; direction on format migration options; whether or not the digital collection is a high preservation risk. 

With the accessioning of the collection, can we assign it a value, 1-4, on its preservation level?  This value can be based on the above as well as the obsoleteness of the collection, the condition of the carrier object (floppy disk, for example), the number of files and the collections size, and the types of files and their status as supported/unsuppported in the repositiory (Emory University's work)

AFC recognizes there also are occasions for *no preservation,* in which we cannot accept responsibility for collections. This may be because the collection files were corrupted or appropriate authorization for preservation actions were not established. AFC can preserve a limited number of supported formats, and can provide limited support to less known, less-adopted, and proprietary formats. 

**Frequency of Policy Review**
This policy will be reviewed bi-annually to assure timely updates to reflect the maturing of the technology by the relevant body. 

**Authenticity**
The mutable nature of digital resources opens the possibility for unauthorized and undetectable changes. Confidence in the authenticity of digital resources over time is particularly crucial owing to the ease with which alterations can be made. From the moment that digital resources are created or acquired, YUL undertakes protective procedures to prevent, discover, and correct loss or corruption of digital resources due to either inadvertent or malicious intent. In addition, supporting evidence, ideally in the form of metadata, must be provided to enable users to evaluate the authenticity of all preserved digital resources. 

AFC can only guarantee digital files when they are transferred with the known fixity of each file. Bagger must be used prior to file transfer so that the files may be validated after they have been transferred. If the files are not bagged before transfer, we will not be able to provide proof that the files have not been corrupted. File corruption can happen for any number of reasons, including hardware failures in hard drives, network failures, and operator (human) failures.

Yale University Library employs both SHA1 and MD5 algorithms upon ingest.
Harvard University - MD5 required with deposit via SFTP to validate
AFC now requires MD5 in order to validate ingest to repository. When fixity is not cteated by donor, AFC staff will create manifest file before ingest.

The long-term authenticity of digital collections held by AFC will be verified using in-house tools created by LC, specifically CTS as of the time of this writing. 





Metadata: 
Preservation metadata includes a number of different types of metadata: administrative (used in managing information resources including rights and permissions), technical (describing hardware and software needed to maintain an information object) and structural (identifying the relationships between objects such as part of, dependent upon that form intellectual entities. Particular attention is paid to the documentation of digital provenance (metadata documenting the history of the object and any actions taken to maintain and provide access), and of relationships among different objects within preservation repositories (vs. relationships between resources, i.e., structural metadata). The preservation process must be able to understand, take in, and maintain metadata submitted with the digital resource while creating its own metadata to manage the preservation of that resource.


		
examples:  A depositor of interactive digital objects may not agree to have migration processes applied to them if those processes change the look and feel of the interaction environment, or if some of the content of the objects is provided as part of the interaction environment. In this case the only agreed preservation approaches may be to use hardware emulation or original/replica hardware to preserve the content. Without an agreement in place at point of deposit (when the content is well understood) it may be impossible to make this judgment in the future without a great degree of expensive manual intervention.


Pre-conditiong (but even in these cases, better to ingest, pre-processing and then alter)
-adding and correcting the file extension
-excluding problematic characters

-all changes must be reversible
“All changes must have a “system-based provenance note that clearly describes the change that has been made to the file.”


*Validation**
Before ingesting processed collections into the repository, it is necessary that we ensure they are valid and well-formed.


