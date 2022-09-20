---
title: Set Up Vendor Bank Account
description: Learn how to associate bank accounts to vendor cards in Business Central, including contact information, SWIFT, and IBAN codes.
author: rubenseishima
ms.service: dynamics365-business-central
ms.topic: article
ms.date: 07/04/2022
ms.author: a-reishima
ms.openlocfilehash: 1839f54de2382ad5b7d8b6b936181e105a56e06b
ms.sourcegitcommit: 5560a49ca4ce85fa12e50ed9e14de6d5cba5f5c3
ms.translationtype: HT
ms.contentlocale: en-AU
ms.lasthandoff: 07/13/2022
ms.locfileid: "9144442"
---
# <a name="set-up-vendor-bank-accounts"></a>Set Up Vendor Bank Accounts

Just as you can use bank account information on [!INCLUDE [prod_short](includes/prod_short.md)] to keep track of your company's banking transactions, you can also set banking details for vendors. Vendor bank account data can simplify payments to suppliers when combined with the [AMC Banking 365 Fundamentals Extension](ui-extensions-amc-banking.md) or the [Export Payments to a Bank File](finance-make-payments-with-bank-data-conversion-service-or-sepa-credit-transfer.md) feature, for example.

## <a name="add-or-edit-a-vendor-bank-account"></a>Add or edit a vendor bank account

[!INCLUDE [purchase-vendor-bank-account](includes/purchase-vendor-bank-account.md)]

> [!TIP]
> You can set additional vendor bank accounts on the **Vendor Bank Account List** page.

## <a name="set-up-a-preferred-vendor-bank-account"></a>Set up a preferred vendor bank account

If a vendor has one or more bank accounts and you want to set a preferred option for the payment journal lines, follow these steps:

1. Choose the ![Lightbulb that opens the Tell Me feature 1.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Vendors**, and then choose the related link.
2. Open the card for the vendor.
3. On the **Payments** FastTab, choose the default vendor bank account in the **Preferred Bank Account Code** field.

## <a name="see-related-training-at-microsoft-learn"></a>See related training at [Microsoft Learn](/learn/modules/cash-management-dynamics-365-business-central/)

## <a name="see-also"></a>See also

[Setting Up Purchasing](purchasing-setup-purchasing.md)  
[Register New Vendors](purchasing-how-register-new-vendors.md)  
[Set Up Bank Accounts](bank-how-setup-bank-accounts.md)  
[Use the AMC Banking 365 Fundamentals Extension](ui-extensions-amc-banking.md)  
[Set Up the Envestnet Yodlee Bank Feeds Service](bank-how-setup-bank-statement-service.md)  
[Work with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)

[!INCLUDE[footer-include](includes/footer-banner.md)]