# Beta dataset

* Frequências estimuladas : **8.0, 8.2, ..., 15.6, 15.8** ( 40 targets)
* Passa faixa : **~6Hz ~16Hz**
* Compute_psd : **7-17 Hz (sugestão )**
* Data shape : **160[40 targets x 4 trials ] ,64 [ channels ] ,750 [ 3s * 250Hz ]**
* Desses eletrodos, esses são os melhores : **P, PO, e O** 

O objeto EpochsArray tem o método drop_channels que pode ser usada para remover os canais que não evocam SSVEP.

Faixa de 0.1 Hz
7.9 ~ 8.1  } Verificar se todos possuem a mesma quantidade de valores
8.1 ~ 8.3  } e após, transformar em np.array ( para não dar o mesmo problema do outro dataset)
