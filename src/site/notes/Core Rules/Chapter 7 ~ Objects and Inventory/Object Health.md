---
{"dg-publish":true,"permalink":"/core-rules/chapter-7-objects-and-inventory/object-health/"}
---

An [[Core Rules/Chapter 7 ~ Objects and Inventory/Objects\|Objects]] [[Core Rules/Chapter 3 ~ The Basics/Health\|Health]] is based on the [[Core Rules/Chapter 7 ~ Objects and Inventory/Materials\|Material]] of the Object, the Objects [[Core Rules/Chapter 7 ~ Objects and Inventory/Bulk\|Bulk]], and the Objects [[Core Rules/Chapter 7 ~ Objects and Inventory/Properties\|Properties]].

Once an Objects Health reaches 0, the Object is considered destroyed, is irreparable, and cannot be used.

>[!Note]
>The Health of an Object refers to the entirety of the Object. An arrow may still go through a massive sail even though the health of the sail is quite high.
## Material
The [[Core Rules/Chapter 7 ~ Objects and Inventory/Materials\|Material]] of an Object gives the base Health of the Object.

| Material Category | Base |
| ----------------- | ---- |
| Soft              | 1    |
| Sturdy            | 4    |
| Hard              | 3    |
| Pliant            | 2    |
## Bulk
The [[Core Rules/Chapter 7 ~ Objects and Inventory/Bulk\|Bulk]] of an Object multiplies the Base health of the Object. This multiplication is directly proportional to the Bulk of the Object.

| Steps | Size   | Bulk | Multiplier |
| ----- | ------ | ---- | ---------- |
| <0.5  | Minute | 0.25 | 0.25       |
| 0.5   | Tiny   | 0.5  | x 1        |
| 1     | Small  | 1    | 4          |
| 2     | Medium | 4    | 16         |
| 3     | Large  | 8    | 32         |
| 4     | Huge   | 16   | 64         |
| ...   | ...    | ...  | ...        |
## Properties
Some [[Core Rules/Chapter 7 ~ Objects and Inventory/Properties\|Properties]] of Objects directly modify the base Health of an Object. This is referenced in the Property itself.