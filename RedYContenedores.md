1.Crear un contenedor nuev
![image](https://user-images.githubusercontent.com/91167307/202954548-e3818402-c3cd-4912-8f20-4c77d47dff8f.png)

2. Crearlo para Postgrestql y su puerto 
![image](https://user-images.githubusercontent.com/91167307/202954673-5d1a59ee-be35-436c-b430-8ac0bab22a2d.png)

3.Introducir el comando  (docker run -d --name dbpsql -e POSTGRES_PASSWORD=admin -p 5432:5432 postgres)
![image](https://user-images.githubusercontent.com/91167307/202957772-1432023c-ef50-4845-9424-8a04678815f1.png)

4.Crear la red con el comando "docker network create --attachable" y agregar el nombre de la Red
![image](https://user-images.githubusercontent.com/91167307/202958679-394c26cb-a2be-438a-b23e-b90debbb3b61.png)

5.Conectar con la red creada con el codigo docker network connect redPabloMacancela postgresql
![image](https://user-images.githubusercontent.com/91167307/202959712-8775f947-d566-441b-9507-cb16d542fe8b.png)

6. Por ultimo  se revisa que la red funciona con el codigo "inspect"
![image](https://user-images.githubusercontent.com/91167307/202960028-7c8d8f98-ffe2-4483-bf01-8fb5f362d64c.png)
![image](https://user-images.githubusercontent.com/91167307/202960152-83c8ba0b-f0d8-4173-a789-67a2fa340427.png)

