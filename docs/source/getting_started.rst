***************
Getting Started
***************

Installing Globus Endpoints
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. topic:: How to Set Up New Endpoints

     - Please visit `Globus Connect <https://www.globus.org/globus-connect>`_ 
     - Select `Globus Connect Personal <https://www.globus.org/globus-connect-personal>`_ if you are researchers and other end users 
     - Select `Globus Connect Server <https://www.globus.org/globus-connect-server>`_ if you are network and system administrators
     - The web link should be self-explanatory with all the details on installation; however, for any issues and questions please contact us at support@globus.org

   .. figure:: figs/gg_1.png 

Access to Globus Genomics Instance
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. topic:: How to Access to Globus Genomics (i.e., https://cgi.globusgenomics.org)

    - Register at http://www.globus.org and send your login name to support@globus.org
    - Once registred, go to https://www.globus.org/groups#id=a172c434-66eb-11e5-8d97-22000ab80e73
    - Click on **Search** and put keyword of your group    
    - Once you find the group of interest, click the group name followed by  **Join Group** that will send a message to an administrator who can approve your request.
    - Once you are added to the group, you can login to https://cgi.globusgenomics.org with your globus username/passwd.

   .. figure:: figs/gg_2.png

.. topic:: How to Transfer Data

    - Login to your Globus Genomics instance
    - From the tool panel, go to **Globus Data Transfer** -> **Browse and Get Data via Globus Online**
    - Set **Source Endpoint** and **Source Path** and then click **Execute** 
    - For bulk transfers, please contact us at support@globus.org

   .. figure:: figs/gg_3.png

   .. figure:: figs/gg_4.png


Globus Connect
^^^^^^^^^^^^^^

.. topic:: Three different types of Globus endpoints are available to setup

   1. Globus Connect Personal (GCP):
      
   - Ideal for individual users using personal computers, and the endpoint will be associated only with the user's Globus account. Please follow the web links for more details:
      
      - GCP: https://www.globus.org/globus-connect
      
      - Firewall/Ports requirements: https://support.globus.org/entries/20999718-What-ports-does-Globus-Connect-Personal-need-open


   2. Globus Connect Server (GCS):
     
   - Ideal for shared hosts where multiple users can use the endpoint, e.g., lab clusters, research computing facilities, server hosts, etc. Please follow the web links for more details on how to install and configure a GCS:
      
      - GCS: https://www.globus.org/globus-connect-server

      - Firewall/Ports requirements: https://support.globus.org/entries/20999723-What-ports-does-Globus-Connect-Server-need-open

   3. AWS S3 Endpoint (**Requires Subscription**):
      
   - Allows you to create a logical endpoint using a single AWS S3 bucket. This allows you to transfer data from any Globus endpoints to a S3 endpointi. Please follow the web link for further details:
      
      - Amazon S3 endpoint: https://www.globus.org/amazon-web-services/s3-endpoint-configuration
