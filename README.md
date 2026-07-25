# GeoRiskAI Sentinel

Aplicación Streamlit para visualizar proyectos de inversión pública, cruzarlos con la carta CITSU y calcular un índice multicriterio de riesgo por tsunami.

## Archivos de datos requeridos

Agrega dentro de `data/`:

1. `MDS_PROYECTOS 2024 2026.xlsx`
2. `CITSU_Coquimbo_La_Serena_2da_Ed_2015.kmz`

## Ejecución local

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Publicación en GitHub

1. Crea un repositorio.
2. Sube todo el contenido de esta carpeta.
3. Confirma que `app.py`, `requirements.txt`, `.streamlit/config.toml` y `data/` estén en la rama `main`.

## Publicación en Streamlit Community Cloud

1. Conecta Streamlit Community Cloud con GitHub.
2. Selecciona el repositorio y la rama `main`.
3. Usa `app.py` como archivo principal.
4. Presiona **Deploy**.

## Nota de seguridad

Si los datos no pueden ser públicos, utiliza un repositorio privado y verifica las condiciones de acceso antes de desplegar.
