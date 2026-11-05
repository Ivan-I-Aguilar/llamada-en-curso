# Llamada en curso

Juego 3D para PC que corre en el navegador. El personaje atiende una llamada y no para de caminar por el predio. Hay que aguantar los 3 minutos de llamada cuidando dos barras:

- **Glucemia:** caminar la baja. Los caramelos y las gaseosas la suben; el alfajor la dispara. Por debajo de 40 o por encima de 300 mg/dL se desmaya.
- **Ansiedad:** sube con la duración de la llamada, con algunas frases y si se queda quieto. Los puchos la bajan.

A medida que avanza la llamada aparecen cada vez más molestias: jardineros con la cortadora, el repartidor de Credifin, los mecánicos de los aviones, una camioneta que entra al playón y la llamada en espera de "Mi amor".

## Cómo jugar

Abrí `index.html` en el navegador o entrá a la versión publicada en GitHub Pages.

| Tecla | Acción |
|---|---|
| WASD / flechas | Caminar |
| Shift | Apurar el paso |
| Mouse (clic y arrastrar) | Mover la cámara |
| Espacio | Atender a Mi amor |
| M | Música |
| P | Pausa |

## Archivos

- `index.html`: el juego (three.js r128).
- `personaje.js`, `edificios.js`, `vehiculos.js`, `vegetacion.js`: los modelos 3D empaquetados para el navegador.
- `modelos/`: los mismos modelos en formato GLB.
- `blender/`: los archivos de Blender para editar edificios, vehículos y vegetación.

## Créditos

- Cuerpo base del personaje: MakeHuman (CC0), texturizado con fotos propias.
- Motor 3D: [three.js](https://threejs.org) (MIT).
