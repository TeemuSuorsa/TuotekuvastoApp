# TuotekuvastoApp
Palautettava tehtava

HomeController sisältää toiminnallisuuden, joka hakee tuotteiden tiedot JSON-tiedostosta ja siirtää ne näkymään.
Product toiminto kutsuu getproduct metodia joka lukee tiedoston sisällön ja palauttaa listana Productille joka laittaa nämä näkymään.

products.json tiedosto sisältää tuotetiedot ja getproduct metodi hakee tätä tiedostosta.

Product.cshtml näkymä ottaa vastaan Product listan ja esittää tiedot.
