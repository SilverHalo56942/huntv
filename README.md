# 🇭🇺 Magyar IPTV

For the English README, click [HERE](https://github.com/SilverHalo56942/huntv/blob/main/README_en.md).

---

Magyar televíziós csatornák gyűjteménye M3U lejátszási lista formátumban.

A lejátszási lista magyar TV-csatornákat tartalmaz csatornalogókkal, valamint ahol elérhető, elektronikus műsorújság (EPG) adatokkal.

## 📺 Lejátszási lista

A fő lejátszási lista:

* [`hun.m3u`](hun.m3u) — Magyar TV-csatornák

### Közvetlen hivatkozás

A lejátszási lista közvetlenül a GitHubról is használható:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

Ez az URL közvetlenül hozzáadható egy kompatibilis IPTV-lejátszóhoz.

## 🖼️ Csatornaikonok

A csatornalogók az [`icons`](icons/) könyvtárban találhatók.

Az ikonok a [Logopediáról](https://logos.fandom.com/) származnak, amely a márkákkal és logókkal kapcsolatos információkat tartalmazó, Fandomon üzemeltetett enciklopédia.

Minden védjegy, logó és kapcsolódó vizuális elem a megfelelő tulajdonos tulajdonát képezi.

## 📡 EPG

A csatornák jelentős része EPG (Electronic Program Guide – elektronikus műsorújság) adatokat tartalmaz.

Az EPG-adatokat az [EPGShare](https://epgshare01.online/) magyar nyelvű részlege biztosítja.

Az EPG elérhetősége csatornánként eltérő lehet, és idővel változhat.

## ▶️ Ajánlott lejátszók

### 🪟 Windows / 🐧 Linux / 🍎 macOS

A [**IPTVnator**](https://4gray.github.io/iptvnator/) az ajánlott IPTV-lejátszó Windows, Linux és macOS rendszerhez.

Támogatja az M3U lejátszási listákat és az EPG-adatokat, valamint kényelmes felületet biztosít a csatornák böngészéséhez és megtekintéséhez.

Add hozzá a következő lejátszási lista URL-jét az IPTVnatorhoz:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

### 📺 Android / Android TV

Az [**IPTV**](https://play.google.com/store/apps/details?id=ru.iptvremote.android.iptv) **Alexander Sofronov** által készített ajánlott alkalmazás Android és Android TV rendszerhez.

Add hozzá a következő lejátszási lista URL-jét az alkalmazáshoz:

```text
https://raw.githubusercontent.com/SilverHalo56942/huntv/main/hun.m3u
```

### Egyéb lejátszók

A lejátszási listának más, szabványos M3U/M3U8 lejátszási listákat támogató IPTV-alkalmazásokkal és médialejátszókkal is működnie kell.

## 🔄 Frissítések

A lejátszási lista időszakosan frissülhet az alábbiak érdekében:

* Új csatornák hozzáadása

* Nem elérhető csatornák eltávolítása

* Stream URL-ek frissítése

* Csatorna-metaadatok frissítése

* Csatornaikonok hozzáadása vagy frissítése

* EPG-információk frissítése

A streamek elérhetősége nem garantált, és előzetes értesítés nélkül változhat.

## 🐛 Hibák bejelentése

Ha hibás streamet, helytelen csatornainformációt, hiányzó ikont vagy egyéb problémát találsz, kérjük, [nyiss egy hibajegyet](https://github.com/SilverHalo56942/huntv/issues).

Hibás csatorna bejelentésekor kérjük, add meg:

* A csatorna nevét

* A probléma hozzávetőleges időpontját

* A használt IPTV-lejátszót

* A probléma rövid leírását

## 🤝 Közreműködés

A közreműködéseket szívesen fogadjuk.

Pull request beküldésekor kérjük, győződj meg arról, hogy:

* Az M3U szintaxisa érvényes.

* A stream URL-je nyilvánosan elérhető.

* A csatornainformációk pontosak.

* A meglévő formázási és elnevezési konvenciók követve vannak.

* Az ikonok az `icons` könyvtárba kerülnek, az elnevezésük pedig követi a többi ikon elnevezését.

* Az EPG-információk, ahol alkalmazható, megfelelően vannak hivatkozva.

## 📁 A repository felépítése

```text
huntv/
├── hun.m3u
├── icons/
│   ├── ...
│   └── ...
└── README.md
```

## ⚖️ Jogi nyilatkozat

Ez a repository tájékoztatási és technikai célokat szolgál.

Maga a repository nem biztosít televíziós előfizetéseket, és nem üzemelteti a lejátszási listában hivatkozott külső streaming szervereket.

Az egyes streamek elérhetősége és jogszerűsége a megfelelő szolgáltatóktól és joghatóságoktól függhet. A felhasználók felelősek azért, hogy a streamek használata megfeleljen a vonatkozó jogszabályoknak és az adott tartalomszolgáltatók feltételeinek.

A csatornanevek, logók, műsorinformációk és egyéb harmadik féltől származó anyagok a megfelelő tulajdonosok tulajdonát képezik.

Ha jogtulajdonos vagy, és úgy véled, hogy a repositoryban található valamely hivatkozás vagy egyéb anyag sérti a jogaidat, kérjük, vedd fel a kapcsolatot a repository karbantartójával.

A csatornák különböző forrásokból származnak, ezek közé tartoznak:

* [iptv-org](https://github.com/iptv-org/iptv/blob/master/streams/hu.m3u) magyar szekciója
* [iptv-web](https://iptv-web.app/HU/) magyar szekciója

---

**Karbantartó: [@SilverHalo56942](https://github.com/SilverHalo56942)**
