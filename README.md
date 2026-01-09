# Nattklar

Dette er en kopi av *Nattklar*, en stjernetittingsapp utviklet under et studentprosjekt ved Universitetet i Oslo.

## Utforst appen

Appen lar deg:
- 🌌 **Se stjernehimmelen** – viser synlige asterismer på himmelen akkurat nå.
- ✨ **Holde deg oppdatert** – få nyheter om kommende begivenheter som nordlys, meteorsvermer og synlige planeter.
- 🌒 **Sjekke stjernetittingsforhold** – se informasjon om værhold, solnedgang og lysforurensing på valgt sted.
- 🪐 **Utforske stjerner og planeter** – les deg opp på hva du kan se på himmelen.
<br>
<br>

<div style="display:flex; flex-wrap:wrap; gap: 4px;">
    <img src="./assets/homescreen.png" style="width:120px; height:auto">
    <img src="./assets/globescreen.png" style="width:120px; height:auto">
    <img src="./assets/weatherconditions.png" style="width:120px; height:auto">
    <img src="./assets/wikiscreen.png" style="width:120px; height:auto">
</div>

## Kom i gang

1. Skaff en [Google Maps API nøkkel](https://developers.google.com/maps/documentation/android-sdk/get-api-key).
2. Fyll inn nøkkelen i:
    - `/project/app/src/main/AndroidManifest.xml`
    - `/project/app/src/main/java/com/example/nattklar/model/dataprocessing/GoogleMaps.kt`
   
   NB: Appen fungerer også uten Google Maps API nøkkel, med unntak av kartfunksjonen.
3. Start appen i [Android Studio](https://developer.android.com/studio).
   -  Alternativt kan `./gradlew assembleDebug` kjøres for å opprette en APK-fil i `app/build/outputs/apk/debug/`. Flytt filen til telefonen og åpne for å installere.


## Prosjektmedlemmer
- [Herman](https://github.com/gremble0)
- Filip
- [Adam](https://github.com/Adam-Karl)
- [Per Ellef](https://github.com/perellef)
- [Dawid](https://github.com/SirLexPLAY)
- Henriette