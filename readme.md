## Installation des Librairies

1. Clonez le projet à partir de votre dépôt Git :

   ```bash
   git clone https://github.com/lulu960/TMBD_IPSSI.git
   cd TMBD_IPSSI
   ```

2. Installez les librairies nécessaires :

   ```bash
   pip install -r requirements.txt
   ```

## Lancer l'Application Streamlit

1. Exécutez la commande suivante pour lancer l'application :

   ```bash
   streamlit run tmdb_api.py
   ```

2. Une fois l'application lancée, une URL sera affichée dans la console. Cliquez dessus (par défaut : [http://localhost:8501](http://localhost:8501)) pour ouvrir l'application dans votre navigateur.

## Lancer le script tmbd_script_json.py

1. Exécutez la commande suivante pour lancer le script
    ```bash
   python tmdb_script_json.py
   ```

## Remarque : 

- Pour exécuter le script en continu, décommentez la ligne `#schedule_update()` à la fin du script.