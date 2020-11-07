# Klimax

Stránka vytvořena dle dodaného grafického návrhu (obrázek v jpg). Tvorba HTML (soubor index.html), stylování v CSS (soubor style.css) s využitím SASS (SCSS) a Bootstrap5 (carousel (modifikace jQuery kód ze stackoverflow.com), dropdown). Live na adrese: https://klima.netlify.app/ 


## Instalace a spuštění aplikace

Pro spuštění stránky stačí otevřít soubor index.html. Souhrnný kód CSS je v souboru style.css. CSS je po provedení buildu upraveno pro 10 předešlých verzí všech prohlížečů a je provedena komprese. Jednotlivé části CSS jsou ve složce sass.  Pojmenování tříd dle BEM (lehce upravené kvůli kolizím s bootstrapem). 

Instalace souborů *npm install*. Spuštění dev prostředí *npm run watch:sass*, spuštění přes Live Server (nebo *npm start*). Finální kompilace s kompresí všech souborů *npm run build:css*, resp. po jednotlivých krocích: kompilace CSS souboru ze Sass *npm compile:sass*, doplnění prefixů 10 předešlých verzí do CSS souboru *npm prefix:css*, komprese CSS souboru *npm compress:css*.



