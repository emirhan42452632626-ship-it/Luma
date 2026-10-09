# luma
Luma

Tek dil. Daha aydınlık bir geliştirme deneyimi.

Luma, web arayüzleri oluşturmayı daha kolay, anlaşılır ve erişilebilir hâle getirmeyi amaçlayan, Türkiye'den geliştirilen bir programlama dili projesidir.

Luma'nın amacı; arayüzleri, bileşenleri ve etkileşimleri sade bir sözdizimiyle ifade edebilmek ve bunları tek bir geliştirme deneyiminde birleştirmektir.

«🚀 Türkiye'de geliştirildi. Dünyanın dört bir yanındaki geliştiriciler için tasarlandı.»

✨ Özellikler

- 🧩 Anlaşılır sözdizimi: Arayüz kodunu daha okunabilir hâle getirmeyi amaçlar.
- 🎨 Arayüz odaklı yapı: Sayfalar, kutular, metinler ve butonlar oluşturmayı destekler.
- ⚡ Olay yönetimi: "onClick" gibi etkileşimleri bileşenlerle birlikte tanımlamayı amaçlar.
- 📁 ".luma" dosyaları: Luma kodları için özel dosya uzantısı.
- 🛠️ Luma Studio: Kod yazmak, dosyaları yönetmek ve kodu çalıştırmayı denemek için geliştirilen editör prototipi.

💜 Luma koduna bir bakış

page Home {
  title: "My First Luma App"

  box #card [
    bg: #1a1a1a,
    radius: 12px,
    pad: 20px,
    width: 400px
  ] {
    text "Hello World" [
      color: #a78bfa,
      size: 32px,
      weight: bold
    ]

    button "Click Me" [
      bg: #a78bfa,
      color: black,
      width: full
    ] {
      onClick {
        notify("Hello from Luma!")
      }
    }
  }
}

Not: Bu örnek, Luma için tasarlanan sözdizimini gösterir. Çalışan özellikler, mevcut prototipin desteklediği kapsamla sınırlıdır.

🖥️ Luma Studio

Luma Studio, Luma kodlarıyla çalışmak için geliştirilen editör prototipidir.

Geliştirme planı

- [x] Temel editör arayüzü
- [x] ".luma" dosyalarıyla çalışma
- [x] Temel kod çalıştırma prototipi
- [ ] Daha kapsamlı Luma çalışma motoru
- [ ] Sözdizimi renklendirme ve hata gösterimi
- [ ] Değişkenler, döngüler ve fonksiyonlar
- [ ] API istekleri ve dinamik veri yönetimi
- [ ] Mobil uygulama ve diğer platformlar için destek

🚧 Projenin mevcut durumu

Luma, geliştirilme sürecinin erken aşamalarında olan bir projedir. Sözdizimi, çalışma motoru ve geliştirme araçları zaman içinde değişebilir. Henüz desteklenmeyen özelliklerin çalıştığı varsayılmamalıdır.

🎯 Vizyonumuz

Luma'nın hedefi, web arayüzü geliştirmeyi daha doğal ve anlaşılır hâle getirmek; geliştiricilerin fikirlerini daha az karmaşık kodla hayata geçirebilmesini sağlamaktır.

🤝 Katkıda bulun

Fikirlerin, hata bildirimlerin ve katkıların bizim için değerlidir. Projeyi inceleyebilir, karşılaştığın sorunları bildirebilir ve geliştirme sürecine katkıda bulunabilirsin.

📜 Lisans

Lisans henüz belirlenmemiştir. Lisans dosyası eklenene kadar projeyi kullanma, değiştirme ve yeniden dağıtma koşullarını ayrıca kontrol etmelisin.

---

Luma — Türkiye'den doğan bir geliştirme fikri. 