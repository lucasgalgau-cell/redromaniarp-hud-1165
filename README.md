# RedRomeniaRP HUD - mod Forge 1.16.5 (client)

Afiseaza HUD-ul rosu RedRomeniaRP: titlu, logo, playeri online, ID, playtime, bani.

## Date
- Playeri online: din tab list. Playtime: din statisticile jucatorului (cerute de la server la ~30 sec).
- ID si Bani: din scoreboard objectives ale serverului. In
  `src/main/java/com/redromaniarp/hud/client/HudData.java` schimba:
  `OBJECTIVE_ID_BANI = "bani"` si `OBJECTIVE_ID_ID = "playerid"`
  cu numele reale folosite pe server.

## Build
Pe GitHub: urca tot continutul folderului intr-un repository, apoi
tab-ul Actions -> descarca artifact-ul `redromaniarp-hud-jar`.
Local: JDK 8 + Gradle 7.4.x -> `gradle build` -> `build/libs/`.

## Instalare
Forge 1.16.5 instalat, jar-ul in folderul `mods`.
