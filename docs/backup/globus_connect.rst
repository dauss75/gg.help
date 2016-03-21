Globus Connect
==============

Globus Transfer
+++++++++++++++

There are three types of Globus endpoints you can setup based:

1. Globus Connect Personal:
   - This is ideal of individual users and the endpoint will be associated only with your Globus account. It is ideal for you laptops or other personal computers. Following are some pointers for more details:
      - Globus Connect personal: https://www.globus.org/globus-connect
      - Firewall/Ports requirements: https://support.globus.org/entries/20999718-What-ports-does-Globus-Connect-Personal-need-open

2. Globus Connect Server:
   - Ideal for shared hosts where multiple users can use the endpoint, e.g: lab clusters, research computing facilities, server hosts, etc. Provides data sharing capabilities. Following are the pointers on how to install and configure a GCS:
      - Globus Connect Server: https://www.globus.org/globus-connect-server
      - Firewall/Ports requirements: https://support.globus.org/entries/20999723-What-ports-does-Globus-Connect-Server-need-open

3. AWS S3 Endpoint (Requires Subscription):
   - Allows you to create a logical endpoint using a single AWS S3 bucket. This allows you to transfer data from any other Globus endpoint to a S3 endpoint:
      - Amazon S3 endpoint: https://www.globus.org/amazon-web-services/s3-endpoint-configuration
