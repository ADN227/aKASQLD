# Consultar una Base de Datos SQL en Azure
![](https://akncus.blob.core.windows.net/git/8/K_109.jpg)
Recordar que para poder usar los recursos de Azure es necesario tener una cuenta de Azure y usa suscripción de Azure.

Es necesario crear dos recursos en Azure:
- SQL Server
- Base de Datos SQL

Una forma de hacer esto es usando un script desde ```Cloud Shell```, en este caso utilizando el repositorio de [Microsoft Learning](https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals).

    git clone https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals dp-900 
    cd dp-900/sql 
    bash setup.sh

Dentro de los mensajes del script se muestra información sobre los recursos que se crearon en Azure.
![](https://akncus.blob.core.windows.net/git/8/K_099.jpg)

Una vez creados los recursos, podemos ver los recursos dentro del grupo de recursos que se indica en los mensajes del script como **resourceGroup** en Cloud Shell.
![](https://akncus.blob.core.windows.net/git/8/K_100.jpg)

Dentro de la base de datos SQL, en la sección **Redes** necesitamos agregar una una dirección IP en la sección ```Reglas de firewall``` para que podamos acceder a la base de datos.
![](https://akncus.blob.core.windows.net/git/8/K_101.jpg)

En el **Editor de consultas**, podemos acceder a la base de datos SQL la información que proporciona el script como ```User``` y ```Password```.
![](https://akncus.blob.core.windows.net/git/8/K_102.jpg)

Dentro de la base de datos SQL, podemos acceder a las Tablas que se crearon en el script. Al selleccionar una tabla, podemos trabajar con la tabla dentro del editor.
![](https://akncus.blob.core.windows.net/git/8/K_104.jpg)
