Virtual Environment Set-up

Abre una terminal, ve hasta la carpeta del proyecto y dependiendo de tu SSOO ejecuta la siguiente linea:

Windows

#     $ conda env create -p .\venv -f .\bin\local\environment.yml

MacOS

#     $ conda env create -p ./venv -f ./bin/local/environment.yml


Activa el virtual environment con el comando que aparece en la terminal, algo similar a:

#     $ conda activate /Users/workspace_github/lc/venv

Dentro del venv ejecuta:

#     $ jupyter lab