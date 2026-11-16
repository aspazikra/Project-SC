# Is Agriculture Still Relevant? G20 Analysis in the Green-Economy Era

Final project of the Data Science Track, Startup Campus (Studi Independen MSIB Batch 7, 2024), by team **Smooth Operators**.

*Apakah Sektor Pertanian di Negara-Negara Anggota G20 Masih Relevan? Menilai Berdasarkan Sosial-Ekonomi dan Produktivitas Sumber Daya di Era Ekonomi Hijau*

## Summary

- Collected 36 socio-economic and environmental indicators for 20 G20 economies (2020–2022) from the OECD SDMX API and World Bank data.
- Cleaned the data (missing values, outliers), analysed correlations and reduced dimensions with PCA (5 components, about 90% of the variance).
- Compared K-Means, DBSCAN and Agglomerative clustering. K-Means had the best silhouette score (0.66, against 0.39 for DBSCAN) and grouped the countries into 7 profiles.
- Mapped the clusters with Plotly choropleth maps and wrote policy recommendations for sustainable agriculture.

## Files

| File | Contents |
|---|---|
| [`G20_Agriculture_Green_Economy_Analysis.ipynb`](G20_Agriculture_Green_Economy_Analysis.ipynb) | Full notebook: business understanding, data collection, cleaning, EDA, PCA, clustering, visualisation and recommendations |
| `Data csv/` | Datasets used in the notebook |

## Tech stack

Python, pandas, NumPy, Requests, scikit-learn, Yellowbrick, Matplotlib, Seaborn, Plotly

## Team

Alifia Septi Anggraeni · Devina Salsabila · Fransiscus Kristian Susanto · Ines Putri Oktoviani · Muhammad Aspa Zikra · Sendhy Maula Ammarulloh
