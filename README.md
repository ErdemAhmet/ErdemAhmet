<h1 align="center">Erdem Ahmet Önar</h1>

<p align="center">
  Yönetim Bilişim Sistemleri · SQL & Veritabanları · Veri Analizi
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/erdem-ahmet-önar-3b8a03394"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:onarerdemahmet@gmail.com"><img src="https://img.shields.io/badge/E--posta-D14836?logo=gmail&logoColor=white" alt="E-posta"></a>
  <img src="https://img.shields.io/badge/İstanbul-Türkiye-lightgrey" alt="İstanbul">
</p>

---

### 👋 Hakkımda

Piri Reis Üniversitesi Yönetim Bilişim Sistemleri mezunuyum. Veri analizi, veri görselleştirme ve veritabanı yönetimiyle ilgileniyorum. Özellikle **SQL, sorgu performansı analizi, veritabanı optimizasyonu ve veri odaklı çözümler** üzerine kendimi geliştirmeye odaklanıyorum. Bunun yanı sıra makine öğrenmesi ve yazılım geliştirme alanlarında projeler üretiyorum.

- 🗄️ PostgreSQL üzerinde sorgu optimizasyonu, indeksleme, yedekleme ve bakım konularıyla ilgileniyorum
- 📊 Python ile veri analizi ve temel makine öğrenmesi projeleri yapıyorum
- 🌐 Flask ve React ile küçük web uygulamaları geliştiriyorum
- 🤖 Yapay zeka destekli geliştirme araçlarını günlük işimde kullanıyorum

---

### 🛠️ Teknolojiler

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/C%23-512BD4?logo=csharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git">
</p>

---

### 📂 Projelerim

| Proje | Ne yapıyor? | Teknolojiler |
|---|---|---|
| 🎮 [**Gameboxd**](https://github.com/ErdemAhmet/REPO_ADI) | Oyun arama, koleksiyon, puanlama ve yorum içeren video oyunu takip platformu. 5 tablolu ilişkisel şema, RAWG API entegrasyonu ve yerel önbellek. | Flask · React · SQLite |
| 📊 [**Ekran Süresi ve İyi Oluş Analizi**](https://github.com/ErdemAhmet/REPO_ADI) | 400 öğrencilik anketle ekran alışkanlıkları ve zihinsel iyi oluş ilişkisi. İyi oluşun ana belirleyicisi ekran süresi değil, üretkenlik çıktı. | Python · Pandas · Seaborn · Scikit-Learn |
| 🚗 [**İkinci El Araba Fiyat Tahmini**](https://github.com/ErdemAhmet/REPO_ADI) | Türkiye ikinci el araç verisiyle fiyat tahmini. Gradient Boosting ile R² ≈ 0,95. | Python · Pandas · Scikit-Learn |

---

### 🗃️ SQL ile ilgili notlar

Bu yaz yaptığım PostgreSQL stajında şunlarla uğraştım:

- Yaklaşık 43 milyon satırlık bir tabloda 3 farklı SQL yaklaşımını kıyaslayıp süreyi **yaklaşık %27** azalttım
- `EXPLAIN ANALYZE` ile execution plan okuyup indeksle bir test sorgusunu **95 ms → 24 ms**'ye indirdim
- `pg_dump` / `pg_basebackup` yedeklerini otomatikleştirdim, WAL ile geri yükleme ve PITR denedim
