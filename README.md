# Portafolio-de-competencias

📌 Portafolio de Evidencias – Carlos Dhali Tejeda Tapia
¡Hola! Soy Carlos Dhali Tejeda Tapia, estudiante del 6to semestre de Ingeniería en Tecnologías Computacionales (ITC) en el Tecnológico de Monterrey. Me apasionan la tecnología, los videojuegos (especialmente League of Legends) y mantenerme activo practicando deportes como voleibol y gimnasio.

Actualmente, mis intereses profesionales se centran en tres áreas principales:

Realizar un posgrado relacionado con análisis de datos y desarrollar una carrera como data analyst.

Trabajar como frontend developer o desarrollador full stack en el área de diseño web.

Participar en la industria de los videojuegos, contribuyendo desde la programación o el diseño técnico.

Durante mi trayectoria académica, he desarrollado proyectos significativos en el área de inteligencia artificial y aprendizaje profundo, particularmente durante mi participación en la concentración de IA para el análisis de datos del Semestre Tec. Aquí te presento dos de mis principales proyectos:

🚀 Proyecto 1: Clasificación de Electrocardiogramas (ECG)
Este proyecto tuvo como objetivo desarrollar un modelo de machine learning capaz de clasificar latidos cardíacos a partir de señales de ECG utilizando dos datasets ampliamente reconocidos:

MIT-BIH Arrhythmia Dataset

PTB Diagnostic ECG Database

🔎 ¿Qué hace este proyecto?
Analiza señales de ECG para identificar y clasificar tipos de latidos cardíacos (normales y anómalos). Los modelos fueron entrenados usando diversas técnicas de aprendizaje automático, explorando métricas de desempeño y validación cruzada para garantizar resultados robustos.

📁 Estructura del proyecto
Los archivos de datos deben colocarse en una carpeta llamada data, al mismo nivel que los notebooks.

Puedes descargar los datasets desde este enlace de Google Drive.

Los notebooks contienen todo el análisis, procesamiento de señales y los modelos de clasificación.

🛠 Instalación
Clona el repositorio.

Navega a la carpeta del proyecto:

bash
Copiar
Editar
cd tu_proyecto
Instala las dependencias necesarias:

bash
Copiar
Editar
pip install -r requirements.txt
🔗 Repositorio del proyecto: [pendiente de agregar]

🧠 Proyecto 2: Myotube Detection and Segmentation Model
Este proyecto consistió en entrenar un modelo basado en YOLOv11 para la detección y segmentación de miotubos (estructuras celulares alargadas observadas en imágenes microscópicas). Fue desarrollado como parte de una iniciativa universitaria enfocada en biomedicina e inteligencia artificial.

🧬 ¿Qué hace este proyecto?
Permite detectar y contar miotubos en imágenes microscópicas utilizando un pipeline de entrenamiento robusto, procesamiento de datos aumentados (espejados horizontal y verticalmente), y un sistema de conversión de anotaciones para entrenar un modelo YOLO personalizado.

⚙️ Pipeline de trabajo
Preparación de datos:

Coloca las imágenes y archivos .json (etiquetados con LabelMe) en la carpeta Labelme.

Aumento de datos:

Ejecuta mirrorH.py y mirrorV.py para crear versiones espejadas.

Junta todos los archivos con merge_files.py.

Conversión de formato:

Usa json_to_yolo_obb.py para convertir a formato YOLO con bounding boxes orientadas.

Entrenamiento:

Instala ultralytics y ejecuta el entrenamiento con YOLOv11.

Personaliza el archivo .yaml para definir las clases y estructura del dataset.

Inferencia:

Usa el modelo entrenado (best.pt) para detectar nuevas imágenes.

📄 Reporte y documentación
Incluye:

Myotubes_report.pdf: reporte en formato LaTeX.

LateX.zip: contiene los archivos necesarios para compilar el reporte en Overleaf.

🔗 Repositorio del proyecto: [pendiente de agregar]

🧬 Sobre mí
Me gusta aprender mediante la práctica y desarrollar soluciones que integren datos, inteligencia artificial y diseño. Me adapto bien a ambientes de trabajo colaborativos y disfruto participar en retos técnicos. Aunque aún no he participado en hackatones, me encuentro motivado para hacerlo en el futuro y destacar con soluciones innovadoras.
