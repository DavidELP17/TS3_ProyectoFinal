# Tratamiento de Señales 3 - Proyecto Final

Este proyecto final tiene como finalidad diseñar e implementar un sistema de reconocimiento de modulaciones utilizando Redes Neuronales Convolucionales (CNN). El proyecto consiste en desarrollar un modelo de CNN robusto capaz de clasificar de manera precisa diversos esquemas de modulación presentes en la base de datos proporcionada (RadioML2016). El reconocimiento de modulaciones es una tarea fundamental en los sistemas de comunicaciones inalámbricas, el estudio de este campo de acción es un paso en el progreso del procesamiento de señales en comunicaciones.

Más información sobre este método de clasificación se puede encontrar en https://arxiv.org/abs/1602.04105

Más información sobre el conjunto de datos RML2016.10a se puede encontrar en http://pubs.gnuradio.org/index.php/grcon/article/view/11

@article{convnetmodrec,
  title={Convolutional Radio Modulation Recognition Networks},
  author={O'Shea, Timothy J and Corgan, Johnathan and Clancy, T. Charles},
  journal={arXiv preprint arXiv:1602.04105},
  year={2016}
}

@article{rml_datasets,
  title={Radio Machine Learning Dataset Generation with GNU Radio},
  author={O'Shea, Timothy J and West, Nathan},
  journal={Proceedings of the 6th GNU Radio Conference},
  year={2016}
}

Para ejecutar el proyecto es recomendable importarlo en Google Colaboratory haciendo uso del Runtime para Python 3, Colaboratory ya cuenta con las dependencias instaladas en su entorno de ejecución, 

Para ejecutar este notebook en un equipo local, deberá descargar o generar el conjunto de datos RML2016.10a (https://radioml.com/datasets/) También necesitarás las dependencias utilizadas como Keras instalado con el backend de Theano o Tensor Flow funcionando!
