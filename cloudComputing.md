<h1 align="center"> cloudComputing </h1>

Documentación oficial NIST

## Aspectos escenciales para los proveedores de servicios

1. **On-demand self-service:** Servicios bajo demanda, que el usuario puda iniciar servicios.
2. **Broad network acces** Acceder desde cualquier lugar.
3. **Resource pooling** modelo de compartición de servidores del proveedor(Aislamiento modelo multi tena).
4. **Rapid elasticity** Escalabilidad de forma automática y facil.
5. **Measured service** Capcidad de reportar el recurso(reportar a los usuarios de actualizaciones o mantenimientos).


## MOdelos de despliegue

1. **Publico** No importa el fin(empresas, freelancer, ...), podemos acceder desde nuestro navegador -> ejemplos: aws, azure, google
2. **Hibrido** Conexión de publico y privado.
3. **Privado** Dentro de tu datacenter fisico tienes una porcion de la nube, solo puede ser accesible por la empresa -> ejemplos: aws Outpost, Azure stack, anthos

> **Multi nube** Empresas que usan varios proveedores cloud *No es un modelo de despliegue*


## Modelos de servicio en la nube ~ Pizza como servicio

1. **Tradicional** ~ Pizza Hecho en casa -> te encargas de todo *NO es considerado como un modelo pero es la base de todo*, te haces responsable del local(espacio, electricidad, ...)
2. **IaaS(Infraestructura como servicio)** ~ Cocina como servicio -> el proveedor se encarga de cocina, gas, horno, electricidad; los ingredientes, hacer la base y el hacer la pizza nosotros nos encargamos. *Hospedar*
3. **PaaS(Plataforma como servicio)** ~ Recoger y hornear -> el proveedor hace la infraestructura y la base de la pizza; nosotros solo horneamos. *CONSTRUIR*
4. **SaaS(Software como servicio)** ~ Delivery -> todo lo hace el proveedor; tu solo disfrutas. *CONSUMIR*

![PizaaaS](https://github.com/jhonPariona/Aws/blob/main/assets/Screenshot_20210703_115244.png?raw=true)
![swaas](https://github.com/jhonPariona/Aws/blob/main/assets/sw.png?raw=true)
