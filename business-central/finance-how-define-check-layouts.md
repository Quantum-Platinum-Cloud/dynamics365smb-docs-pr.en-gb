---
title: Specify the Layout of a Cheque
description: You can design and print your cheques in different formats to conform with standards set by your local authorities.
author: edupont04
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 'print check, customize'
ms.search.form: '374, 404'
ms.date: 06/16/2021
ms.author: edupont
---
# <a name="select-a-check-layout" />Select a Cheque Layout

You can design your cheques to conform with the standards set by the local authorities. Cheque images can be printed in English, French, or Spanish.

Cheques are designed to print in both the United States and Canadian cheque image formats in either a cheque-stub-cheque format or a stub-stub-cheque format.

## <a name="to-select-a-check-layout" />To select a cheque layout

1. Choose the ![Lightbulb that opens the Tell Me feature.](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Report Selections Bank Account**, and then choose the related link.
2. On the **Report Selection - Bank Acc.** page, in the **Usage** field, select **Cheque**.
3. Select one of the following report IDs.

| Report ID | Report Name | Description |
| --- | --- | --- |
| 1401 |Cheque |This is the default report. |
| 10411 |Cheque (Stub/Stub/Cheque) |This report is designed to print cheques in a stub/stub/cheque format. |
| 10412 |Cheque (Stub/Cheque/Stub) |This report is designed to print cheques in a stub/cheque/stub format. |
| 10413 |Three Cheques per Page |This report is designed to print three cheques on each page. |

When you have set up cheque layouts, you can print cheques from the **Payment Journal** page. For more information, see [Work with Cheques](payables-how-work-checks.md).

To change one of these default cheque layouts, use either the Word or the RDLC integration to do so. For more information, see [Create and Modify Custom Report Layouts](ui-how-create-custom-report-layout.md).

## <a name="use-micr-and-security-fonts" />Use MICR and Security Fonts
The online version of [!INCLUDE[prod_short](includes/prod_short.md)] contains pre-installed fonts on the servers that can be used when defining cheque layouts. The following outlines which fonts are available and has links to detailed information by the 3rd-party suppliers of the fonts.

> [!Important]
> MICR and cheque security fonts in Microsoft Dynamics [!INCLUDE[prod_short](includes/prod_short.md)] are licensed in a font package from IDAutomation.com, Inc. These products may only be used as part of and in connection with Microsoft Dynamics [!INCLUDE[prod_short](includes/prod_short.md)].

In update 15.3 and newer, Magnetic Ink Character Recognition (MICR) fonts are installed and available to use. Both the E-13B and the CMC-7 standards are supported. In addition to MICR fonts, special security fonts are available to generate text, names, amounts, and the currency symbols Dollar, Euro, Pound, and Yen, which are hard to tamper with once a cheque has been printed.

> [!NOTE]
> For security and legal reasons, you cannot upload custom fonts to the [!INCLUDE[prod_short](includes/prod_short.md)] environment.

### <a name="micr-e-13b-specifications" />MICR E-13B Specifications

The following summarises specifications for the MICR E-13B fonts that may be useful when calibrating fonts to be on cheque layouts with specific MICR printers.

![MICR E-13B Specifications.](media/font_MICR_E-13B_Specifications.png "MICR E-13B Specifications")

### <a name="delimiter-characters" />Delimiter characters

![Delimiter characters.](media/font-micr-letters.png "Delimiter characters")

The full specification of MICR E-13B fonts can be found in the supplier's documentation here: (https://www.idautomation.com/micr-fonts/e13b/).

### <a name="micr-cmc-7-specifications" />MICR CMC-7 Specifications

The following CMC-7 fonts are available in [!INCLUDE[prod_short](includes/prod_short.md)] online:

- IDAutomationCMC7
- IDAutomationCMC7n10
- IDAutomationCMC7n25
- IDAutomationCMC7n40

The following summarises specifications for the MICR CMC-7 fonts that may be useful when calibrating fonts to be on cheque layouts with specific MICR printers.

![MICR CMC-7 Specifications.](media/font_MICR_CMC-7_Specifications.png "MICR CMC-7 Specifications")

### <a name="delimiter-characters" />Delimiter characters

![Delimiter characters for CMC-7.](media/font-cmc7-letters.png "Delimiter characters for CMC-7")

The full specification of MICR CMC-7 fonts can be found in the supplier's documentation here: (http://www.idautomation.com/micr-fonts/cmc7/).

### <a name="secure-font-specifications" />Secure Font Specifications

The following Summarises specifications for cheque security fonts that may be useful when calibrating fonts to be on cheque layouts with specific MICR printers.

![Cheque Security Font Specifications.](media/font_check-security-font_Specifications.png "Cheque Security Font Specifications")

The full specification of cheque security fonts can be found in the supplier's documentation here: (https://www.idautomation.com/security-fonts/).

Fonts for other purposes are also available in [!INCLUDE[prod_short](includes/prod_short.md)]. For more information, see [Available Fonts](ui-fonts.md)

## <a name="see-also" />See Also

[Create and Modify Custom Report Layouts](ui-how-create-custom-report-layout.md)  
[Fonts in Business Central](ui-fonts.md)  
[Managing Payables](payables-manage-payables.md)  
[Reconciling Bank Accounts](bank-manage-bank-accounts.md)   
[Completing Period-End Processes](year-how-complete-period-end-processes.md)  
[Work with [!INCLUDE[prod_short](includes/prod_short.md)]](ui-work-product.md)  
[General Business Functionality](ui-across-business-areas.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]
