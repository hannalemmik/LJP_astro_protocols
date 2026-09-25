# Whole plasmid sequencing (Eurofins ONT Lite)

**Author:** Hanna Lemmik  
**Source:** Lab instructions from Nicolas FB

## Abstract

This protocol describes how to prepare and submit plasmid DNA for whole plasmid sequencing with the Eurofins Genomics ONT Lite (Oxford Nanopore) service, and how to align the returned sequence to the reference. Whole plasmid sequencing gives the full sequence of the plasmid without primers for the same cost as Sanger sequencing.

## Guidelines

- No primers are needed.
- Use the **blue** pre-paid ONT Lite coupons with a QR code which are in a drawer under the NanoDrop. The white coupons are for Sanger sequencing.
- Drop samples off **before 3:30 PM** to make that day's pickup.
- Measure DNA concentration with a **fluorometric method (e.g. Qubit)** as spectrophotometric methods are unreliable for concentration. Eurofins asks to double the concentration if NanoDrop is used.
- Samples that don't meet the concentration requirement may fail or give inaccurate assemblies, and Eurofins will not repeat samples that failed because of wrong concentrations.

## Materials

- Purified plasmid DNA (e.g. Qiagen miniprep)
- Nuclease-free water or elution buffer (10 mM Tris, pH 8.5)
- 1.5 ml Eppendorf tubes
- Qubit fluorometer and dsDNA assay kit (for concentration)
- NanoDrop (for purity measurement only)
- Pre-paid blue Eurofins ONT Lite coupons (use only the ones with a QR code)
- Envelope
- Access to the lab's Eurofins Genomics account (ask Hanna or Nicolas FB)

## Sample requirements

| Size category | Plasmid length | Concentration | Minimum volume | Turnaround time |
|---|---|---|---|---|
| Regular | 2.5–25 kbp | 30 ng/µl | 20 µl | 1–2 days |
| Large | 25–125 kbp | 50 ng/µl | 30 µl | 5–7 days |
| XL | 125–300 kbp | 50 ng/µl | 50 µl | 5–7 days |

- **Sample type:** clonal, circular, double-stranded plasmid DNA.
- **Buffer:** nuclease-free water or elution buffer (10 mM Tris, pH 8.5).
- **Concentration:** measure with Qubit. Double the concentration if measured with NanoDrop.
- **Purity:** OD260/280 of 1.8–2.0.
- **Avoid ethanol contamination.** With the Qiagen miniprep kit, do the optional PB buffer wash step to increase purity.

## Procedure

### A. Prepare the sample

1. Purify the plasmid and elute in nuclease-free water or elution buffer (10 mM Tris, pH 8.5).
   *With the Qiagen miniprep kit, include the optional PB wash and make sure no ethanol is carried over.*
2. Check purity on the NanoDrop: OD260/280 should be 1.8–2.0.
3. Measure the concentration with Qubit.
4. In a 1.5 ml Eppendorf tube, prepare the plasmid at the concentration and volume for its size category (see table above).
5. Stick a blue pre-paid coupon **horizontally** on each tube so the QR code is easy to scan, and note which Eurofins code belongs to which sample.
   *Don't seal the tubes with tape or parafilm.*

### B. Drop off the samples

1. Put the tubes in an envelope. Samples travel at ambient temperature.
2. Put the envelope in the Eurofins DropBox (IBPS, building A, 4th floor, in the stairwell) **before 3:30 PM**. Pickup from the DropBox is free, and samples go to the Eurofins sequencing lab in Cologne, Germany.

### C. Register the order online

1. Log in to the lab's account on the [Eurofins Genomics website](https://eurofinsgenomics.eu/en/ecom/checkout/login-register/?nodeId=4302).
2. Go to **Products & Services** → **Nanopore Sequencing** → **ONT Lite Portfolio** → **Whole Plasmid Sequencing**.
3. Choose **Order in tubes**.
4. Enter your sample information and the Eurofins code from the coupon on each tube.
5. Choose the DropBox: IBPS, building A, 4th floor, in the stairwell.

### D. Analyse the results

1. When aligning the returned sequence to your reference, paste both as linear sequences starting at the same position.
   *Plasmids are circular, so the sequencing result may start at a different point than your reference map.*
2. If the alignment fails, try the reverse complement of the result since the plasmid may have been read in the opposite orientation.

## Alternative formats (for many samples)

### 96-well plates

- Use 96-well PCR plates labelled with a Whole Plasmid Sequencing plate barcode (WPP-Barcode) on the narrow side at column 12.
- Seal plates with 8-cap strips to prevent sample loss.
- Use Eurofins' approved sample bags and boxes for transport.

### Stab cultures in soft agar (no miniprep needed)

1. Prepare your own 96-well agar plate with the appropriate antibiotic. Label it with a WPP-Barcode on the narrow side at column 12.
2. With sterile toothpicks, pick single colonies from your Petri dish and inoculate one colony per well.
3. Cover the plate with a gas-permeable foil and incubate at 37 °C for 8–12 h (overnight).
4. Seal the plate with adhesive plastic foil and ship at ambient temperature to the Eurofins sequencing lab in Cologne, Germany.
