# Como crear un Recurso de Azure con una plantilla
En este repositorio tenemos una demostración del uso de una plantilla de Azure, más concretamente, la implementación de una cuenta de almacenamiento.

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com).
- Un dispositivo, por ejemplo una computadora.
- Acceso a internet.
- Navegador de internet como Google Chrome, Opera, Mozilla Firefox, etc.
- Editor de texto, como [Visual Studio Code](https://code.visualstudio.com) 

---

## Importante
- Esta es otra forma de implementar recursos en Azure.
- Es necesario tener creado ya previamente un grupo de recursos.

---

## Archivos
El **azuredeploy.json** tiene la plantilla de implementación de una cuenta de almacenamiento en Azure.
El **README.md** tiene las instrucciones.

---

## Pasos a seguir
- Para poder crear un recurso es importante tener ya creado un grupo de recursos, para poder guardar nuestro recurso.
- Ahora crearemos un archivo en nuestro editor de texto, llamado "azuredeploy.json", igual que el que se encuentra en este repositorio.
- El que se encuentra en este repositorio, lo que hace es implementar una cuenta de almacenamiento.
- Ahora abrimos un "cmd" dentro de la carpeta donde tenemos el archivo **azuredeploy.json**.
![P1](https://github.com/DagonNR/Plantilla-ARM-Azure/blob/main/images/P1.PNG)

- Y escribimos "az deployment group create --name aqui-ponemos-un-nombre-a-la-plantilla --resource-group aqui ponemos el nombre de nuestro grupo --template-file azuredeploy.json" (ponerlo sin las "").
![P2](https://github.com/DagonNR/Plantilla-ARM-Azure/blob/main/images/P2.PNG)

- Ahora verificamos que la implementación, se haya realizado de manera correcta.
