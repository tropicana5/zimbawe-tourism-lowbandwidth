**Project**: 

Creating a low-bandwidth tourism website with compatibility for handheld devices



**The Problem:**

Many Zimbabwean tourism websites rely on large images, video and heavy scripts. Mobile data is costly and connections vary from one region to another due to infrastructural and geographical challenges. As a result potential visitors and local travelers may lose interest and leave before a page loads, and operators lose enquiries as a result.



**The Objective:**

This project examines how well three real tourism websites namely: Zimbabwe Tourism Authority, Zimbabwe National Parks and Victoria Falls Safari Lodge perform under low-bandwidth conditions highlighting the weaknesses and coming up with a possible solution that improve the usability and performance of Zimbabwean tourism websites for low end devices and slow internet speeds. For this survey i will be using Google Chrome’s Web developer tool DevTools to run a mobile simulation of the cellphone model Google Pixel 9 which will be capped to 3G for network connectivity which will be sufficient to imitate a cellphone set to roaming. For feedback on site accessibility scores and averages I will be using the auditing tool Lighthouse built into Devtools as well as PageSpeed online auditor.



**Target user**

1. A local traveler browsing on a limited mobile data bundle.
2. An international visitor planning a trip on a slow or roaming connection plan.
3. A small operator who needs enquiries to reach them easily, for example through WhatsApp.



Below are the test results from all 3 websites:





|Measure|ZTA|ZimParks|Vic Falls Safari Lodge|
|-|-|-|-|
|Connection setting used|Slow 4G|Slow 4G|Slow 4G|
|Total page weight, homepage (MB)|5.1|16|25.8|
|Number of requests|102|177|128|
|Load time (seconds)|0.692|84|26.7|
|Largest Contentful Paint (seconds)|9.3|11.6|19|
|Lighthouse Performance score (mobile)|91|93|88|
|Largest image: size (KB) and format|1,026|1,804|20,996|
|Images larger than the screen needs (yes/no)|yes|yes|yes|
|Autoplay video, carousel or slider (yes/no)|yes|yes|yes|
|Third-party scripts (count)|19|17|29|





