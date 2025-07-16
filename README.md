# Freelance Invoice App (Mendix Project)

> ⚠️ Bu proje bir şirket için özel olarak geliştirildiği için kaynak kod ve proje dosyaları (.mpk) gizlilik nedeniyle paylaşılmamaktadır.

## 📝 Proje Hakkında

Freelance çalışanların dijital olarak fatura oluşturabilmesini, bu faturaların PDF olarak üretilmesini ve e-posta ile gönderilmesini sağlayan Mendix tabanlı bir uygulamadır. Ek olarak, kullanıcıların oluşturduğu belgeler uygulama içinde görüntülenebilir ve şifrelenmiş olarak saklanır.

Bu uygulama, muhasebe süreçlerini kolaylaştırmak ve manuel işlemleri minimuma indirmek için geliştirilmiştir.

## 🚀 Özellikler

- Fatura oluşturma (form bazlı giriş)
- Otomatik PDF oluşturma
- E-posta ile fatura gönderimi
- Belgeleri uygulama içinde görüntüleme (Document Viewer)
- Verilerin şifrelenerek saklanması
- Kullanıcıya özel veri erişimi

## 🧰 Kullanılan Teknolojiler

- **Mendix Studio Pro** (Low-code geliştirme)
- **Email Connector** (SMTP üzerinden e-posta gönderimi)
- **PDF Document Generation** (Document Template ile dinamik PDF)
- **Encryption** (Veri güvenliği için şifreleme)
- **Mx Model Reflection** (Dinamik veri yapıları ve roller)
- **Document Viewer** (Kullanıcı arayüzünde belge önizleme)
- **Microflow & Domain Model Tasarımı**

## 👨‍💻 Rolüm
- Uygulamanın domain modelini ve şeklini ve ilişkili veri yapısını Mendix Studio Pro kullanarak tasarladım.
- Fatura oluşturma sürecini modellemek için kullanıcı dostu veri giriş formları geliştirdim.
- Fatura özel içerikle dinamik olarak PDF belge üretimi yapılandırdım(PDF Document Generation kullanarak).
- Oluşturulan PDF'lerin, kullanıcı e-posta adresine otomatik olarak gönderilmesi için Email Connector entegre ettim.
- Kullanıcıların oluşturduğu PDF belgelerini uygulama içinde görüntülemelerini sağlayacak şekilde Document Viewer yapılandırdım.
- Uygulamadaki roller ve dinamik yapıların yönetim sağlamak için Mx Model Reflection modülünü entegre ettim ve yapılandırdım.
- Tüm iş akışlarını(kaydetme, gönderme, belge oluşturma vb.) yöneten microflow'ları tasarladım ve koşullara göre yapılandırdım.
- Kullanıcı deneyimini artırmak için mantıksal hataları ve olası senaryoları test ederek gerekli hata kontrollerini mikro akışlara entegre ettim.
- Uygulamanın genel kullanıcı arayüzü düzenini oluşturup, temiz ve işlevsel bir deneyim sunacak şekilde geliştirdim.

## 🔐 Gizlilik

Proje bir şirket için geliştirildiğinden .mpk dosyası paylaşılmamaktadır. Ancak genel işleyiş ve kullanılan teknolojiler hakkında bilgi vermekten memnuniyet duyarım.
