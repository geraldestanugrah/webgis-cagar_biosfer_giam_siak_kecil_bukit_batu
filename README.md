# WebGIS Tutupan Lahan,Fragmentasi Lanskap, Kelembapan Permukaan, dan Suhu Permukaan
Cagar Biosfer Giam Siak Kecil–Bukit Batu

**Peta interaktif:** https://geraldestanugrah.github.io/webgis-cagar_biosfer_giam_siak_kecil_bukit_batu/

Peta interaktif berbasis Leaflet (dibuat dengan Python/Folium) dari data skripsi.

## Isi peta
- Raster tanpa grid: tutupan lahan (LULC), NDMI, LST, PD, ED, AI (tooltip nilai saat kursor didekatkan)
- Grid 500 × 500 m: LST, NDMI, PD, ED, AI 
- Batas zona: inti, penyangga, transisi, dan buffer 5 km
- Beberapa pilihan peta dasar

## Cara menggunakan
Nyalakan layer di panel kanan atas, atur transparansi raster dengan slider,
dan dekatkan kursor ke peta untuk melihat nilai.

## Data dan metode
Data berasal dari hasil skripsi penulis (Landsat 9 tahun 2025, Google Earth Engine).
Klasifikasi tutupan lahan, NDMI, LST, PD, ED, dan AI. Pemrosesan tampilan memakai Python
(GeoPandas, Rasterio, Folium).

## Catatan
- Raster ditampilkan dengan resolusi diperkecil (sekitar 70 m) untuk keperluan tampilan.
  Nilai pada tooltip bukan untuk analisis.
- Area tanpa data pada raster ditampilkan transparan.

## Atribusi peta dasar
Esri; © OpenStreetMap contributors; © OpenTopoMap; Sentinel-2 cloudless by EOX IT Services GmbH
(contains modified Copernicus Sentinel data 2020).

## Penulis
Geraldo Desta Anugrah — linkedin.com/in/geranugrah
