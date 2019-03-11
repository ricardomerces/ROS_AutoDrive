# ROS - AutoDrive 1.0


#### Criar o pacote com o catkin:

`cd ~/workspace/src`
`catkin_create_pkg auto_drive rospy`

#### Compilar:

`cd ~/workspace`
`catkin_make`
`rospack profile`

#### Copiar o código drive.py:

`cp ~/auto_drive/src/drive.py ~/workspace/auto_drive/src`

#### Mudar o permissionamento:

`chmod +x ~/workspace/auto_drive/src/drive.py`

#### Executar:

`rosrun auto_drive drive`
