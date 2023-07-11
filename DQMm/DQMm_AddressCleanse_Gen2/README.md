Example for performing address cleansing using the REST API Client operator to call Data Quality Management microservices
===========
#### Description
A Python operator is used to format a table of data into individual requests for the REST API Client operator. The REST API Client operator sends the requests to the Data Quality Management microservices service and passes the responses to a Python operator. The Python operator parses the responses and outputs CSV formatted data. The CSV data is then output to a Terminal operator.

#### Prerequisites
* Subscription to the Data Quality Management, microservices for location data (Data Quality Services).



#### Create the Connection object

A Connection object needs to be created which contains the connection and credential information for calling the Data Quality Services instance.

Follow the steps below to create the Connection object:

1. Open the Data Intelligence Launchpad and open the **Connection Manager**.

2. Click on the Create Connection icon.

3. Set **Connection Type** to HTTP.

4. Enter dqmm in the **Id** field.

5. Enter the host of the application URL for your subscription into the **Host** field.

6. Enter 443 into the **Port** field.

7. Enter /dq into the **Path** field.

8. Select OAuth2 in the **Authentication** field.

9. Select client_credentials in the **OAuth2 Grant Type** field.

10. Enter the token endpoint into the **OAuth2 Token Endpoint** field.

11. Enter your client ID into the **OAuth2 Client ID** field.

12. Enter your client secret into the **OAuth2 Client Secret** field.



<br>
<div class="footer">  
   &copy; 2023 SAP SE or an SAP affiliate company. All rights reserved.
</div>
