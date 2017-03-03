to see documentation of changes: https://github.com/juliaykim/preservation_plan/blob/master/AFC_plan_overview.md
(Do not circulate draft document)

Frequency of Policies and Guidelines Review:
This policy will be reviewed bi-annually to assure timely updates to reflect the quickly changing digital preservation landscape, alongside reviews of self-assessment periods (ie.TRAC, LC Levels,...). While the policy and guidelines documentation is still nascent and will be actively worked on in the next few months, the next review is planned for September 2016.  tbd
AFC can only guarantee digital files when they are transferred with the known fixity values. Bagger (or a CLI tool, like "md5sum") should be used prior to file transfer to corroborate authenticity. Without this technical manifest, we can make no absolute guarantee. File corruption can (and does) happen for any number of reasons, including hardware failures in hard drives, network failures, and operator (human) failures.  In order to better preserve and create access to collections, AFC's SIP requirements include file and directory listing and their corresponding hash values as a way to verify perfect bit-level transfers. 
 The mutable nature of digital resources opens the possibility for unauthorized and undetectable changes. Confidence in the authenticity of digital resources over time is particularly crucial owing to the ease of alteration. From the moment that digital resources are created or acquired, AFC undertakes protective procedures to prevent, discover, and correct loss or corruption of digital resources. In addition, supporting evidence, ideally in the form of metadata, must be provided to enable users to evaluate the authenticity of all preserved digital resources.

Digital preservation is the whole of the activities and processes involved in the physical and intellectual protection and technical stabilization of digital resources through time in order to reproduce authentic copies of these resources.
Digital preservation decisions are made on the basis of this Policy, the Library's Strategic Plan, the digital resources’ enduring value and the feasibility of the digital resources’ preservation.
When possible, decisions about the need for preservation are made at the time of creation or acquisition. 
Preservation of digital resources may include any actions necessary to preserve continued access to the digital material, ensure its authenticity, mitigate and/or reverse the effects of hardware and software obsolescence and media decay.
This Policy recognizes that the maintenance and the reliable long-term access to digital resources are supported by a preservation planning function, research (monitoring) about technology that supports a repository and the requirements of the designated community it serves, as well as outreach and education regarding policies, procedures and best practices for digital resources.
AFC recognizes that not all collections require or mandate the same amount of processing, staff time, and resources. In the initial assessment, each accession of a collection should be evaluated and designated a tier level of 1-5 to indicate, very roughly, the resources required for the collection. Difficulty (Tier 4) would indicate major preservation actions needed because of corrupt or obsolete file types; older physical carriers (floppy disks), a large collection size, complicated or unclear rights, and a high-priority (mandated collection or grant funded collection, for example) project. All of these factors combined would require much more resources. 


Processing difficulty	
Tier 1
Tier 2
Tier 3
Tier 4
Tier 5
Files types and material is:
Broadly supported/simple
Moderately supported
Large quantity or large size
 more complexity
Unsupported file types
Have many obsolete/proprietary dependencies. 
Many pieces of media.
Highly complex – interactive, has many components and dependencies
Examples
.txt, .pdfA

.mp4, doc(x), ppt(x), xlx,.wav, .mov
collections w/hundreds of audiovisual interviews 
databases
Ps4, wmp, rmp…quick books
collection with hundreds of optical media with VCD file system
Video games, complex artwork,
DPX files



While the majority of AFC's current incoming collections are in the Tier 1 and Tier 2 category, AFC also has many collections that need to be re-processed because of their Tier1-4 status. These collections present additional complications due to the increased lag in time and the quick (2-5 year) cycles of digital obsolescence. Collection acquired only several years ago may require extensive preservation migration actions.
AFC recognizes there also are occasions for no preservation, in which we cannot accept responsibility for collections. This may be because the collection files were corrupted, or appropriate authorization for preservation actions were not established. This recognizes that AFC can preserve a limited number of supported formats, and can provide limited support to less known, less-adopted, and proprietary formats (see http://www.digitalpreservation.gov/formats/).
AFC recognizes that not all collection can or should be processed at the highest or "best practice" level.

Processing levels	
Tier 1 - "Dark Archive"
Files are copied
Tier 2 - Bit Level Security
Pre-processing
Tier 3  - Content level Management
Minimal to moderate processing
Tier 4 -
Moderate processing
Tier 5 - Preservation and Access
Characteristic
Traits
Not migrated from physical media (floppy, optical, hard drive) or copied to longterm preservation tape to pre-processing space
little to no processing, little to no access, little to no access points for patrons
Copy to longterm preservation pre-processing
Collection-level patron access point,
Collection-level Ruby inventory records
Copy to longterm preservation, copied to processing for processing work
file level validation and QC, renaming, excluding invalid characters.
technical metadata (exiftool, medianinfo, FITS/jhove)
SIP level Ruby records

Copy to longterm storage, copy to processing, prepare for online access.
hierarchical metadata and/or preservation metadata, administrative metadata collected
Finding Aid
P1 online access
Copy to longterm storage, copy to processing, online access
hierarchical structured metadata
Finding Aid
File level records in Ruby database.
Files are migrated, if needed.
Examples	
early accessioned collections,
almost all collections with optical media or floppy disk
StoryCorps.Me

most 2015 accessioned collections (see below)

to some degree, AFC Field Projects collections.
Civil Rights History Project


 Pre-Processing
As we develop our new full-processing procedures, a short-term solution is to minimally process digital content. This has been the default processing tier for most collections the past 1.5 years.
Characteristics of the pre-procesing workflow are:
Files are never renamed, changed, or qc'ed otherwise.
If content was not bagged content, it's optional to bag them.
Minimal "sip" and "hdd" level Ruby records should be created (although AFC recognizes that this has not always been the case due to staff contsraints- ex: most of AFC Field Projects)
Files are transferred via FileZilla and CTS to lcbp/afc/afcasreceived, not to their afc collection sub-directory. See Workflow Document.

Processing collections, however, should include QC, checking vendor records against what we've received, running file identification and assessment tools, and making any modifications to the file (such as renaming or re-organizing files).
The files on "asrecie

AFC naming conventions
*Consult with Julia before renaming any files.

Hard drive and physical media naming
AFC has traditionally named hard drives and physical media with digital content on them in the following format, for ex: afc2004004_hdd_20160613.
In the case of media with already given donor names,  AFC's practice has been to incorporate original names in a middle string, for ex: afc20000001_1254_cf01.
In the case of optical media, AFC had previously often confused practices of distinguishing between: sound ("sr"), moving image ("mv"), and computer file ("cf") for ex: afc2000001_sr01 and afc200001_mv01.

SIP naming (corresponds to cts "bag id"), directory, and file naming conventions
AFC has traditionally named SIPs (or "submission information packages") following hdd naming conventions: afc2004004_sip_20140202_01.
the string "20140202" is meant to indicate SIP creation date.
the string "01" is for versioning practices, in case multiple SIPs were created from the same collection on the same date.
the above practices allowed AFC to easily meet the unique collection-level SIPs names that are a prerequisite for using CTS.

afc2004004_sr01 [for sound recordings]
afc2004004_ph01 [for photographic images]
afc2004004_ms01 [for manuscripts, or scans of documents]
afc2004004_mv01 [for digital video]
afc2004004_cf01 for [computer files]* problematic

~or~

afc1945016_ct4292_0001.tif [example from afc9999008 Lomax Jackets projects where we referred to containers], where
afc9999008_ms0025_0001.tif  [another example from the dusk jackets for loose manuscript pages]
note the shift to four digit numbering systems.cd
processing/afc1940001/afc1940001_xxxx/afc1940001_xxxx_01.tif
afc9999008/afc9999008_ms0003/afc9999008_ms0003_0001.tif in cts bag afc9999008_01.

Ruby Metadata
Documentation for defining metadata fields for Ruby Oracle Database. For documentation on how to upload the files, see the all-in-one workflow documentation.
Ruby includes multiple layers of records and can also track progress and processes.
Ruby includes:
collection level records,
hdd (the physical media, or hard drive), as well as
sip (submission information package), and
aip and dips records (not defined  or in use currently).
Create Ruby Collection level record if it does not exist:
Click on Collections.
Click on Create.
For Coll Number, type AFC YYYY/### (Ex.: AFC 2015/037).
For Coll Number Norm, type afcYYYY### (Ex.: afc2015037).
For Coll Title, copy & paste the formal title from the record in the AFC Collections Database.
For Remediated, choose Process while you are processing the collection.
Click Create to make and save the collection record in Ruby.


 
Acquire content from HDD, CD, DVD, flash drive, FTP, or another method. 
Create the parent HDD record in Ruby w/the dropdown:

 

If you are transferring files using FileZilla and there is no SIP folder for the content on the F drive, you need to create one.
Create a new folder on the F drive.
Name it based on the SIP naming convention: afcYYYY###_sip_YYYYMMDD_01 (Ex.: afc2015037_sip_20150921_01). 
If collection size is small (it will transfer in 1 hour or is less than 50 GB), copy sip files into a new SIP folder on the F drive (F:\DigitalStorageMgmt\dropbox\Workspace).
Check and make sure all files transferred completely by comparing total byte size and number of folders. Before moving files over via FileZilla, make sure you structure them in SIP folders not in excess of 1 TB. You will not be able to change the directory structure after they have been moved to staging (sh_ingest).
If you encounter an upload problem (i.e., bytes and/or file size don’t match) create a new sip based on the old one, but add “_ver01”
Confirm that total bytes and the file count for the local files match the total bytes and the file count for the remote set of files
Next, add a new Ruby record for each SIP:
Navigate to Collections & the desired collection number.
Choose  Add New Directory/Bag/Drive
Next, fill out the field as follows:
For OAIS Class, select SIP.
Parent HDD is n/a if the files are “loose” and not transferred on external media. 
Enter the Bag ID (or Drive ID) as afcYYYY###_sip_YYYYMMDD_01 
Ex.: afc2005046_sip_20130725_01.
Enter the AFC Collection Number (Normalized): afcYYYY### 
Ex.: afc2005046.
For Server, select sun9.
For Full Path, use format: /sh_ingest/afc/ afcYYYY###_sip_YYYYMMDD_01 
Ex.:/sh_ingest/afc/afc2005046_sip_201307025_01).
If ingesting using the Madison ingest station (and not FileZilla), the path would change.
    Ex.:/lcbp / afc / afcasreceived/ afc2005046_sip_201307025_01/.
For Content Type, choose one:
Manuscripts
Mixed
Moving images
Sound recordings
Still images
For Content Range, enter the first & last files of an SIP folder 
Ex.: afc2005046_sr01.aif – afc2005046_sr02.aif    (range is indicated with “space hyphen space”)
For Note, enter total bytes size, number of files, and number of folders
Ex: 903046379168 bytes, 279 files, 13 folders.
Feel free to enter more information, but separate it with a hard return and enter on the next line.    
For Project Name, select which most applicable: AFC—Digital Acquisitions or AFC—Collections Digitization.
For Content Access, leave default “lcstaff only.”

 






