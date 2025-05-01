---
#MIOP terms
methodology_category: Omics analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: 'PCR [OBI:0000415]'
analyses: 'PCR [OBI:0000415]'
geographic_location: 'North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]'
broad_scale_environmental_context: 'marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024]'
local_environmental_context: 'oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447], marine benthic biome [ENVO:01000024]'
environmental_medium: 'sea water [ENVO:00002149]'
target: '18S Ribosomal RNA [NCIT:C48172]'
creator: 'Shannon Brown, Han Weinrich, Zachary Gold'
materials_required: 'vortexer [OBI:0400118], PCR instrument [OBI:0000989]'
skills_required: 'sterile technique, pipetting skills, and standard molecular technique'
time_required: 210
personnel_required: 1
language: en
issued: '2025-05-01'
audience: 'scientists'
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'

# FAIRe terms
pcr_0_1: 1
inhibition_check_0_1: not applicable
inhibition_check: not applicable
thermocycler: Applied Biosystems Veriti 96-well thermal cycler
assay_name: ssu18sv8_machida
assay_validation: The assay has been validated through mutli-step in-silico, in-vitro, and in-situ validations. In addition to repeat analysis with alternate assays and intra/inter species tests. See BeBOP for citations.
targetTaxonomicAssay: "18S rRNA gene sequencing targeting the V8 region using primers Machida 18S #3 F and Machida 18S #5 R"
targetTaxonomicScope: metazoan organisms
target_gene: 18S
target_subfragment: V8
ampliconSize: 380
pcr_primer_forward: GYGGTGCATGGCCGTTSKTRGTT
pcr_primer_reverse: GTGTGYACAAAGGBCAGGGAC
pcr_primer_name_forward: Machida_18S V78 F
pcr_primer_name_reverse: Machida_18S V78 R
pcr_primer_reference_forward: https://doi.org/10.1371/journal.pone.0134314
pcr_primer_reference_reverse: https://doi.org/10.1371/journal.pone.0134314
pcr_primer_vol_forward: 0.75
pcr_primer_vol_reverse: 0.75
pcr_primer_conc_forward: 5.0
pcr_primer_conc_reverse: 5.0
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: AmpliTaq Gold Fast PCR Master Mix
custom_mm: PCR reactions were run in 25 uL reaction volumes, with 2 uL of DNA, 10 uL of AmpliTaq Gold, 11.5 uL of water, and 0.75 uL of each primer (5 uM).
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
amplificationReactionVolume: 25
pcr_dna_vol: 2.0
pcr_rep: 1.0
nucl_acid_amp: https://doi.org/10.5281/zenodo.11398146
pcr_cond: initial denaturation:95_10;normal_cycling;denaturation:95_0.75;annealing:55_0.75;elongation:68_1.5;final elongation:68_5;30
annealingTemp: 55
pcr_cycles: 30
pcr_analysis_software: missing":" not provided
pcr_method_additional: Quality was validated via confirmation of a product on a gel.
---

# NOAA PMEL OME Machida Metazoan 18S V8 PCR Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

## AUTHORS

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
|Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2024-02-02|
|Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2024-02-02|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-02|
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-02|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2024-02-02|
|Brynn Zalmanek	|Ocean Molecular Ecology, NOAA PMEL	|0009-0004-8906-5907	|2025-04-30|

- All authors known to have contributed to the preparation of this protocol should be listed, including those who filled in the template.
- Visit <https://orcid.org/> to register for an ORCID.

## Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
- External Protocols: Protcols from manufacturers or other groups. 
- Include the link to each protocol.
- Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE |
| ------------- | ------------ | ------------ | ------------ |
| OME Gel electrophoresis protocol (in progress)  | TBD | 0.0| TBD |

#### External Protocols

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE |
| ------------- | ------------ | ------------ | ------------ |
|  |  | |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2024-02-01 | Initial release |
| 1.1.0 | 2025-05-01 | Addition of FAIR eDNA terms in YAML frontmatter and formatting edits |

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.
- 
### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|18S V8 rRNA gene|18S ribosomal nucleic acid sequencing assay targeting V8 gene region |
|BSC	|Biosafety cabinet|
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies
|MBARI| Monterey Bay Aquarium Research Institute|
|MBON	|Marine Biodiversity Observation Network|
|NOAA|National Oceanic and Atmospheric Administration|
|NTC	|No template control
|OME	|Ocean Molecular Ecology
|PCR| Polymerase chain reaction |
|PMEL	|Pacific Marine Environmental Laboratory|
|PPE    | Personal protective equipment |
|UW| University of Washington
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or empty filter run through the DNA extraction process to control for contamination in the DNA extraction step. |
| Field blank  | Sampling negative control. Typically distilled or reverse osmosis water run through a filter like an seawater eDNA sample to control for contamination in the field sampling step. |
| No template control | PCR negative control. Typically nuclease-free water loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## BACKGROUND

### Summary

This protocol is for amplifying the Small subunit ribosomal ribonucleic acid (SSU rRNA) 18S v8 gene in eukaryotes. The primers (forward: Machida 18S #3 F, reverse: Machida 18S #5 R) were first presented in [Machida & Nowlton 2012](https://doi.org/10.1371/journal.pone.0046180). The target amplicon size is ~380 base pairs.

This primer set targets metazoan organisms (e.g., molluscs, arthropods, and vertebrates). Important note, this primer also amplifies non-target organisms including single-celled phytoplankton (e.g., dinoflagellates, diatoms, and haptophytes).

The protocol presented here is intended as the first PCR of a two-step PCR next generation sequencing library preparation using Illumina Nextera Unique Dual Indices. Our written protocol does not include the second PCR step in which unique library-specific barcodes are attached to each round 1 PCR product. 

### Method description and rationale

This protocol was chosen because it has been used by the Arctic Marine Biodiveristy Observation Netowrk (AMBON) as well as MBON, a leader in the field of eDNA research and an important partner in the Arctic/Alaska region, to generate marine eDNA time series. Our protocol uses the same polymerase, and thermocycling conditions as MBARI and MBON 16S v4 protocol, but is only 25 µL in total reaction volume. We intentionally chose this protocol to promote standardization of ocean biomolecular observations and easily facilitate integration of PMEL OME eDNA data with AMBON eDNA time series.

This amplification protocol is accessible to most molecular biology labs.

### Spatial coverage and environment(s) of relevance

This protocol has been used to amplify extracted DNA from thousands of filtered sea water samples taken from coastal stations off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf).

### Personnel required

One person with molecular biology experience.

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to chemical reagents.

### Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time needed to execute the procedure

PCR preparation and running the PCR protocol for a single 96-well plate takes 3.5 hours (210 minutes), 120 mins of which is the thermocycler run time. Additional plates can be run simultaneously without greatly increasing the time required. 

## EQUIPMENT

For a 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|Pipetman P10L|Gilson|1|Can be substituted with any accurate pipettor|
|Pipetter: 20 - 200 uL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor|
|Pipetter: 100-1000 uL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic - internal UV light required|
|Thermocycler|Veriti 96-well thermal cycler |Applied Biosystems| 1|	Can be substituted with generic|
| Mini-centrifuge | Personal mini centrifuge  | BioExcell | 1 | Can be substituted with generic, but needs to fit 1.5-2.0 mL tubes |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic|
| Plate spinner | [Salad spinner]( https://doi.org/10.3390/mps3020041) | Cuisinart | 1| Can be substituted with generic or plate centrifuge |
| Foil roller | Rubber roller | Generic | 1 ||
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Eppendorf | 1 | Can be substituted with generic|
| 1.5 mL tube cooler rack | Benchtop cooler | Thermo Scientific  | 1 | Can be subsituted with generic |
| 2 mL tube rack | Microcentrifuge tube rack | VWR | 1 | Can be substituted with generic |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic |
|Wash bottle|Safety Wash Bottle for Ethanol 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Wash bottle|Safety Wash Bottle for Hypochlorite Bleach 500mL|VWR|1|Can be substituted with generic - must be sterilized before use|
|Freezer|Freezer capable of reaching and maintaining -20°C|Generic|1| Used to store DNA and PCR reagents **NOTE: A separate freezer should be used to store PCR products if possible.**|
|Fridge| Refrigerator capable of reaching and maintaining 4°C|Generic|1|Used to store some PCR reagents **NOTE: A separate fridge should be used to hold PCR products if possible.**|
|Trash bag holder|Bel-Art scienceware bench-top biohazard holders|Fisher Scientific|1|Can be substituted with generic|
|Cryoboxes|TruCool hinged lid cryoboxes|VWR|2| Can be substituted with generic - must be sterilized before use |
| **Consumable equipment** |
| 1000 μL pipette tips | TipOne RPT filter tips 1000 μL XL graduated | USA Scientific | 4 | Can be subsituted with generic - must be sterile and filtered |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be subsituted with generic - must be sterile and filtered |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be subsituted with generic - must be sterile and filtered |
| PCR plates | Twin.tec LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 1 | Can be subsituted with generic - must be DNA low retention |
| PCR aluminum foil | Adhesive sterile PCR foil seals | VWR| 2 | Can be substituted with generic - must be sterile |
| 2 mL tubes | Snap cap DNA LoBind 2.0 mL tubes, PCR-clean| Eppendorf |5 | Can be substituted with generic - must be sterile |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |2 | Can be substituted with generic - must be sterile |
| Kimwipes | Delicate task wipes | Kimtech | 5 | |
| Nitrile gloves | Powder Free Nitrile Gloves | Fisher Scientific | 4 | Can be subsituted with generic nitrile gloves. Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
|Trash bags for BSC|Teivio 1.2 Gallon 360 Counts Strong Trash Bags|Teivio|1|Can be substituted with generic|
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH  |
|**Optional Equipment**|||			
|Repeater Pipetter: 10-300  μL|E1-ClipTip electronic single channel pipette, 10-300 μL |ThermoFisher|	1|Can be substituted with generic - not required but reduces protocol time|
| 300 μl repeater pipette tips | ClipTip 300 filtered sterile tips| Thermo Scientific| 2| Can be substituted with generic. Must fit repeater pipette. Must be sterile and filtered. |
|8-channel multichannel pipetter: 1-10 μL| Pipetman Multichannel P8X10|	Gilson|	1|Can be substituted with generic. Not required but reduces protocol time.|
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Can be substituted with generic - recommended not required |
| **Chemicals** |
| PCR master mix 2x|AmpliTaq Gold Fast PCR master mix | Applied Biosystems | 1040 μl per plate | Store at 4°C |
| Forward primer | Custom oligo | IDT |78 μl per plate| Store at -20°C|
| Reverse primer| Custom oligo | IDT | 78 μl per plate | Store at -20°C|
| Nuclease free water | UltraPure DNase/RNase-free distilled water | ThermoFisher | 1196 μl per plate|
| Positive control| gBlocks HiFi Gene Fragments | IDT | 2 μl per plate | Store at -20°C |
| 70% EtOH | Molecular grade ethanol| Generic | 40 mL |
| 10% bleach| Hypochlorite bleach |Clorox| 40 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Sterilize workspaces and durable equipment, including pipettes within the BSC with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
2. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. 
3. Run the UV light in the BSC for 30 minutes before starting work.
4. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins). Recommended labeling scheme includes plate name, primer, date of PCR, and personnel initials.


#### PCR

**Primer Sequences without Adapters**: PCR primer sequences (target sequence bolded)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|Machida_18S V78 F | Forward |**GYGGTGCATGGCCGTTSKTRGTT** |
| Machida_18S V78 R | Reverse | **GTGTGYACAAAGGBCAGGGAC** |

**Primer Sequences Used**: PCR primer sequences with Illumina Adapters
(Adapter sequence + **target sequence bolded**)
| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|18S Machida - Nex - F|Forward  | TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**GYGGTGCATGGCCGTTSKTRGTT** |
| 18S Machida - Nex - R| Reverse | GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**GTGTGYACAAAGGBCAGGGAC** |

**Reaction Mixture**: PCR reagents, volumes, initial, and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |-----|
|AmpliTaq Gold Fast PCR Master Mix  |1040|  10|100% | 40%|
| Forward Primer| 78| 0.75|5 μM | 0.15 μM |
| Reverse Primer |78| 0.75|5 μM |0.15 μM |
| Nuclease-Free Water |1196| 11.5| N/A|N/A |
| Template DNA|N/A| 2 | 100%|8% |
| **Total**|**2392**| **25** | **N/A** |**N/A**|


**PCR Cycling Program**:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|10min|	1X
|**Normal Cycling**||||
|Denaturation|	95°C|	45s|	30X|
|Annealing|	55°C|	45s	|30X|
|Extension 	|68°C	|90s	|30X|
|Final extension	|68°C	| 5min	|1X|
|Hold	|4°C	|∞	|1X|


**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease free water. Then tap/flick AmpliTaq rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted in above in reagent mixture table.
4. Set out template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well (See [Machida Metazoan 18S V8 PCR Protocol Sheet Draft](https://docs.google.com/spreadsheets/d/14exlweJkmsPSTahdmubbECPgm2iUhXlben1yksLek1Y/edit#gid=1701210116)), but reserve two wells for the positive control and a no template control (NTC). 
7. To one well each, add 2 μL of the positive control and 2 μL of nuclease-free water for the NTC.
8. Seal the PCR plate with foil.
9. Spin down the plate, and then transport in cooler blocks before placing in thermocycler.
10.  Run thermocycler protocol.

### Quality control

1. Plates should be removed from the thermocycler  after the run completes and stored at 4°C until run on a gel. Storing the PCR product at -20˚C is ideal for 1-6 month term storage, while -80˚C is ideal for long-term storage.
2. Run gel visualization to confirm successful PCR. [NOAA-PMEL-OME-GelVisualization-Protocol pending]

**Positive Control**
A positive control is used in every PCR run to verify success of the PCR reaction. 2μL of positive control diluted to 10^3 copies/µL is used in place of template DNA. One well per plate is alotted for the positive control. The positive control used for Machida metazoan 18S V8 is  the heterotrophic nanoflagellate *Halocafeteria seosinensis*. The reference sequence used to develop the positive control sequence can be found on GenBank: [Accession: DQ269470.1 ](https://www.ncbi.nlm.nih.gov/nuccore/DQ269470.1)


|Positive Control Sequence|
|--------------------------|
|GCTCTTTCTTGATTCTATGGGTGGTGGTGCATGGCCGTTCTTAGTTGGTGGAGTGATTTGACTGGTTAATTCCGTTAACGAACGAGACCTCCGCCTGCTAATTAGTTTCCAAGTGTGTGCACTTGGTGAAACTTCTTAGAGGGACTATGAGCGTTTAGCTCATGGAAGTTGGAGGCAATAACAGGTCTGTGATGCCCTTAGATGTTCTGGGCCGCACGCGCGCTACGCTGACCGGTGCAACAAGTTTGTATCCTTGGCTCGAAAGGCCTGGGGAATCTTGCAAAGCCGGTCGTGATGGGGATAGATTCTTGCAATTTTTAATCTTCAACGAGGAATTCCTAGTAAACGCAAGTCATCAACTTGCATTGATTACGTCCCTGCCCTTTGTACACACCGCCCGTCGCACCTACCGATTGAATGGTCCGGTGAAACCTCCGGATTGGCGTCGGTTCCCGCAAGGGTCCGCGCCAAAAAGTTGGTTGAACCTTACCATTTAGAGGAAGGTGAAGTCGTAACAAGGTTTCCGTAGGTGAACCTGCAGAAGGATCATTAGAGAGGGAATATA|

**Negative Control**

Nuclease-free water is used as a no template control (NTC) when setting up each PCR plate. One well per plate is alloted to a NTC. NTCs should be run in addition to both field blanks and extraction blanks.


### Basic troubleshooting guide

**Issue 1**: Streaking is observed for sample wells in gel but positive control band appears normal. 

**Solution**: Dilute the sample DNA to a 1:10 dilution with nuclease-free water. If smearing is still observed using a 1:10 dilution, dilute the DNA samples further to a 1:100 dilution. If the samples do not amplify under these conditions the sample likely is inhibited or has too little target DNA and thus is unlikely to yield valuable results. Alternative solutions include cleaning DNA extractions with a commercial clean up kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired and rerun the PCR. If positive control fails again, reagents or positive control are likely compromised. 

**Issue 3**: Band observed in no template control.

**Solution**: The PCR was likely contaminated. Sterilize lab space thoroughly and rerun with new aliquots of reagents.

## REFERENCES

1. Machida, R. J., & Knowlton, N. (2012). PCR Primers for Metazoan Nuclear 18S and 28S Ribosomal DNA Sequences. PloS One, 7(9), e46180–e46180. https://doi.org/10.1371/journal.pone.0046180

## APPENDIX A: DATASHEETS
Protocol Sample Sheet: [Machida Metazoan 18S V8 PCR Protocol Sheet Draft](https://docs.google.com/spreadsheets/d/14exlweJkmsPSTahdmubbECPgm2iUhXlben1yksLek1Y/edit#gid=1701210116)
