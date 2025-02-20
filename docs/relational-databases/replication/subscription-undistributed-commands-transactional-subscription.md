---
title: "Undistributed Commands (Replication Monitor)"
description: Describes the 'Undistributed Commands' tab of the Replication Monitor in SQL Server Management Studio (SSMS).
author: "MashaMSFT"
ms.author: "mathoma"
ms.date: "03/07/2017"
ms.service: sql
ms.subservice: replication
ms.topic: conceptual
ms.custom: updatefrequency5
f1_keywords:
  - "sql13.rep.monitor.subscription.performance.f1"
monikerRange: "=azuresqldb-current||>=sql-server-2016"
---
# Subscription, Undistributed Commands (Transactional Subscription)
[!INCLUDE[sql-asdb](../../includes/applies-to-version/sql-asdb.md)]
  The **Undistributed Commands** tab displays information about the number of commands in the distribution database that have not been delivered to the selected Subscriber, and the estimated time to deliver those commands. For information about viewing the commands in the distribution database, see [sp_replshowcmds &#40;Transact-SQL&#41;](../../relational-databases/system-stored-procedures/sp-replshowcmds-transact-sql.md).  

[!INCLUDE[azure-sql-db-replication-supportability-note](../../includes/azure-sql-db-replication-supportability-note.md)]
  
## Options  
 **Number of commands in the distribution database waiting to be applied to this Subscriber**  
 The number of commands in the distribution database that have not been delivered to the selected Subscriber. A command consists of one Transact-SQL data manipulation language (DML) statement or one data definition language (DDL) statement.  
  
 **Estimated time to apply these commands, based on past performance**  
 The estimated amount of time to deliver commands to the Subscriber. If this value is greater than the amount of time required to generate and apply a snapshot to the Subscriber, consider reinitializing the Subscriber. For more information, see [Reinitialize Subscriptions](../../relational-databases/replication/reinitialize-subscriptions.md).  
  
## See Also  
 [Start the Replication Monitor](../../relational-databases/replication/monitor/start-the-replication-monitor.md)   
 [Monitor Performance with Replication Monitor](../../relational-databases/replication/monitor/monitor-performance-with-replication-monitor.md)   
 [Monitoring Replication](../../relational-databases/replication/monitor/monitoring-replication.md)  
  
  
