
# 🧪 Checklist de Pruebas de Login

Repositorio con casos de prueba manuales para validar formularios de autenticación. Diseñado para perfiles junior que deseen practicar QA funcional con documentación clara y estructura modular.

![Status](https://img.shields.io/badge/estado-en%20desarrollo-yellow)
![License](https://img.shields.io/badge/licencia-MIT-blue)
![Testing](https://img.shields.io/badge/testing-manual-critical)


## 🎯 Objetivo

Este proyecto tiene como finalidad documentar y ejecutar pruebas manuales de formularios de inicio de sesión. Se incluyen escenarios comunes como:

- Verificación de campos obligatorios.
- Contraseñas mal ingresadas.
- Flujo de recuperación de contraseña.

---

## 📁 Estructura del Repositorio



## 📁 Estructura del Repositorio

login-test-checklist/ ├── README.md ├── test-cases/ │ ├── campo-obligatorio.md │ ├── contraseñas-inválidas.md │ ├── recuperación-contraseña.md │ └── tabla-resumen.xlsx ├── assets/ │ └── capturas/ │ ├── caso1.png │ ├── caso2.png │ └── caso3.png ├── docs/ │ └── instrucciones-prueba.html ├── .github/ │ └── ISSUE_TEMPLATE/ │ └── reporte-de-error.md ├── .gitignore ├── .gitattributes └── LICENSE

## 📝 Casos de Prueba

Los archivos `.md` dentro de `test-cases/` contienen la documentación detallada:

- **Campo Obligatorio:** Verifica que no se pueda enviar el formulario vacío.
- **Contraseña Inválida:** Evalúa el mensaje ante error de autenticación.
- **Recuperación de Contraseña:** Comprueba funcionalidad del link de recuperación.

Además, la tabla resumen (`.xlsx`) consolida todos los escenarios, priorizaciones y resultados.


## 🖼️ Capturas de Pantalla

Se incluyen imágenes reales de cada prueba en ejecución, disponibles en `assets/capturas/`.

## 🔧 Formulario de Prueba

Se provee un archivo HTML básico (`docs/instrucciones-prueba.html`) para simular el entorno de login desde navegador y ejecutar los escenarios manualmente.


## 🐞 Reporte de Errores

El template ubicado en `.github/ISSUE_TEMPLATE/reporte-de-error.md` permite registrar bugs detectados durante las pruebas, con formato estandarizado.


## 🌐 Topics

`qa-manual`, `login-testing`, `form-validation`, `html-form`, `documentation`, `junior-qa`, `accessibility`, `bug-report-template`


## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Podés consultarla en el archivo `LICENSE`.

## 🤝 Contribuciones

¡Bienvenidas! Si querés sumar casos o mejoras, seguí la plantilla de errores y buenas prácticas del repositorio. Se recomienda mantener formato uniforme y claridad en la documentación.

## 🧭 Próximos Pasos

- Versión bilingüe (`README.en.md`).
- Validación accesible con ARIA roles y navegación por teclado.
- Integración con GitHub Pages para mostrar el formulario online.

Este repositorio busca demostrar que el testing manual puede ser claro, accesible y profesional desde la base.  
¡Gracias por visitar!
