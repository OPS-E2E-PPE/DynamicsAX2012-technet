---
title: Price simulation and discounts
TOCTitle: Price simulation and discounts
ms:assetid: 8a1c0dbf-5e00-449b-ac0c-4f5ef8128cce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498237(v=AX.60)
ms:contentKeyID: 36058462
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- discounts
- discount
- price simulation
audience: Application User
ms.search.region: Global
---

# Price simulation and discounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To guarantee that discounts and prices are calculated correctly, be careful when you run price simulations on quotations that have discounts. Because all price simulations are treated as special discounts on the active quotation line or the whole quotation, you must track the differences in the discounts.

## Discounts in trade agreements

Trade agreements in Microsoft Dynamics AX can have four kinds of price discounts. These discounts can be set up for different items, customers, or price groups, and they can be limited by date. To avoid miscalculations, you must consider trade agreements when you run price simulations.

The four types of discounts in trade agreements are as follows:

  - Sales price – Separate sales prices can be specified for items. When quotation lines are created, the program searches for the correct sales price for an item and transfers it to the quotation lines. Therefore, a trade agreement that has this kind of discount does not affect the price simulation. The sales price that is used in the quotation line reflects the trade agreement.

  - Line discount – Special discounts are specified for items, depending on the amount that is ordered. Line amounts are typically reduced by the line discount before a price simulation is run. Therefore, a trade agreement that has this kind of discount affects the price simulation.

  - Multiline discount – If the combined amounts exceed the limit that you have defined, predefined combinations of ordered items trigger a discount on the whole order. Line amounts are typically reduced by the line discount before a price simulation is run. Therefore, a trade agreement that has this kind of discount affects the price simulation.

  - Total discount – If the combined amounts exceed the limit that you have defined, predefined ordered items trigger a discount on the whole order. The total discount is generated by the quotation lines. However, because the total discount is applied to the quotation total as a discount, it reduces the total amount of the quotation. Therefore, a trade agreement that has this kind of discount severely affects the price simulation.

## Quotation lines and trade agreements

  - When you create or adjust a quotation line, line discounts are automatically calculated. The relevant sales price is found for the item, based on the trade agreement.

## See also

[Price simulation](price-simulation.md)

[Price simulation examples](price-simulation-examples.md)

  

