---
title: "Update a Task Link"
type: docs
url: /update-a-task-link/
weight: 30
---

# **Introduction**
This example allows you to update a task link in a Project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/taskLinks|PUT|Update a existing task link|[PutTaskLink](https://apireference.aspose.cloud/tasks/#/TasksTaskLinks/PutTaskLink)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v https://api.aspose.cloud/v3.0/tasks/{documentname}/taskLinks?appsid=xxxx&signature=xxxx \

     -X POST \

	 -d {"dto": [{

  		"Link": {

    	"Href": "string",

    	"Rel": "string",

    	"Type": "string",

    	"Title": "string"

  		},

  		"Index": 0,

  		"PredecessorUid": 6,

  		"SuccessorUid": 1,

  		"LinkType": "string",

  		"Lag": 9600,

  		"LagFormat": "string"

		}]} \

	 -H "Content-Type: application/json" \

     -H "Accept: application/json"  



```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "code": 0,

  "status": "string",

  "taskLink": {

    "link": {

      "href": "string",

      "rel": "string",

      "type": "string",

      "title": "string"

    },

    "index": 0,

    "predecessorUid": 0,

    "successorUid": 0,

    "linkType": "FinishToFinish",

    "lag": 0,

    "lagFormat": "Minute"

  }

}

```

{{< /tab >}}

{{< /tabs >}}
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="3" tabID="4" tabName1="C#" tabName2="Python" tabName3="Node.js" >}}

{{< tab tabNum="1" >}}



{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "765de786e9815b9db6e2525ceb0cda8f" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "9cbeae487fe48f61c0c696116936d7cf" >}}

{{< /tab >}}

{{< /tabs >}}