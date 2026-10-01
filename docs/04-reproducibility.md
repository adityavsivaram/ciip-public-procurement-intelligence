# Reproducibility

## Public source

The study uses San Francisco public procurement datasets published through DataSF.

DataSF provides SODA API access and exposes API endpoints/available columns through each dataset's Export interface.

Source portal:

https://data.sf.gov/

Developer resources:

https://data.sf.gov/developers

## Reproduction approach

1. Retrieve the relevant source datasets directly from DataSF.
2. Record extraction date and source metadata.
3. Profile fields, row counts and missingness.
4. Normalize identifiers without destroying original IDs.
5. Establish cross-system identity bridges.
6. Apply indicator eligibility gates.
7. Run only indicators supported by available evidence.
8. Preserve row/line/PO semantics.
9. Reconcile payment populations using validated identifier relationships.
10. Produce case-level outputs.
11. Apply the evidence gate before writing a commercial conclusion.

## Reproducibility boundary

The original bulk datasets are intentionally not committed to this repository.

The published artifacts document the methodology and final public case. Future releases may add reproducible notebooks for selected transformations where redistribution and source terms permit.
