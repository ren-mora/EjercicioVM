<img width="720" height="292" alt="image" src="https://github.com/user-attachments/assets/6183437b-6791-494d-b17e-10f01f132c1d" />

Ante la decisión de cómo se comunicará la máquina virtual con el mundo exterior, de los varios modos que ofrece VirtualBox opté por elegir el de Red Interna (Internal Network). De este modo,la VM no tiene acceso a Internet ni a mi computadora Host. Solo puede hablar con otras máquinas virtuales que estén configuradas en la misma "Red Interna". Esto la hace el entorno más seguro, siendo ideal para hacer pruebas de ataques controlados o análisis de malware peligroso. 

La razón para no elegir el modo de Adaptador Puente (Bridged) es que hace que la VM se conecte directamente al router de mi casa, como si fuera un dispositivo físico más, haciendo a la VM visible para todos en mi red. Por lo que un atacante en internet podría encontrarla y al ser de mis primeros laboratorios, opté por no usar este mismo.

<img width="916" height="385" alt="image" src="https://github.com/user-attachments/assets/1671390e-71e7-4248-b082-3f85c3d5f3e6" />
