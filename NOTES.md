## Eiga

Angular CLI diegimas npm install -g @angular/cli.
Projekto sukūrimas, terminale pasirenkame lokaciją (direktoriją) ir kviečiame komandą ng new projekto-pavadinimas.
Projekte būna pridėtas komponentas (app.component.[ts/scss/html]).
Produkto modelio (klasės) aprašymas. Klasė turėtų šiuos atributus: paveikslėlį (nuoroda, string), pavadinimas (string), kaina (number), nuolaida (boolean/number).
Komponento viduje apibrėžiamas (sukuriamas) produkto modelis (panaudojant klasę).
Komponento template viduje (html) atspausdinami modelio (prekės) duomenys.
Elementams priskiriamos direktyvos. Direktyvos nulemia komponento atvaizdavimo logiką, pvz.: NgClass direktyva leidžia nuimti/pridėti elementui klasę. [disabled] direktyva leidžia aktyvuoti/deaktyvuoti mygtuką.
