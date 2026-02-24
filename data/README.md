# 📂 Data Source Information

The data used in this project is sourced from the **NYC Taxi & Limousine Commission (TLC) Trip Record Data**.

## 🔗 Source Links
- **Public URL:** [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Format:** Parquet
- **Files Processed:** - `yellow_tripdata_2024-01.parquet`
    - `yellow_tripdata_2024-02.parquet`

## 🏗️ Storage in Microsoft Fabric
The raw files are ingested via the `01_Ingestion_Bronze` notebook and stored in the **Microsoft Fabric Lakehouse (OneLake)** under:
- **Files:** `Files/raw_data/`
- **Tables (Delta):** `bronze_nyc_taxi`

> **Note:** Actual data files are not hosted in this repository due to size. The notebooks are configured to pull the data directly from the public source into the Fabric environment.