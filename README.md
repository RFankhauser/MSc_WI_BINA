# Gruppenarbeit BINA

## Set-up

1. clone repository mit GitHub Desktop
    ```
    https://github.com/RFankhauser/MSc_WI_BINA.git
    ```
2. Installiere das Environment mit uv
   - install uv ([installing uv](https://docs.astral.sh/uv/getting-started/installation/))
   - install the venv (in project folder) from the pyproject.toml and .python-version files
    ```
    uv synch
    ```

 3. Installiere nbstripout für die automatische Bereinigung der .ipynb (Jupiter Notebook) Dateien 
    - Für alle .ipynb Dateien
    ```
    uv run nbstripout --install
    ```
    - Nur für das aktuelle Repository
    ```
    uv run nbstripout --install --global
    ```