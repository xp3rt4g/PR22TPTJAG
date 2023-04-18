# Analiza prometnih nesreč v Sloveniji
Tim Povše, Anže Goršek, Tim Jevšenak



### Cilji/Zastavljena vprašanja
Pri analizi nas najbolj zanimajo: 
- najpogostejši razlogi za prometne nesreče
- vpliv starosti pri prometnih nesrečah
- kako se spreminja število hudih prometnih nesreč skozi čas
- prometne nesreče po regijah, spreminjanje uporabe varnosntnega pasu
- vpliv alkohola pri prometnih nesrečah
- v katerem delu dneva se zgodi največ prometnih nesreč
- vpliv spola na povzročitev prometnih nesreč



### Zbirka podatkov
Podatki so iz slovenskega portala [OPSI](podatki.gov.si). Gre za podatke o prometnih nesrečah od leta 2009 do leta 2022. Za področje prometne varnosti je na voljo ena datoteka na leto. V datoteki so zajete vse prometne nesreče, pri ogledu katerih je sodelovala policija in so se zgodile v obravnavanem obdobju.



### Opis podatkov
Podatki za vsko leto imajo 35 tributov, in sicer:
- številka za štetje in ločevanje posamezne prometne nesreče
- klasifikacija nesreče glede na posledice (Izračuna se avtomatično glede na najhujšo posledico pri udeležencih v prometni nesreči)
- upravna enota, na območju katere se je zgodila prometna nesreča
- datum nesreče (format: dd.mm.llll) 
- ura nesreče (format: hh.mm) 
- indikator ali se je nesreča zgodila v naselju (D) ali izven (N)
- lokacija nesreče
- vrsta ceste ali naselja na kateri je prišlo do nesreče
- oznaka ceste ali šifra naselja kjer je prišlo do nesreče
- tekst ceste ali naselja, kjer je prišlo do nesreče
- oznaka odseka ceste ali šifra ulice, kjer je prišlo do nesreče
- tekst odseka ali ulice, kjer je prišlo do nesreče
- točna stacionaža ali hišna številka, kjer je prišlo do nesreče
- opis prizorišča nesreče
- glavni vzrok nesreče
- tip nesreče
- vremenske okoliščine v času nesreče
- stanje prometa v času nesreče
- stanje vozišča v času nesreče
- stanje površine vozišča v času nesreče
- Geo Koordinata X je z letom 2013 v D96/TM koordinatnem sistemu, pred tem v Gauß-Krüger-jev koordinatnem sistemu
- Geo Koordinata Y je z letom 2013 v D96/TM koordinatnem sistemu, pred tem v Gauß-Krüger-jev koordinatnem sistemu
- številka za štetje in ločevanje oseb, udeleženih v prometnih nesrečah
- kot kaj nastopa oseba v prometni nesreči
- starost osebe (LL)
- spol
- upravna enota stalnega prebivališča
- državljanstvo osebe
- poškodba osebe
- vrsta udeleženca v prometu
- ali je oseba uporabljala varnostni pas ali čelado (polje se interpretira v odvisnosti od vrste udeleženca) (Da/Ne)
- vozniški staž osebe za kategorijo, ki jo potrebuje glede na vrsto udeleženca v prometu (LL)
- vozniški staž osebe za kategorijo, ki jo potrebuje glede na vrsto udeleženca v prometu (MM)
- vrednost alkotesta za osebo, če je bil opravljen (n.nn v enoti mg alkohola/liter izdihanega zraka (mg/l))
- vrednost strokovnega pregleda za osebo, če je bil odrejen in so rezultati že znani (n.nn v enoti g alkohola/kg krvi (g/kg))


### Vizualizacija podatkov
Podatke smo za vsa leta smo združili v dataframe in naredili vizualizacijo za:
- klasifikacijo nesreč
- število nesreč po mesecih
- število nesreč glede na starost
- število nesreč glede na regijo
- vinjeni in trezni vozniki
- procent vinjenih po letih
- primerjava uporabe varnostnega pasu
- procent uporabe varnostnega pasu
- število prometnih nesreč s hudim izidom po letih

#### Procent alkoholiziranih
![% graph](/graphs/alkoholizirani_procent.png)

#### Procent pripasanih
![% graph](/graphs/pripasani_procent.png)

