---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = AccessPackageResourceRoleScope(
	role = AccessPackageResourceRole(
		id = "cde82ecb-e461-496b-98fb-4f807c7ca640",
		display_name = "Standard User",
		description = "Standard User",
		origin_system = "AadApplication",
		origin_id = "a29a7690-b3c4-4ed5-96c6-f640cde06fb8",
		resource = AccessPackageResource(
			id = "5f80c0c7-a180-4521-b585-18200048a0d8",
			origin_id = "e81d7f57-0840-45e1-894b-f505c1bdcc1f",
			origin_system = "AadApplication",
		),
	),
	scope = AccessPackageResourceScope(
		id = "dbeb8772-9907-4e95-a28e-a8d70dbcda69",
		origin_id = "e81d7f57-0840-45e1-894b-f505c1bdcc1f",
		origin_system = "AadApplication",
		is_root_scope = True,
	),
)

result = await graph_client.identity_governance.entitlement_management.acce_packages.by_acce_package_id('accessPackage-id').resource_role_scopes.post(body = request_body)


```