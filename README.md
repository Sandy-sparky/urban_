# HS524M Practical — Urban Informatics & Spatial Analytics

A Python-first submission scaffold for the attached assignment PDF. Includes Question 1 Folium mapping code, Question 2 Google Earth Engine Python analysis code, notebooks, a glassmorphism portfolio webpage with 3D-inspired animation and a working light/dark toggle, plus hosting instructions.

**Q1 is now populated from the supplied `Urban_CS25M117.zip`:** 44 point observations were imported from `notes.gpkg`; 37 matching photographs were copied into the website and linked to the records. Seven observations have no matching photo attachment in the archive and therefore show without a photo. The original archive is not duplicated in this project; rerun the import script with its path if needed.

**Q2 is populated and generated** from the supplied Rajkot (M.COP, ULB code 802501) boundary, 2020 VIIRS monthly radiance, and WorldPop 2020. The reproducible Earth Engine workflow is `q2_rajkot/analyze_rajkot_viirs.py`; its annual exposure estimate is 984,821 residents total, with 500,540 (50.8%) in the city-specific upper quartile of annual mean radiance. These are gridded population estimates, not individual exposure measurements. The monthly slider, GIF, annual exposure map, charts, tables, and source discussion are available in `outputs/q2_rajkot/index.html` and the hosted copy at `website/outputs/q2_rajkot/index.html`.

Start with `RUN_ME_FIRST.md`.

## Main external documentation
- Earth Engine Python setup: https://developers.google.com/earth-engine/guides/quickstart_python
- VIIRS monthly radiance dataset: https://developers.google.com/earth-engine/datasets/catalog/NOAA_VIIRS_DNB_MONTHLY_V1_VCMSLCFG
- WorldPop population dataset: https://developers.google.com/earth-engine/datasets/catalog/WorldPop_GP_100m_pop
- Suggested Indian ULB boundary release: https://github.com/ramSeraph/indian_admin_boundaries/releases/tag/urban
