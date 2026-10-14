# TeknoFest
Bu proje, Teknofest kapsamında geliştirilen insansız kara aracı sistemidir. Projenin amacı aracın otonom şekilde hareket etmesi, çevresini algılayarak engellerden kaçması, belirli bir GPS noktasına ulaşması, hedefleri görüntü işleme ile tanıyıp lazer işaretleme ve atış yapabilmesi olarak tanımlanmıştır.

Son aşamada şu çalışmalar tamamlanmıştır:

Motor kontrol algoritması (PID tabanlı) geliştirildi.
Servo kontrol sistemi yazıldı, hedef yönlendirme için altyapı hazırlandı.
LoRa haberleşme yapısı ROS2 üzerinde kuruldu ve test için dummy veriyle çalıştırıldı.
Lidar ve ultrasonik sensörler ile basit engel kaçınma algoritması (sensor fusion) yazıldı.
GPS/IMU verileriyle hedefe yönelme algoritması kod üzerinde denendi, temel testler yapıldı.

Tüm algoritmaların akış diyagramları draw.io üzerinde hazırlandı.

Sonraki aşamada tüm kodların güncel teknolojik altyapı ile test edilmesi, YOLO tabanlı hedef tespit algoritmasının tamamlanması, SLAM haritalama yönteminin opsiyonel olarak değerlendirilmesi ve tüm sistemin sahada gerçek testler ile doğrulanması gerekmektedir.

Herhangi bir sorunda github üzerinden dökümantasyonu, kodları ve log dosyalarını (csv file) inceleyebilirsiniz. Başarılar dilerim.
