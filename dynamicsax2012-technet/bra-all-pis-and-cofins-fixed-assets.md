---
title: (BRA) All PIS and COFINS fixed assets
TOCTitle: (BRA) All PIS and COFINS fixed assets
ms:assetid: 1348fc19-862f-48e5-93cf-27faccb8a4a6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Mt297848(v=AX.60)
ms:contentKeyID: 66271896
ms.date: 07/08/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) All PIS and COFINS fixed assets 


When a legal entity purchase a fixed asset, the PIS and COFINS tax credit, which is calculated on that transaction, can be appropriated in specific quantity of installments. In order to have the correct calculation for this tax refund, the legal entity must present a specific fiscal book or report the information in the SPED EFD Contributions file to demonstrate the correct appropriation of PIS and COFINS tax credit amount. The control of credit appropriated in the tax assessment period is detailed in the records F120 and F130 of SPED EFD Contributions.

The tax credit amount can be calculated from the asset acquisition transactions or the depreciation transactions since the legislation allows the companies to appropriate the credit based on these criteria.

In order to calculate the credit amount to appropriate the PIS and COFINS tax, create the fixed asset in the Fixed asset module and complete all the fiscal information related. See [(BRA) Set up a fixed asset group](bra-set-up-a-fixed-asset-group.md).

## Acquire fixed asset for PIS and COFINS credit appropriation

To generate fixed asset tax credit appropriation, Fiscal Books module uses the transactions generated in accounts payable module (acquisition and acquisition adjustment) and Fixed asset module (depreciation). These transactions are included in the PIS and COFINS tax assessment during the Synchronization action when booking period is created. See. (BRA) Create a new booking period \[AX 2012\] \>

### Acquire and depreciate asset transactions

1.  Create a purchase order for the fixed asset acquisition.

2.  On the purchase order, on the **Line details** FastTab, on the **Fixed assets** tab, select the fixed asset number and the value model, and then select Acquisition for the transaction type.

3.  The PIS and COFINS parameters are also displayed in this form and the information will be saved on the fiscal document.

4.  Create and post a purchase invoice for the purchase order.

5.  When the booking period is created, the fiscal document will be processed and a PIS and COFINS fixed asset will be created.

6.  You can view the PIS and COFINS fixed assets, click **Fiscal books** \> **Common** \> **All CIAP fixed assets**. Click **CIAP fixed asset** in the group on the Action Pane.

7.  You can also execute the depreciation journal of fixes assets with PIS and COFINS credit appropriation marked in Fixed asset setup. The depreciation transactions generated are displayed into **Fiscal books** \> **Common** \> **All CIAP fixed assets**. See [Post fixed asset journals](post-fixed-asset-journals.md).
    

    > [!NOTE]
    > <P>Sales tax code with fiscal value 3 (without credit) and the tax rate related must be used in the purchase invoice in other to post in to the long term account the tax amount to be appropriated every month through the process of PIS and COFINS tax assessment.</P>



## All PIS and COFINS fixed assets

Use this form to see all fixed asset with PIS and COFINS tax credit per fiscal establishment, company and fixed asset ID.

You can create a New entry of fixed asset when the acquisition or depreciation transaction is not posted in the accounts payable module or Fixed asset module. In general use this option to migrate the initial balances.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Fixed asset number</strong></p></td>
<td><p>The fixed asset number created in Fixed asset module.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fiscal establishment ID</strong></p></td>
<td><p>The establishment ID where the fixed asset is located.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p>The name of fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main Account</strong></p></td>
<td><p>The main account where the fixed asset is posted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost Center</strong></p></td>
<td><p>The cost center allocated for this fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed asset origin</strong></p></td>
<td><p>This field identifies the source of fixed asset.</p>
<ul>
<li><p>Internal Market</p></li>
<li><p>External Market</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>PIS and COFINS Asset ID</strong></p></td>
<td><p>This ID is automatically generated by Fiscal Books module to identify the asset credit appropriation process.</p></td>
</tr>
<tr class="even">
<td><p><strong>Status</strong></p></td>
<td><p>Identifies the status of credit appropriation of Fixed asset</p></td>
</tr>
<tr class="odd">
<td><p><strong>Method</strong></p></td>
<td><p>Identifies the Method of credit appropriation</p>
<ul>
<li><p>Acquisition</p></li>
<li><p>Amortization</p></li>
<li><p>Depreciation</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Group</strong></p></td>
<td><p>Identify the type of group of fixed asset</p></td>
</tr>
<tr class="odd">
<td><p><strong>Utilization</strong></p></td>
<td><p>Identify the type of utilization</p></td>
</tr>
<tr class="even">
<td><p><strong>PIS taxation code</strong></p></td>
<td><p>The Taxation code for PIS tax. This taxation is used to identify the CST of depreciation apropriation</p></td>
</tr>
<tr class="odd">
<td><p><strong>COFINS taxation code</strong></p></td>
<td><p>The Taxation code for COFINS tax. This taxation is used to identify the CST of depreciation apropriation</p></td>
</tr>
<tr class="even">
<td><p><strong>Transaction type</strong></p></td>
<td><p>The type of credit appropriation transaction</p>
<ul>
<li><p>Acquisition</p></li>
<li><p>Credit of installment</p></li>
<li><p>End of Credit period</p></li>
<li><p>Disposal Sale</p></li>
<li><p>Disposal Scrap</p></li>
<li><p>Disposal Transfer</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date of credit appropriation transaction</p></td>
</tr>
<tr class="even">
<td><p><strong>PIS installment amount</strong></p></td>
<td><p>The PIS credit amount calculated in the tax assessment process</p></td>
</tr>
<tr class="odd">
<td><p><strong>COFINS installment amount</strong></p></td>
<td><p>The COFINS credit amount calculated in the tax assessment process</p></td>
</tr>
<tr class="even">
<td><p><strong>Referenced Process</strong></p></td>
<td><p>Additional information of referenced process</p></td>
</tr>
<tr class="odd">
<td><p><strong>Agency</strong></p></td>
<td><p>The agency where the process take place.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reference process number</strong></p></td>
<td><p>The number of reference process.</p></td>
</tr>
</tbody>
</table>


## Calculate PIS and COFINS credit appropriation

The PIS and COFINS credit appropriation is calculated in the PIS and COFINS tax assessment per fiscal organization, period and fixed asset ID.

### Calculate the credit appropriation installment

1.  Select or create **Fiscal Books** \> **Common** \> **Tax assessment** \> **PIS and COFINS**.

2.  Click **Fixed asset credit**. .

3.  Automatically, the process creates the installments related based on the information available in All PIS and COFINS fixed asset. The installment amount is created when the fixed asset has acquisition amount or depreciation amount for this period depending on the type of credit appropriation selected.

4.  Click PIS and COFINS fixed asset transactions to view the details of credit appropriation transactions.
    

    > [!NOTE]
    > <P>The <STRONG>PIS installment amount</STRONG> is automatically calculated based on the tax base amount and the installments defined in the asset setup.</P>
    > <P>The <STRONG>COFINS installment amount</STRONG> is automatically calculated based on the tax base amount and the installments defined in the asset setup.</P>
    > <P>The <STRONG>Installment number</STRONG> is automatically updated every time that a new PIS and COFINS tax assessment is created.</P>



5.  Click **Referenced Process** to add an specific reference process number to an specific fixed asset.

6.  Click **New** to add manually credit appropriation transactions.

7.  Click **Remove** to manually remove an existing credit appropriation transaction.

8.  You can also add information about Referenced process.
    
    1.  Click Referenced process fast tab.
    
    2.  Select the Agency and enter the Process number.

## See also

[(BRA) Create a new booking period](bra-create-a-new-booking-period.md)

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

  

