MOOM 8.0 - SILAH GORUNUMU, BOMBAtAR VE BOLUM SECIMI

BU SURUMDE
- Ayarlar ekranina WEAPON VIEW secenegi eklendi: 3D / 2D.
- 2D modunda 3D silah modeli gizlenir ve ekranda sabit 2D silah cizimi gosterilir.
- R1 ile dolasilan silah listesine GRENADE LAUNCHER eklendi.
- Bombaatar atisi, yakin cevredeki dusmanlara mesafeye gore alan etkili oyun ici hasar verir.
- Uzaktan saldiran dusmanlarin hasari dusuruldu:
  - Tip 1: 9-13 yerine 4-6
  - Tip 2: 12-19 yerine 5-8
- Ana menude OYNA secilince dogrudan ilk bolum baslamaz; yedi bolumun listelendigi BOLUM SEC ekrani acilir.
- Bolum listesinde yukari/asagi ile gezinilir, X veya START ile secilir, O ile ana menuye donulur.
- Onceki silahlar, levye, menu kapagi ve ses sistemi kaynakta korunmustur.

KONTROLLER
- Ana menu: Yukari/Asagi secim, X veya START onay
- Bolum secimi: Yukari/Asagi gezinme, X veya START baslatma, O geri
- Ayarlar: Yukari/Asagi satir secimi, X secenegi degistir, O geri
- Oyun: Analog/yon tuslari hareket ve donus; L1 yana yurume; R1 silah degistir; X/Kare silah kullan

DERLEME
main.c ve Makefile dosyalarini PSP SDK projenize koyup PSPSDK ile EBOOT.PBP derleyin.

DOGRULAMA
Kaynak kodda istenen dort degisiklik kontrol edildi. Bu calisma ortaminda PSP SDK (psp-config / psp-gcc) bulunmadigindan PSP derlemesi ve PPSSPP uzerinde calisma testi yapilamadi. Bu nedenle derlenmis EBOOT.PBP veya calisma garantisi sunulmuyor.

MOOM 8.1 - Bombaatar efekt duzeltmesi:
- Bombaatar ateslendiginde 0.62 saniyelik genisleyen turuncu/sari patlama halkasi,
  kisa merkez parlama ve dagilan duman katmanlari cizilir.
- Dusmanlara uygulanan alan etkisi korunmustur.
