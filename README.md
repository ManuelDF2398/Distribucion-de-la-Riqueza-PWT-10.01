## Autores:
### Díaz Flores Manuel Antonio
### Mauro Orlando Gutierrez Matínez

##

# Análisis de la Distribución Mundial de la Riqueza

## Descripción

Este repositorio contiene un análisis detallado de la evolución de la distribución mundial de la riqueza, centrado en el PIB per cápita entre países desde 1960 hasta 2010. El análisis se basa en datos de la Penn World Table (versión 10.0) y utilizo Stata para el procesamiento y visualización de datos.

## Estructura del Proyecto

El proyecto se divide en las siguientes secciones:

1. **Evolución de la Distribución Mundial de la Riqueza (1960-2010)**
2. **Milagros y Despegue Económico**
3. **Externalidades y Despegue Económico**

## Contenido del Repositorio

- `data/`: Contiene los datos utilizados, incluyendo la versión 10.0 del Penn World Table.
- `scripts/`: Scripts en Stata utilizados para el análisis de datos.
- `figures/`: Gráficos y tablas generados.
- `results/`: Resultados finales del análisis.
- `report/`: Informe final en formato PDF.

## Instrucciones de Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/ManuelDF2398/Distribuci-n-de-la-Riqueza---PWT-10.01.git
    ```

2. Abre Stata y establece el directorio de trabajo:
    ```stata
    cd "ruta/al/repositorio"
    ```

## Uso

### Análisis de Datos

Para replicar el análisis de datos, sigue los siguientes pasos:

1. Navega al directorio `scripts`:
    ```stata
    cd scripts
    ```

2. Ejecuta los scripts de análisis:
    ```stata
    do analyze_data.do
    ```

### Generación de Gráficos

Para generar los gráficos utilizados en el informe:

1. Navega al directorio `scripts`:
    ```stata
    cd scripts
    ```

2. Ejecuta los scripts de generación de gráficos:
    ```stata
    do generate_figures.do
    ```

## Resultados

### Evolución de la Distribución Mundial de la Riqueza (1960-2010)

He replicado y actualizado los gráficos del artículo de Parente y Prescott (1993) para el período 1960-2010, identificando milagros y desastres del desarrollo económico.

### Milagros y Despegue Económico

He clasificado los países según su crecimiento relativo al PIB per cápita de Estados Unidos y destacado aquellos que mostraron un despegue económico significativo entre 1960 y 2000.

### Externalidades y Despegue Económico

He analizado la evolución del PIB per cápita en los países que experimentaron un despegue económico, evaluando las hipótesis de Lucas (2000) sobre el crecimiento económico.

## Paper utilizado en referencia a la investigación
El paper se encuentra en el repositorio libre [FEDERAL RESERVE BANK OF MINNEAPOLIS][homepage], disponible en https://www.minneapolisfed.org/research/qr/qr1721.pdf.

[homepage]: https://www.minneapolisfed.org/

## Contribuciones

Agradezco cualquier contribución al proyecto. Para contribuir, por favor:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva característica'`).
4. Envía tus cambios a tu repositorio fork (`git push origin feature-nueva`).
5. Crea un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## Contacto

Para preguntas o comentarios, por favor contactar a:

- Autor: Manuel Antonio Díaz Flores
- WhatsApp: +51 983693233

---

### Referencias

1. Parente, Stephen y Edward Prescott. "Changes in the Wealth of Nations". Federal Reserve Bank of Minneapolis Quarterly Review, 1993.
2. Lucas, Robert. "Some Macroeconomics for the 21st Century". Journal of Economic Perspectives, Winter 2000.
