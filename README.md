<!-- PROJECT SHIELDS -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">PRA1: Implementación de un agente para la robótica espacial</h3>
  <p align="center">
    Proyecto de la asignatura de Aprendizaje por refuerzo.
    <br />
    <a href="https://github.com/alephsub0/TestAssigner/issues">Reportar un Problema</a>
    <br />
    <br />
    Abrir en 
    <br />
    <a href="https://drive.google.com/file/d/1zggWDbNfR_aEFSOyivg9lJoJ2728dHtT/view?usp=sharing">
    <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=fff&style=for-the-badge" alt="Google Colab Badge">
    </a>
  </p>
</div>



## Sobre el Proyecto

Este proyecto se ha desarrollado en el marco de la asignatura de Aprendizaje por refuerzo, en el Máster Universitario de Ciencia de Datos de la UOC. El objetivo de este proyecto es implementar un agente para la robótica espacial, que sea capaz de aterrizar un módulo lunar. 

Para ello, se elige [lunar-lander](https://github.com/openai/gym/blob/master/gym/envs/box2d/lunar_lander.py) como entorno simplificado. Lunar Lander consiste en una nave espacial que debe aterrizar en un lugar determinado del campo de observación. El agente conduce la nave y su objetivo es conseguir aterrizar en la pista de aterrizaje.

![Lunar Lander](/videos/agente_DQN.gif)

El enunciado completo de la actividad se puede encontrar en el siguiente [enlace](/M2_883_20221_Práctica-Enunciado.pdf).

### Construido con

![Jupyter Badge](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=for-the-badge) ![PyTorch Badge](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=fff&style=for-the-badge) ![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge) ![OpenAI Gym Badge](https://img.shields.io/badge/OpenAI%20Gym-FFAC45?logo=openai&logoColor=fff&style=for-the-badge)

## Descripción

En este repositorio se presenta la solución a la actividad PRA1. La solución se ha desarrollado en Python y se ha implementado un agente que utiliza el algoritmo DQN (Deep Q-Network) para resolver el problema de aterrizaje de la nave espacial.

### Contenido del Repositorio

Se tienen los siguientes archivos en el repositorio:

- [M2_883_20221_Práctica-Enunciado.pdf](/M2_883_20221_Práctica-Enunciado.pdf): Enunciado de la práctica.
- [M2_883_20221_Práctica_Sol_AndresMerinoToapanta.pdf](/M2_883_20221_Práctica_Sol_AndresMerinoToapanta.pdf): Informe de la solución de la práctica.
- [M2_883_20221_Práctica_Sol_AndresMerinoToapanta.ipynb](/M2_883_20221_Práctica_Sol_AndresMerinoToapanta.ipynb): Notebook con la implementación de la solución.
- [agentDQN_Trained_Model.pth](/agentDQN_Trained_Model.pth): Modelo entrenado del agente DQN.
- [agentA2C_Critic_Trained_Model.pth](/agentA2C_Critic_Trained_Model.pth): Modelo entrenado del agente A2C, critic.
- [agentA2C_Actor_Trained_Model.pth](/agentA2C_Actor_Trained_Model.pth): Modelo entrenado del agente A2C, actor.
- [videos](/videos): Video de la simulación de los agentes.
 
 
## Créditos

Andrés Merino\
[Proyecto Alephsub0](https://www.alephsub0.org/about/),\
Docente Investigador\
Pontificia Universidad Católica del Ecuador\
aemerinot@gmail.com\
[![LinkedIn][linkedin-shield]][linkedin-url-aemt]

## Licencia

Distribuido bajo la licencia MIT. 

[![MIT License][license-shield]][license-url]




<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/Aprendizaje-por-refuerzo---lunar-lander.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/Aprendizaje-por-refuerzo---lunar-lander/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/Aprendizaje-por-refuerzo---lunar-lander.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/Aprendizaje-por-refuerzo---lunar-lander/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/Aprendizaje-por-refuerzo---lunar-lander?style=for-the-badge
[stars-url]: https://github.com/andres-merino/Aprendizaje-por-refuerzo---lunar-lander/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/Aprendizaje-por-refuerzo---lunar-lander.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/Aprendizaje-por-refuerzo---lunar-lander/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/Aprendizaje-por-refuerzo---lunar-lander.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/
