# Nodexra — preuzimanja

Zvanična distribucija instalacija i prateće dokumentacije za Nodexra aplikacije, Euromedicina doo.

## Nodexra L-PFR 1.0.0 - Windows x64

[Instalacija i paket za tehničko testiranje — build 27.10.2026.](https://github.com/bora5/nodexra-downloads/releases/tag/lpfr-v1.0.0-20261027)

Datoteke se preuzimaju iz odeljka **Assets** na stranici izdanja, bez GitHub prijave:

- `Nodexra-LPFR-1.0.0-Windows-x64-Setup.exe` — instalacija za Windows x64; uključuje Javu i OpenSC paket za rad sa karticom.
- `Nodexra-LPFR-1.0.0-paket-za-testiranje-Windows-x64.zip` — isti installer, korisničko i administratorsko uputstvo, opis proizvoda, dokument o proveri sata, postupak offline aktivacije i kontrolne sume. Za tehnički pregled Poreske uprave preuzeti ovaj ZIP.
- `SHA256SUMS.txt` — SHA-256 kontrolne sume objavljenih datoteka.

Ovo izdanje je pripremljeno za tehničko testiranje; objavljivanje ne predstavlja potvrdu odobrenja proizvoda za produkcionu upotrebu.

## Linux i macOS - testno izdanje

[Preuzimanje Linux x64 i macOS Apple Silicon/Intel paketa](https://github.com/bora5/nodexra-downloads/releases/tag/lpfr-v1.0.0-linux-macos-test-20261027)

- **Linux x64:** DEB (Ubuntu 24.04) ili TAR.GZ.
- **macOS Apple Silicon:** arm64 DMG ili PKG.
- **macOS Intel:** x64 DMG ili PKG.

Java je uključena. Preuzeti i `PROCITAJ.txt` i `SHA256SUMS.txt` sa stranice izdanja. Za Mac je potrebna zasebna instalacija OpenSC-a; Mac paketi nisu Apple Developer ID potpisani niti notarizovani. Svaka instalacija zahteva svoju važeću licencu.

Ovo izdanje služi za testiranje i odvojeno je od prijave Poreskoj upravi 1773, koja ostaje ograničena na Windows x64.

## Aktivacija za tehnički pregled

Za sada je dostupna samo offline aktivacija. Posle instalacije izabrati **Licenca → Sačuvaj zahtev** i poslati `.licreq` datoteku na **borivoj.bogdanovic@euromedicina.co.rs**. Dobavljač vraća potpisanu `.license` datoteku, koja se uvozi preko **Licenca → Uvezi licencu** na istom računaru.

Za tehnički pregled Poreske uprave predviđeno je 90 dana, za najviše 3 računara, uz poseban zahtev za svaki računar. Aktivirana licenca nije prenosiva kopiranjem na drugi računar. Nema automatskog probnog perioda. Ne slati PIN, lozinke ili privatne sertifikate.

## Sadržaj repozitorijuma

Repozitorijum sadrži distribuciju i uputstva. Izvorni kod aplikacije nije objavljen. GitHub stavke „Source code (zip/tar.gz)“ odnose se samo na javni sadržaj ovog repozitorijuma; za instalaciju koristiti navedeni Setup ili paket za testiranje.

Sva prava na Nodexra aplikacije zadržava dobavljač. Korišćenje zahteva važeću licencu; komponente trećih strana imaju svoje licence priložene uz instalaciju.

Kontakt: borivoj.bogdanovic@euromedicina.co.rs · +381 21 466800 · https://www.euromedicina.co.rs/
