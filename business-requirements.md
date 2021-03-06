# Use Cases

Assume a company with different departments who use different API Management solutions (because there was no rule to use a single API Management solution initially or the disparity was the result of a company merger). 
E.g. Department A uses WSO2 API Manager, Department B uses Apigee and Department C uses Kong. 

<b> Federated Publisher </b>
<p>Now the company wants to unify the API Creation process, and have a single place and one way to do this because the different solutions provide different ways of doing this. Most customers like WSO2 Publisher and would like to use it to publish the APIs using the same to different gateways. In most cases, they might not even be using the WSO2 API gateway, but come to us because they need a publisher portal to publish to their gateways. Why not switch to the full API management solution in that case? Due to time constraints and variations in price, organizations prefer to continue using their current gateways. 
</p>

	
<b> Federated Marketplace </b>
<p>They also want to allow internal and external application developers to discover the APIs and subscribe to them via a unified store. This is a federated marketplace. To unify a single portal that can work across multiple gateways of different vendors, a common API format is required - most of this can be achieved with Swagger/OAS 3.0. Marketplaces only have the store interface with security types etc. It’s a federated marketplace behaving as a single point of discovery of APIs.
</p>
