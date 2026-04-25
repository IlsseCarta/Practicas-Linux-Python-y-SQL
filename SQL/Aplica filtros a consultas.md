## 🗄️ SQL Lab: Aplicar filtros a consultas SQL

### 📌 Overview  
En esta práctica se utilizaron consultas SQL para investigar un posible incidente de seguridad, analizando intentos de inicio de sesión y datos de empleados mediante el uso de filtros.

El objetivo fue identificar actividades sospechosas y obtener información relevante para la toma de decisiones en un contexto de ciberseguridad.

---

### 🎯 Objetivos  
- Filtrar intentos de inicio de sesión fallidos  
- Analizar actividad fuera del horario laboral  
- Consultar registros por fechas específicas  
- Identificar accesos fuera de una ubicación  
- Filtrar empleados por departamento y ubicación  

---

### 🧪 Consultas realizadas  

#### 🔹 1. Intentos de inicio de sesión fallidos fuera del horario laboral  

`
SELECT *
FROM log_in_attempts
WHERE success = 0
AND login_time > '18:00:00'`;

-----

Revisa el archivo aquí 🔗: https://drive.google.com/file/d/1kRKgQGhOU0r_oVQu6hxCEsyQb8Xl5oNU/view?usp=drive_link
