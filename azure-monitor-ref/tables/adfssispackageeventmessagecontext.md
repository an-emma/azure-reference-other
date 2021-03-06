---
title: Azure Monitor Logs reference - ADFSSISPackageEventMessageContext
description: Reference for ADFSSISPackageEventMessageContext table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 4/30/2020
---

# ADFSSISPackageEventMessageContext

 ADF SSIS package execution event message context

## Solutions

- LogManagement




## Columns

|Column|Type|Description|
|---|---|---|
|Category|string|The name of the log that belongs to|
|ContextDepth|int|Context depth|
|ContextSourceId|string|Context source Id|
|ContextSourceName|string|Context source name|
|ContextType|int|Context type|
|CorrelationId|string|correlation id|
|DataFactoryName|string|Data factory name|
|IntegrationRuntimeName|string|Integration runtime name|
|Level|string|Verbosity level of log|
|OperationId|long|Operation id|
|OperationName|string|The name of the operation represented by this event|
|PackagePath|string|Package path|
|PropertyName|string|Property name|
|PropertyValue|dynamic|Property value|
|_ResourceId|string||
|SourceSystem|string||
|TenantId|string||
|TimeGenerated|datetime|The timestamp (UTC) of the log|
|Type|string||
