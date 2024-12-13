# Análisis Técnico de Tiras LED Flex

## Descripción del Proyecto
Este repositorio contiene un informe técnico detallado sobre el análisis de tiras LED Flex encapsuladas en una cobertura de goma flexible con un diseño prismático rectangular.
El objetivo principal es determinar las causas por las cuales los LEDs se queman durante o después del proceso de soldadura, tomando en cuenta factores como mal manejo técnico, 
cortocircuitos, estática, o degradación por ciclos de encendido/apagado.

El informe incluye:
- Inspección visual y pruebas iniciales.
- Medición de potencia y luminiscencia.
- Simulaciones de soldadura controlada.
- Pruebas de factores externos.
- Gráficos y análisis de comportamiento.

## Estructura del Repositorio
```
/
├── informe.md                # Informe técnico completo
├── gráficos/                 # Carpeta con gráficos generados
├── datos/                    # Archivos CSV utilizados en el análisis
└── README.md                 # Archivo README actual
```

## Herramientas Utilizadas
- **Fuente de alimentación regulada**: Para aplicar voltajes precisos a las tiras.
- **Multímetro**: Para medir corriente, voltaje y resistencia.
- **Estación de soldadura**: Con control de temperatura para pruebas controladas.
- **Software para gráficos**: Para análisis y representación visual de los datos (Python/Excel).
- **Base de datos**: Para registro de mediciones y resultados obtenidos.

## Resultados Esperados
1. Identificar patrones comunes en las fallas de los LEDs.
2. Determinar las causas principales de daño (exceso de calor, cortocircuito, etc.).
3. Proveer recomendaciones técnicas para evitar estas fallas en el futuro.

## Pasos para Subir este Proyecto

1. **Crea un Repositorio en GitHub**:
   - Ve a [GitHub](https://github.com) y crea un nuevo repositorio llamado `analisis-tiras-led`.
   - Añade una descripción y selecciona **Public** o **Private** según tus necesidades.

2. **Clona el Repositorio en tu Computadora**:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd analisis-tiras-led
   ```

3. **Añade los Archivos del Proyecto**:
   - Copia este archivo README y el `informe.md` en la carpeta del repositorio.
   - Crea las carpetas `gráficos/` y `datos/` si tienes contenido adicional.

4. **Sube los Archivos a GitHub**:
   ```bash
   git add .
   git commit -m "Añadir informe técnico sobre tiras LED Flex"
   git push origin main
   ```

5. **Verifica el Repositorio en GitHub**:
   - Ve a tu repositorio en GitHub y confirma que los archivos se han subido correctamente.

## Contribuciones
Este repositorio está abierto a mejoras y sugerencias. Si encuentras algo que pueda optimizarse o deseas contribuir, por favor abre un *issue* o envía un *pull request*.

## Licencia
El contenido de este repositorio está licenciado bajo la [Licencia MIT](LICENSE).
