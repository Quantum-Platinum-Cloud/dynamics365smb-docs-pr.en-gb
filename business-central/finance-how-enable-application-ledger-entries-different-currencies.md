---
title: Apply Entries in Different Currencies
description: 'You can apply ledger entries in multiple currencies, for example, if you sell in one currency and receive payment in another.'
author: edupont04
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'multiple currencies, payment, reconcile'
ms.search.form: '148, 460, 25'
ms.date: 04/01/2021
ms.author: edupont
---
# <a name="enable-application-of-ledger-entries-in-different-currencies" />Enable Application of Ledger Entries in Different Currencies

If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.

Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.

The following procedure describes how to set this up for vendor ledger entries on the **Purchases & Payables Setup** page. The setup is similar for customer ledger entries on the **Sales & Receivables Setup** page.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies" />To enable application of vendor ledger entries in different currencies

1. Choose the ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Purchases & Payables Setup**, and then choose the related link.
2. In the **Appln. between Currencies** field, select one of the following options.

| Option | Description |
| --- | --- |
| None |Application between currencies is not allowed. |
| EMU |Application between EMU currencies is allowed. |
| All |Application between all currencies is allowed. |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences" />To set up G/L accounts for currency application rounding differences

If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.  

> [!NOTE]  
> You must set up the general ledger accounts before you complete the task. For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).

1. Choose the ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Customer Posting Groups**, and then choose the related link.  
2. In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.  
3. Choose the ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Vendor Posting Groups**, and then choose the related link.  
4. In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.  

## <a name="see-related-microsoft-trainingtrainingmodulesprocess-foreign-currency-payments-dynamics-365-business-central" />See related [Microsoft training](/training/modules/process-foreign-currency-payments-dynamics-365-business-central/)

## <a name="see-also" />See also

[Managing Payables](payables-manage-payables.md)  
[Managing Receivables](receivables-manage-receivables.md)  
[Work with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
