# Rootless Containers Article

This repository contains an article on Rootless Containers. It was written in November 2023 as part of my Cloud Computing and Security master's program. [Here](Rootless_Containers_Aleksi_Hirvensalo.pdf) is the full article. Below you can read the abstract. 

# Abstract

Containers are used to isolate applications at the operating system level.
However, that isolation can be escaped and currently the threat is am-
plified by how containers are being run. Most containers run as root by
default, which means that if they can escape the isolation, they are a root
user of the host machine. To tackle the issue, rootless containers have been
created. Rootless means to run the container and its runtime as non-root.
This paper introduces rootless containers and gives a general overview
of the topic. Furthermore, a practical example is given on how to attack
poorly configured containers and how to prevent the attack by enabling
rootless containers.

KEYWORDS: container, container security, docker, rootless containers, sand-
boxing
