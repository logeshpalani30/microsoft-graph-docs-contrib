---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)


result = await graph_client.print.printers.by_printer_id('printer-id').task_triggers.by_task_trigger_id('printTaskTrigger-id').get()


```