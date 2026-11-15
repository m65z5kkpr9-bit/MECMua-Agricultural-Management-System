**https://mec-mua-agricultural-management-system.replit.app**
# MECMua Agricultural Management System

MECMua is a smart agricultural management dashboard developed to digitally monitor, analyze, and optimize agricultural operations. The project visualizes land data on a map for different agricultural regions, fetches live meteorological data, analyzes soil conditions, and simulates drone-based agricultural operations. It provides a single-page web interface offering decision support for farmers, field managers, and agricultural teams.

## About the Project

In agricultural fields, this system aims to:
- increase land productivity,
- monitor soil and weather conditions,
- enable more informed irrigation and spraying decisions,
- visualize drone-based agricultural operations,
- optimize operations with the help of automation rules.

The project is a frontend-only application operating with user interface and simulation logic. It does not include a real database or backend server infrastructure; data flow is provided via external open APIs.

## Key Features

- **Regional agricultural data**
  - Custom agricultural profiles for Central Anatolia, Mediterranean, Aegean, Black Sea, and Eastern Anatolia
  - Field area size, soil type, current crop, NDVI value, and yield increase metrics

- **Map-based field view**
  - Map representing the field built with Leaflet
  - Area coordinates and field boundaries
  - Flight path and drone movement simulation

- **Live meteorology and soil analysis**
  - Fetching temperature, wind speed, relative humidity, and radiation data via the Open-Meteo API
  - Soil moisture analysis and irrigation status assessment
  - Agricultural operation recommendations

- **Smart recommendations and automation**
  - Recommended workflows based on weather conditions
  - Automation rules based on temperature, humidity, and wind thresholds
  - Safe operating conditions for autonomous drone operations

- **Drone simulation**
  - Visual representation of drone movements over the field
  - Flight progress percentage, battery status, and operational output

- **PDF report export**
  - Exporting the visually prepared analysis page in a printable PDF format

## Technologies

- HTML5
- CSS3
- JavaScript
- Leaflet.js
- Open-Meteo API
- Lucide Icons

## Usage

1. Clone the repository.
2. Open the `indexx.html` file on your computer.
3. Once the page loads in the browser, regional data and live analysis start automatically.
4. You can switch regions, start the drone simulation, and manage automation rules.
5. You can export the page as a PDF.

## Project Structure

- `indexx.html`
  - Complete user interface design
  - Stylesheets
  - JavaScript logic
  - Map and analysis functions

## References / Data Sources

- **Open-Meteo API**
  - https://open-meteo.com/
  - Used for meteorological data, temperature, wind, relative humidity, radiation, and soil moisture analysis.

- **Leaflet**
  - https://leafletjs.com/
  - Used for map rendering and visualizing land coordinates.

- **ArcGIS World Imagery**
  - https://www.arcgis.com/
  - Used as the map background layer.

- **Google Fonts**
  - https://fonts.google.com/
  - Used for typography design and modern interface appearance.

- **Lucide Icons**
  - https://lucide.dev/
  - Used for symbol and icon design.
  NASA POWER API (Prediction Of Worldwide Energy Resources)
https://power.larc.nasa.gov/
Used for satellite-derived solar radiation, agroclimatology parameters, and surface meteorological baseline data across regional agricultural profiles.
Esri / NASA ArcGIS World Imagery & Earth Observation Layers
https://www.arcgis.com/
Used for high-resolution satellite base mapping, terrain visualization, and geospatial field boundary rendering.

## Project Team

- **Muhammed Emrecan ÖZTÜRK** – Project Lead / Interface and Architecture
- **Mert KUMANDAŞ** – Mapping and Data Visualization
- **Muhammed Ali ÖZDEMİR** – Agricultural Data Analysis and Autonomous Logic
- **Can KUMANDAŞ** – UI/UX and Design
- **Salih TÜRKER** – Reporting, Testing, and Documentation

## Development Purpose

MECMua is designed as a solution that digitalizes modern agricultural operations and makes agricultural decisions more efficient. The project serves as a strong reference application for land-based decision support systems and can be expanded in the future with real sensor data, database integration, and mobile application support.


**TÜRKÇE**












Tabii — aşağıdaki metni doğrudan GitHub README olarak kullanabileceğin şekilde hazırladım. Kaynakça kısmı, veri çekim kaynaklarını net gösteriyor; en altta da 5 kişilik proje görevleri için yer bırakıldı. İsimleri sen doldurabilirsin.

MECMua Agricultural Management System

MECMua, tarım operasyonlarını dijital olarak izleme, analiz etme ve optimize etme amacıyla geliştirilen akıllı bir tarım yönetim panelidir. Proje, farklı tarım bölgeleri için arazi verilerini harita üzerinde görselleştirir, canlı meteorolojik verileri çeker, toprak koşullarını analiz eder ve drone tabanlı tarım operasyonlarını simüle eder. Çiftçiler, saha yöneticileri ve tarım ekipleri için karar destek sağlayan tek sayfalık bir web arayüzü sunar.

Proje Hakkında

Bu sistem, tarım alanlarında:
- arazi verimliliğini artırmayı,
- toprak ve hava koşullarını takip etmeyi,
- sulama ve ilaçlama kararlarını daha bilinçli almaya,
- drone tabanlı tarım operasyonlarını görselleştirmeyi,
- otomasyon kuralları yardımıyla operasyonları optimize etmeyi hedefler.

Proje, yalnızca kullanıcı arayüzü ve simülasyon mantığı ile çalışan bir frontend uygulamasıdır. Gerçek veritabanı veya arka plan sunucu altyapısı içermemektedir; veri akışı, dış kaynaklı açık API’ler üzerinden sağlanmaktadır.

Öne Çıkan Özellikler

- Bölgesel tarım verileri
  - İç Anadolu, Akdeniz, Ege, Karadeniz ve Doğu Anadolu için özel tarım profilleri
  - Alan büyüklüğü, toprak tipi, mevcut ürün, NDVI değeri ve verim artışı bilgileri

- Harita tabanlı arazi görünümü
  - Leaflet kullanılarak tarlayı temsil eden harita
  - Alan koordinatları ve tarla sınırları
  - Uçuş rotası ve drone hareket simülasyonu

- Canlı meteoroloji ve toprak analizi
  - Open-Meteo API ile sıcaklık, rüzgar hızı, bağıl nem ve radyasyon verisi çekimi
  - Toprak nemi analizi ve sulama durumu değerlendirmesi
  - Tarımsal operasyon önerileri

- Akıllı tavsiye ve otomasyon
  - Hava koşullarına göre önerilen iş akışları
  - Sıcaklık, nem ve rüzgar eşiklerine göre otomasyon kuralları
  - Otonom drone operasyonu için güvenli çalışma koşulları

- Drone simülasyonu
  - Tarlada drone hareketlerinin görsel gösterimi
  - Uçuş ilerleme yüzdesi, batarya durumu ve operasyon çıktısı

- PDF rapor çıktısı
  - Görsel olarak hazırlanan analiz sayfasını yazdırılabilir PDF formatında alma

Teknolojiler

- HTML5
- CSS3
- JavaScript
- Leaflet.js
- Open-Meteo API
- Lucide Icons

Kullanım

1. Repository’yi klonlayın.
2. indexx.html dosyasını bilgisayarınızda açın.
3. Tarayıcıda sayfa yüklendikten sonra otomatik olarak bölge verileri ve canlı analiz başlatılır.
4. Bölge değiştirilebilir, drone simülasyonu başlatılabilir ve otomasyon kuralları yönetilebilir.
5. Sayfayı PDF olarak dışarı aktarabilirsiniz.

Yapı

- indexx.html
  - Tüm arayüz tasarımı
  - Stil dosyaları
  - JavaScript mantığı
  - Harita ve analiz fonksiyonları

Kaynakça / Veri Kaynakları

- Open-Meteo API
  - https://open-meteo.com/
  - Meteorolojik veriler, sıcaklık, rüzgar, bağıl nem, radyasyon ve toprak nemi analizi için kullanılmıştır.

- Leaflet
  - https://leafletjs.com/
  - Harita görüntüleme ve arazi koordinatlarının görselleştirilmesi için kullanılmıştır.

- ArcGIS World Imagery
  - https://www.arcgis.com/
  - Harita arka plan katmanı olarak kullanılmıştır.

- Google Fonts
  - https://fonts.google.com/
  - Yazı tipi tasarımı ve modern arayüz görünümü için kullanılmıştır.

- Lucide Icons
  - https://lucide.dev/
  - Simge ve ikon tasarımı için kullanılmıştır.

Proje Ekibi

- Muhammed Emrecan ÖZTÜRK – Proje Lideri / Arayüz ve Mimari
- Mert KUMANDAŞ – Harita ve Veri Görselleştirme
- Muhammed Ali ÖZDEMİR – Tarım Veri Analizi ve Otonom Mantık
- Can KUMANDAŞ – UI/UX ve Tasarım
- Salih TÜRKER – Raporlama, Test ve Dokümantasyon

Geliştirme Amacı

MECMua, modern tarım operasyonlarını dijitalleştiren ve tarımsal kararları daha verimli hale getiren bir çözüm olarak tasarlanmıştır. Proje, araziye dayalı karar destek sistemleri için güçlü bir örnek uygulamadır ve gelecekte gerçek sensör verileri, veritabanı entegrasyonu ve mobil uygulama desteğiyle genişletilebilir.

