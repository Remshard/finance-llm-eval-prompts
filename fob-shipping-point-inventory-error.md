# FOB Shipping Point – Inventory Recognition Error

##  Prompt (First-Person Realism):
During an end-of-day inventory count at a warehouse, I observed the following:
- All inventory was physically on-site and unsorted
- Nothing had been staged for pickup or shipping

After the count, I received a call from a sales rep. He said a buyer had agreed to purchase 200 units of one SKU, and they’d be picked up tomorrow. The sale was confirmed as **FOB shipping point**.

**Question:**  
As of the time of the count, should I exclude the 200 sold units from inventory?

---

##  Model Response (Incorrect):
> Yes. Since the sale was already agreed to and marked FOB shipping point, the inventory should be excluded from the end-of-day count.

---

##  Evaluation:
This response is incorrect.

Under **FOB shipping point**, ownership transfers **when the goods leave the seller’s facility** — not when the sale is agreed to. At the time of the inventory count:
- The items were still on-site  
- No pickup had occurred  
- No physical transfer had begun

Therefore, the inventory **remains the seller’s asset** at the count time.

The model confuses **economic agreement** with **legal transfer of title**. This is a common misstep when LLMs interpret FOB terms without grounding in accounting standards.

According to U.S. GAAP (FASB ASC 606 and inventory recognition guidance), goods remain on the books until **control is transferred**. For FOB shipping point, control transfers when the goods are shipped — not before.

Generally, for goods to be excluded from inventory *prior to shipment*, all of the following must be true:
1. The goods are **segregated from general inventory**
2. They are **clearly identified for a specific customer**
3. They are **ready for physical shipment**
4. Legal title has passed or is **contractually deemed to have passed**
5. There is no **remaining obligation** preventing delivery

None of these conditions were met in the scenario above, nor is there a bill and hold agreement. Therefore, inventory should **not** be removed under ASC 606.


---

##  Correct Answer:
No. The inventory should remain on the books until it leaves the premises, as no transfer has occurred under FOB shipping point terms.

---

##  Notes:
This prompt evaluates whether the model correctly applies **revenue recognition** and **inventory cutoff logic** under FOB terms, consistent with GAAP.
