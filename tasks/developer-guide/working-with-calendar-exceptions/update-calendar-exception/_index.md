---
title: "Update Calendar Exception"
type: docs
url: /update-calendar-exception/
weight: 30
---

## **Introduction**
This example explains you how to update calendar exception, using Aspose.Tasks Cloud. Aspose.Tasks Clous is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/calendars/{calendarUid}/calendarExceptions/{index}|PUT|Update a Calendar Exceptions|[PutCalendarException](https://apireference.aspose.cloud/tasks/#/TasksCalendar/PutCalendarException)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "https://api.aspose.cloud/v3.0/tasks/Home%20move%20plan.mpp/calendars/1/calendarExceptions/1" -H "accept: application/json" -H "Content-Type: application/json" -d "{ \"Index\":1, \"EnteredByOccurrences\":true, \"FromDate\":\"2019-08-13T00:00:00\", \"ToDate\":\"2019-08-13T23:59:00\", \"Occurrences\":0, \"Name\":\"New Test\", \"Type\":\"Daily\", \"Period\":1, \"DaysOfWeek\":[ ], \"MonthItem\":\"Undefined\", \"MonthPosition\":\"Undefined\", \"Month\":\"Undefined\", \"MonthDay\":0, \"DayWorking\":true, \"WorkingTimes\":[ { \"FromTime\":\"0010-01-01T23:16:00Z\", \"ToTime\":\"0010-01-01T23:16:00Z\" } ] }"    

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
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="4" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-PutCalendarException.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-putCalendarException.php" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "8b5f140e35a59c5a232fa0fc79d40724" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "86061cf7b844b0e79cde1ae857928a4d" >}}

{{< /tab >}}

{{< /tabs >}}
