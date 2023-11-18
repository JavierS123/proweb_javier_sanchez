# proweb_javier_sanchez
Evaluación Nro. 1 Programación Web.    

- Crear tres branchs: main, staging, develop     


Primero abrimos la terminal, clonamos el repositorio creado en github y accedemos a la carpeta creada con el nombre del repositorio.     

---

![step-1-image](/step1.png)

---

Con el comando git branch se ve la lista de branchs actuales, por predeterminado se crea la branch "main".   
Para crear branchs adicionales se usa el comando git branch nombre_branch    


---
Usamos el comando git branch seguido del nombre de la branch a crear.   
Ejemplo: git branch staging || git branch develop   
![step-2-image](/step2.png)   

---

Estas ramas estarán creadas en local en nuestro dispositivo, pero no aparecerán en el repositorio de github online.   
Para esto, usamos el comando git switch seguido del nombre de la branch creada para cambiar a esta branch.   
Al cambiar de branch, hacemos git push origin nombre_branch para que se sincronice con el repositorio online.

---

Ejemplo: git swich staging || git branch develop
Ejemplo: git push origin staging || git push origin develop   
![step-3-image](/step3.png)
---

Ya con esto están creadas y sincronizadas las tres branchs solicitadas