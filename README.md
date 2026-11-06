# Dörtyüzlünün 24 simetrisi

Elif Medetoğulları'nın *Matematik Dünyası*'nda yayımlanan “Galois Origami Biliyor muydu?” yazısına eşlik eden etkileşimli sayfalar.

Düzgün dörtyüzlünün köşeleri, dördüncü dereceden bir polinomun dört kökü $x_1, x_2, x_3, x_4$ gibi düşünülür. Altı ayrıt, ortak köşesi olmayan üç çifte ayrılır ve her çifte bir sayı karşılık gelir:

- $y_1 = x_1x_2 + x_3x_4$ (12 ve 34 ayrıtları)
- $y_2 = x_1x_3 + x_2x_4$ (13 ve 24 ayrıtları)
- $y_3 = x_1x_4 + x_2x_3$ (14 ve 23 ayrıtları)

Dörtyüzlünün 24 simetrisinin her biri bu üç çifti yalnızca kendi aralarında karıştırır. Sayfalar, her simetride $y$'lerin nereye gittiğini gösterir ve 24 simetriyi 4'erli 6 sütuna toplar ($S_4/V_4 \cong S_3$). Bu, dördüncü derece denklemin üçüncü derece çözücü kübiğe indirgenmesinin ve dolayısıyla kâğıt katlayarak çözülebilmesinin nedenidir.

## Sayfalar

- **`index.html`**: Bilgisayar ve telefon için. İki modu var: 24 simetriyi sırayla oynatan *İzle* ve okurun kendisinin çevirip yansıttığı *Kendin dene*.
- **`vr.html`**: WebXR sürümü. Meta Quest gibi gözlüklerde **VR'da aç**, destekleyen cihazlarda **Odanızda aç (AR)** düğmesi çıkar. Kumandayla ya da elle bir köşeyi, ayrıtı veya hamle düğmesini işaret edip seçin. WebXR olmayan cihazlarda sahne normal 3B olarak açılır.

Her iki sayfa da tek dosyadır ve bir derleme adımı gerektirmez. `vr.html`, three.js 0.160.0 kütüphanesini jsDelivr'den yükler.

## Yayınlama (GitHub Pages)

1. Bu dosyaları bir GitHub deposunun kök klasörüne yükleyin.
2. Depoda **Settings → Pages** bölümünde kaynak olarak **Deploy from a branch**, dal olarak `main` ve klasör olarak `/ (root)` seçin.
3. Birkaç dakika içinde sayfa `https://KULLANICI-ADI.github.io/DEPO-ADI/` adresinde yayına girer. VR sürümü aynı adresin sonuna `vr.html` eklenerek açılır.

WebXR yalnızca HTTPS üzerinden çalışır; GitHub Pages bunu kendiliğinden sağlar.
