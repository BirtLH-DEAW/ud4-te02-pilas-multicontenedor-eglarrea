# UD4-Multicontenedor_base
TE02 - proyecto base

Éste es un proyecto base del que podéis partir para el desarrollo de la TE02. Podéis modificarlo tanto como necesitéis y consideréis para cumplir con los requisitos del enunciado.

*Propuesta de mejora:* para el servicio de Apache, ¿podríamos utilizar un contenedor más específico y evitar el de Ubuntu?

Haciendo pruebas, en mi docker-compose, se podria quitar el servicio de apache que tira de ubuntu, y habilitar el servicio de wordpress.  Esta forma arrancaría wordpress is usar la imagen de ubuntu e instalar apache..
