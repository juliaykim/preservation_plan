*This document is a work-in-progress,* This document does not imply consent, permission granted, or adoption by the organizations mentioned. Do not assume this draft is working policy.

_This document was created to document changes in the digital preservation policy and guidelines at AFC, specifically by creating time-stamped, multi-authored documentation.
The AFC DAM's hire in 7/2015 precipiated the need to create documentation of processes as *they were, as they had been previously, and as they would be during her tenure.*
Without clearer documentation practices, the AFC DAM was unable to understand the processes and organization of previous collections into the repository.Decisions and the historic mechanisms for them, such as priortizing collections, directory and file-naming conventions of some organizations, and so forth were sometimes opaque.
During the first 6 months, the DAM was told to prioritize making decisions for several projects including the Field Projects digitization, the issues surrounding the Civil Rights Oral History Collection, and other examples that required immediate decisions to keep a usable workflow for vendors and external partner organization. The near-loss of valuable content exposed the dangers of loose documentation practicers during years of major staff turnover. This document should help impede this_

**Sampling of Policies/Guidelines**
[Yale University:](http://www.library.yale.edu/iac/DPC/revpolicy2-19-07.pdf)
[SCAPE project]
[York University]
[New Zealand]

**American Folklife Center, Library of Congress**
"American folklife" means the traditional expressive culture shared within the various groups in the United States: familial, ethnic, occupational, religious, regional; expressive culture includes a wide range of creative and symbolic forms such as custom, belief, technical skill, language, literature, art, architecture, music, play, dance, drama, ritual, pageantry, handicraft; these expressions are mainly learned orally, by imitation, or in performance, and are generally maintained without benefit of formal instruction or institutional direction;

**Digital Preservation**
Digital preservation is the whole of the activities and processes involved in the physical and intellectual protection and technical stabilization of digital resources through time in order to reproduce authentic copies of these resources. 

Digital preservation decisions are made on the basis of this Policy, the Library's Strategic Plan, the digital resources’ enduring value and the feasibility of the digital resources’ preservation. When possible, decisions about the need for preservation are made at the time of creation, acquisition, or licensing of digital resources. 

Preservation of digital resources may include any actions necessary to preserve continued access to the digital material, ensure its authenticity, mitigate and/or reverse the effects of hardware and software obsolescence and media decay. This Policy recognizes that the maintenance and the reliable long-term access to Yale’s digital resources are supported by a preservation planning function. Research (monitoring) about technology that supports a repository and the requirements of the designated community it serves is a core activity to preservation planning, as well as outreach and education regarding policies, procedures and best practices for digital resources. 

AFC recognizes there are occasions for *no preservation,* in which we cannot accept responsibility for collections. This may be because the collection files were corrupted or appropriate authorization for preservation actions were not established.

**Frequency of Policy Review**
This policy will be reviewed bi-annually to assure timely updates to reflect the maturing of the technology by the relevant body. 

**Criteria for determining preservation-levels"
AFC recognizes that not all collections require or mandate the same amount of processing, staff time, and resources. This flexiblity is at the heart of our interpretation of "more product, less process." Whether analog or digital, collections should be evaluated before they are accessionined to understand the responsibilities the repository is committing. Criteria can include:
(1) Rights - do we have the minimum rights to, for example, transform the work?
(2) Metadata - do we have sufficient intellectual controls and descritptive metadata to accept responsilbilty for the collection? Are we collecting sufficient metadata for the content type (for examples, images, photographs, sound recordings, audiovisual files)? 

With the accessioning of the collection, can we assign it a value, 1-4, on its preservation level?  This value can be based on the above as well as the obsoleteness of the collection, the condition of the carrier object (floppy disk, for example), the number of files and the collections size, and the types of files and their status as supported/unsuppported in the repositiory (Emory University's work)

**Authenticity** 
The mutable nature of digital resources opens the possibility for unauthorized and undetectable changes. Confidence in the authenticity of digital resources over time is particularly crucial owing to the ease with which alterations can be made. From the moment that digital resources are created or acquired, YUL undertakes protective procedures to prevent, discover, and correct loss or corruption of digital resources due to either inadvertent or malicious intent. In addition, supporting evidence, ideally in the form of metadata, must be provided to enable users to evaluate the authenticity of all preserved digital resources. 
	
Yale University Library employs both SHA1 and MD5 algorithms upon ingest.
Harvard University - MD5 required with deposit via SFTP to validate
AFC now requires MD5 in order to validate ingest to repository. When fixity is not cteated by donor, AFC staff will create manifest file before ingest.

The long-term authenticity of digital collections held by AFC will be verified using in-house tools created by LC, specifically CTS as of the time of this writing. 

Metadata: 
Preservation metadata includes a number of different types of metadata: administrative (used in managing information resources including rights and permissions), technical (describing hardware and software needed to maintain an information object) and structural (identifying the relationships between objects such as part of, dependent upon that form intellectual entities. Particular attention is paid to the documentation of digital provenance (metadata documenting the history of the object and any actions taken to maintain and provide access), and of relationships among different objects within preservation repositories (vs. relationships between resources, i.e., structural metadata). The preservation process must be able to understand, take in, and maintain metadata submitted with the digital resource while creating its own metadata to manage the preservation of that resource.

Pre-Accessioning/Donor
-The Digital Assets Manager should be notified and consulted of any major new digital collections accepted, preferably before any agreement is made 
-to assess for preservation and access concerns, including:
	-ensuring the archive is receiving the best quality, most well-supported, and 
most-understood files.
	-this can be accomplished through consulting the “Donor Pre-Accessioning 
Document” and communication with the DAM.
-to ensure that digital access and preservation concerns are understood by the donor, including:
-this can be done by having the donor sign the Creative Commons license to 
indicate future use restrictions.
		
examples:  A depositor of interactive digital objects may not agree to have migration processes applied to them if those processes change the look and feel of the interaction environment, or if some of the content of the objects is provided as part of the interaction environment. In this case the only agreed preservation approaches may be to use hardware emulation or original/replica hardware to preserve the content. Without an agreement in place at point of deposit (when the content is well understood) it may be impossible to make this judgment in the future without a great degree of expensive manual intervention.

	Deaccesioning note:

**Bagging**
-All content must be bagged before ingest 
	Any content from an external vendor should be bagged.
	Any content created internally must be bagged.
	Accessions from StoryCorps, NVLP, and other periodically accessioned collections must 
be bagged.
Donors with no bagging experience, with the help of the DAM, should use AVPreserve’s app.
	
-All content must have a complete Ruby record
include byte size and number of folders and files.
-No collection material should be altered or edited in any way before it is ingested into longterm preservation. This includes: changing file names, editing files, combining files.

Pre-conditiong (but even in these cases, better to ingest, pre-processing and then alter)
-adding and correcting the file extension
-excluding problematic characters

-all changes must be reversible
“All changes must have a “system-based provenance note that clearly describes the change that has been made to the file.”

**Processing**
If we decide that an active re-arrangement of files is necessary, the Archive will also record the directory structure.

In the initial assessment, each accession of a collection should be given a score  of 1-4 to indicate, very roughly, the processing difficulty and include: preservation actions needed; direction on format migration options; whether or not the digital collection is a high preservation risk. 


Technical analysis before excessive description 
what if files are junk?

*Validation**
Before ingesting processed collections into the repository, it is necessary that we ensure they are valid and well-formed.

**Defining SIP, AIP, DIP**

**SIP**

**AIP**
“to provide a concise way of referring to a set of information that has, in principle, all the qualities needed for permanent, or indefinite, Long Term Preservation of a designated Information Object.” (4-36)
(access rights, fixity, provenance, content information, reference information)

**DIP**
A DIP on the other hand, is intended for the “consumer,” meaning that DIPs contain the “access copies” of content. 

**Creation of Access Copies**
Until such time as we have assurances that we have space to create copies available, the DAM will create access copies before returning donor content locally if the Curator deems the collection likely in high demand.

Access
In preserving the accessibility of digital resources, the Library will: 
o Maintain information regarding rights and permissions governing access.
 o Maintain the means of accessing an acceptable presentation of the digital resource; 
 o Maintain the ability to locate the digital resource reliably. 




