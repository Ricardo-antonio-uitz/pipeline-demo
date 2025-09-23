# pipeline-demo

Proyecto de práctica para configurar un pipeline CI con GitHub Actions.

## Archivos
- `app.py`: función simple `suma`.
- `tests/test_app.py`: prueba unitaria usando `pytest`.
- `requirements.txt`: dependencias (pytest).
- `.github/workflows/ci.yml`: workflow para CI (checkout, setup python, instalar dependencias, ejecutar pruebas).

## Cómo usar localmente
1. Crear y activar un entorno virtual (opcional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate   # Windows
   ```
2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecutar pruebas:
   ```bash
   pytest
   ```

## Notas
- Sube este proyecto a un repositorio público en GitHub y verifica la pestaña **Actions** para ver el pipeline en ejecución.
