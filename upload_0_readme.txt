URL APLIKACIJE ---  "https://web2-spa-zlef.onrender.com"
Napomena prilikom lokalnog pokretanja zipanog filea, prvo npm install!
LISTA SVOJSTAVA:
	1.interpolation/one-way binding -Da, src/components/MovieDetails.vue, :4, :7 
	2.two-way binding-Da, src/components/CreateMovie.vue, :7, :15 varijabla newMovieTitle je dvosmjerno povezana s inputom u retku 7 pomo?u v-model...
	3.methods-Da, src/views/MoviesView.vue, :55, :72 gdje vidimo nekolicinu metoda poput brisanje filma, kreiranje novog...
	4.computed properties-Da, src/views/MoviesView.vue, :49, :54 , getFavs() function pomo?u koje mijenjamo prikaz ali ne i podatke
	5.barem jedan scoped style-Da, src/views/HomeView.vue, :26
	6.koristiti barem jedan lifecycle hook-Da, src/views/HomeView.vue, :18, :23 gdje se sat updatea svake sekunde
	7.routing (vi?e stranica)-Da, src/routers/index.js, :1, :30 s dvije route("/", "/movies") te sve druge rute ?e biti uhva?ene te ?e se prikazati poruka s
   		naputkom da se preusmjeri na "/" rutu
	8.(barem) dvije komponente, komponenta bez stanja, koristiti properties, komponenta sa stanjem-Da, komponenta bez stanja - src/components/MovieDetails.vue,
				komponenta sa stanjem - src/components/CreateMovie.vue
   9.barem jedna komponenta mora emitirati barem jedan event-Da, src/components/MovieDetails.vue :25 brisanje odabranog filma
   10.store (Pinia)-Da, src/stores/movieStore.vue, :1, :89, store sa napunjenim podatcima te metodama poput(dohvacanje svih, unosenje, brisanje, azuriranje)
   11.asinkroni dohvat podataka s backenda-Ne
