﻿# Hack-Series-Hack-the-Insurance

Lumiflight Projesi
Lumiflight, kullanıcıların akıllı cihazlarından elde edilen sağlık verilerini değerlendirerek, yapay zeka destekli bir sağlık takip sistemini temsil eder. 

Teknolojik Altyapı
Frontend
Projede, kullanıcı arayüzünü oluşturmak için Angular kullanılmıştır. İki farklı frontend projesi bulunmaktadır:

Watch: Kullanıcıların anlık sağlık verilerini takip etmelerini sağlayan proje.
Hasta Veri Girişi: Sağlık verilerini girmek ve yönetmek için kullanılan proje.
Backend
Spring Boot kullanılarak geliştirilen backend, RESTful API'lerle sağlık verilerinin işlenmesini ve yönetilmesini sağlar. Bu API'ler, kullanıcıların veri eklemesini, getirmesini ve listelemesini destekler.

Nasıl Çalışır?
Backend: Spring Boot ile yazılan backend, veritabanında sağlık verilerini işleyen RESTful API'leri barındırır. Bu API'ler, kullanıcıların sağlık verilerini yönetmelerine olanak tanır.

Frontend - Watch: Angular kullanılarak geliştirilen bu proje, kullanıcılara anlık sağlık verilerini takip etme imkanı sunar. Backend ile iletişim kurarak güncel verilere erişir.

Frontend - Hasta Veri Girişi: Diğer Angular projesi, kullanıcıların sağlık verilerini girmelerini ve yönetmelerini sağlar. Bu veriler, backend üzerinden API'ler aracılığıyla işlenir.

Projeyi Çalıştırma Adımları
Backend:

Spring Boot uygulamasını çalıştırarak RESTful API'leri ayağa kaldırın.
Frontend:

İlgili Angular projelerini çalıştırarak kullanıcı arayüzlerini gözlemleyin.
İstekler:

Frontend projelerinden gelen istekler, backend tarafından işlenerek veritabanına kaydedilir veya mevcut verilere erişim sağlar.
