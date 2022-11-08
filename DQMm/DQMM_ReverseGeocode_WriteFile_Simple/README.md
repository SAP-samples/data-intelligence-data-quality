Example for performing reverse geocoding using DQMm operators to call Data Quality Management microservices
===========
#### Description
The DQMm Reverse Geo operator creates a request from data that can be passed to the DQMm Client operator to be sent to the service.

#### Prerequisites
* Subscription to the Data Quality Management, microservices for location data service.

#### Configure and Run the Graph
Follow the steps below to run the example from the Data Pipeline UI:

1. Start the DQMm Reverse Geo demo graph (com.sap.demo.dqmm.reverseGeo).

2. Set the host of the DQMm application URL in the DQMm Client operator.

3. Choose either to authenticate using basic or oauth. You can use basic if you are accessing your subscription from your account on Trial. Use oauth if you are accesing your subscription from your account on a Factory landscape.

4. If you are using ouath, log into your SAP Cloud Platform account and create an OAuth client for your subscription.

5. In the DQMm Client operator, set the OAuth Token URL, Client ID, and the Client Secret.

6. By default, the graph writes the output to the /tmp folder. Change this if you want the result written to another folder.

7. Start this demo graph, which will automatically start invoking a series of operations.

<br>
<div class="footer">  
   &copy; 2021 SAP SE or an SAP affiliate company. All rights reserved.
</div>
