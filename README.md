# sattlite-image-analysis

data:
* **PAN** – 0.6 m panchromatic, 16-bit
* **MSS** – 4-band (Blue, Green, Red, NIR) at ≈ 2.4 m

Setup: Mounted Google Drive, changed directory, listed files.
Libraries: Installed rasterio and ultralytics, imported various image processing and ML libraries.
Data: Verified paths for MSS and PAN image files.
Loading & Analysis: Loaded and analyzed metadata and samples of the MSS and PAN images.
Visualization: Created 8-bit scaled images and RGB composites, displayed various visualizations including true color, false color, single bands, statistics, and histograms.
Road Detection: Applied Canny edge detection and Hough line transform on the PAN sample to detect potential road features and visualized the results.
Land Cover Analysis: Calculated NDVI and NDWI from the MSS sample, created vegetation and water masks based on thresholds, and visualized the indices and masks.
SAM Masking: Installed and loaded the SAM model, applied SAM to the MSS true color composite using point, box, and combined prompts, and visualized the resulting segmentation masks.

