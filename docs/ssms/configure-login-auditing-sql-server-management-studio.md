---
title: "Configure Login Auditing (SQL Server Management Studio) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2017"
ms.prod: sql
ms.prod_service: "sql-tools"
ms.reviewer: ""
ms.technology: ssms
ms.topic: conceptual
helpviewer_keywords: 
  - "auditing [SQL Server]"
  - "audits [SQL Server], logins"
  - "logins [SQL Server], auditing"
ms.assetid: 16961116-57ac-4eef-8037-791b26ade548
author: "markingmyname"
ms.author: "maghan"
manager: craigg
---
# Configure Login Auditing (SQL Server Management Studio)
[!INCLUDE[tsql-appliesto-ss2008-xxxx-xxxx-xxx-md](../includes/tsql-appliesto-ss2008-xxxx-xxxx-xxx-md.md)]
This topic describes how to configure login auditing in [!INCLUDE[ssCurrent](../includes/sscurrent-md.md)] to monitor [!INCLUDE[ssDEnoversion](../includes/ssdenoversion_md.md)] login activity. Login auditing can be configured to write to the error log on the following events.  
  
-   Failed logins  
  
-   Successful logins  
  
-   Both failed and successful logins  
  
You must restart [!INCLUDE[ssNoVersion](../includes/ssnoversion-md.md)] before this option will take effect.  
  
## <a name="SSMSProcedure"></a>Using SQL Server Management Studio  
  
#### To configure login auditing  
  
1.  In [!INCLUDE[ssManStudioFull](../includes/ssmanstudiofull-md.md)], connect to an instance of the [!INCLUDE[ssDEnoversion](../includes/ssdenoversion_md.md)] with Object Explorer.  
  
2.  In Object Explorer, right-click the server name, and then click **Properties**.  
  
3.  On the **Security** page, under **Login** auditing, click the desired option and close the **Server Properties** page.  
  
4.  In Object Explorer, right-click the server name, and then click **Restart**.  
  
