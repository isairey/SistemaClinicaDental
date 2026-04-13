# 🦷 Sistema de Clínica Dental

<p align="center">
 
</p>

<p align="center">
  <strong>Sistema de gestión para clínicas dentales</strong>
</p>

<p align="center">
  Desarrollado para administrar pacientes, citas, tratamientos y expedientes clínicos
</p>

<p align="center">
  <a href="#características">Características</a> •
  <a href="#inicio-rápido">Inicio Rápido</a> •
  <a href="#instalación">Instalación</a> •
  <a href="#uso">Uso</a> •
  <a href="#estructura">Estructura</a> •
  <a href="#contribuir">Contribuir</a>
</p>

---

## 🏥 ¿Qué es este sistema?

Este sistema de clínica dental es una aplicación diseñada para ayudar a dentistas y consultorios a gestionar de manera eficiente:

- Pacientes
- Citas
- Tratamientos
- Historial clínico

Permite llevar un control digital completo, mejorando la organización y atención al paciente.

---

## ✨ Características

### 👨‍⚕️ Gestión de Pacientes
- Registro de pacientes
- Historial clínico
- Datos personales y de contacto
- Edición y eliminación de registros

### 📅 Gestión de Citas
- Agendar citas
- Calendario de consultas
- Control de asistencia
- Recordatorios

### 🦷 Tratamientos Dentales
- Registro de tratamientos
- Seguimiento por paciente
- Notas médicas

### 📄 Expedientes Clínicos
- Historial completo
- Diagnósticos
- Evolución del paciente

### 🔐 Usuarios
- Registro e inicio de sesión
- Roles (Administrador / Dentista / Asistente)
- Control de acceso

---

## 🚀 Inicio Rápido

```bash
# Clonar repositorio
git clone https://github.com/isairey/SistemaClinicaDental.git
cd clinica-dental

# Crear entorno virtual
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Migrar base de datos
python manage.py migrate

# Crear usuario administrador
python manage.py createsuperuser

# Ejecutar servidor
python manage.py runserver
