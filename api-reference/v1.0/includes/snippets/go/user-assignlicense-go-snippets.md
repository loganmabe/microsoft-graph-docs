---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.New()
requestBody.SetAddLicenses( []AssignedLicense {
	msgraphsdk.NewAssignedLicense(),
	SetAdditionalData(map[string]interface{}{
		"disabledPlans":  []String {
			"11b0131d-43c8-4bbb-b2c8-e80f9a50834a",
		}
		"skuId": "45715bb8-13f9-4bf6-927f-ef96c102d394",
	}
}
requestBody.SetRemoveLicenses( []String {
	"bea13e0c-3828-4daa-a392-28af7ff61a0f",
}
result, err := graphClient.Me().AssignLicense().Post(requestBody)


```