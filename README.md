🦑🎮 Juego del Calamar – Predictor de Supervivencia

<img width="1536" height="1024" alt="ChatGPT Image 3 dic 2025, 12_09_49 a m" src="https://github.com/user-attachments/assets/513e178b-7ca2-4d14-ad9b-3e06de02b3fe" />

Un proyecto de Machine Learning + Python + Tkinter

Este proyecto utiliza un modelo de Random Forest para predecir si un jugador sobrevive o no en una simulación inspirada en el Juego del Calamar.
Además, incluye una interfaz simple con Tkinter que muestra un popup final al estilo "¿Sobrevive o muere?".

🚀 Características del Proyecto

Entrenamiento de un modelo RandomForestClassifier.

Preprocesamiento de datos con scikit-learn.

Predicción personalizada usando entrada del usuario.

Interfaz gráfica emergente con Tkinter mostrando el resultado:

🔥 ¡Sobrevive!

💀 No sobrevive

Código listo para modificar y expandir.

📁 Estructura del Proyecto
📦 squid-game-predictor
├── data/
│   └── dataset.csv
├── model/
│   └── trained_model.pkl
├── app/
│   ├── predictor.py
│   └── popup_result.py
├── README.md
└── requirements.txt

🧠 ¿Cómo funciona?

Se carga un dataset con características del "jugador" (edad, fuerza, estrategia, etc.).

Se entrena un modelo de Random Forest.

El usuario ingresa sus datos (próximamente por interfaz).

El modelo predice si sobrevive.

Se muestra un popup con el resultado final usando Tkinter.

▶️ Ejecución

Instala dependencias:

pip install -r requirements.txt


Entrena el modelo:

python predictor.py


Cuando la predicción esté lista, se abrirá un popup tipo:

🔥 ¡SOBREVIVE! 🔥


o

💀 No sobrevive

📦 Requisitos

Python 3.10+

scikit-learn

pandas

numpy

tkinter (ya viene con Python)

🛠️ Mejoras futuras

Crear una interfaz completa con Tkinter o PyQt.

Agregar sliders para edad, fuerza, velocidad, etc.

Exportar modelo con joblib.

Versión web con Streamlit.

Integrar sonidos estilo Squid Game.

🌟 Contribuciones

¡Las contribuciones son bienvenidas!
Puedes abrir un issue o enviar un pull request.

👩‍💻 Autora

Proyecto creado por La Hechicera del Cpodigo ❤️.
Enfocado en combinar Machine Learning con experiencias interactivas.

📜 Licencia

MIT License. Puedes usarlo libremente para aprender o crear tus propias variantes.
