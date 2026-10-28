# yo-1

**GISエンジニア / 森林技術者 — 地籍・森林の実務と、GX（グリーントランスフォーメーション）に資する森林情報基盤づくり、そしてQGISプラグイン開発をつなぐ仕事をしています。**
**GIS engineer & forestry professional — bridging field practice in cadastre and forestry with forest data infrastructure for Green Transformation (GX) and QGIS plugin development.**

行政向けアプリ・QGISプラグイン開発では、実務の流れを要件に翻訳、仕様策定から実装まで一貫して担います。**「現場発の内製スタイル」**です。
In developing apps and QGIS plugins for government use, I translate real-world workflows into requirements and carry everything from specification through to implementation — a **field-first, in-house style**.

---

## 🧩 QGIS Plugins / QGISプラグイン

| Plugin | Description |
|---|---|
| [CS Map Sheets](https://github.com/yo-1/csmap-sheets) | DEM のマージ・CS立体図の色調調整・国土基本図図郭 GeoTIFF・XYZタイル生成 / DEM merging, CS hillshade tuning, map-sheet GeoTIFF & XYZ tile export |
| [MORIZON Reloaded](https://github.com/yo-1/MORIZON-Reloaded) | 林野庁公式ツール「もりぞん」の現行QGIS対応移植（森林ゾーニング支援）/ Port of the Forestry Agency's "MORIZON" zoning tool to current QGIS |
| [QGIS Dev Probe](https://github.com/yo-1/qgis-dev-probe) | MCP（AI）クライアントが QGIS を検査・操作するための開発用ブリッジ / A bridge that lets MCP (AI) clients inspect and operate QGIS |
| [GeoHex QGIS](https://github.com/yo-1/geohex-qgis) | ポリゴンから GeoHex v3 六角セルを生成 / Generate GeoHex v3 hexagon cells from polygons |
| [forest-map-sheet-generator](https://github.com/yo-1/forest-map-sheet-generator) | 森林資源メッシュ用 国土基本図図郭作成 / Map-sheet frames for forest resource meshes |
| [forest-mesh20m](https://github.com/yo-1/forest-mesh20m) | 森林資源量メッシュ（20m）生成 / 20 m forest resource mesh generation |

CS Map Sheets、MORIZON Reloaded、QGIS Dev Probe は [plugins.qgis.org](https://plugins.qgis.org/search/?q=yo-1) でも審査を経て公開中です。
Three of these are also published, after review, on the official QGIS plugin repository.

## 🗾 Open GIS Data / 公開データ

- [japan-forest-planning-zones](https://github.com/yo-1/japan-forest-planning-zones) — 市町村ポリゴンに森林計画区・広域流域情報を付加したGISデータ / Municipal polygons enriched with forest planning districts and watershed basins
- [japan-plane-rectangular-cs-zones](https://github.com/yo-1/japan-plane-rectangular-cs-zones) — 平面直角座標系（全国19系）の適用区域ポリゴン / Application-area polygons of Japan's plane rectangular coordinate systems (19 zones)

## 🛠 Tools / ツール

- [fme-csmap-pipeline](https://github.com/yo-1/fme-csmap-pipeline) — DEM から CS立体図を生成するスタンドアロンCLI / Standalone CLI to build CS hillshade maps from DEMs
- [folder-csv-tool](https://github.com/yo-1/folder-csv-tool) — フォルダ・ファイル一覧のCSV化 / Inventory folders and files into CSV
- [photo-metadata-tool](https://github.com/yo-1/photo-metadata-tool) — 写真メタデータの検査・編集 / Inspect and edit photo metadata
- [udc-presentation-timer](https://github.com/yo-1/udc-presentation-timer) — プレゼンテーション用タイマー / Presentation timer
- [mitakihara-records-platform](https://github.com/yo-1/mitakihara-records-platform) — CKAN を公開投影先とする事業型情報記録基盤 / A records platform projecting to 

実務（地籍・森林・GX）と開発（QGIS・GISデータ基盤）と普及（研修・学会・公開）を、一人の技術者の中でつなぐことを目指しています。
Connecting practice (cadastre, forestry, GX), development and outreach — in the field, in code, and in the community.
