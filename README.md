# ImEx2025
Export and Import Recommendation Based on ImEx BPS 2025 Data.

###Title Project###
Saran untuk Ekspor dan Impor Indonesia 2025

###Project overview###
Saya bekerja sebagai advisor disektor rantai pasok ekspor dan impor, Client diminta untuk membuat bagaimana cara mengurangi import lima komoditas terbesar yang dikonsumsi dengan memproduksi sendiri dan satu komoditas ekspor di Indonesia bisa di improve, pastikan disesuaikan dengan kondisi lingkungan dan potensi komoditas yang bisa dimanfaatkan oleh negara Indonesia. Pastikan summerizationnya akurat.

Dalam Classification task diperlukan peningkatan akurat seperti focus komoditas. Sedangkan Summarization tasks, penjelasan jangan terlalu umum perlu diperjelas dengan akurat.

Menggunakan model granite-3.3-8b-instruct maka, perlukan
- Max_token untuk memfokuskan point dan respons output serta memastikan datanya relevan menggunakan.
- Agar lebih terstruktur dan sesuai diminta client menggunakan top_k, top_p, repetition_penalty, dan stopping sequence.
- Evaluasi parameter tersebut agar akurat dan arah hasilnya sesuai.

###Raw Data Set Link###
https://www.bps.go.id/id/exim
https://colab.research.google.com/drive/1tThqGyZbVMaxLb-70NUoEEgQm24SeU0k?usp=sharing

###Insight and Findings###
Dalam Konteks komoditas Impor, Indonesia seharusnya bisa memproduksi sendiri yaitu Binatang Hidup (HS 01), Ikan, Daging Hewan (HS 02), Serealia (HS 10). tanpa harus mengimpor karena kondisi alam yang beragam serta lingkungan yang mendukung untuk budidaya Hewan Perdagingan dan Tanaman Serealia.

Lalu, komoditas ekspor yang harus ditingkatkan yaitu Hasil Perikanan (HS 03) berpotensi bisa meningkatkan value per weight.


###AI support explanation###

Generating category summaries...
Generated 98 category summaries

Generating final national trade summary...

=== INDONESIA TRADE SUMMARY BY HS CODE ===
**National Trade Report: Opportunities for Indonesian Exports and Areas for Import Improvement**
**1. Top 3 Import Commodities and Opportunities for Indonesian Production:**
Based on the data, the top three import commodities with significant disparities indicating potential for Indonesian production are:
- **Live Animals (HS 01):** Indonesia imports a vast quantity of live animals, valued at USD 69,239,214.50 and weighing 23,383,518.33 kg. Given Indonesia's agricultural capabilities and existing livestock industries, there's an opportunity for Indonesia to increase production and export of specific livestock breeds or value-added products like processed meat.
- **Meat and Edible Meat Offal (HS 02):** Imports of meat and edible meat offal are substantial, valued at USD 79,981,831.00 and weighing 25,376,892.08 kg. Indonesia has a large agricultural sector, including poultry and beef production. Enhancing processing capabilities and quality standards could position Indonesia as a competitive exporter of processed meat products.
- **Cereals (HS 10):** Indonesia imports cereals heavily, valued at USD 300,774,117.12 and weighing 1,051,850,497.35 kg. With a substantial agricultural base, Indonesia could focus on improving rice and other cereal production, processing, and value-added products like packaged foods to reduce reliance on imports.
**2. Export Commodities Needing Improvement:**
One export commodities where Indonesia could focus on improvement to maximize export results are:
- **Fish, Crustaceans, and Aquatic Invertebrates (HS 03):** Indonesia excels in this category, exporting USD 307,931,800.16 worth of these products. However, there's room for improvement in value per unit of weight.
