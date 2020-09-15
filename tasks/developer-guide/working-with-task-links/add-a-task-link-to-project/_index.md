---
title: "Add a Task Link to Project"
type: docs
url: /add-a-task-link-to-project/
weight: 20
---

# **Introduction**
This example allows you to add a task link to a Project using Aspose.Tasks Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
### **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/taskLinks|POST|Add a new task link|[PostTaskLink](https://apireference.aspose.cloud/tasks/#/TasksTaskLinks/PostTaskLink)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -v http://api.aspose.cloud/v3.0/tasks/{documentname}/taskLinks?appsid=xxxx&signature=xxxx \

     -X POST \

	 -d {"dto": [{

  		"Link": {

    	"Href": "string",

    	"Rel": "string",

    	"Type": "string",

    	"Title": "string"

  		},

  		"Index": 1,

  		"PredecessorUid": 6,

  		"SuccessorUid": 1,

  		"LinkType": "string",

  		"Lag": 0,

  		"LagFormat": "string"

		}]} \

	 -H "Content-Type: application/json" \

     -H "Accept: application/json"  



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
# **SDK Source**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/available-sdks/)
## **SDK Examples**
{{< tabs tabTotal="9" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Android" tabName6="Objective C" tabName7="Perl" tabName8="Python" tabName9="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-DotNET-CSharp-TaskLinks-AddTaskLink-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-tasks" "23b0f75cdca18da366acbc7b03948573" "Examples-JAVA-src-main-java-com-aspose-tasks-cloud-tasks-AddTaskLinkToProjectExample-AddTaskLinkToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "" "72c1e50fb93c3d7198242d06647df3d5" "Examples-PHP-Tasks-PostTaskLink-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "" "df32dc1897c82032a59a48474217bfe0" "Examples-Ruby-Tasks-add\_new\_task\_link\_to\_project-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-tasks" "d6f826e62b6c0277a2aad6ea116bbdfa" "Examples-Android-app-src-main-java-com-aspose-tasks-examples-cloud-tasks-AddTaskLinkToProjectExample-AddTaskLinkToProjectExample.java" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "" "e59b9df657ee5aacd1f25a6884554362" "Examples-Perl-TaskLinks-AddTaskLink-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< gist "aspose-cloud" "4d75afe3593b4e28643604c561fb2286" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "863f2199f7870ff9c0cf503d3109fd98" >}}

{{< /tab >}}

{{< /tabs >}}