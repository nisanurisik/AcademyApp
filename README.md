# AcademyApp

AcademyApp, çevrimiçi eğitim platformlarını hedefleyen bir **ASP.NET Core MVC** uygulamasıdır. Bu proje, kullanıcıların kurslara katılmasını, eğitmenlerin derslerini yönetmesini ve yöneticilerin platformu yönetmesini sağlayan modern bir web uygulamasıdır.

## 🚀 Kullanılan Teknolojiler

### Backend
- **ASP.NET Core MVC (6.0+)**
- **Entity Framework Core** (Code-First yaklaşımı)
- **SQL Server** (Veritabanı)
- **Repository Pattern** implementasyonu
- **Cookie tabanlı kimlik doğrulama** ve **Role tabanlı yetkilendirme**

### Frontend
- **HTML / CSS / JavaScript**
- **Tailwind CSS** & **DaisyUI** (Tailwind component library)
- **Font Awesome** ikonları

---

## 🏗️ Proje Mimarisi

### 📂 Controllers
- **UsersController** → Kullanıcı işlemleri
- **CoursesController** → Kurs yönetimi
- **CategoriesController** → Kategori yönetimi
- **EnrollmentsController** → Kayıt işlemleri
- **InstructorsController** → Eğitmen yönetimi
- **StudentsController** → Öğrenci yönetimi

### 📌 Entities
- **User** → Kullanıcılar
- **Course** → Kurslar
- **Category** → Kategoriler
- **Enrollment** → Kurs kayıtları
- **Role** → Kullanıcı rolleri
- **Level** → Kurs seviyeleri

### 🏛️ Repository Pattern
- **IBaseRepository** (Generic CRUD operasyonları)
- **Her entity için özel repository sınıfları**
- **Entity Framework Core implementasyonu**

---

## 🔑 Temel Özellikler

### 1️⃣ Kullanıcı Yönetimi
- Kayıt ve giriş işlemleri
- Rol tabanlı yetkilendirme (**Admin, Instructor, Student**)
- Profil yönetimi

### 2️⃣ Kurs Yönetimi
- Kurs oluşturma, düzenleme, silme
- Kategori bazlı organizasyon
- Seviye bazlı sınıflandırma
- Kurs detay sayfaları

### 3️⃣ Kayıt Sistemi
- Öğrencilerin kurslara kaydı
- Kayıt durumu takibi
- Kurs ilerleme takibi

### 4️⃣ Admin Paneli
- Kullanıcı yönetimi
- Kurs yönetimi
- Kategori yönetimi
- Kayıt yönetimi

---

## 🔒 Güvenlik Özellikleri

### ✅ Kimlik Doğrulama
- Cookie tabanlı oturum yönetimi
- Güvenli parola yönetimi

### ✅ Yetkilendirme
- Rol bazlı erişim kontrolü
- Sayfa ve işlem bazlı yetkilendirme

---

## 🎨 Arayüz Özellikleri

### 📱 Responsive Tasarım
- **Mobil uyumlu** ve **modern kullanıcı dostu arayüz**

### 🔍 Dinamik İçerik
- **Arama fonksiyonu**
- **Filtreleme seçenekleri**
- **Kurs derecelendirme sistemi**

---

