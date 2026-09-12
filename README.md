# Web Projesi - Git Merge Conflict (Çakışma) ve Çözüm Ödevi

Bu repo, Git ve GitHub üzerinde branch yönetimi ve çakışma (merge conflict) çözümünü uygulamalı olarak göstermek amacıyla hazırlanmıştır.

## Proje İçeriği ve Branch Yapısı

- **`main`**: Ana yayın dalı. Temel web projesi iskeletini barındırır.
- **`feature/header-nav`**: Başlık alanına navigasyon ve bağlantı menüsü ekleyen özellik dalı.
- **`feature/header-search`**: Başlık alanına arama çubuğu ve filtreleme butonu ekleyen özellik dalı.

## Çakışma ve Çözüm Senaryosu
1. `feature/header-nav` dalı `main` ile birleştirilmiştir.
2. `feature/header-search` dalı `main` ile birleştirilmek istendiğinde `index.html` dosyasının aynı satırlarında çakışma (merge conflict) üretilmiştir.
3. Çakışma VS Code ve GitHub Desktop araçları kullanılarak her iki özelliğin de uyumlu çalışacağı şekilde çözülmüş ve birleştirilmiştir.
