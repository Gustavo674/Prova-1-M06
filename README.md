# Prova-1-M06

Como executar a PROVA:

(Obs: Este tutorial considera que voce ja tem instalado o ROS2 e seus componentes para rodar a PROVA.)

## Passo 1:

- Clone o repositorio em sua maquina com o seguinte comando `git clone https://github.com/usuario/repositorio.git`

## Passo 2:

- Construa o projeto usando `colcon`:
    -cd ~/Prova-1-M06
    -colcon build --packages-select my_turtle_controller
    -source ~/Prova-1-M06/install/setup.bash

## Passo 3:

- Abra dois terminais, em um voce executa `ros2 run turtlesim turtlesim_node` e no outro `ros2 run my_turtle_controller turtle_controller`

## Passo 4:

- Assistir a arte
