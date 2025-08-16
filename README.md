# analysis-tool
Recopila datos públicos de competidores como precios, redes sociales, novedades y genere un informe simple.

# Herramienta de Análisis de Competencia

## Características

- Recopila información de sitios web y redes sociales de competidores.
- Genera informes en formato Markdown o CSV.
- Fácil de configurar (solo edita `config.json`).

## Estructura

```
├── README.md
├── requirements.txt
├── config.json
├── src/
│   ├── main.py
│   ├── fetcher.py
│   └── reporter.py
├── data/
│   └── reports/
└── .gitignore
```

## Instalación

1. Clona este repositorio.
2. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Edita `config.json` para agregar competidores.
4. Ejecuta la herramienta:
   ```bash
   python src/main.py
   ```

## Ejemplo de informe

```
# Informe de Competencia - 2025-08-13

## Competidor: Ejemplo S.A.
- Precio actual: $199
- Última publicación en Instagram: "¡Lanzamos nuevo producto!"
- Última novedad en la web: Descuento del 20% en agosto
```

## Contribuir

¡Eres bienvenido a mejorar la herramienta! Puedes proponer nuevas fuentes de datos, mejorar los informes, o agregar funcionalidades.

## Licencia

MIT
