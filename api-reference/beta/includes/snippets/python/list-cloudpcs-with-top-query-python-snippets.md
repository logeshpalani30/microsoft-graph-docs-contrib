---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = CloudPCsRequestBuilder.CloudPCsRequestBuilderGetQueryParameters(
		top = 2,
)

request_configuration = CloudPCsRequestBuilder.CloudPCsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.device_management.virtual_endpoint.cloud_p_cs.get(request_configuration = request_configuration)


```