---
title: NSDocument[] GetProjectDocumentsByTemplateTypes(Integer projectId, DateTime startTime, DateTime endTime, Integer count, Integer[] documentTemplateIds)
path: /EJScript/Classes/NSDocumentAgent/Member functions/NSDocument[] GetProjectDocumentsByTemplateTypes(Integer p_0, DateTime p_1, DateTime p_2, Integer p_3, Integer[] p_4)
intellisense: 1
classref: 1
sortOrder: 2488
keywords: GetProjectDocumentsByTemplateTypes(Integer,DateTime,DateTime,Integer,Integer[])
---


Method that returns a specified number of document appointments within a time range, filtered by document template types. The document appointments belong to the project specified.



* **projectId:** The project id
* **startTime:** The start of the time interval we want appointments from. This will usually be the current time.
* **endTime:** The end of the time interval.
* **count:** The maximum number of appointments that should be returned. -1 means no count restrictions.
* **documentTemplateIds:** Ids of the document template types to filter on.
* **Returns:** Array of Appointments.


