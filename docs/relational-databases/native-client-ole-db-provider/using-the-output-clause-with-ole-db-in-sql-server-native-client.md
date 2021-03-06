﻿---
title: "Using the OUTPUT Clause with OLE DB in SQL Server Native Client | Microsoft Docs"
ms.custom: ""
ms.date: "03/03/2017"
ms.prod: "sql"
ms.prod_service: "database-engine, sql-database, sql-data-warehouse, pdw"
ms.service: ""
ms.component: "native-client-ole-db-provider"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 

ms.tgt_pltfrm: ""
ms.topic: "reference"
ms.assetid: 53deeb99-c088-4fde-844b-b2d91d6de1eb
caps.latest.revision: 7
author: "MightyPen"
ms.author: "genemi"
manager: "craigg"
monikerRange: ">= aps-pdw-2016 || = azuresqldb-current || = azure-sqldw-latest || >= sql-server-2016 || = sqlallproducts-allversions"
---
# Using the OUTPUT Clause with OLE DB in SQL Server Native Client
[!INCLUDE[appliesto-ss-asdb-asdw-pdw-md](../../includes/appliesto-ss-asdb-asdw-pdw-md.md)]
[!INCLUDE[SNAC_Deprecated](../../includes/snac-deprecated.md)]

  If you use an OUTPUT clause in an INSERT, UPDATE, DELETE, or MERGE command, the count of affected rows is not available. The application must count the number of rows in the rowset that is returned by the OUTPUT clause.  
  
## See Also  
 [Creating a SQL Server Native Client OLE DB Provider Application](../../relational-databases/native-client-ole-db-provider/creating-a-sql-server-native-client-ole-db-provider-application.md)  
  
  
