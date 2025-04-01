# 💻 Diseño de Software - CU Iniciar Sesión

Este proyecto implementa el **Caso de Uso "Iniciar Sesión"** como parte de un sistema más amplio, siguiendo una arquitectura modular basada en el modelo 4+1. El proyecto está dividido en tres módulos:

- `dto_negocios`: Define objetos de transferencia de datos (DTOs).
- `negocios_controlSesion`: Subsistema de negocio (mock) que valida el inicio de sesión.
- `presentacion_iniciarSesion`: Interfaz gráfica con Swing que permite al usuario iniciar sesión.

---

## 🧱 Estructura del proyecto

```
CU_IniciarSesion/
├── dto_negocios/               # Proyecto DTO
├── negocios_controlSesion/     # Subsistema de negocio (mock)
├── presentacion_iniciarSesion/ # Interfaz gráfica (Swing)
│   └── lib/
│       ├── dto_negocios.jar
│       └── negocios_controlSesion.jar
├── .gitignore
└── README.md
```

---

## 🚀 Requisitos

- Java JDK 8 o superior
- NetBeans (recomendado para abrir los 3 proyectos fácilmente)

---

## 📦 Cómo abrir el proyecto

1. Clona el repositorio:

   ```bash
   git clone https://github.com/CharlyCastrejon/DS_CU_IniciarSesion.git
   ```

2. Abre **NetBeans**.

3. Selecciona **Archivo > Abrir proyecto** y abre los siguientes tres proyectos:
   - `dto_negocios`
   - `negocios_controlSesion`
   - `presentacion_iniciarSesion`

4. Asegúrate de que en el proyecto `presentacion_iniciarSesion`:
   - Están configuradas las bibliotecas (`lib/dto_negocios.jar` y `lib/negocios_controlSesion.jar`)
   - Puedes correr la clase `InicioSesion.java` como clase principal

---

## 🎨 Interfaz Gráfica

- Interfaz hecha con **Java Swing**
- Campos: Tipo de Usuario, Usuario, Contraseña
- Mensajes visuales con `JOptionPane`

---

## ✅ Estado

✅ Funcional y listo para pruebas del CU Iniciar Sesión  
📦 Modular y preparado para integración con objetos reales e infraestructura futura

---

## 👤 Autor

Carlos A. Ruiz Castrejón  
Proyecto académico como ejemplo para el desarrollo de presentación y subsistemas nivel 1

