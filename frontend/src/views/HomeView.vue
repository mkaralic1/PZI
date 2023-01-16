<template>
  <div>
  
  <v-row>
    <v-col xs="1" sm="1" md="2" lg="2" xl="2"></v-col>
    <v-col  xs="10" sm="10" md="8" lg="8" xl="8">
      <br>
      <p align="left">
        Ovo je naslovna stranica projekta iz kolegija Programiranje za internet kod 
        profesora dr. sc. Tomislava Volarić doc. Projekt se zove E-Sweepstaks i on je 
        zamišljen kao internetska stranica na kojoj će se moći igrati i pratiti nagradne igre. 
        Tehnologije koje ćemo koristiti u projektu su Vue.js, Laravel, Laragon.
      </p>
      <p align="left">
        Projekt je nastao kao ideja da se sve nagradne igre nalaze na jednom mjestu, te da 
        korisnik može sve imati na jednom mjestu. Organizatorima nudi pregled svih igara. 
        Korisnik može pronaći kategoriju igre koju želi.
      </p>
      <p align="left">
        Svakome se barem jednom desilo da je propustio nagradnu igru ili da nikada nije 
        saznao na nju. Te nam je cilj ovog projekta bio napraviti web stranicu na kojoj 
        će se pratiti sve aktualne nagradne igre, koje se nalaze na jednom mjestu te su 
        prijave na njih vrlo jednostavne, što će privući mnogo korisnika koji će nakon jedne 
        odigrane igre ostat duže vrijeme.
      </p>
      <div class="text-center">
        <v-btn
      href="https://github.com/Pero5511/E-Sweepstakes/blob/main/Vizija.docx?raw=true"
      depressed
      color="primary"
      target="_blank"
      >
        Link vizije
      </v-btn>
      <v-btn
      href="https://github.com/Pero5511/E-Sweepstakes/blob/main/img/ES-DB.jpg"
      depressed
      color="primary"
      target="_blank"
      >
        Link baze podataka
      </v-btn>
      </div>
      
    </v-col>
    <v-col xs="1" sm="1" md="2" lg="2" xl="2"></v-col>
  </v-row>
  <br><hr><br>


  <v-row>
    <v-col md="2" lg="2" xl="2"></v-col>
    <v-col xs="12" sm="12" md="2" lg="2" xl="2">
      <v-img
      contain
      src="@/assets/perica.jpg"
      max-height="360"
      ></v-img>  
    </v-col>
    <v-col xs="12" sm="12" md="2" lg="2" xl="2">
      <p>
        Zovem se Perica Topić, dolazim iz peteročlane obitelji. 
        Rođen sam u Slavonskom Brodu. Prešao sam iz osječkog FERIT-a na 
        SUM zbog novonastale situacije sa koronavirusom. Trenutno studiram 
        treću godinu na Mostarskom Sveučilištu, studij Informatika u dislociranom 
        centru Orašje. Osnovnu školu sam pohađao u svom mjestu, pod nazivom 
        "Osnovna škola Stjepana Radića". Srednju školu sam pohađao u glavnom gradu 
        općine - Orašju, pod nazivom "Srednjoškolski centar fra Martina Nedića“. U 
        slobodno vrijeme se bavim trčanjem, volim šah, kvizove i društvene igre.
      </p>
      <v-btn
      href="https://github.com/Pero5511"
      depressed
      color="primary"
      target="_blank"
      >
        Github link
      </v-btn>
    </v-col>

    <v-col xs="12" sm="12" md="2" lg="2" xl="2">
      <v-img
      contain
      src="@/assets/martin.png"
      max-height="360"
      ></v-img>  
    </v-col>
    <v-col xs="12" sm="12" md="2" lg="2" xl="2">
      <p>
        
Zovem se Martin Karalić. Rođen sam u Vinkovcima 18. rujna 2001. godine, te trenutno 
imam 21 godinu.Osnovnu školu sam završio u Cerni pod nazivom Osnovna škola Matije Antun 
Reljković. Srednju školu sam pohađao u rodnom gradu i zove se Tehnička škola Ruđera Bošković 
Vinkovci te završio za Tehničara za mehatroniku. Trenutno studiram na Sveučilištu u Mostaru, 
FPMOZ studij Informatike. Neki od mojih hobija su folklor i sviranje u TS Birtaši.
      </p>
      <v-btn
      href="https://github.com/mkaralic1"
      depressed
      color="primary"
      target="_blank"
      >
        Github link
      </v-btn>
    </v-col>
    <v-col md="2" lg="2" xl="2"></v-col>
  </v-row>
  <br><br>

  <v-row>
    <v-col xs="12" sm="12" md="12" lg="12" xl="12">
      <h4 align="center">FPMOZ - 2022.</h4>
    </v-col>
  </v-row>
    
</div>
</template>

<script>
  

  export default {
    name: 'HomeView',

    
  }
</script>
