Shared Library using Globus
===========================

1. Login to www.globus.org and select the endpoitns

2. Transfer your files inside the /scratch/averahealth/go/<username>/<gatk_bundle> folder.

3. Once you transfer is completed, go to the Galaxy instance and to the Shared library to which you want to add the datasets:

4. From the Upload files to a data library interface:
 
   - Select “Upload files from filesystem paths”
   - If you know the format of the files, select that.
   - Under Paths to Upload, paste the path of the folder from Step 2 above (Don’t include /~/).
   - Select “Link to files without copying into Galaxy” so as not to replicate the files.
   - Genome: Select HG19 or the appropriate one
   - And click Submit.

5. That should add the files to the library. It takes a few minutes to detect the file format.
