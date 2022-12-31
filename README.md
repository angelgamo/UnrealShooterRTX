# ShooterRTX
Developed with con Unreal Engine 5
Juego estilo shooter basado en "3D Bloons", modelos 3d (2k + nanite), texturas arena 8k

![Logo](https://cdn.discordapp.com/attachments/417309952470810625/1056628677007388762/00261-1231900956-a_monkey_holding_a_sniper_rifle_looking_at_baloons_in_the_sky_inside_an_island_hyperrealistic_detailed_4k_cinematic_light.png)

## Base
- Control del personaje con ACharacter.
- Capacidad de disparar, con Traceline (Raycast).
- Inteligencia artificial por parte de los enemigos que siguen al jugador.
- Uso de delegados.
- 3 tipos de armas, diferentes static meshes, diferentes penetraciones de bala.
- Uso de las macros de Unreal Engine, privaticacion, escritura y lectura.


## Features
- RTX.
- Nanite.
- Lumen.
- ComplexShaders.
- NiagaraSystem.
- SoundSystem.
- Landscape.
- Waterbody.
- Foliage.
- Modeling.
- Metahuman.

## Controls
- "WASD" moviemiento horizontal del jugador, "Space" salto.
- Auto pickup de armas por proximidad.
- "click izquierdo" con un arma en la mano para disparar.

## HUD
- Crosshair.

## Special
- /BP/bLOONdb (ballon hierarchy)
- /BP/DynamicVehicle (BP custom follow spline and oscilation)
- /BP/ImpactFXBP (Actor for sounds and particles)
- /Materials/GloboShader (Shader)
- /Materials/M_Landscape (Shader for landscape ground)
- /Materials/M_Confetti (Shadder balloons explosions)
- /Niagara/* (NiagaraSystems)