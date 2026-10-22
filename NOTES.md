# NOTI — it-traduzzjoni Maltija tal-proġett Selah (selah-mt)

Dan il-fajl jiġbor **il-versi li messithom id jew deċiżjoni** — biex il-qarrej jara jekk vers għamlitu l-magna,
id jew deċiżjoni, u għaliex. Jiġbor ukoll il-mistoqsijiet li qed jistennew widna Maltija, u — fl-aħħar — **dak li
għadu miftuħ**. *(Fid-daħliet tissemma l-forma Lhudija; għalhekk xi kliem jibqa' bil-Lhudi. Il-mogħdijiet kollha —
bħal `genesis/22/13` — huma mill-għerq tar-repożitorju.)*

---

## §1 · Versi korretti bl-id

### Wara r-round (a2ae0c05, `dev/scripts/mt_post_round_mends.py`)

- **L-Isem miktub ħażin jew b'ittra żgħira** — *jaħwe*, *Ġaħwe* (2 Sam 18:19), *Ħaħwe* (1 Kron 13:10), *Joħwe*
  (Eż 13:3), *Jaħde* (Eżek 3:23), *Jahwe* (1 Slat 22:54 — *f'Jahwe* → **lil Jaħwe**) → **Jaħwe**, f'kull post.
- **Eż 39:7** — l-Isem kien nieqes: *kif amar ⟨את⟩ lil Moxe* → **kif Jaħwe amar ⟨את⟩ lil Moxe**.
- **Il-muntun, mhux iċ-ċerv — erba' postijiet**: ir-ringiela tal-annimali (D4) kienet tgħid `איל → ċerv`. Ir-ringiela
  ġiet korretta (`אַיִל` = **muntun**; `אַיָּל` = **ċerv**), u l-erba' postijiet li niżlu qabel ġew imsewwija bl-artiklu
  Malti mibni mill-ġdid: Ġen 22:13 **il-muntun**; Eż 25:5 **tal-imtaten**; Eż 29:1 **żewġ imtaten**; Eż 29:3
  **iż-żewġ imtaten**.
- **Sinjali miksura** — `<את>` → **⟨את⟩** (Ħos 5:9; Num 4:10); `〈hu〉` → **⟨hu⟩** (2 Kron 8:2).
- **Il-pressa tat-33:** l-awto-korrezzjonijiet tal-magna mħollija fil-vers (*— le,* · *— no:* — 22 darba) u versi mħawda.
- **Il-pressa tas-47 — l-Isem MIŻJUD fejn il-Lhudi m'għandux** (Ġen 42:16, Eż 9:17, 1 Slat 8:28, Ġob 8:3 …); l-aħħar
  sitta bl-id: Ġen 18:23 (*u qal: Jaqaw*); Ħos 6:11 (`יהודה` — **Jehuda**, mhux l-Isem); Salm 145:19 (*minnu
  jagħmel*); Salm 66:6 (**Biddel il-baħar f'art niexfa**, `הפך`); Imħ 13:16 (**offriha.**); 2 Slat 18:6 (**li Jaħwe
  ordna ⟨את⟩ lil Moxe**).

### Il-qari wara l-bieb — applikat bl-id · 2026-10-21 (`dev/scripts/mt_reading_mends.py`)

Il-lista tal-qari (8cab973d) applikata, b'kull vers moqri kontra l-kliem Lhudi tiegħu. `translation` u l-`gloss`
tal-kliem li jaqblu biss; `surface` u l-oqsma l-oħra ma ġewx mmissa (ivverifikat: 2,357 fajl, 0 bidla barra minn dawk
iż-żewġ oqsma). L-iskript huwa idempotenti u jikkonverġi f'run waħda (ivverifikat minn kopja nadifa ta' 8cab973d).
Ir-regoli tal-jum (Scott, 2026-10-21) — issa fir-regoli Maltin:

- **`עלה` → sagrifiċċju tal-ħruq** — forma waħda għall-54 variant (*olà*, *olá*, *ola*, *olot*, *olosta*, *olokaust*,
  *olokawst*, *olokausto*, *olokausta*, *oloth*, *olostawt*, *olocaustu*, *oloqot* …), bl-artiklu Malti mibni mill-ġdid
  (*is-*, *tas-*, *għas-*, *mis-*, *fis-*, *bis-*, *lis-*, *mas-*; plural **sagrifiċċji tal-ħruq** fejn il-Lhudi huwa
  plural). Mill-kliem Lhudi: kull `עלה`-nom li l-glossa tiegħu kienet forma *ol-*. **233 vers.** Ukoll Dewt 33:10
  (`כליל`, **sagrifiċċju tal-ħruq sħiħ**) u Esd 6:9 (Aramajk).
- **`ארון` → l-arka** (*l-arka tal-patt*, *l-arka ta' Elohim*), bl-artiklu mibni mill-ġdid (*tal-arka*, *fl-arka*,
  *lill-arka* …) — il-50 glossa (*tebut*, *tabut*, *aron*, *arċa*, *arġit*, *aruna*, *arza*, *istangu*, *kenur*, *it-Tinda*,
  *it-Teva* …). **145 vers.** **Tebut** biss għal Josef (Ġen 50:26); **senduq** biss għas-senduq tal-flus (2 Slat 12;
  2 Kron 24 — 2 Slat 12:10–11 *arġun* → **senduq**).
- **It-`תבה` ta' Noaħ → l-arka** (Ġen 6–9; *tabut*, *teba*, *teva*, *vieħba*, *vaska*, *tevra*) — **23 vers.**
- **(a) *c* → *ċ*** (*wiċċ*, *innoċenti*, *preċetti*, *saċerdozju*, *prinċep*; *ġudici* → **imħallfin**; *niriscatta* →
  **nifdi**) u **(b1) *ch* → *ħ*** (*Koraħ*, *Pesaħ*, *Menaħem*, *Joħanan*, *Manowaħ*, *Peqaħja*, *niftaħ*) u l-ismijiet
  b'*c* (*Amatsjahu*, *Mitspa*, *Siħon*, *Retsin*), u l-*y* (*Arjokh*, *quddiemi*, *jaqdi*, *Għeljon*, *Tsogħan*,
  *Tsurijel*, *Jarovgħam*) — **96 vers.**
- **(b2) *sh* → *x* fl-ismijiet** — biss fejn il-kelma Lhudija ġġorr `ש` (*Xelomo*, *Axur*, *Axer*, *Xekem*, *Ħexbon*,
  *Xomron*, *Belxatsar*, *Xa'ul*, *Xim'on*, *Kuxan-Rix'atim*, *Mixa'el*); u *shofar* → **xofar** (*ix-xofar*) — **336
  vers.** *Jitshar* (`יצהר` — *ts*+*h*) baqa' kif inhu.
- **(c2)** `אמה` *kubit-* (u *xiber* f'Ġen 6) → **driegħ / dirgħa / dirgħajn**; `עשרון` / `עשירית` → **għaxar parti**;
  `מעשר` → **l-għexur** — **29 + 5 vers.**
- **(e) *żaħħar*** — Dewt 28:4 maqlub mil-Lhudi (**Imbierek il-frott ta' ġufek … il-frieħ tal-baqar tiegħek u l-ħrief
  tan-nagħaġ tiegħek**); Prov 11:12 (**Min jistmerr lil ġaru m'għandux qalb**).
- **(f) Ittri barra mill-alfabett Malti** — *š ŝ ş* → **x**, *ʿ* → **għ**, *ḥ* → **ħ**, *ṭ ḍ ł ī ū ā é á í ó ú ğ ģ ž č*
  …, Grieg, Ċirilliku, 平/我/ァ, il-ligaturi *ﬁ ﬂ*; kliem bl-id fejn l-ittra ma kinitx biżżejjed (Lev 7:32 *tal-islám* →
  **tas-sliem**; 2 Sam 12:10 *δεspisejtni* → **stmerrejtni**; Salm 57:4 → **Jibgħat**; Salm 89:53 → **Imbierek Jaħwe …
  Ammen, u ammen**; Ġen 30:30; 2 Kron 28:24 **il-bibien**, **l-għodod**; 2 Slat 4:25) — **460 vers.**
- **(f2) Karattri moħbija, tab u linja ġdida** ġewwa l-vers — **29 vers.**
- **(g) *gh* → *għ*** (*fil-għodu*, *tiegħu*, *tagħhom*, *erbgħin*) — bil-kliem Malti; ismijiet b'ittra kbira biss fejn
  il-Lhudi għandu `ע` (*Jegħiel*); *Roghel* → **Rogel** — **231 vers.**
- **(g2) Ingliż** — *swarms*, *tremor*, *jihadists*, *prostitutes*, *verb Virgin* (→ **xebba**), *blessed*, *Wolves*,
  *ministries*, *Block*, *magical* (→ **romblu**) … — u **Prov 15:20**, kollu bl-Ingliż, maqlub mil-Lhudi: **Iben
  għaref iferraħ lil missier, u bniedem iblah jistmerr lil ommu.**
- **(h) Parentesi** — (h1) parentesi miksura (*⟨…>*, *>>*, *[ ]*, *{ }*, *`<i>`*, *_*) — 43 vers, kull wieħed moqri;
  (h2) l-artiklu u t-Taljan barra mill-⟨ ⟩ (*⟨il⟩-xifer* → **ix-xifer**, *⟨l-⟩Elohim* → **l-Elohim**, *⟨sono⟩* imneħħi)
  — 84 vers; (h3) ittri Lhud ġewwa ⟨ ⟩ — 16-il vers (Salm 22:17 *⟨הם⟩* …); (h4) ⟨אתו⟩ · ⟨אתם⟩ · ⟨את lilhom⟩ … →
  **⟨את⟩** + pronom Malti barra (*⟨את⟩ lilu*) — 114-il vers.
- **(i) *Elohim*** — *Elohom*, *Eloheim*, *Elohum*, *Elohem*, *Elohimkom*, *Elohi*, *Eloħi* → **Elohim** (bil-kuntest:
  *l-Elohim ta' Jagħaqov*, *l-Elohim tal-ħelsien tiegħi*) — **31 vers.**
- **(i2) Alla / Elohim kontra l-Lhudi** — 2 Kron 9:23 *Alla* → **Elohim** (`האלהים`); Imħ 16:24 → **alla tagħna**
  (alla tal-Filistin); Esd 5:1 *⟨l-Alla⟩* imneħħi; Ġob 33:14 `אל` → **El**; Salm 143:10, 145:1, 18:47 `אלוהי` → **Elohim
  tiegħi** / **l-Elohim tal-ħelsien tiegħi**; Ġen 18:25, Prov 16:10, Dewt 6:20 maqlubin mil-Lhudi (*Alla* li ma kienx
  hemm, imneħħi).
- **(j) Versi ivvintati, imħawda jew b'awto-korrezzjoni** — maqlubin mil-Lhudi, il-vers u kull glossa: Ġen 21:27;
  Ġoż 21:7; 2 Kron 9:21; 9:23; Ġer 44:16; 2 Sam 8:6; Prov 11:17; 15:20; 16:10; 11:12; Eżek 37:6; Eż 39:40; 27:10;
  Num 14:4; 29:10; Ġob 13:11; 38:10; 2 Slat 19:34; 1 Slat 8:27; 1 Sam 29:5; Salm 137:9; Dewt 28:4; 6:20; Ġen 18:25;
  34:5; 1 Kron 4:10; Ġoż 24:22; Lev 14:49 — **28 vers.** Ukoll Num 13:26 (*/c/5712* — kodiċi ta' Strong) u 2 Kron 30:23
  (*⟨Ġ-7*).
- **(k) *il-knisja* → il-ġemgħa** — biss fejn il-vers iġorr `עדה` / `קהל` — **25 vers.**
- **(l) L-ismijiet tar-regoli** — *Ġeruxalajim*, *Jerużalajim*, *Ġerusalemm*, *Ġerusalem*, *Jerusalem* … → **Jeruxalajim**;
  *Israel*, *Jisriel*, *Ġisrael* → **Jisrael**; *Ġagħaqov*, *Jagħaqob* → **Jagħaqov**; *Mose*, *Moshe* → **Moxe**;
  *Aaron*, *Aron*, *Aħaron* → **Aharon** — **88 vers.** (Il-kampijiet `marks` ma ġewx mmissa.)
- **(n) Il-kampjun, vers b'vers** — Ġen 1; 22; 6–9; Eż 3; 20; Lev 19; Dewt 6; Iż 6; 53; Ġer 31:31–34; Eżek 36:25–27;
  37:1–14; Salm 1; 22:1–22; 23; Ġob 38:1–12; Rut 1; Għan 2; Dan 7:1–14; it-30 vers għall-għarrieda — **403 vers**
  b'pari moqrija (u l-glossi tagħhom). Fosthom is-sens ħażin: Eż 20:5 **il-missirijiet** (`אבות`); Iż 6:4 **bid-duħħan**;
  Iż 6:13 **iz-zokk**; Iż 53:5 **minħabba l-ħtijiet tagħna**; Għan 2:3 **Fid-dell tiegħu**; Għan 2:8 **jinqabeż**; Għan
  2:12 **wasal żmien l-għana**; Rut 1:6 **in-nisa ta' wliedha**; 2 Slat 14:23 **Fil-ħmistax-il sena**; 2 Slat 18:4
  **is-serp tar-ram**; Dan 7:14 **ħakma** (mhux *saħtan*); Eż 3:1 **ħmuh**; Eż 20:14–15 **Ma tiżnix. · Ma tisraqx.**
- Il-bieb mill-ġdid (wara l-qari): l-Isem **6,007 / 6,007**; *fewer* **0**, *added* **0**, l-Isem miktub ħażin **0**,
  awto-korrezzjonijiet **0**, tħassir **0**, *Alla* fis-sedja tal-Isem **0**, NT **0**, Ingliż **0**, parentesi **0**,
  Lhudi **0**, NFC **0**; **bleed 0** (kien 101); *indovin* **1** — 2 Slat 23:24, fuq `הידענים` (tajjeb).

## §2 · Versi maqluba mill-ġdid

- **L-inżul** (2026-10-21 19:17): it-Tanakh kollu — 23,213 / 23,213 vers.
- **Ir-round taċ-ċensiment** (2026-10-21): 2,423 post, kollha tajbin wara s-sellum.
- **Ir-restawr tat-test Lhudi** (2026-10-21): il-kliem Lhudi mibdul (`surface`) inġieb lura mis-sors.
- **Il-qari** (2026-10-21): 28 vers maqlubin mil-Lhudi bl-id (§1 (j)).

## §3 · Dak li huwa tajjeb — tbiddilx

- **`sid` / `sidi`** dwar bniedem (Ġen 44:20 *U għedna lil sidi*).
- **`alla` / `allat`** b'ittra żgħira dwar l-allat tal-ġnus u l-idoli (Eż 20:3 *allat oħrajn*). *Allat* b'ittra kbira
  fil-bidu tas-sentenza (1 Slat 20:23) huwa tajjeb.
- **`l-eżerċti`** dwar l-armati tal-bnedmin (Eż 12:41.51; Num 1:52; 10:14; 1 Slat 2:5; Iż 34:2) — mhux *Jaħwe Tsebawot*.
- **`ram`** — il-metall (`נחשת`), kelma Maltija.
- **`il-midluk`** dwar qassis jew sultan (1 Sam 24:7; Lev 4:3).
- **`qabar`** għal `קבר` (Ġen 23) — mhux *Xeol*.
- **`Elohei Jisrael`** Ġen 33:20 — l-isem tal-artal, b'tifsira warajh.
- **`l-Elohim`** bl-artiklu Malti (*l-Elohim ta' missirijietkom*, Eż 3:15; Dewt 6:4) — 196 vers; il-kelma ma tinbidilx.
- **`tebut`** Ġen 50:26 u **`senduq`** 2 Slat 12; 2 Kron 24 — skont ir-regola tal-arka.
- **`indovin`** fuq `ידענים` (2 Slat 23:24) — kelma tal-għorrief fuq kelma tal-għorrief.
- **Kliem doppju** bħall-Lhudi (*ħafna ħafna*, *filgħodu filgħodu*, *żewġ żewġ*) — ripetizzjoni Lhudija, mhux żball.
- **`Jitshar`** (`יצהר`) — *ts* + *h*, mhux *sh*.

## §4 · Kliem li qed jistenna widna Maltija

1. **`Jaħwe`** — *ħ* għall-`ה`; jew **`Jahwe`**?
2. **`Jagħaqov` · `Jitsħaq`** — *għ* għall-`ע`, *ħ* għall-`ח`. Il-Malti għandu l-ittri Semitiċi — iżżommhom?
3. **L-ismijiet li r-regoli ma jsemmux** — ara Mistoqsijiet miftuħa, 1.
4. **`מלאך`** — *mibgħut* (madwar 120), *anġlu* (42) jew *messaġġier* (madwar 40)? Ir-regoli ma jgħidux; it-tlieta
   huma mħallta, anki fl-istess kapitlu (Ġen 22:11.15).
5. **`נפש`** — *ruħ* (il-biċċa l-kbira) jew *nefes* / *nefex* / *nefesh* (madwar 50 vers; Dewt 6:5 *b'nefesk*)?
6. **`מצוה`** — *mitzva* / *mitzvot* / *mitsva* (51 vers) jew **kmandament**? `תועבה` — *to'eva* / *to'evot* jew **ħaġa
   mistkerha**? `אלילים` — *l-elilim* (Lev 19:4) jew **l-idoli**? U `עולם` — *olam* (10 vers, *mill-olam*) jew
   **dejjem**?
7. **`השטן`** — *is-Satan* / *Satana* bħala isem (Ġob 1–2; Żak 3:1–2; 1 Kron 21:1) jew *l-avversarju*? (1 Slat 11:14
   *satan* b'ittra żgħira — avversarju ta' Xelomo — tajjeb.)
8. **L-Aramajk** (`אלהא`, Dan u Esd) — *Elah* / *Elaha* / *Elohim* / *Elowaħ*. Forma waħda.
9. **`ja Jisrael`** (Dewt 6:3–4; Għan 2:7 *ja bniet*) — il-vokattiv *ja*, jew **Isma', Jisrael** biss?
10. **`עדה` / `קהל`** — wara *il-knisja* → **il-ġemgħa**, il-corpus għad għandu wkoll *il-kongregazzjoni* u
    *l-assemblea* (62 vers). Kelma waħda?
11. **Il-kliem kollu** — il-qarrejja Maltin għandhom bżonnu.

---

## Mistoqsijiet miftuħa — għadhom miftuħa (2026-10-21, wara `mt_reading_mends.py`)

Il-klassijiet li nstabu bit-tfittxija ngħalqu (§1). **Dan huwa li jibqa'** — deċiżjoni, jew qari, mhux tfittxija:

1. **L-ismijiet li r-regoli ma jsemmux, b'ħafna kitbiet — ma ġewx normalizzati** (deċiżjoni). L-għadd huwa tal-glossi
   qabel il-qari; l-ittri barranin u *sh* / *ch* biss ġew imsewwija:
   - **`יהודה`** — *Jehuda* 492 / *Juda* 168 / *Ġuda* 64 / *Jħuda* 26 / *Jhuda* 12 / *JUDA* 9 / *Jhudah* 8 / *Judaħ* 5 /
     *Judah* 4 / *Judea* 3 / *Jehudah* 3 / *Judà* 2 / *Juhda* (Ġer 31:31 *Judaħ*; Rut 1:1–7 *Juda*).
   - **`ציון`** — *Sijon* 47 / *Sjon* 35 / *Sion* 15 / *Sajon* 14 / *Tsijon* 11 / *Xijon* 4 / *Tsjon* 4 / *Żjon* 3 …
   - **`שלמה`** — *Xlomo* / *Xelomo* (*Shelomo* 46 issa *Xelomo*) / *Salamun* 25 / *Slomon* / *Slomo* / *Salomo* …
     (1 Slat 3:4 *Sqolomonheħ*, ivvintat, sar **Xelomo**.)
   - **`שאול`** — *Xaul* / *Saul* / *Sawl* / *Xawl* / *Xa'ul* / *Xawul* …
   - **`פרעה`** — *Paroħ* 51 / *Paroh* 42 / *Faragħon* 35 / *Faragħun* 31 / *Paro* 27 / *Fargħun* 17 …
   - **`יוסף`** — *Josef* / *Jusef* / *Josif* / *Jossif* / *Ġużeppi* / *Jossef* / *Josief* …
   - **`יהושע`** — *Joxwa* / *Jehoxua* / *Jehoxwa* / *Joxva* / *Ġożwè* / *Joxue* …
   - **`שמואל`** — *Samwel* / *Xmuwel* / *Xemwel* / *Xemuwel* / *Samuel* / *Xemuel* …
   - **`איוב`** — *Ijov* / *Ġob* / *Ijob* / *Iġob* / *Ġobb* / *Ajov* …
   - **`נח`** — f'Ġen 6–9 issa **Noaħ** (il-kampjun); barra minnhom (1 Kron 1:4; Iż 54:9; Eżek 14) — ara.
   - **`נעמי`** — *Noemi* 15 / *Naomi* 3 / *Naħomi* 2 / *Noomi* / *Naamit* (Rut 1 — ma ġewx normalizzati).
   - **`קרח`** — *Qoraħ* / *Koraħ* (kien *Korach*) / *Koraj* / *Kareaj* / *Kareaħ* / *Korħ* / *Korak* …
   - **`פסח`** — *Pesaħ* (kien *Pesach*) / *Pesah* / *Paseaħ*.
   - **`ירמיהו`**, **`ישעיהו`**, **`אליהו`**, **`אלישע`**, **`פלשתים`**, **`מנשה`**, **`שמרון`**, **`בבל`**,
     **`יהונתן`**, **`רבקה`**, **`לבן`**, **`עשו`**, **`אפרים`**, **`כנען`** — għaxar sa għoxrin forma kull wieħed.
   - **`מצרים`** bħala poplu — *Mitsrijin* / *Eġizzjani* / *Misrijin* / *Mitsrijim* / *Mitsriti* …
   - **`צ`** — ir-regoli jiktbu *ts*; il-corpus għandu wkoll *Tz-* (*Tzuf*, *Tzion*).
   - **`נגב`** — *Neghev* / *Negheb* (23 vers): il-*gh* hawn mhux *għ* (m'hemmx `ע`), u għalhekk ma nbidilx. **Negev**?
2. **Il-kliem ivvintat — l-ikbar klassi, u miftuħa.** Il-kampjun sab madwar żewġ kelmiet ivvintati f'kull vers. Il-qari
   saħħaħ biss il-versi tal-kampjun (§1 (n)); il-bqija tat-test għandu l-istess rata. **Il-Malti jidħol l-ewwel fir-round
   tal-qari sħiħ fiċ-ċirkwit tar-raffinament** (Scott, 2026-10-21).
3. **Is-sinjali li ma ġewx mmissa** — parentesi tondi fil-vers (75 vers: *(xeqel)*, *(lura)*, *(F'xi manuskritti: …)*,
   *(nefex)*); tliet tikek (14); virgoletti (11). Uħud huma noti tal-magna fil-vers (Regola 6: l-ebda nota tat-traduttur).
   Fittex: `\(` · `\.\.\.` · `"`.
4. **`תבה` ta' Moxe** (Eż 2:3.5 — *teva*, *it-teba'*) — ir-regola tal-arka kienet għal Noaħ; il-qoffa ta' Moxe ma
   ġietx imsemmija. **L-arka** wkoll, jew **qoffa**?
5. **Ġen 30:30** *⟨mini⟩* u **1 Sam 18:23** *Qisha* — kliem maqsum li ma nqalax; 2 Kron 29:29 *miegħu,u xteħtu*.
6. **§4** — il-mistoqsijiet hemm (l-Isem, `מלאך`, `נפש`, *mitzva* / *to'eva* / *elilim* / *olam*, *Satan*, *Elah*, *ja*,
   `עדה`) baqgħu miftuħa; ma ġewx mibdula.
7. **Il-kampjun huwa kampjun.** Il-klassijiet tal-qari ngħalqu bit-tfittxija u bil-kampjun; vers moqri minn Malti jiżen iktar
   minn din il-lista kollha.
