---
title: View Table Information
author: jswymer
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 04/20/2020
ms.author: jswymer
ms.openlocfilehash: de93063a60e6b64405b1491a67489c8bfa4657ad
ms.sourcegitcommit: 99915b493a7e49d12c530f2f9fda1fcedb518b6e
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 04/21/2020
ms.locfileid: "3275326"
---
# <a name="viewing-table-information"></a>Viewing Table Information

The page **8700 Table Information** provides information about all system and business tables in a Business Central solution. In particular, the page displays information about the amount of data the tables contain.

This information is useful for troubleshooting performance problems, because let's you see the distribution of data size across tables.

## <a name="viewing-table-information"></a>Viewing table information

To open this page, select the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Table Information**, and then choose the related link.

The following table describes the information provided for each table:

|Column|Description|
|------|-----------|
|Company Name|The name of the company, if any, that the table belongs to.|
|Table Name|The name of the table.|
|Table No.|The ID of the table|
|No. of Records|The total number of records stored in the table.|
|Record Size|The average record size in KB/record. The value is calculated using the following formula: 1024(Size)/(No. of Records)`. |

## <a name="see-also"></a>See Also

[Inspecting Pages](across-inspect-page.md)  
[Performance Articles For Developers](/dynamics365/business-central/dev-itpro/performance/performance-developer)  