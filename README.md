# Explain Like I'm 5 (ELI5)


## Introducción
En este notebook vamos a configurar una aplicación simple para trazar con LangSmith. 

## Pre-work

### Clonar el repo
```
git clone https://github.com/sergiosiro/cursoGenAI-LangSmith.git
```

### Crear archivo .env 

Seguir el ejemplo de .env.example para completar la información necesaria para correr la aplicación

### Instalar dependencias

Crear un entorno virtual
```
python3 -m venv .venv
Luego, activa el entorno virtual. El comando varía según tu sistema operativo:

- **En Windows:**
  ```
  .venv\Scripts\activate
  ```

- **En macOS y Linux:**
  ```
  source .venv/bin/activate
  ```
```

Instalar dependencias
```
pip install -r requirements.txt
```

## Correr el proyecto

Ya estás listo para correr los cuadernos! Usá el comando
```
jupyter notebook
```
en el directorio raiz para abrir los cuadernos.

Los  notebooks están diseñados para ser utilizados en el siguiente orden:
1. eli5_tracing
2. eli5_types
4. eli5_prompting
5. eli5_experiment
