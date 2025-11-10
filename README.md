# Öğrenci No: 220404013 – Arda Adar

## Mobil Programlama – Lab 7  
**Konu:** React Native Lab 2 – İnteraktif Yapılacaklar Listesi  
**Tarih:** 10/11/2025  

Bu proje, React Native kullanılarak geliştirilen interaktif bir **Yapılacaklar Listesi (To-Do App)** uygulamasıdır.  
Amaç; state yönetimi, kullanıcı girdisi, listeleme (FlatList) ve basit etkileşimler (Pressable) gibi temel React Native kavramlarını uygulamalı olarak öğrenmektir.  

---

## Özellikler
- Görev ekleme (`TextInput` + `Button`)
- Görevleri dinamik listeleme (`FlatList`)
- Görevlere dokunarak silme (`Pressable`)
- Klavye açıldığında düzenin bozulmaması (`KeyboardAvoidingView`)
- Görev eklendikten sonra klavyenin otomatik kapanması (`Keyboard.dismiss`)

---

## Kullanılan Teknolojiler
- **React Native**
- **Expo CLI**
- **React Hooks (useState)**
- **react-native-safe-area-context**

---

## Kurulum ve Çalıştırma

```bash
# Projeyi klonla
git clone https://github.com/<kullanici-adin>/TodoApp.git
cd TodoApp

# Gerekli paketleri yükle
npm install

# Expo başlat
npx expo start
