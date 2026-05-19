# ESP32-Aircraft-Warning-System
# Basic ESP32 Aircraft Warning System

## English

This is one of my first ESP32 projects.
I already had some experience with Arduino before starting ESP32, so I wasn’t completely new to electronics or basic sensor logic, but this project was my first real step into ESP32-based embedded systems.

The main idea was to build a simple aircraft-style warning system while learning how different components work together.

### Components Used

* ESP32 DevKit
* OLED Display
* Potentiometer
* Red LED
* Buzzer

The potentiometer is used as a simulated temperature input.
When the value goes above a certain level:

* the red LED turns on,
* the buzzer alarm becomes active,
* and a warning message appears on the OLED display.

While building this project, I mainly focused on understanding:

* analog input reading,
* GPIO control,
* OLED communication,
* basic warning logic,
* and how small embedded systems are structured.

Right now I’m still learning ESP32 and working mostly in simulation environments, but later I want to build more advanced systems using a real ESP32 board and real sensors.
I’m especially interested in aviation-inspired embedded systems, warning panels and real-time sensor-based projects.

This project is small, but it represents the direction I want to continue in.

---

# Basic ESP32 Aircraft Warning System

## Türkçe

Bu proje, ESP32 ile yaptığım ilk projelerden biri.
ESP32’ye başlamadan önce Arduino ile uğraştığım için elektronik ve temel sensör mantığına tamamen yabancı değildim ama bu proje benim için ESP32 tarafındaki ilk gerçek başlangıçlardan biri oldu.

Projeyi yaparken amacım sadece birkaç parçayı çalıştırmak değil, parçaların bir sistem içinde birlikte nasıl çalıştığını anlamaktı. Bu yüzden projeyi küçük bir uçak ikaz sistemi mantığında geliştirmeye çalıştım.

### Kullanılan Parçalar

* ESP32 DevKit
* OLED ekran
* Potansiyometre
* Kırmızı LED
* Buzzer

Potansiyometreyi sıcaklık verisi gibi kullanarak sistemi ona göre çalıştırdım.
Belirli bir değerin üstüne çıkıldığında:

* kırmızı LED aktif oluyor,
* buzzer alarm vermeye başlıyor,
* OLED ekranda warning mesajı gösteriliyor.

Bu proje sırasında özellikle:

* analog veri okuma,
* GPIO kontrolü,
* OLED ekran kullanımı,
* alarm mantığı kurma,
* temel embedded sistem yapısı

gibi konuları öğrenmeye çalıştım.

Şu an hâlâ ESP32 öğrenme sürecindeyim ve çoğu şeyi simülasyon ortamında geliştiriyorum. İleride gerçek ESP32 kartı ve gerçek sensörlerle daha gelişmiş sistemler yapmak istiyorum. Özellikle havacılık sistemlerinden esinlenen embedded projeler ilgimi çekiyor.

Bu proje küçük bir başlangıç olsa da ilerlemek istediğim alanın temelini oluşturuyor.
