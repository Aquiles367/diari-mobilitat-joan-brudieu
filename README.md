# El meu diari de mobilitat

Web educativa de 2n d’ESO amb quatre rutes des de l’Institut Joan Brudieu, registre diari dels quilòmetres indicats pel professor i comparació de CO₂ amb cotxe i autobús.

## Publicació a GitHub Pages

Els fitxers de la web són a l’arrel i no necessiten compilació.

1. Puja el contingut d’aquesta carpeta a un repositori anomenat `diari-mobilitat-joan-brudieu`.
2. A Settings > Pages, selecciona Deploy from a branch, branca `main` i carpeta `/(root)`.
3. Desa i espera que GitHub mostri l’enllaç publicat.

Documentació: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Dades dels alumnes

Els diaris es desen al navegador amb localStorage, no al repositori ni en un servidor. No se sincronitzen entre dispositius. Els alumnes poden exportar CSV i còpies JSON. En canviar del domini anterior al de GitHub Pages, cal exportar i importar la còpia JSON per conservar el diari.

## Mapes i càlcul

Traçats orientatius calculats amb OSRM a peu sobre OpenStreetMap el 9/10/2026. El professor ha de revisar el recorregut abans de sortir. La distància registrada és la que indica el professor.

Factors OCCC 2026: cotxe de gasolina, 0,182 kg CO₂/vehicle·km; autobús dièsel, 0,971 kg CO₂/vehicle·km. El càlcul divideix per ocupació i compara emissions directes a igual distància. És una estimació, no una mesura de l’estalvi real ni una petjada del cicle de vida. No se sumen les alternatives.

## Dependències

Leaflet 1.9.4 inclòs localment. Llicència a `vendor/LEAFLET-LICENSE.txt`. El mapa base necessita connexió a OpenStreetMap. Tots els camins dels recursos són relatius, compatibles amb GitHub Pages.

Pràctica de CAFE.
