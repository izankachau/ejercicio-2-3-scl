# Analizador y Generador SCL (IEC61131)

Plataforma Web para generar y comprobar rutinas lógicas escritas en Structured Control Language (SCL) para PLCs.

## Características
- **Interfaz Web Limpia**: Plataforma base en Flask.
- **Base de Datos de Lógica**: SQLite implementado para persistencia de rutinas SCL.
- **Generación de Reportes PDF**: Funciones incorporadas para crear manuales PDF de calidad corporativa (Premium, Industrial, Ultra-Safe).
- **Herramientas de Análisis**: Validación de estándares de programación.

## Requisitos
- Python 3.8+

## Instalación y Uso
1. Navega a la carpeta principal del programa:
   ```bash
   cd Programa_SCL
   ```
2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta el portal web local:
   ```bash
   python app.py
   ```
4. Ingresa a `http://localhost:5000` en tu navegador de confianza.

## Estructura
- `Programa_SCL/`: Motor web de validación y base de datos local SQLite.
- `Documentacion/`: Documentación IEC y la bitácora del proyecto.
