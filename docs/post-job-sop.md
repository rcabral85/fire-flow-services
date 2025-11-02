# Post-Job SOP (Data Import + QA)

Standard operating procedure for closing out a fire flow testing job.

## 1. Data Consolidation
- [ ] Verify all hydrants in scope are tested or marked deferred
- [ ] Collect photos and GPS metadata
- [ ] Export raw readings (static, residual, pitot) from FieldKit/HydrantHub

## 2. Calculation & Validation
- [ ] Validate coefficients and nozzle sizes
- [ ] Recompute Q = 29.83 × c × d² × √P for each outlet
- [ ] Confirm available fire flow at 20 PSI residual (NFPA 291)
- [ ] Flag anomalies for operator review

## 3. Reporting
- [ ] Generate per-hydrant PDF reports
- [ ] Compile zone/district summary report
- [ ] Produce water supply curves
- [ ] Package GIS exports (GeoJSON/KML) with classes AA/A/B/C

## 4. Import into HydrantHub
- [ ] Upload PDFs and data to HydrantHub project
- [ ] Attach photos to asset records
- [ ] Verify GIS mapping and coordinates

## 5. Quality Assurance
- [ ] Spot-check 10% of records against field notes
- [ ] Ensure timestamps and operator IDs are present
- [ ] Archive raw data and reports with versioning

## 6. Client Handover
- [ ] Email deliverables and portal access instructions
- [ ] Document remediation recommendations
- [ ] Capture feedback and future scheduling windows
