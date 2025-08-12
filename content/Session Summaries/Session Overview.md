---
{"publish":true,"created":"2024-06-09T12:47:52.000+02:00","modified":"2025-08-12T18:22:51.480+02:00","cssclasses":""}
---


[[index\|🏠 Back Home]]

>[!iinfo] Main Campaign Sessions 
>```dataview
 TABLE join(Date, ", ") AS Date, join(In-Game-Date, ", ") AS "In Game Date", join(link(whichparty), ", ") AS "Party", join(link(Current_Location), ", ") AS "Location"
 FROM #session-notes-summary and #maincampaignsummary
 
 SORT Session ASC

#TODO 
- [ ] someshot summaries
- [x] rest of main campaign summaries