Data Transfer and Endpoint Testing
==================================

**Here are a few details on how to first verify your S3 endpoint is working and then transfer the tar file to the genomics instance.**

1. Login to https://www.globus.org/xfer/StartTransfer and then select your S3 endpoint (which I think would be bcoon#globusHli). If you see the listing for the files, it means you have access to the endpoint.

2. Test: if you want to test the transfers, you can select a test endpoint called go#ep1 on the right hand side window and try a very small transfer (less than 1or2Mb files). Screenshot below shows this:

3. Transfer the Tar file to Globus genomics:

- Go to hlizero.globusgenomics.org and create a new history by using the top-right gear.
- Under Globus Data Transfer in left tool panel, select “Get Data via Globus Online” (2nd tool).
- Then provide the endpoint name and path to the flow-cell tar-file. (Currently it only support file transfers and not folders),
- Provide a larger deadline (1000) just in case, and click Execute.
