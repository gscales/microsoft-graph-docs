---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewBaseTaskList()
displayName := "Travel Plan"
requestBody.SetDisplayName(&displayName) 

result, err := graphClient.Me().Tasks().ListsById("baseTaskList-id").Patch(context.Background(), requestBody, nil)


```