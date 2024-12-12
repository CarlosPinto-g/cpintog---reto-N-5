### Reto N°5

###### 1- Dado la figura de la imagen, desarolle: 

[![tareita.png](https://i.postimg.cc/Pxm8MRmy/tareita.png)](https://postimg.cc/Kk8zGQp3)

- Una función matemática para calcular el volumen y el área superficial.

- Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado r1, r2 y h.

- Revise como utilizar el valor de pi usando import math y math.pi

### Desarrollo:

-  Desarrollar una función matemática para calcular el volumen y el área superficial.

```pseudocode
  instrucciones

import math

def calcular_cono(r2, h):
    volumen = (1/3) * math.pi * (r2 ** 2) * h
    area = math.pi * r2 * (r2 + math.sqrt((r2 ** 2) + (h ** 2)))
    return volumen, area


volumen, area = calcular_cono(3, 4)
print(f"Volumen: {volumen:.2f}")
print(f"Área: {area:.2f}")

```

[![Imagen-A-del-reto-N5.png](https://i.postimg.cc/nrxV8N2P/Imagen-A-del-reto-N5.png)](https://postimg.cc/1nW1wCLG)


------------


- Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado r1, r2 y h.


```pseudocode
  instrucciones
  
import math

def volumen_cono(r2, h):
    return (1/3) * math.pi * (r2 ** 2) * h

def area_superficial_cono(r2, h):
    return math.pi * r2 * (r2 + math.sqrt((r2 ** 2) + (h ** 2)))


r1 = float(input("Ingrese el radio de la esfera (r1): "))
r2 = float(input("Ingrese el radio del cono (r2): "))
h = float(input("Ingrese la altura del cono (h): "))


volumen = volumen_cono(r2, h)
area = area_superficial_cono(r2, h)

print(f"Volumen: {volumen:.2f}")
print(f"Área superficial: {area:.2f}")

```

[![Imagen-B-del-reto-N5.png](https://i.postimg.cc/x18zFbcb/Imagen-B-del-reto-N5.png)](https://postimg.cc/21py1ydz)

###### ⬆️ como pueden ver, al correr el programa, nos pide que ingresemos valores, r1, r2 y h.

------------


- Revise como utilizar el valor de pi usando import math y math.pi


```pseudocode
  instrucciones
  
  import math

def calcular_con_pi(valor):
    return valor * math.pi

numero = float(input("Ingresa un número para multiplicar por pi: "))
resultado = calcular_con_pi(numero)
print("Resultado:", resultado)

```
[![Imagen-C-del-reto-N5.png](https://i.postimg.cc/rszvdJf9/Imagen-C-del-reto-N5.png)](https://postimg.cc/ctyD2QyK)

------------


### Parte N°2 del reto N°5:
1. 
1. Dado la figura de la imagen, desrrolle:

[![segunda-imagen-del-reto-N5.png](https://i.postimg.cc/Dyk9fqq1/segunda-imagen-del-reto-N5.png)](https://postimg.cc/NLDJp2C0)

- Una función matemática para calcular el área y el perimetro.
- Cree dos funciones en python para calcular los valores antes establecidos, al ingresar por teclado r, a y b.
- Revise como utilizar el valor de pi usando import math y math.pi

------------


1. Diseñe una función que calcule la cantidad de carne de aves en kilos si se tienen N gallinas, M gallos y K pollitos cada uno pesando 6 kilos, 7 kilos y 1 kilo respectivamente.

1.  Haga un programa que utilice una función para calcular el valor de un préstamo C usando interés compuesto del i por n meses.

1. Escriba un programa que pida 5 números reales y calcule las siguientes operaciones usando una función para cada una:

- El promedio
- El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
- La potencia del mayor número elevado al menor número
- La raíz cúbica del menor número

1. Consultar qué es y cómo funciona pip en python.

#### ¿ Qué es pip ?

###### Pip (acrónimo de “Python Installer Package”) es un sistema de gestión de paquetes para Python, utilizado para instalar, actualizar y eliminar paquetes de software de Python. Es una herramienta fundamental para cualquier desarrollador de Python, ya que facilita la gestión de dependencias y bibliotecas necesarias para proyectos Python.Pip (acrónimo de “Python Installer Package”) es un sistema de gestión de paquetes para Python, utilizado para instalar, actualizar y eliminar paquetes de software de Python. Es una herramienta fundamental para cualquier desarrollador de Python, ya que facilita la gestión de dependencias y bibliotecas necesarias para proyectos Python.Pip (acrónimo de “Python Installer Package”) es un sistema de gestión de paquetes para Python, utilizado para instalar, actualizar y eliminar paquetes de software de Python. Es una herramienta fundamental para cualquier desarrollador de Python, ya que facilita la gestión de dependencias y bibliotecas necesarias para proyectos Python.Pip (acrónimo de “Python Installer Package”) es un sistema de gestión de paquetes para Python, utilizado para instalar, actualizar y eliminar paquetes de software de Python. Es una herramienta fundamental para cualquier desarrollador de Python, ya que facilita la gestión de dependencias y bibliotecas necesarias para proyectos Python.

#### ¿ cómo funciona pip en Python ?

###### Pip se comunica con el índice de paquetes de Python (PyPI, Python Package Index), un repositorio centralizado que almacena miles de paquetes de software de Python. Cuando se instala un paquete con pip, este verifica la versión del paquete en PyPI y descarga la versión correspondiente. Luego, pip instala el paquete en el sistema y gestiona las dependencias necesarias para que el paquete funcione correctamente.Pip se comunica con el índice de paquetes de Python (PyPI, Python Package Index), un repositorio centralizado que almacena miles de paquetes de software de Python. Cuando se instala un paquete con pip, este verifica la versión del paquete en PyPI y descarga la versión correspondiente. Luego, pip instala el paquete en el sistema y gestiona las dependencias necesarias para que el paquete funcione correctamente.

Mas información:

https://youtu.be/QUtPsQ_uSD4?si=FhabPkZaws6PcziG

1. Hacer un listado de módulos populares para python que se puedan instalar com pip y consultar cómo instalarlos.

#### Módulos populares de Python con pipMódulos populares de Python con pip

##### Listado de módulos populares para Python que se pueden instalar con pip:Listado de módulos populares para Python que se pueden instalar con pip:

- **NumPy**: Biblioteca para computación numérica y análisis de datos. Instalar con: pip install numpy

- **Pandas**: Biblioteca para análisis y manipulación de datos en formato tabla. Instalar con: pip install pandas


- **Matplotlib**: Biblioteca para crear gráficos 2D y visualizar datos. Instalar con: pip install matplotlib

- **Scikit-Learn**: Biblioteca para aprendizaje automático y machine learning. Instalar con: pip install scikit-learn

- **TensorFlow**: Biblioteca para aprendizaje automático y deep learning, desarrollada por Google. Instalar con: pip install tensorflow

- **BeautifulSoup**: Biblioteca para web scraping y parsing de HTML y XML. Instalar con: pip install beautifulsoup4

- **Requests**: Biblioteca para hacer solicitudes HTTP y trabajar con APIs. Instalar con: pip install requests

- **Kivy**: Biblioteca para desarrollo de aplicaciones móviles y desktop con Python. Instalar con: pip install kivy

- **Scipy**: Biblioteca para ciencia computacional y análisis de datos. Instalar con: pip install scipy

- **Statsmodels**: Biblioteca para estadística y análisis de datos. Instalar con: pip install statsmodels

- **OpenCV**: Biblioteca para visión por computadora y procesamiento de imágenes. Instalar con: pip install opencv-python

- **Seaborn**: Biblioteca para visualización de datos y creación de gráficos. Instalar con: pip install seaborn

- **NLTK**: Biblioteca para procesamiento de lenguaje natural y análisis de texto. Instalar con: pip install nltk

- **Spacy**: Biblioteca para procesamiento de lenguaje natural y análisis de texto, con un enfoque en el procesamiento de lenguaje natural en tiempo real. Instalar con: pip install spacy

#### Cómo instalar módulos con pip:
1. Verificar la versión de pip ejecutando **pip --version**.

1. Instalar un módulo especificando su nombre, por ejemplo: **pip install numpy**.

1. Si deseas instalar una versión específica de un módulo, puedes especificarla después del nombre del módulo, por ejemplo:** pip install numpy==1.20.0.
**

1. Para instalar múltiples módulos al mismo tiempo, puedes separarlos con espacios, por ejemplo: **pip install numpy pandas matplotlib.**

1. Si deseas crear un archivo de requisitos** (requirements.txt) **para instalar múltiples módulos de una vez, puedes crear un archivo con la lista de módulos separados por líneas, por ejemplo:


```
numpy==1.20.0
pandas==1.3.5
matplotlib==3.5.1
```
Luego, ejecutar **pip install -r requirements.txt** para instalar todos los módulos listados en el archivo.
**
NOTA:**
###### Recuerda que, antes de instalar un módulo, asegúrate de tener Python y pip instalados correctamente en tu sistema.Recuerda que, antes de instalar un módulo, asegúrate de tener Python y pip instalados correctamente en tu sistema.

**Paginas de consulta:**
https://programminghistorian.org/es/lecciones/instalar-modulos-python-pip

https://docs.python.org/es/3/installing/index.html

https://geekflare.com/es/popular-python-libraries-modules/

https://www.freecodecamp.org/espanol/news/como-usar-pip-install-en-python/

https://medium.com/@diego.coder/m%C3%B3dulos-y-paquetes-en-python-ff0c391cedcd 



