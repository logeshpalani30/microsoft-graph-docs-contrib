---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = UserScopeTeamsAppInstallationRequestBuilder.UserScopeTeamsAppInstallationRequestBuilderGetQueryParameters(
		expand = ["teamsAppDefinition"],
)

request_configuration = UserScopeTeamsAppInstallationRequestBuilder.UserScopeTeamsAppInstallationRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.users.by_user_id('user-id').teamwork.installed_apps.by_installed_app_id('userScopeTeamsAppInstallation-id').get(request_configuration = request_configuration)


```