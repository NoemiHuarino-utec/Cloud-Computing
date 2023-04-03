
## Dirección IP
Significa Internet Protocolo. Es aquella que busca identificar un dispositivo a traves de una red.
- Cuenta con 8 bits que puede ir en un rago de: [0, 255]

Colocando `ipconfig` en la consola **CDM** puedes ver la ip actual. De la siguiente manera:

```ruby 
C:\Users\usuario>ipconfig
```

## Modelos de precio - Máquina virtual en AWS

La máquina virtual es un pago por uso, es decir, solo pagas por el tiempo que lo usas.

La máquina virtual te cobra:
* **Compute**: CPU, Menmoria RAM --> [Simulación de Precio Compute](https://aws.amazon.com/es/ec2/pricing/on-demand/)
* **Storage**: Es el almacenamiento, te cobran por el almacenamiento que quieras tener y usar.
* **Data Out**: Todo lo que sale de AWS al mundo es la Data Out (Tranferencia de Datos Salientes). Mientras más datos salgan, incrementan el precio.

  Recuera👀: 
  La transferencia de datos es el volumen de datos que genera nuestra página debido a los visitantes y sus interacciones con los elementos de la misma.
