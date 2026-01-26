# Pruebas-de-aplicaciones-web
Ejecución de pruebas funcionales y de UI para identificar errores críticos y generar reportes en Jira
## 🎯 Objetivo
Analizar y asegurar que los endpoints admitan los nuevos requisitos
## 🛠️ Tecnologías utilizadas
-Excel (Registro de pruebas y resultados)
- Postman (colección de pruebas)
- JIRA (Registro y seguimiento de errores)

## 🔍 Casos de prueba ejecutados
- CP01: Verificar que el usuario pueda añadir un producto existente a un kit.
- CP02: Verificar que el usuario no pueda añadir un producto existente a un kit inexistente.
- CP03: Verificar que el usuario no pueda añadir un producto existente sin un kit.
La documentación completa de los casos de prueba, resultados y reportes se encuentra en el archivo:
- [casos_prueba.xlsx](casos_prueba.xlsx)
## 📊 Resultados
![Captura de pruebas](docs/evidencia.png)

## 🧠 Aprendizajes
- Identifiqué errores que se pueden estar ocasionándose por no usar
- Practiqué validación de status codes y tiempos de respuesta.

## 🚀 Próximos pasos
- Integrar pruebas en CI/CD con GitHub Actions.
- Añadir validaciones de payload más complejas.
  
