# GitHub Pages-deploy

## Filer
- `index.html` är hela webbsidan.

## Publicera gratis på GitHub Pages
1. Skapa ett nytt publikt repo på GitHub, till exempel `kartoverlay`.
2. Ladda upp `index.html` till repots rot.
3. Gå till **Settings** -> **Pages**.
4. Under **Build and deployment**, välj **Deploy from a branch**.
5. Välj branch `main` och mapp `/root`, spara.
6. Efter någon minut får du en URL i stil med `https://dittnamn.github.io/kartoverlay/`.

## Viktigt
- Geolocation i mobilen kräver normalt HTTPS, vilket GitHub Pages ger.
- Kartan använder din MapWarper-overlay här:
  `https://mapwarper.net/maps/tile/106490/{z}/{x}/{y}.png`
- Om kartan inte hamnar rätt från start, ändra `overlayBounds` i `index.html` till rätt område.
- Om du vill ha en appikon på mobilen: öppna sidan i Safari/Chrome och välj "Lägg till på hemskärmen".
