---
title: Amend or Cancel Unpaid Purchase Invoices | Microsoft Docs
description: Explains how to correct, cancel, or undo a posted purchase invoice and automatically create a purchase CR/Adj Note.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 43fa63ce0c69c1f040faec4c257fa179a3a3fa31
ms.contentlocale: en-au
ms.lasthandoff: 03/22/2018

---
# <a name="correct-or-cancel-unpaid-purchase-invoices"></a>Correct or Cancel Unpaid Purchase Invoices
You can correct or cancel a posted purchase invoice. This is useful if you want to correct a typing mistake, or if you want to change the purchase early in the order process.

If you have already paid for products on the posted purchase invoice, you cannot correct or cancel it from the posted purchase invoice itself. Instead, you must manually create a purchase CR/Adj note to reverse the purchase, optionally managed with a purchase return order. For more information, see [Process Purchase Returns or Cancellations](purchasing-how-process-purchase-returns-cancellations.md).

In the **Posted Purchase Invoice** window, you can choose the **Correct** button or the **Cancel** button. When you correct or cancel a posted purchase invoice, the corrective purchase CR/Adj note is applied to all general ledger and inventory ledger entries that were created when the initial purchase invoice was posted. This reverses the posted purchase invoice in your financial records and leaves the corrective posted purchase CR/Adj note for your audit trail. In the following the use of **Correct** and **Cancel** is described.

## <a name="to-correct-a-posted-purchase-invoice"></a>To correct a posted purchase invoice
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.  
2. Select the posted purchase invoice that you want to correct.  

    > [!NOTE]  
    >   If the **Canceled** check box is selected, then you cannot correct the posted purchase invoice because it has already been corrected or canceled.
3. In the **Posted Purchase Invoice** window, choose **Correct**.

    A new purchase invoice with the same information is created where you can make the correction. For more information, see [Record Purchases](purchasing-how-record-purchases.md). The **Cancelled** field on the initial posted purchase invoice is changed to **Yes**.

    A purchase CR/Adj note is automatically created and posted to void the initial posted purchase invoice.
4. Choose **Show Corrective CR/Adj Note** to view the posted purchase CR/Adj note that voids the initial posted purchase invoice.

## <a name="to-cancel-a-posted-purchase-invoice"></a>To cancel a posted purchase invoice
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Purchase Invoices**, and then choose the related link.  
2. Select the posted purchase invoice that you want to cancel.

    > [!NOTE]  
    >   If the **Canceled** check box is selected, then you cannot cancel the posted purchase invoice because it has already been canceled or corrected.
3. In the **Posted Purchase Invoice** window, choose **Cancel**.

    A purchase CR/Adj note is automatically created and posted to void the initial posted purchase invoice. The **Cancelled** field on the initial posted purchase invoice is changed to **Yes**.
4. Choose **Show Corrective CR/Adj Note** to view the posted purchase CR/Adj note that voids the initial posted purchase invoice.

## <a name="see-also"></a>See Also
[Purchasing](purchasing-manage-purchasing.md)  
[Record Purchases](purchasing-how-record-purchases.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
