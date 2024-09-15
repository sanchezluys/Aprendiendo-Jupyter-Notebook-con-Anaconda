# 🎓 Aprendiendo Jupyter Notebook con Anaconda

**Guía para instalar y usar Jupyter Notebook con Anaconda y Python** 🐍  
_Tomado de:_ [Video tutorial](https://www.youtube.com/watch?v=AlgyR1txA3Y) 🎥

---

## 🚀 Instalando Anaconda

1. 🌐 Dirígete a [Anaconda.com](https://www.anaconda.com/) y descarga el instalador.
2. ✉️ Ingresa tu correo para recibir el enlace de descarga.
3. ✅ El instalador es compatible con Windows, Linux y macOS.

⚠️ **Nota:** Se recomienda ejecutar el instalador como administrador para evitar problemas. La primera vez que abras Anaconda puede tardar unos minutos.

Una vez instalado, verás la pantalla del **Anaconda Navigator**. Si se recomienda alguna actualización, asegúrate de aplicarla. ⚙️

![alt jupy_0](/img/imagen.png)

---

## 🌱 Creando un Entorno Virtual (Environments)

1. 🔧 Es recomendable crear un entorno específico para trabajar con Jupyter Notebook.
2. En la pestaña de **Environments**, crea un nuevo entorno para aislar tus proyectos.

![alt jupy_13](/img/imagen-13.png)

3. 🚀 Activa el entorno y desde la pestaña de **Home**, lanza Jupyter Notebook.

---

## 🛠️ Resolviendo Problemas Comunes

1. 💥 Si encuentras algún error al lanzar Jupyter, intenta reiniciarlo como administrador.
2. Si Jupyter no abre desde el **Launch** en Anaconda, prueba ejecutarlo desde la consola:

    ```bash
    jupyter notebook
    ```

3. Una vez iniciado el servidor, abre el enlace que contiene el **token** indicado en la consola para acceder a Jupyter desde tu navegador. 🌐

---

## 📓 Creando y Usando un Nuevo Notebook

1. Crea un nuevo notebook y comienza a programar en Python. 👩‍💻👨‍💻
2. Si al intentar importar alguna librería te aparece un error, puedes instalarla desde la consola con:

    ```bash
    pip install pandas
    ```

3. También puedes instalar librerías directamente en el notebook utilizando:

    ```python
    !pip install pandas
    ```

4. 💾 Cuando termines tu trabajo, puedes descargar tu notebook en formatos como Python, HTML, entre otros.

![alt jupy_22](/img/imagen-22.png)

---

🎉 ¡Y eso es todo! Ahora ya sabes cómo instalar y usar Jupyter Notebook con Anaconda. ¡Feliz aprendizaje! 📚✨
