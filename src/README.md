[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vA18DeTD)

![example workflow](https://github.com/cpit252/lab-5-TareqB1/actions/workflows/classroom.yml/badge.svg)

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/TareqB1/lab-05-vid/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/TareqB1/lab-05-vid/tree/main)

[![codecov](https://codecov.io/gh/TareqB1/lab-05-vid/branch/main/graph/badge.svg?token=TSI0WUIDH4)](https://codecov.io/gh/TareqB1/lab-05-vid)


Question: Explain how the adapter design pattern binds the client to an interface not a concrete implementation??

Answer:.    The client code doesn’t get coupled to the concrete adapter class as long as it works with the adapter via the client interface.
            Thanks to this, you can introduce new types of adapters into the program without breaking the existing client code. This can be useful when the interface of the service class gets changed or replaced,
            you can just create a new adapter class without changing the client code.