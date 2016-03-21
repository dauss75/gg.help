How to use Admin/Data Library Panel
===================================

I have made you the admin of the Galaxy instance. Please be very careful in how you use some of the features :) If you are not sure of any features, please let us know before you use them.

With that disclaimer let me show you how to use use this feature:

1. Once you login, you should see a new “Admin” link in the top menu. Click on that and that should show a new interface and new menu on the left panel.
2. Click on “Manage data libraries” under “Data” section and click on “Create a new data library”.
3. Give a name to the library (avoid spaces if possible), and then once the library is created, click on “Add datasets”
4. Now, on this screen you will see a couple of options that are important: Please look at the screenshot below:

   - Select "Upload files from filesystem paths”
   - Then under Paths to upload, use the path to the files or folder that has the files. This would the path that you have in the email below (without ~ ). For example, /scratch/kumc2/go/rama/genomics/fridley/Mayo-RNASeq/Endometrioid/
   - Under Copy data to Galaxy, select “Link to files without copying to Galaxy” so that you are not making multiple copies of the same files
   - Check “Preserve directory structure” if you have a lot of files in different folders. You can uncheck, if you want all the files at just one level.
   - then lastly, select “Genome” to be hg19 or anything appropriate for your samples.
   - and finally click on “Upload to library”. Then you will see all the files listed in that library. It typically takes sometime to appear.

Let me know if you have any questions.
By the way, Galaxy folks also have a detailed tutorial on this section if you want to take a look: https://wiki.galaxyproject.org/Admin/DataLibraries/Libraries But it might take the whole day to read through it :) Its just too long.
