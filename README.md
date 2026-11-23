# Anime Jutsu (Forge 1.20.1) — Fase 1

Port del addon Bedrock ANIME JUTSU (Kubo Studios) a Forge 1.20.1 + GeckoLib 4.

## Incluye
- 8 mascotas domables con el Pacto de Domador: Wolfive, Monowl, Dogumaru, Catviathan, Warpu, Sphynkh, Slade y Orbe Consciente
  (vida 100 y rangos de daño tomados de tu versión modificada).
- Modelos (.geo), animaciones y texturas convertidos del addon. También están los de las evoluciones
  (five_tailed_wolf, elder_monowl, dogekomaru, armored_feline, warper, desert_warlock) listos para la fase 2.
- Huevos generadores + pestaña creativa para probarlas.

## Cómo compilar
1. Descarga el MDK de Forge 1.20.1 (47.3.0) y copia aquí sus archivos `gradlew`, `gradlew.bat` y la carpeta `gradle/`.
2. Necesitas JDK 17.
3. `./gradlew build` → el .jar queda en `build/libs/`. Ponlo en `mods/` junto con GeckoLib 4.4.9 para 1.20.1.
   (O abre la carpeta en IntelliJ y ejecuta `runClient`.)

## Uso en el juego
Pestaña creativa "Anime Jutsu": genera la mascota, clic derecho con el Pacto de Domador para domarla,
clic derecho con la mano vacía para sentarla, y comida para curarla.

## Pendiente / aproximaciones
- Monowl: su comida original (resin_clump) no existe en 1.20.1; uso panal como sustituto.
- Variantes de textura, partículas, sonidos, evolución y habilidades: siguientes fases.
- Las animaciones usan molang de Bedrock; GeckoLib puede avisar en el log de expresiones que no soporte.
- No pude compilar aquí (sin internet): si Gradle da errores, pásamelos y los corrijo.
