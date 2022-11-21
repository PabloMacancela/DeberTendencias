# DeberTendencias

1.Crear una cuenta en Docker Hub
![image](https://user-images.githubusercontent.com/91167307/202941458-0c1a146a-114c-4d2d-b28b-3c4768a86e2a.png)

2.Entrar al Play with Docker y añadir una nueva instancia 
![image](https://user-images.githubusercontent.com/91167307/202942247-9943471a-31d8-43b7-91af-0671aad69e0c.png)

3.En la consola añadir el contenedor utilizando el comando "docker run --name serverweb -p 80:80 -d nginx" 
![image](https://user-images.githubusercontent.com/91167307/202942796-f4094d8e-b293-43f2-b058-6f4514c2298e.png)

4.Utiliza el comando "docker ps" y revisa si el contenedor esta corriendo
![image](https://user-images.githubusercontent.com/91167307/202942931-398705ef-4555-49de-9557-be741e9d900a.png)

5.Obtener un archivo html desde un repositorio en github con el comando "wget" 
![image](https://user-images.githubusercontent.com/91167307/202943258-6eacd646-06e8-47e7-a928-8f87bc0bea78.png)

6.Duplicar el repositorio con el comando "git clone"
![image](https://user-images.githubusercontent.com/91167307/202943417-a43528f0-0c2d-4707-b56f-544c0de4bc8a.png)

7. Ingresa al directorio con el comando "cd"
![image](https://user-images.githubusercontent.com/91167307/202943542-6e032200-60f7-4103-ad03-34121b33396b.png)

8.Comprobar con el comando "ls"
![image](https://user-images.githubusercontent.com/91167307/202943689-73d9621a-c790-418c-b2f8-ffba736f1726.png)

9.Extraer el el archivo con el comando "docker cp index2.html serverweb/usr/share/nginx/html/index2.html"
![image](https://user-images.githubusercontent.com/91167307/202943960-d0df1cdf-eee6-45d1-8cea-712858bff757.png)

10.Ingresar a OPEN PORT y agregar el puerto "80"
![image](https://user-images.githubusercontent.com/91167307/202944077-48ff1088-2adb-4a97-8fd8-10c24185fa53.png)

11.Se agrega al final "index2.html" y se observa que la página web se cargo correctamente
![image](https://user-images.githubusercontent.com/91167307/202944297-ee7ffc27-4a88-4b53-9db5-9b26c2d737e0.png)
