# NG911 Road Centerline vs PSAP Boundary QA – Pleasant Grove, AL

## Project Overview
This project evaluates NG911 road centerline data for jurisdictional accuracy by comparing road segment geometry against the authoritative Pleasant Grove, Alabama PSAP boundary. The analysis focuses on identifying road centerlines that fall partially or fully outside the PSAP jurisdiction, which may impact call routing, responder dispatch, and GIS-based emergency operations.

## Data Used
- NG911 Road Centerlines (local government source)
- PSAP Jurisdiction Boundary (authoritative)
- Basemap layers for visual reference

## Methodology
Road centerline features were spatially analyzed in ArcGIS Pro using Select By Location to identify road segments not fully contained within the PSAP boundary. Results were visually reviewed, validated against jurisdiction limits, and exported for documentation and quality assurance reporting.

## Results
The analysis identified multiple road centerline segments extending beyond the PSAP boundary. These discrepancies indicate potential data maintenance issues or boundary misalignment that should be reviewed prior to NG911 deployment or updates.

## Deliverables
- QA summary report (PDF)
- Map export highlighting road centerlines outside PSAP jurisdiction
- Supporting screenshots documenting analysis steps

## Skills Demonstrated
- NG911 data quality assurance
- Spatial analysis in ArcGIS Pro
- Jurisdictional boundary validation
- GIS documentation and reporting
