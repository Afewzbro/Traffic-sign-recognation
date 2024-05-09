Başlık: Evrişimli Sinir Ağları Kullanarak Trafik İşareti Tanıma

Amaç: Bu projenin amacı, trafik işaretlerini doğru bir şekilde tanıyabilen bir makine öğrenmesi modeli geliştirmektir. Trafik işaretlerini anlamak, güvenli navigasyon için otonom sürüş sistemlerinde kritik öneme sahiptir.

Yöntem: Bu görev için Python'da TensorFlow ve Keras kütüphaneleri kullanılarak uygulanan bir Evrişimli Sinir Ağı (CNN) modeli kullandık. Model, birkaç evrişimli ve maksimum havuzlama katmanından, ardından tamamen bağlı bir katman ve softmax çıktı katmanından oluşur. Model, 0.001 öğrenme hızına sahip Adam optimizatörü kullanılarak eğitildi.

Materyaller: Modelin eğitim ve testinde kullanılan veri seti, 43 farklı trafik işaretinin 50.000'den fazla görüntüsünü içeren Alman Trafik İşareti Tanıma Benchmark (GTSRB) veri setidir. Veri seti, bir eğitim seti ve bir test seti olmak üzere ikiye ayrıldı, verilerin %80'i eğitim için ve %20'si test için kullanıldı.

Sonuçlar: Model, eğitim setinde 94.8% ve test setinde 98.4% doğruluk elde etti. Karmaşıklık matrisi, modelin belirli işaretleri tanımada özellikle iyi olduğunu, ancak diğerleriyle mücadele ettiğini göstermektedir.
