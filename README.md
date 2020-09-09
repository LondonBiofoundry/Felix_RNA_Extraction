# Felix_RNA_Extraction
Extraction script for running RNA extraction using multiple manufacturer kits

# Hardware requirements
- CyBio FeliX Liquid Handler (Analytik Jena OL5015-24-100)
- 1x CyBio Head R96/1000 μl (Analytik Jena*)
- 2x 96-channel magazine (Analytik Jena OL3396-352-25*)
- 2x 97 mm Support (Analytik Jena OL3317-11-105*)
- 1x CyBio FeliX Gripper (Analytik Jena*)
- 1x 37 mm Support (Analytik Jena OL3317-11-120*)
- 1x Magnum FLX Enhanced magnet adapter (Alpaqua*)
- 1x BioShake D30-T elm with deep well adapter (QInstruments 2016-0518; note: *not* included in Extraction Set)
- 1x Magic Tip Thing (one or two spares are probably desirable, 3D-printed STL file included in repository)
- Laptop with a minimum of two USB ports, running Windows (Windows 10 has been confirmed to work)

&ast; included in Analytik Jena Extraction Set OL5015-25-120

# Consumable requirements per kit
- 2x 1000 μl Tecan-style filter tips (Analytik Jena OL3811-25-939-F)
- 2x protective plate (Analytik Jena 31-01641)
- 7x 96-well 2 ml deep-well plates (e.g. ThermoFisher KingFisher Flex A43075)
- 1x 96-well elution plate (e.g. FrameStar 96 well skirted PCR plate 4titude 4ti-0960)
- 1x 96 reaction extraction kit (see below for supported kits)

# Software
- Analytik Jena Composer - with support for Bioshake D30-T elm and CyBio Head R96/1000 μl, confirmed with Windows 10
- Extraction script (v16.bms)

# Supported Extraction Kits
- innuPREP Virus DNA/RNA Kit - FX (Analytik Jena 845-FX-2096096, 845-KS-4800)
- Maxwell HT Viral TNA - Custom (Promega AX2340)

# Instructions
- the file `instructions.pdf` describes the procedure for preparing with the innuPREP Virus DNA/RNA kit or the Maxwell HT Viral TNA kit.

# 3D printing
- the Magic Tip Thing permits a more reliable transfer of tips from their packaging into the magazine
- printed using an FDM printer (Prusa MK3S) with 0.2 mm layer height, no supports
- print the files `Ejector.stl` and `Retainer.stl` which will slot into each other when in use
