# Tabla comparativa de ISOs

| ISO | Versión | Arquitectura | RAM mínima | Disco mínimo | Tamaño ISO | Ventajas | Inconvenientes | Decisión |
|---|---|---:|---:|---:|---:|---|---|---|
| ISO 01 | TrixiePup64 | 64 bits | 256-512MB | 400-600MB | 1.1GB | Base Debian, carga entera en RAM | Root por defecto, inestable (testing) | Respaldo |
| ISO 02 | 8.2 MinimalGUI | 64 bits | 256MB | 10-15GB | 1.5GB | Muy personalizable, ocupa poco | Curva de aprendizaje alta, configuración manual | Alternativa |
| ISO 03 | 23.1 Arditi | 64 bits | 256MB | 5GB | 1.7GB | Sin systemd, vuela en el Core 2 Duo | Interfaz muy antigua, posibles ajustes de vídeo | Opción principal |

## Resumen de la comparación

- La distribución antiX me parece la más interesante porque al no llevar systemd hace que el procesador Core 2 Duo vaya mucho más fluido que con las otras. 

- Como opción más equilibrada dejo Sparky Linux (ISO 02), ya que al ser una versión mínima me permite montar un sistema Debian a mi medida sin meterle software que no necesite, aunque me toque trabajar más la configuración. Por último, Puppy Linux (ISO 01) es mi opción de seguridad por su capacidad de ejecutarse directamente desde la RAM es algo que me llama la atención y puede ser útil para recuperar datos o trabajar si el disco duro falla.