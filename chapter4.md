## 4.7 Software Object-Oriented Design
### 4.7.1. Class Diagrams.
<p align="center">
<img src="/assets/diagrama de clases open.png">
</p>

### 4.7.2.Class Dictionary
En esta sección se mostrará el diccionario de las clases, usado para el desarrollo de nuestra app.<br>
__Account__: Clase que contiene los atributos de la cuenta como nombre de usuario, contraseña y rol.<br>
__Professional__: Clase que contiene los atributos de los profesionales como nombre, apellido y correo electrónico.<br>
__Patient__: Clase que contiene los atributos de los pacientes como nombre, apellido, correo y vínculo a la historia clínica.<br>
__ClinicalHistory__: Clase que contiene los antecedentes médicos, síntomas y motivo de consulta de un paciente.<br>
__Diagnostic__: Clase que contiene los diagnósticos médicos vinculados a una historia clínica.<br>
__Session__: Clase que contiene los atributos de las sesiones médicas, incluyendo fecha, profesional, paciente y nota.<br>
__Note__: Clase que contiene las notas clínicas de cada sesión, describiendo síntomas y observaciones.<br>
__Treatment__: Clase que contiene los tratamientos asignados a los pacientes, con nombre, descripción e intervalo de tiempo.<br>
__Medication_-: Clase que contiene los medicamentos prescritos a los pacientes, su dosificación y duración del tratamiento.<br>
__Prescription__: Clase que contiene una receta que agrupa múltiples medicamentos para un paciente.<br>
__MedicalPrescription__: Clase que contiene las prescripciones médicas asociadas a un paciente y a un profesional.<br>
__Speciality__: Clase que contiene la especialidad de los profesionales, como psiquiatría o psicología clínica.<br>
__PatientMood__: Clase que contiene los registros de estado de ánimo de los pacientes.<br>
__BiologicalFunction__: Clase que contiene los registros de funciones biológicas del paciente como hambre, hidratación, sueño y energía.<br>
__Task__: Clase que contiene las tareas asignadas a los pacientes, su estado y fechas de creación y actualización.<br>
__PatientNotification__: Clase que contiene las notificaciones no vistas por el paciente.<br>
__PatientMoodAnalytic__: Clase que contiene el análisis mensual del estado de ánimo del paciente.<br>
__PatientBiologicalAnalytic__: Clase que contiene el análisis mensual de las funciones biológicas del paciente.<br>
### 4.8. Database Design
### 4.8.1 Database Diagram
<p align="center">
<img src="/assets/base de datos .png">
</p>
