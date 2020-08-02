# thsconline command line tool

## System Requirements:
* Windows 8.1 and Windows 10 supported, with Powershell v4.0 or v5.0 installed.
* Windows 7 will need to install Microsoft .NET Framework 4.5 and Windows Management Framework 4.0.
* Mac and Linux not currently supported. It may work with Powershell Core on newer versions, however this has not been tested and may have unexpected results.

## Command Line Parameters
* _get_ - the path to retrieve files from (drop extension, see examples below)

Examples:
  > GET value of /s/yr12/Maths/trialpapers_extension2  will grab all files associated with this website. In this case it will grab the Maths Ext 2 trial papers.
  
  > GET value of /json/5340 will grab all files linked with view number 5340. In this case will download all the HSC papers for Maths Ext 2

  > GET value of /s/upload will start the Bulk Upload File service.

* _filter_ - filter out particular files
 
Examples
  > FILTER value of James Ruse, will grab all James Ruse papers on a page
  
  > FILTER value of 2019, will grab all 2019 papers on a page

  > FILTER value of w. sol, will grab all papers with solutions on a page

* _filepath_ - output folder path.

 Examples
  > FILEPATH value of C:\Temp will download all files to the C:\Temp folder
