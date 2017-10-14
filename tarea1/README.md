# Tarea 1 Máquinas de Aprendizaje

## Autores

- Ignacio Araya
- Cristián Serpell

## Instrucciones

Para ejecutar la tarea usando Jupyer Notebook, se deben seguir los siguientes pasos:

- Instalar python3, pip3 y virtualenv: `pip3 install virtualenv`.
- Crear virtualenv en directorio actual: `virtualenv entrega`.
- Entrar en virtualenv: `. entrega/bin/activate`.
- Instalar dependencias de python: `pip install -r requirements.txt`. Entre ellas, jupyter, sklearn, scipy, pandas, matplotlib.
- Descargar datos de [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction).
- Descomprimir archivo descargado `unzip housesalesprediction.zip`.
- Obtener datos de parte 4:
```
wget http://www.inf.utfsm.cl/~cvalle/movies.tar.gz
tar -xzvf movies.tar.gz
rm movies.tar.gz
```
- Ejecutar `jupyter notebook`.
