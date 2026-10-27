# Merit Medical: Real, Publicly Named Suppliers (research Oct 27 2026)

**Bottom line:** Public sources name only a few of Merit's ~1,034 direct suppliers. US bill-of-lading aggregators (Panjiva, ImportKey) show part of the import picture, and the rest is behind paywalls. **ImportYeti (importyeti.com/company/merit-medical-systems) returned HTTP 403 (blocked), and so did TradeInt. Volza only shows locked category pages.** Every Tijuana-cluster supplier we found (Viant, Jabil, Arterex, Brentwood, Phase 2) advertises molding, packaging or machining for medical OEMs, but **none of them names Merit as a customer.** Also, Merit's Mexico plant imports under its own maquiladora entity (Merit Maquiladora Mexico S. de R.L. de C.V.). That means US import data mostly shows Merit shipping to itself, and the plant's local Mexican suppliers don't appear at all. **This gap supports our pitch: Merit's small Mexican suppliers can't be seen from outside, and only Merit's own vendor master shows who they are.**

The strongest real example is **Jiangsu Shenli Medical Production Co. (China)**. Merit's custom kits included syringes made by this company. FDA found the syringes were unauthorized and issued warning letters (Mar 2024), and Merit recalled the affected kits in June 2024. Cardinal Health then recalled its downstream Presource kits. It is a public, documented case of a hard-to-see Chinese component maker causing a recall at Merit.

## Supplier table

Tier = our framework (anchor = large and EcoVadis-capable; critical-stuck = small or single-plant, hard to replace, can't complete EcoVadis; long tail = low spend, easy to replace). **All tier and size calls are our assumptions, not facts from the sources.**

| # | Supplier | Country / city | What they supply to Merit | Evidence | Size (assumption) | Tier (ASSUMPTION) |
|---|---|---|---|---|---|---|
| 1 | **Jiangsu Shenli Medical Production Co., Ltd.** | China (Jiangsu) | Plastic syringes used as components in Merit convenience/custom kits (e.g., K04 Custom Syringe Kit, K11 Custom Pressure Monitoring Kit) | FDA warning letter (Mar 2024) and Merit's recall of kits containing Shenli syringes (Jun 2024, Class II, e.g., Z-2561-2024 and Z-2566-2024). Cardinal Health's Presource recall lists Merit kits. Sources: plasticstoday.com, massdevice.com, drugdeliverybusiness.com, Cardinal recall PDF, CDPH notice | Mid (single-country Chinese OEM) | Critical-stuck. The **China phase-2 archetype**. Historical: after the recall Merit presumably no longer uses this source [UNVERIFIED] |
| 2 | **Meixin Medical (Suzhou) Co., Ltd.** | China (Suzhou, Jiangsu) | Not stated in the shipment record. Bloomberg profile says it makes lap/gauze sponges, medical kits and nonwovens, which matches "gauze" in the consignee's top products | Panjiva: shipments to "Merit Medical / RL Jones", 8830 Siempre Viva Rd, San Diego CA 92154 (Otay Mesa, at the Tijuana border crossing, likely a customs broker/warehouse feeding Merit Tijuana). Dates Jan 2025 and May 15 2025 | Small-mid | Critical-stuck or long tail. Kit components (gauze) are fairly substitutable. **Strong candidate for China phase 2** |
| 3 | **Knudsen Plast A/S** | Denmark (Frederiksværk; plant in Slovakia) | Medical injection-molded plastic components (inferred from the company's business. The commodity field on the shipment is redacted) | Panjiva: shipment to Merit Medical / RL Jones, San Diego (Tijuana border), Jun 29 2025. Acquired by MGS (US) in 2026 | Mid (now part of MGS) | Anchor-ish / critical (custom molds are hard to switch). **Not Mexico/China** |
| 4 | **Chimall Electronic Technology Co.** | China (Shenzhen, Guangdong) | Electronics (product not stated). Possibly related to Chimall Universal, a Shenzhen SMT/PCB equipment maker [UNVERIFIED link] | ImportKey "MERIT MEDICAL SYSTEMS INC": 3 shipments, buyer shown = Merit Medical Systems Inc | Small | Long tail [UNVERIFIED product] |
| 5 | **Katoen Natie Logipark BV** | Netherlands (Hoek). Origin port Sines, Portugal | "Magnum natural ABS" (HTS 390330, ABS resin, a Trinseo brand) via a logistics provider | ImportKey "Merit Medical Systems Inc" page: 16 shipments to Oakland CA. **But the buyer shown in the supplier summary is Quality Distribution Inc, so the link to Merit is [UNVERIFIED]** | Large (logistics). Resin maker is large | Anchor (resin) [UNVERIFIED] |
| 6 | **Jiya Langfang Electronics Co., Ltd.** | China (Langfang, Hebei) | LCD panels (HTS 852491). This would fit inflation-device or monitoring displays [assumption] | Shown on ImportKey's Merit Medical Systems Inc page (12 shipments, latest Oct 22 2026), **but the buyer listed is Phoenix Display International Inc. It may be a tier-2 supply via a display distributor, or a mis-matched record [UNVERIFIED]** | Small-mid | Critical-stuck (custom display) if real [UNVERIFIED] |
| 7 | **Merit Medical (Beijing) Co., Ltd.** | China (Beijing) | Masked (HTS 2914.19, a chemical) to the San Diego/Tijuana consignee, Oct 2025 | Panjiva | Internal Merit affiliate, **not an external supplier** | n/a |
| 8 | **Merit Medical Ireland Ltd → Merit Maquiladora Mexico** and **Merit Medical Singapore** | Ireland / Singapore | Guide wires to the Tijuana maquiladora (30 shipments, Cobh → Wilmington NC). BP measurement systems | ImportKey | Internal transfers. Shows **Galway supplies guidewire into Tijuana** | n/a |
| 9 | **Cook Medical** (transition) | USA (Bloomington, IN) | Contract manufacturing of the acquired lead-management portfolio for a ~2-year transition (TSA) | Merit 8-K, Sep 2024 ($210M deal) | Large | Anchor (temporary) |
| 10 | **AngioDynamics** (transition) | USA | Contract Manufacturing Agreement + TSA for the acquired dialysis catheter + BioSentry assets | Merit 8-K, Jun 2023 | Large | Anchor (temporary) |
| 11 | Merit Sensor Systems, Inc. | USA | Pressure sensors for digital inflation devices | Merit FY2025 10-K | Merit subsidiary, **not external** | n/a |
| 12 | Sterigenics (Salt Lake City) / BD Sandy EtO | USA (Utah) | EtO contract sterilization | Only evidence: these are the two EtO sterilizers in Salt Lake County. Merit's 10-Ks say "substantially all of our products are sterilized by only a few different entities" / "a limited number of third parties". **No source names which ones Merit uses [UNVERIFIED]** | Large | Anchor / systemic single-point [UNVERIFIED] |

### Seen on the aggregated "MERIT MEDICAL" ImportKey page. Probably NOT Merit (name collision). Do not use.
- Bioptimal International Pte Ltd (Singapore; "TD catheter" from Qingdao). Buyer shown = Biomedical Sales International.
- ACG F.lli Manca Srl (Italy; medical plastic clamps). Buyers shown = BD, GVS, Codan, Medline.
- PT Volex Indonesia (cable assemblies). Buyers shown = Volex, Aptiv, Tesla.

## What the import data tells us (usable facts)
- **Merit Tijuana is the import hub:** Panjiva's "Merit Medical / RL Jones" consignee at 8830 Siempre Viva Rd, San Diego (Otay Mesa) lists **23 suppliers** across 82–171 shipment records. Top products: stainless, gauze, pressure gauges, plastic, needles. Top HS chapters: 90, 39, 84, 85, 30. **Only 3 of the 23 supplier names are visible free.** A paid Panjiva/ImportYeti pull of this one consignee would give the real Tijuana-feeding supplier list.
- Merit Mexico Sales S. de R.L. de C.V. (Av. Sor Juana Inés de la Cruz 19970, Tijuana) received 824 import records from Merit Medical Systems (South Jordan) via Nuevo Laredo. These are internal flows.
- Merit Maquiladora Mexico receives guidewire from Galway (30 shipments).
- Merit's UK Modern Slavery statement (FY2025, adopted Feb 2026): **>1,034 direct suppliers, top 78 = >65% of spend, ~half in the continental US.** Risk review covers tier 1 only (tier 2 is a "future aim"). No supplier countries are named. The California Transparency Act page says audits and surveys are run by Merit staff and don't specifically test for trafficking or slavery.
- The FY2025 10-K names **no** external suppliers. It says raw materials are "purchased worldwide", that Merit uses contract manufacturers, and that Merit "generally contract[s] with third parties for the tooling of our molds". The FY2018 10-K flags resin suppliers refusing to sell to medical device makers.

## Implication for "which suppliers first"
1. **The long tail is 1,034 − 78 ≈ 956 suppliers holding <35% of spend.** That is where the small Mexico/China makers sit, and it is exactly what public data can't see. Pilot selection must come from Merit's vendor master, filtered to: Tijuana-area or China location × single-plant × no EcoVadis score × sole-sourced part.
2. Public proof that this segment matters: the **Shenli syringe recall** (a China kit component, FDA action, downstream customer recall at Cardinal).
3. Candidate profile for phase 2 (China): kit-component makers like **Meixin Medical Suzhou** (gauze/kits) and display/electronics makers (Chimall, possibly Jiya Langfang). Present these as *archetypes*, not as accused suppliers.
4. For Tijuana, the cluster includes contract molders, packagers and machine shops (Viant, Jabil, Arterex, Brentwood, Phase 2 on the large end; hundreds of small tool and mold shops on the small end). Those are the kinds of firms that make molds and parts for Merit, but **none is publicly confirmed as a Merit supplier.**

## How to present this on a slide responsibly
- Say "**Public U.S. import records show** Merit's Tijuana operation receives components from at least 23 overseas suppliers, including makers in Suzhou and Shenzhen", not "Merit's suppliers are X, Y, Z".
- Use the **Shenli recall** as the illustrative case. It is public, FDA-documented and already widely reported. Frame it as "a visibility problem", not "Merit's failure".
- **Don't single out small suppliers negatively** (Meixin, Chimall, Jiya). If you name them, put them under "example supplier profiles from public import data", with neutral language such as "the kind of supplier the pilot is designed to support". Better: anonymize as "a Suzhou kit-component maker" or "a Shenzhen electronics supplier".
- Label import data as partial (3 of 23 names visible, paywalled) and possibly mismatched (name-collision risk on aggregator sites).
- Never imply any named supplier uses forced labor or fails ESG. We have no evidence of that.
- Close with the ask: "Merit's vendor master, not public data, picks the 10–15 pilot suppliers. Here is the filter we'd run."

## Blocked / not available
- ImportYeti: 403. TradeInt: 403. Panjiva Merit Medical Asia: 404. Volza: paywalled category pages only.
- No Tijuana supplier website, press release or case study found naming Merit as a customer.
- No named contract sterilizer for Merit found.
