# UTS PEMWEB

**Oleh**

```python
20230801536-FRANS DANDY RIAUDY MISSAH

```
# PICOS FRAMEWORK DEFINITION

# P (Platform/Suspect)
**Platform Digital & Karakteristik Pengguna

Website pemesanan online

Mobile aplikasi

Social media integration

Demografi pengguna (usia, lokasi, perilaku)**

# I (Intervention)
**Fitur dan Fungsi Website

User interface design

Proses pemesanan

Payment integration

Recommendation system

Loyalty program**

# C (Comparison)
**Perbandingan dengan Metode Lain

Pemesanan offline (langsung di restoran)

Platform third-party (GoFood, GrabFood)

Metode pemesanan tradisional (telepon)

Versi website yang berbeda (A/B testing)**

# O (Outcome)
**Hasil yang Diukur

Conversion rate

User satisfaction

Operational efficiency

Revenue impact

Customer retention**

# S (Study Design)
**Jenis Penelitian

Experimental studies

Observational studies

User testing

Analytics analysis

# A. PLATFORM/SUSPECT-FOCUSED RQs

RQ1: Bagaimana karakteristik demografi pengguna (usia, jenis kelamin, lokasi) mempengaruhi preferensi terhadap platform pemesanan online vs offline?

RQ2: Apa perbedaan perilaku pemesanan antara pengguna smartphone dan desktop dalam menggunakan website pemesanan fast food?

RQ3: Bagaimana tingkat tech-savviness pengguna mempengaruhi adoption rate dan frequency of use platform website pemesanan?

RQ4: Apa perbedaan kebutuhan dan ekspektasi antara first-time users dan repeat customers dalam menggunakan platform digital?

# B. INTERVENTION-FOCUSED RQs
User Interface & Experience
RQ5: Bagaimana pengaruh desain user interface (minimalist vs feature-rich) terhadap conversion rate dan user satisfaction?

 RQ6: Seberapa efektif implementasi progressive web app (PWA) dibandingkan website tradisional dalam meningkatkan mobile user engagement?

RQ7: Bagaimana pengaruh personalized menu recommendations terhadap average order value dan customer loyalty?

Ordering Process
RQ8: Apa perbedaan completion rate antara single-page checkout dan multi-step checkout process?

RQ9: Bagaimana pengaruh guest checkout option terhadap conversion rate dibandingkan mandatory registration?

RQ10: Seberapa efektif real-time order tracking dalam mengurangi customer anxiety dan meningkatkan satisfaction?

Payment & Security
RQ11: Bagaimana preferensi pengguna terhadap berbagai payment methods (e-wallet, bank transfer, COD) dan pengaruhnya terhadap completion rate?

RQ12: Apa pengaruh visible security indicators (SSL, trust badges) terhadap user trust dan conversion rate?

# C. COMPARISON-FOCUSED RQs
Website vs Traditional Methods
RQ13: Apa perbedaan average order value antara pemesanan melalui website dan pemesanan langsung di restoran?

RQ14: Bagaimana perbedaan peak hour order distribution antara platform online dan offline?

RQ15: Apa perbedaan complexity of orders (customization, special requests) antara pemesanan digital dan tradisional

# IMPLEMENTASI WEBSITE

1.  cd UTS-PEMWEB-2025
2.  Buat folder project:
    mkdir public
3.  Pindahkan template Feane:    mv      feane-1.0.0 public/
4.  Masuk ke folder public:
    cd public
5.  Cek isi template:
    ls
6. Buat file docker-compose.yml di root project:
    cp docker-compose.yml ../docker-compose.yml
7.  Jalankan Docker:
    docker compose up -d
8.  Cek container berjalan:
    docker ps
9.  Akses website di browser:
    http://localhost:8080
10. Jika ingin stop container:
    docker compose down