# Claude-Code

## Proje Açıklaması

Bu depo, [Claude Code](https://claude.com/claude-code) ile GitHub iş akışlarının entegrasyonunu denemek ve göstermek için oluşturulmuştur. Issue ve pull request'lerde `@claude` etiketi kullanılarak Claude'a görev verilebilir; Claude da isteği analiz eder, gerekli kod veya doküman değişikliklerini yapar ve sonucu GitHub üzerinden raporlar.

### Nasıl Çalışır?

- Bir issue veya yorumda `@claude` ifadesiyle istek yazılır.
- `.github/workflows` altındaki Claude Code iş akışı tetiklenir.
- Claude, isteği değerlendirir, değişiklikleri ayrı bir dalda (branch) yapar ve ilerlemeyi yorum olarak paylaşır.
- Yapılan değişiklikler için pull request oluşturulabilir.
