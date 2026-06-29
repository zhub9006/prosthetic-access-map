# Prosthetic Access Atlas

An open-access resource mapping prosthetic and orthotic care access gaps across underserved communities in the United States, combined with clinical trial data from ClinicalTrials.gov.

## Mission

To identify and visualize disparities in prosthetic/orthotic care access, particularly in rural and medically underserved regions, and to connect these gaps with ongoing prosthetic clinical research.

## Data Sources

- **Clinical Trials**: ClinicalTrials.gov API — prosthetic-related trials analyzed by status and country
- **Geospatial Data**: OpenStreetMap (via OSM MCP) — healthcare provider mapping
- **Target Regions**: Rural West Virginia, Appalachian Eastern Kentucky, Mississippi Delta

## Key Findings

### Clinical Trial Landscape (Prosthetic)
- **Total studies**: 2,169 prosthetic-related clinical trials
- **US dominance**: 2,383 studies associated with the United States (including multi-country trials), far outpacing all other nations
- **Status breakdown**: See `clinical-trial-data.json` for full details

### Coverage Gaps

| Region | Coordinates | Specialized Prosthetic/Orthotic Providers | General Healthcare Only |
|--------|------------|------------------------------------------|------------------------|
| Rural West Virginia | 38.48°N, 80.84°W | **None identified** | Pharmacies, clinics, VA clinic |
| Appalachian Eastern KY | 37.25°N, 83.20°W | **None identified** | Pharmacies, clinics, therapy services |
| Mississippi Delta | 32.77°N, 90.41°W | **None identified** | Clinics, hospitals, dentists |

**Critical Gap**: No prosthetic or orthotic Specialists, prosthetists, or orthotists were found in any of the three target regions. Residents must travel significant distances for specialized prosthetic care.

## How to Contribute

1. Add more region profiles
2. Submit PRs with updated clinical trial data
3. Integrate insurance/Medicaid data for coverage analysis
4. Add patient outcome datasets

## License

Open Access — freely available for research and advocacy purposes.