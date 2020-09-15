---
title: "Add Assignment to Project With Cost"
type: docs
url: /add-assignment-to-project-with-cost/
weight: 50
---

# **Introduction**
This API allows you to add assignments to your project file with specifying its cost and returns assignment item in a response.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/assignments|POST|Add a new assignment to a MS Project File|[PostAssignment](https://apireference.aspose.cloud/tasks/#/TasksAssignments/PostAssignment)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v "https://api.aspose.cloud/connect/token" 

-X POST 

-d "grant\_type=client\_credentials&client\_id=78946fb4-3bd4-4d3e-b309-f9e2ff9ac6f9&client\_secret=b125f13bf6b76ed81ee990142d841195" 

-H "Content-Type: application/x-www-form-urlencoded" 

-H "Accept: application/json"

```

```java

curl -X POST "https://api.aspose.cloud/v3.0/tasks/Cost\_Res.mpp/assignments?taskUid=0&resourceUid=1&cost=2" 

-H "accept: application/json" 

-H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "Code": "200",

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="5" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "d4e1ff37b441a508b2149192768cd567" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "c698f3b7905f5b8b18814a5edecb5e8a" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "1d12645f59e675ba65a3df56cdce596c" >}}

{{< /tab >}}

{{< /tabs >}}