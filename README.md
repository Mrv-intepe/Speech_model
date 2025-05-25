# # Analizimde türkçe komut tanıma veri setini kullandım. 

# Veri seti toplamda 14 farklı komuttan oluşmaktadır (aç, aşağı, başlat, devam, dur, evet, geri, hayır, ileri, kapa, sağ, sol ve yukarı). Veri seti toplamda 26,485 ses kaydından oluşmaktadır, her ses kaydı tam olarak 1 saniye uzunluğundadır 

# Verileri tanımak, görselleştirmek, tanımlayıcı istatistiklerine bakmak vb. için keşfedici veri analizi (EDA) yaptım. Amacımız, veri setini oluşturan değişkenleri anlamaktır. 

# Veri ses dosyası olduğundan veriyi incelerken Waveshow, Spectrogram, Chromagram kullandım.  

# Ses dosyası özellik çıkarım için feature.mfcc kullandım. Mfcc(Mel-Frequency Cepstral Coefficients), karmaşık ses verisini makine öğrenmesi algoritmaları için uygun hale getirir. 

# Veriyi train-test-validation olarak ayırdım. 

# Modelimde LGBMClassifier kullanarak fit ettim. 

# Validation ve test verisinin predict aşamasını  classification report ile değerlendirme yaparak görselleştirdim. 

# Validation accuracy:0.65 

# Test accuracy:0.63 

# Iki farklı örnek ekleyerek modelimi destekledim

https://www.kaggle.com/code/merveintepe/speech-model#T%C3%BCrk%C3%A7e-komut-tan%C4%B1ma-veri-seti 
