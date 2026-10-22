# PROVENJENZA — kif saret din it-traduzzjoni

*Malti. Il-Bibbja Lhudija, vers b'vers. Bdiet fil-21 ta' Ottubru 2026 fil-11:47; it-Tanakh kollu niżel
fil-21 ta' Ottubru 2026 fis-19:17; ir-round taċ-ċensiment u t-tiswijiet bl-id intemmu fit-22:18 tal-istess jum;
il-qari wara l-bieb sar wara (ħin tal-Lvant tal-Istati Uniti, EDT = UTC−4).*

Dan huwa d-dokument li jiġbor kif saret din it-traduzzjoni u x'għad irid jiġi korrett. Traduzzjoni magħmula minn
magna ma jistħoqqilhiex fiduċja jekk ma tarax kif saret. Għalhekk dan il-fajl jgħid kollox — **anki
l-iżbalji tagħna.**

---

## Kif sar ix-xogħol

Kull vers inqaleb mit-test Lhudi tiegħu (OSHB / Westminster Leningrad Codex), skont regoli miktuba bil-Malti
(`docs/methodology/translation-discipline/mt.md`, fil-proġett Selah). Magna: **glm-5.3** (Zhipu) fit-23,213
fajl kollha; il-qasam `tier` għandu l-valur **glm-5.2** — it-triq li minnha għaddew is-sejħiet. 20,729 fajl għandhom
blokka `provenance` sħiħa (SHA-256 tal-mistoqsija tas-sistema u tal-utent, il-fajl tal-mistoqsija, il-verżjoni
tal-kodiċi); it-2,484 l-oħra — il-biċċa l-kbira miktuba mill-ġdid fir-round taċ-ċensiment — għandhom `model`, `tier`
u `timestamp` biss.

Għal kull grupp ta' mhux iktar minn erba' versi, il-magna rċeviet: it-test Lhudi (bil-vokali u bil-konsonanti
biss); kull kelma bil-forma tad-dizzjunarju tagħha, in-numru ta' Strong u t-tifsira ta' Strong; il-versi ta' ħdejhom
(bħala kuntest, bl-Ingliż); ir-regoli bil-Malti; u **seba' traduzzjonijiet Ingliżi għall-paragun** (Wycliffe,
Geneva 1599, King James, Young's Literal, American Standard, JPS 1917, Berean Standard). *(Dawn il-paraguni tħallew
apposta u huma ddikjarati pubblikament; ir-round "kamra nadifa" — it-test Lhudi u d-dizzjunarju biss — jiġi
iktar 'il quddiem, bħala bidla separata.)*

Kull vers għandu żewġ forom: **kelma Maltija għal kull kelma Lhudija** u **l-vers sħiħ** bil-Malti. It-tnejn
jinżammu.

## Qabel ma bdiet il-prova

Għoxrin kelma nqalbu għall-Malti u lura għall-Ingliż: **19 / 20** reġgħu lura. Il-prova tal-annimali fil-vers
(exp 1200): **35 / 46** — in-nuqqasijiet (`ועגל` → *ġerġur*, ġrillu; `גדי` → *tgħażżiż*, qanfud; `ויחמור` → *far*,
ġurdien; `השפן` → *irkom*) marru fir-regoli. Ir-regoli kellhom **it-tabella tal-Ismijiet u tal-kliem ewlieni** u
**it-tabella tal-annimali** mill-ewwel vers — kelma waħda għal kull post, dejjem.

**Ir-regoli ssewwew f'nofs il-ħruq.** Ir-ringiela tal-annimali maqsuma mas-siġġijiet l-oħra kienet tgħid `איל`
→ *ċerv*. Iżda `אַיִל` huwa **l-muntun** (is-sagrifiċċji, Ġen 22:13), u `אַיָּל` biss huwa ċ-ċerv. Ir-ringiela
ġiet korretta waqt il-ħruq (`אַיִל` = **muntun**, `אַיָּל` = **ċerv**), u l-erba' postijiet li kienu diġà niżlu
qabel ma ssewwiet ġew imsewwija bl-id (ara isfel).

## X'ġie ivverifikat

Il-bieb (`dev/scripts/mt_gate.clj`), fuq it-23,213 fajl, fil-ħin tal-commit. Jaqra l-Isem fit-test tal-vers innifsu,
fiż-żewġ direzzjonijiet — fejn il-Lhudi għandu l-Isem u l-Malti le, u fejn il-Malti għandu l-Isem u l-Lhudi le:

- **L-Isem:** `Jaħwe` f'**6,007 / 6,007** vers.
- L-Isem nieqes fil-vers (*fewer*): **0**. L-Isem miżjud fejn il-Lhudi m'għandux (*added*): **0**.
- Awto-korrezzjonijiet tal-magna mħollija fil-vers (*'— le,'* · *'— no:'*): **0**.
- It-tħassir tal-Isem (`Mulej`, `MULEJ`, `l-Etern`, `Ġeħova`, `YHWH` floku): **0**.
- Kliem Ingliż (*the*, *of*, *which*, *with*): **0**. Parentesi b'Ingliż jew `⟨ה⟩`: **0**.
- Ittri Lhud fil-vers (barra mill-parentesi): **0**. Test mhux NFC: **0**.
- **Bleed** (c bla tikka, y, Taljan, ittri Għarab): **101** kandidat — **miftuħa**, għall-qari.

**Iżda l-bieb ma jarax kollox.** Il-qari wara l-bieb (il-21 ta' Ottubru 2026: iktar minn 300 vers mit-tliet
taqsimiet — Ġen 1, Ġen 22, Eż 3, Eż 20, Lev 19, Dewt 6, Iż 6, Iż 53, Ġer 31:31–34, Eżek 36:25–27, Eżek 37,
Salm 1, Salm 22, Salm 23, Ġob 38, Rut 1, Għan 2, Dan 7, u 30 vers għall-għarrieda — u tfittxija ta' kull klassi
fil-corpus kollu) sab dak li l-bieb ma jarax:

- **Kliem ivvintat jew maqsum** — fil-kampjun, kważi kull vers fih kelma jew tnejn li mhumiex Malti (*twettjek*,
  *Rromblawh*, *jidgħajfir*, *Instaħtaġ*, *liġġri*). Din hija l-ikbar klassi; ma tistax tingħadd bit-tfittxija.
- **Versi ivvintati jew imħawda** — Ġen 21:27 u Ġoż 21:7 (test li m'għandu x'jaqsam xejn mal-Lhudi, b'*Alla*
  miżjud), 2 Kron 9:21, Ġer 44:16 (fih il-vers 17), Prov 15:20 (bl-Ingliż kollu).
- **Awto-korrezzjonijiet li l-bieb ma jafx** — 2 Sam 8:6 *"— hm, correction:"*; Prov 11:17 *"— ieħor:"*.
- **Ittri barranin** — 449 vers b'ittri li mhumiex fl-alfabett Malti (*š*, *ŝ*, *ḥ*, *ṭ*, *ł*, *ī*, Grieg, Ċirilliku,
  平); 23 vers b'karattri moħbija (soft hyphen, zero-width); 5 b'tab jew linja ġdida ġewwa l-vers.
- **Kliem Ingliż** li l-bieb ma jfittixx — madwar 60 vers (*swarms*, *tremor*, *jihadists*, *prostitutes*,
  *Virgin*, *blessed*).
- **Parentesi miksura** — 43 vers (*⟨…>*, *>>*, *[ ]*, *{ }*, *`<i>`*); l-artiklu bejn il-parentesi (*⟨il-⟩*, *⟨il⟩*)
  f'101 vers; ittri Lhud ġewwa ⟨ ⟩ li mhumiex ⟨את⟩ f'16-il vers.
- **Elohim miktub ħażin** — 36 vers (*Elohom*, *Eloheim*, *Elohi*, *Elohum*); **Alla** fis-sedja ta' `אלהים`
  (2 Kron 9:23) u miżjud fejn il-Lhudi m'għandu l-ebda alla.
- **`עדה` / `קהל` maqluba *il-knisja*** — 25 vers. Kelma tal-Knisja fit-Tanakh.
- **Isem il-post u n-nies barra mir-regoli** — *Ġeruxalajim*, *Ġerusalemm*, *Iżrael*; u ismijiet li r-regoli ma
  jsemmux b'għaxar sa għoxrin kitba (Jehuda, Sijon, Xelomo, Paro, Ġużeppi / Josef, Noaħ / Noċe).
- **Il-klassijiet tal-bleed**: *c* minflok *ċ* (90 vers), *ch* minflok *ħ* (30), *sh* minflok *x* fl-ismijiet
  (madwar 320), Taljan (*olokausto* u 30 forma oħra għal `עלה` f'105 vers; *kubiti* f'29; *deċimu* f'5).
- **L-arka** — `ארון` b'iktar minn tletin forma (*arka*, *tebut*, *aron*, *tabut*, *senduq*, *arċa*, *arġit* …);
  it-`תבה` ta' Noaħ b'disa' (*tabut*, *teba*, *teva*, *arka*, *vieħba*, *vaska*, *tevra*).
- **Sens ħażin** — Eż 20:5 *l-ommijiet* (`אבות`, il-missirijiet); Iż 6:4 *riħa ta' l-iskart* (`עשן`, duħħan);
  Iż 53:5 *traskendenzi* (`פשע`); Għan 2:3 *Fix-xita tiegħu* (`בצלו`, fid-dell tiegħu); Rut 1:6 *l-ikel tagħha*
  (`כלתיה`); 2 Slat 14:23 *sittax* (`חמש עשרה`, ħmistax); 2 Slat 18:4 *in-naħas tan-naħas* (`נחש הנחשת`).

**Ebda vers ma nbidel f'dan il-qari** — il-lista sħiħa, b'kull fajl, kliem ħażin u tiswija proposta, tinsab
fl-aħħar ta' `NOTES.md` ("Mistoqsijiet miftuħa"). Ma nstab l-ebda kelma tat-Testment il-Ġdid (*Kristu*, *Ġesù*,
*Messija*, *Spirtu s-Santu*, *appostlu*, *evanġelju*): **0** — ħlief *il-knisja* hawn fuq. Ma nstab l-ebda *Mulej*:
**0**.

## X'ġie korrett

- **It-test Lhudi:** il-kliem Lhudi mibdul inġieb lura mis-sors (surface restore).
- **Ir-round taċ-ċensiment** (2,423 post, kollha tajbin wara s-sellum): ittri barranin, kliem Ingliż, sinjali,
  kliem Lhudi fil-vers.
- **Bl-id** (a2ae0c05, `dev/scripts/mt_post_round_mends.py`): l-Isem b'ittra żgħira jew miktub ħażin (*jaħwe*,
  *Ġaħwe*, *Ħaħwe*, *Joħwe*, *Jaħde*, *Jahwe* → **Jaħwe**); Eż 39:7 l-Isem miġjub lura (*kif Jaħwe amar*);
  **l-erba' mtaten li r-regoli kienu għamlu ċriev** (Ġen 22:13; Eż 25:5; 29:1; 29:3 — *ċerv* → **muntun**, *ċervi* →
  **mtaten**, bl-artiklu Malti mibni mill-ġdid); sinjali miksura (`<את>` → **⟨את⟩**, `〈hu〉` → **⟨hu⟩**).
- **Il-pressa tat-33:** l-**awto-korrezzjonijiet** tal-magna mħollija fil-vers (*— le,* · *— no:* — 22 darba) u versi
  mħawda.
- **Il-pressa tas-47:** **l-Isem MIŻJUD** fejn il-Lhudi m'għandux (Ġen 42:16 il-post tal-Fargħun; Eż 9:17 *il-poplu
  ta' Jaħwe*; 1 Slat 8:28 *qaddej ta' Jaħwe*; Ġob 8:3 `אל` …). L-aħħar sitta ngħalqu bl-id: Ħos 6:11 (`יהודה` —
  **Jehuda**, mhux l-Isem), Salm 66:6, 145:19, Imħ 13:16, 2 Slat 18:6, Ġen 18:23.

## Il-magna u l-bniedem

**Il-kliem kollu fil-fajls tal-versi għamlitu l-magna**, ħlief it-tiswijiet bl-id imsemmija f'`NOTES.md` §1.
Il-biċċa l-kbira tal-versi ma qrahom ebda bniedem. **L-ebda Malti għadu ma qara din it-traduzzjoni.** Dik hija
l-iktar mistoqsija miftuħa.

L-istorja sħiħa tax-xogħol: `NOTES.md` u l-istorja ta' git.
