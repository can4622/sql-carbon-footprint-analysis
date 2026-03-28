
🌍 Industry Carbon Footprint Analysis with SQL
Bu proje, farklı endüstri gruplarının ürün bazlı karbon ayak izlerini (PCF) PostgreSQL kullanarak analiz etmek amacıyla hazırlanmıştır. Çalışma, DataCamp platformundaki gerçek dünya veri setleri üzerinden yürütülmüştür.

📊 Veri Seti Hakkında
Analiz edilen product_emissions tablosu şu kritik sütunları içermektedir:

product_name: Analiz edilen ürünün adı.

industry_group: Ürünün ait olduğu endüstri kolu.

carbon_footprint_pcf: CO2 eşdeğeri olarak ürünün toplam karbon ayak izi.

Emission Breakdown: Upstream, Operations ve Downstream aşamalarının yüzdesel dağılımı.

🎯 Analiz Hedefleri
Bu çalışmada SQL sorguları ile şu sorulara yanıt aranmıştır:

En yüksek karbon salınımına sahip endüstri gruplarının tespiti.

Üretim aşamalarının toplam emisyon içindeki ağırlığının analizi.

Çevresel sürdürülebilirlik raporlaması için verinin anlamlandırılması.

🛠️ Teknik Yetkinlikler
Bu proje kapsamında uygulanan teknik SQL becerileri:

Aggregate Functions: SUM(), AVG() ve ROUND() ile sektörel hesaplamalar.

Data Filtering: WHERE ve HAVING ile kritik emisyon noktalarının belirlenmesi.

Ordering: ORDER BY ile en yüksek etkiye sahip sektörlerin sıralanması.

🚀 Proje İçeriği
notebook.ipynb: Tüm SQL sorgularını ve analiz adımlarını içeren ana çalışma dosyası.

pollution.jpg: Projenin görsel temsilidir.
