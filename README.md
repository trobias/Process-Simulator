# Process-Simulator

### Simulador de Gestión de Procesos y Memoria en Sistemas Operativos 🚀  

Este proyecto es un simulador interactivo que emula la gestión de procesos y memoria en un sistema operativo sin memoria virtual. Fue desarrollado para explorar conceptos clave como la asignación de memoria, el ciclo de vida de los procesos y la gestión de recursos compartidos, con una interfaz gráfica intuitiva basada en **Tkinter**.  

---
![image](https://github.com/user-attachments/assets/d5fa807b-74f4-41c1-a522-e2469cbb7873)

### **Características principales 🛠️**  

1. **Gestión de memoria dinámica**  
   - Selección de algoritmos de asignación:  
     - *First-Fit*: Encuentra el primer bloque libre adecuado.  
     - *Best-Fit*: Selecciona el bloque más pequeño que cumpla con los requisitos.  
     - *Worst-Fit*: Utiliza el bloque más grande disponible.  
   - **Memoria swap**: Los procesos se transfieren dinámicamente entre memoria principal y secundaria cuando la RAM alcanza su capacidad.  

2. **Simulación del ciclo de vida de los procesos**  
   - Estados representados: *Nuevo*, *Listo*, *Ejecutando*, *Bloqueado* y *Terminado*.  
   - Cambios de estado automáticos y aleatorios, con visualización en tiempo real.  

3. **Visualización gráfica en tiempo real 📊**  
   - Estado actual de la memoria principal y secundaria, mostrando bloques ocupados y libres.  
   - Procesos representados por su *PID* y su estado actual.  
   - Estadísticas de memoria utilizada y disponible.  

4. **Gestión de recursos con semáforos 🔒**  
   - Simulación de exclusión mutua utilizando semáforos binarios.  
   - Control de acceso seguro a recursos compartidos.  

5. **Compactación de memoria 🧹**  
   - Reorganiza los bloques de memoria para reducir la fragmentación y optimizar el uso del espacio.  

---

### **Opciones configurables ⚙️**  
- Algoritmos de asignación de memoria: *First-Fit*, *Best-Fit*, *Worst-Fit*.  
- Método de gestión: *Paginación dinámica* o *Compactación*.  
- Tamaño y recursos de los procesos (asignados de forma aleatoria).  

---

### **Requisitos de instalación 🔧**  
- **Python 3.x**  
- **Tkinter** (generalmente incluido con Python).  

---

### **Ejecución 💻**  
1. Clona este repositorio:  
   ```bash  
   git clone <URL-del-repositorio>  
   cd <nombre-del-repositorio>  
   ```  
2. Ejecuta el simulador:  
   ```bash  
   python simulador.py  
   ```  

---

### **Propósito educativo 🎓**  
Este simulador fue desarrollado como parte del trabajo práctico integrador de la materia **Sistemas Operativos II** en la carrera de **Ingeniería en Sistemas de Información**. Su objetivo es ofrecer una herramienta práctica para visualizar y analizar conceptos fundamentales de los sistemas operativos, como la asignación de memoria y la gestión de procesos.  

---

¡Contribuciones y sugerencias son bienvenidas! 😊  
