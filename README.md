<!DOCTYPE html>
<html>

<head>
  <link rel="stylesheet" href="style.css" type="text/css">
  <title>Úklidový servis Němec</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap" rel="stylesheet">
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.0.0/mdb.min.js"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" rel="stylesheet" />
  <link href="https://cdnjs.cloudflare.com/ajax/libs/mdb-ui-kit/3.0.0/mdb.min.css" rel="stylesheet" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>

<body>

  <div class="uppernav">
    <div class="text">
      <i class="fas fa-mobile-alt"></i> +420 602 307 205 &nbsp; &nbsp;<i class="far fa-envelope"></i>
      uklid-nemec@seznam.cz
    </div>
  </div>

  <!-- As a heading -->
  <nav id="nav" class="navbar navbar-light bg-light">
    <div class="container-fluid">
      <span id="link" class="navbar-brand mb-0 h1">jn-uklid</span>
      <form class="d-flex input-group w-auto">
        <ul id="link" class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <div data-mdb-toggle="modal" data-mdb-target="#kontaktmodal" id="onoff">
              Kontakt
            </div>
          </li>
        </ul>
      </form>

    </div>
  </nav>

  <script>
    $('#kntkt').click(function () {
      $('#kontaktomodal').modal({
        show: true
      });
    });
  </script>

  <div class="modal fade" id="kontaktmodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div style="height: 100%;" class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Kontakt
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            <i class="fas fa-at"></i> Email - <a href="mailto:uklid-nemec@seznam.cz">uklid-nemec@seznam.cz</a><br><br>
            <i class="fas fa-phone"></i> Telefon - +420602307205<br><br>
            Jiří Němec<br><br>

            IČO: 60566159
          </h3>
        </div>
      </div>
    </div>
  </div>

  <header>
    <div class="container-sm">
      <h1 id="title">
        Jn Úklid
      </h1>
      <p id="paratitle">
        Jsme flexibilní a dynamickou firmou s bohatými zkušenostmi v oboru. Vždy klademe důraz na maximální spokojenost
        zákazníka. K tomu neodmyslitelně patří kvalitně a profesionálně odvedená práce. Náš tým Vám nabízí ty nejlepší
        služby v oblasti úklidu.
      </p>
      <button data-mdb-toggle="modal" data-mdb-target="#cenikmodal" id="headerbutton">
        &nbsp;Ceník&nbsp;
      </button>
      <button data-mdb-toggle="modal" data-mdb-target="#nasepracemodal" id="codelame">
        Naše práce
      </button>
    </div>
  </header>

  <div class="modal fade" id="nasepracemodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Naše práce
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body modal-dialog-scrollable">
          <h3 id="mmoto">
            <div id="carouselExampleInterval" class="carousel slide" data-mdb-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active" data-mdb-interval="10000">
                  <img src="https://i.postimg.cc/TPLCmrrs/019.jpg" class="d-block w-100" alt="..." />
                </div>
                <div class="carousel-item" data-mdb-interval="2000">
                  <img src="https://i.postimg.cc/zv5j969m/017.jpg" class="d-block w-100" alt="..." />
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/mZNVQZHT/Bartolom-jsk-gener-ln-klid-038.jpg" class="d-block w-100"
                    alt="..." />
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/Pxnzw0fL/tn-zoom-obrazek-311.jpg" class="d-block w-100" alt="..." />
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/vB77LXD0/obraz272.jpg" class="d-block w-100" alt="..." />
                </div>
              
                
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/mgK7q5LX/164542118-173574351143777-3767237421091252469-n.jpg" class="d-block w-100" alt="..." />
                </div>
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/ZnYNpkHR/164676322-293541452134983-3763755773821362926-n.jpg" class="d-block w-100" alt="..." />
                </div>
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/tRDWyTRV/164525437-2105628909735669-4282090578754338188-n.jpg" class="d-block w-100" alt="..." />
                </div>
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/yYbRgbZ1/164186883-795205364428141-6946837254780334080-n.jpg" class="d-block w-100" alt="..." />
                </div>
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/y83ZFymF/164186883-142936427737612-4098007669643164302-n.jpg" class="d-block w-100" alt="..." />
                </div>
                 <div class="carousel-item">
                  <img src="https://i.postimg.cc/yYbRgbZ1/164186883-795205364428141-6946837254780334080-n.jpg" class="d-block w-100" alt="..." />
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/tRDWyTRV/164525437-2105628909735669-4282090578754338188-n.jpg" class="d-block w-100" alt="..." />
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleInterval" role="button" data-mdb-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleInterval" role="button" data-mdb-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </a>
            </div>
          </h3>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="cenikmodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Ceník
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body modal-dialog-scrollable">
          <h3 id="mmoto">
            1.) Pravidelný úklid nebytových prostor- od 0,6Kč/m2<br><br>

            2.) Jednorázový úklid domu či bytu- od 200Kč/hod<br><br>

            3.) Periodický úklid domu či bytu- od 160Kč/hod<br><br>

            4.) Úklid společných prostor bytových domů- od 80Kč/bytová jednotka<br><br>

            5.) Mytí oken, výloh, omyvatelných stěn- 25Kč/m2<br><br>

            6.) Vysátí průmyslových prostor- od 5Kč/m2<br><br>

            7.) Vysátí koberců- od 4Kč/m2<br><br>

            8.) Extrakční čistění koberců-
            30Kč/plocha do 100m2
            25Kč/plocha nad 100m2
            45Kč/ plocha nad 200m2<br><br>

            9.) Extrakční čistění čalouněného nábytku-
            židle 30Kč/ks
            sedací souprava 130Kč/sedací místo
            křesla 150Kč/ks
            matrace 150Kč/ks
            dvojmatrace 300Kč/ks<br><br>

            10.) Čištění a inpregnace podlahovin s výrobní PU/PUR- úpravou povrchu ( PVC, CV, LINOLEUM, KAUČUK) -
            55Kč/m2<br><br>

            11.) Komplexní vyčistění interiéru vozidla suchou cestou- 800Kč<br><br>

            12.) Komplexní vyčistění interiéru vozidla extrakční cestou- 1300Kč<br><br>

            13.) Předkolaudační úklidy jakéhokoliv rozsahu- cena je stanovena individuálně po shlédnutí<br><br>
          </h3>
        </div>
      </div>
    </div>
  </div>

  <h1 id="ctitle">Naše služby</h1>
  <div class="container">
    <div class="row">
      <div type="button" data-mdb-toggle="modal" data-mdb-target="#uklidmodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-broom fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Úklid
        </h3>
        <p id="cpip">
          Úklid domů,bytů, chodníků, společných prostor bytových domů a více
        </p>
      </div>
      <div data-mdb-toggle="modal" data-mdb-target="#extraktmodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-water fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Čištění extrační cestou
        </h3>
        <p id="cpip">
          Extrakční čištění koberců, sedacích souprav, křesel, čalouněných židlí
        </p>
      </div>
      <div data-mdb-toggle="modal" data-mdb-target="#ciksmodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-feather-alt fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Čistění a inpregnace KOŽENÝCH sedacích souprav
        </h3>
        <p style="font-size: 15px;" id="cpip">
          K čistění používáme přípravky od Bristonu, sedací soupravu nejprve dokonale vyčistíme pomocí gelu a
          speciálních houbiček a poté naimpregnujeme.
        </p>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div data-mdb-toggle="modal" data-mdb-target="#interierymodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-broom fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Čistění interiéru vozidel
        </h3>
        <p id="cpip">
          Provádíme ruční čištění interiérů osobních aut, dodávek, off-roadů a autobusů.
        </p>
      </div>
      <div data-mdb-toggle="modal" data-mdb-target="#impregnacemodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-water fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Čištění a impregnace podlahovin
        </h3>
        <p id="cpip">
          Čištění po ukončení stavebních prací Nově položená krytina musí být před používáním důkladně základně
          vyčištěna
        </p>
      </div>

      <div data-mdb-toggle="modal" data-mdb-target="#aerorosolmodal" class="col-sm"><br>
        <span id="icon"><i class="fas fa-pump-soap fa-2x"></i></span><br><br>
        <h3 id="ctit">
          Dezinfekce vašich prostor aerosolem
        </h3>
        <p id="cpip">
          Ůčinná ochrana proti virům a bakteriím s rychlým a trvajícím účinkem
        </p>
      </div>
    </div>
  </div>

  </div>



  <!--MODALS-->
  <div class="modal fade" id="uklidmodal" tabindex="-1" aria-labelledby="uklidModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-broom"></i> Úklid
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            Vaše starosti s úklidem jakýchkoliv prostor nechejte na nás. Vyškolený profesionální personál s odbornými
            znalostmi a praktickými zkušenostmi je Vám k dispozici při jakékoliv úklidové práci.<br><br>
            Toto je jen zlomek úklidových služeb, které u nás můžete využít. Nabízíme:
          </h3>
          <li>Úklid domů,bytů, chodníků</li>
          <li>Úklid společných prostor bytových domů</li>
          <li>Úklid kanceláří a administrativních budov</li>
          <li>Úklid obchodních ploch</li>
          <li>Úklid staveb po rekonstrukci</li>
          <li>Mytí oken a výloh</li>
          <li>Úklid školních zařízení</li>
          <li>Úklid sněhu</li>
          <li>Péče a údržba zeleně</li>
          <li>..a mnohem více</li>
        </div>
      </div>
    </div>
  </div>


  <div class="modal fade" id="extraktmodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Čistění extrakční cestou
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            Extrakční čištění koberců, sedacích souprav, křesel, čalouněných židlí - extrakční čištění je vhodné pro
            všechny druhy sedaček s textilním po- tahem jak přírodním - vlněným nebo bavlněným, tak syntetickým. Při
            čištění nedochází ke srážení povrchů. Extrakčním čištěním dochází k dokonalému odstranění nečistot (prachu,
            mastnoty a různých bilologic- kých skvrn - jídlo, pot). Čistit sedací soupravy doporučujeme 2x ročně, tím
            prodloužíte jejich životnost i o několik let. Extrakční čištění koberců neprovádíme u koberců s extrémně
            dlouhým vlasem nebo u perských koberců.
          </h3>
        </div>
      </div>
    </div>
  </div>


  <div class="modal fade" id="ciksmodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Čistění a inpregnace KOŽENÝCH sedacích souprav
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            K čistění používáme přípravky od fy Briston sedací soupravu nejprve dokonale vyčistíme pomocí gelu a
            speciálních houbiček a poté naimpregnujeme
            balzamém.<br><br>

            <a href="http://www.bristoncz.cz/produkty/cistici-gel-na-kuzi/">Čistící gel na kůži</a><br><br>

            Čistič kůže je vhodný na pravou kůži i umělé kůže a koženky všeho druhu. Je ideální na čištění kožených
            sedacích souprav, křesel, kožených bund či kabátů, kožených interiérů automobilů a dalších kožených výrobků.
            Vyčistí i mastné skvrny od rukou, například od hlavy na sedačce či od krku na kabátě. Používá se i na
            čištění sportovní obuvi, protože nepoškodí lepení a navíc nemusíte hodiny či dny čekat na vysušení obuvi,
            tak jako při běžném praní.<br><br>

            Účinně odstraňuje nečistoty a skvrny. Čistič kůže šetrně, ale účinně vyčistí každou nečistotu z pórů kůže.
            Kůže nepromočí jako při čištění vodou.
          </h3>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="aerorosolmodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Ošetření vašich prostor aerosolem
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            Používáme vysocé účinný dezinfekční přípravek AIRSAN-3D<br><br>

            Vlastnosti přípravku AIRSAN-3D:
            <ol>
              <li>Bezchlorový</li>
              <li>Bezalkoholový</li>
              <li>Bez obsahu peroxidu vodíku</li>
              <li>Netoxický pro zdraví člověka</li>
            </ol><br><br>

            <div style="text-decoration: underline;">Rychlá dezinfekce aerosolem pomocí ULV fogeru</div><br><br>

            Co to je dezinfekce aerosolem pomocí ULV fogeru?<br><br>

            Způsob dezinfekce pomocí přípravku AIRSAN-3D, který aplikujete pomocí "fogovacího" ULV přístroje vytvoří v
            celém prostoru místnosti mlhu sestávající z mikrokapének 10-50µm
            která během 15 minut "dosedne" na veškeré povrhy a důkladně ošewtří veškeré plochyvčetně míst která jsou při
            normálním úklidu nedostupné.
          </h3>
        </div>
      </div>
    </div>
  </div>


  <div class="modal fade" id="interierymodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i> Čistění interiéru vozidel
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            Provádíme ruční čištění interiérů osobních aut, dodávek, off-roadů a autobusů. Vysajeme a vyčistíme sedadla,
            stropnici, zavazadlový prostor a ostatní čalounění. Speciálními přípravky ošetříme kožená sedadla. Plastové
            díly vyčistíme a nakonzervujeme. Umyjeme okna, zpětná zrcátka a gumové koberce.
          </h3>
        </div>
      </div>
    </div>
  </div>


  <div class="modal fade" id="impregnacemodal" tabindex="-1" aria-labelledby="extraktModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
      <div class="modal-content">
        <div class="modal-header">
          <h2 class="modal-title" id="mtitulek">
            <i class="fas fa-drop"></i>Čištění a impregnace podlahovin
          </h2>
          <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <h3 id="mmoto">
            Podlahoviny s výrobní PU/PUR-úpravou povrchu (PVC, CV, LINOLEUM, KAUČUK)<br><br>

            1. Čištění po ukončení stavebních prací Nově položená krytina musí být před používáním důkladně základně
            vyčištěna, aby byly odstraněny všechny zbytky výrobních a montážních nečistot. K tomuto čištění použijte
            CC-PU-čistič zředěný s vodou v poměru 1:10. Při nepatrném znečištění je možno tuto koncentraci zvýšit podle
            stupně znečištění. Čistící roztok naneste stejnoměrně na podlahu a po asi 10 minutách působení celou plochu
            vydrhněte jednokotoučovým rotačním strojem CC-SRP 1 nebo CC-SRP 2+S s kartáčem nebo s červeným padem.
            Rozpuštěné nečistoty odsajte vysavačem na vodu a celou plochu důkladně zneutralizujte čistou vodou až do
            úplného odstranění všech zbytků čistícího roztoku.<br><br>

            2. Běžné čištění a ošetřování<br><br>

            2.1 Odstraňování prachu: Odstraňování volně ležícího prachu a nečistot provádějte stíráním vlhkým mopem.
            2.2 Manuální nebo strojové mokré čištění: Pro odstranění přilnutých nečistot použijte CC-PU-čistič zředěný v
            poměru 1 : 200 s vodou a plochu vytírejte ručně vhodným mopem (např. CC-Quick-Step) nebo čistícím automatem
            (např. CC-Premium F2). V prostorách, ve kterých je nutno pravidelně provádět plošné desinfekční čištění,
            používejte CC-Desinfekční prostředek-koncentrát.
            2.3 Mezistupňové čištění: Pokud není možno ulpívající nečistoty odstranit běžným čištěním, doporučuje se
            provést mezistupňové čištění roztokem CC-PU-čističe a vody v koncentraci, která odpovídá stupni znečištění
            plochy (např. 1:50 až 1:100). Čištění provádějte za pomoci kartáče nebo čistícím automatem (např. automatem
            na mytí tvrdých povrchů CC-Premium F2) nebo sprejovou metodou. Pro optimální udržení hodnoty povrchu se
            doporučuje vyčištěný povrch pavidelně leštit jednokotoučovým rotačním strojem CC-SRP 2+S s bílým padem nebo
            leštícím kartáčem.<br><br>

            3. Odstraňování skvrn a rýh od gumových podpatků Tvrdošíjné skvrny a rýhy od gumových podpatků odstraníte
            neředěným CC-PU-čističem za pomoci hadříku nebo jemného bílého padu. Na závěr místo přemyjte čistou vodou.
            Skvrny odstraňujte pokud možno neodkladně, neboť některé typy skvrn při zestárnutí do povrchu migrují a
            jejich úplné odstranění je poté velmi obtížné nebo nemožné.<br><br>

            4. Základní čištění Základní čištění se provádí v tom případě, že není možné obzvláště tvrdošíjné nečistoty
            a usazeniny, které narušují dobrý optický vzhled, odstranit při běžném denním čištění nebo pokud je nutné
            připravit podlahovinu pro sanaci opotřebeného povrchu CC-PUochrannou vrstvou. Pro základní čištění použijte
            CC-Základní čistící přípravek R v koncentraci až 1:5 s vodou. Roztok naneste na podlahu a po asi 10 - 15
            minutách působení celou plochu intenzivně vydrhněte jednokotoučovým rotačním strojem CC-SRP se zeleným
            padem. Pokud nebude následovat ošetření povrchu, použijte červený pad nebo kartáč. Rozpuštěné nečistoty
            odsajte vysavačem na vodu (např. CC-Extraktor nebo CC-Premium F2) a celou plochu důkladně zneutralizujte
            čistou, pokud možno teplou vodou, až do úplného odstranění nečistot a zbytků čistícího roztoku (voda už
            potom nepění!).<br><br>

            5. Proaktivní dlouhodobá ochrana / sanace Aby bylo možno udržet dlouhodobě vlastnosti PU-úpravy povrchu, tj.
            ochranný účinek, snížení přilnavosti nečistot a zjednodušení denního čištění, doporučuje se proaktivní
            dlouhodobá ochrana PU-úpravy povrchu, popř. včasné provedení sanace poškozených míst.
            5.1 Proaktivní dlouhodobá ochrana: Po delším čase používání, nejpozději však při výskytu prvních
            opotřebených míst, se doporučuje výrobní povrchovou PU-úpravu oživit pomocí CC-PU-ochranné vrstvy (matné,
            extramatné nebo lesklé). K tomuto použijte pomocí příslušného tvrdidla aktivovanou CC-PU-ochrannou vrstvu a
            naneste ji neředěnou na důkladně vyčištěný povrch (viz. Základní čištění). Nanášení CC-PU-ochranné vrstvy
            provádějte CC-Lakovacím válečkem „Aguatop“ 10 mm přesně podle návodu k použití na dokonale suchý povrch. 12
            hodin po nanesení poslední vrstvy je možno podlahu používat. Konečná odolnost ochranného systému bude
            dosažena asi po sedmi dnech.<br><br>
            5.2 Sanace: Při rozsáhlém opotřebení výrobní PU-úpravy bude nutné nanést CC-PUochrannou vrstvu dvakrát. Mezi
            jednotlivými vrstvami je nutno nechat vždy předchozí nátěr dostatečně zaschnout (min. 2 hodiny), oba nátěry
            musí být ale provedeny ve stejný den. Upozornění: Před nanešením CC-PU-ochranné vrstvy je nutné provést
            pomocí jednokotoučového rotačního stroje CC-SRP 2+S a CC-PU-sanačního padu šedého zmatovatění povrchu, aby
            byly opticky sjednoceny i přechodové prostory a zajištěno dokonalé přilnutí ochranného nátěru. U podlahovin
            se silnou strukturou povrchu není toto zmatovatění abrazivním padem možné.<br><br>

            6. Udržení hodnoty ve speciálních objektových prostorách Použitím CC-PU-ochranné vrstvy je vytvořena na
            povrchu nejlepší možná ochrana, srovnatelná s výrobními úpravami. Pokud bude nutné chránit povrch ve
            speciálních objektech před vlivy zabarvení, např. ošetřovny lékařů, kadeřnické salóny, autosalony (např.
            kvůli minimalizování zabarvení povrchu vlivem barevných substancí jako dezinfe
            kce na poranění, barvy na vlasy, změkčovadla).<br><br>
          </h3>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
