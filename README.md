<div style="background-color:#f5f5f5; padding:20px; border-radius:10px; color:#000; font-family:Arial;">

<h1>🏥 Sistema de Agendamiento de Citas Médicas (SACM)</h1>
<p><strong>Proyecto de Análisis y Diseño de Sistemas</strong></p>

<p>
<img src="https://img.shields.io/badge/Estado-En%20Desarrollo-yellow" />
<img src="https://img.shields.io/badge/Tipo-Académico-blue" />
<img src="https://img.shields.io/badge/Base%20de%20Datos-MySQL-orange" />
<img src="https://img.shields.io/badge/Modelado-UML-green" />
<img src="https://img.shields.io/badge/Lenguaje-SQL-lightgrey" />
<img src="https://img.shields.io/badge/Version-1.0-brightgreen" />
</p>

<hr>

<h2>📌 Descripción</h2>
<p>
El SACM es un sistema diseñado para optimizar la gestión de citas médicas,
permitiendo organizar la interacción entre pacientes, médicos y personal administrativo.
</p>

<h2>🎯 Problemática</h2>
<ul>
<li>❌ Duplicidad de citas</li>
<li>❌ Procesos manuales</li>
<li>❌ Falta de control de horarios</li>
<li>❌ Dificultad para generar reportes</li>
</ul>

<h2>💡 Solución</h2>
<ul>
<li>✔ Agendamiento en línea</li>
<li>✔ Disponibilidad en tiempo real</li>
<li>✔ Notificaciones automáticas</li>
<li>✔ Generación de reportes</li>
</ul>

<h2>🧩 Módulos del Sistema</h2>
<ul>
<li>👤 Usuarios</li>
<li>🧑 Pacientes</li>
<li>🧑‍⚕️ Médicos</li>
<li>📅 Citas</li>
<li>⏰ Disponibilidad</li>
<li>📊 Reportes</li>
</ul>

<h2>⚙️ Tecnologías</h2>
<p>
<span style="background:#ddd; padding:5px 10px; border-radius:5px;">MySQL</span>
<span style="background:#ddd; padding:5px 10px; border-radius:5px;">UML</span>
<span style="background:#ddd; padding:5px 10px; border-radius:5px;">SQL</span>
<span style="background:#ddd; padding:5px 10px; border-radius:5px;">Workbench</span>
</p>

<h2>📊 Ejemplo de Consulta SQL</h2>

<pre style="background:#eaeaea; padding:15px; border-radius:8px;">
SELECT 
c.id_cita,
p.nombre AS paciente,
m.nombre AS medico,
c.fecha,
c.hora
FROM Cita c
JOIN Paciente p ON c.id_paciente = p.id_paciente
JOIN Medico m ON c.id_medico = m.id_medico;
</pre>

<h2>👥 Equipo</h2>
<ul>
<li>Yorbis Blanco</li>
<li>Wellington Méndez</li>
<li>Jeffersson Rodríguez</li>
<li>Hector B. Báez</li>
<li>Roldyn Espinal</li>
</ul>

<h2>📌 Estado del Proyecto</h2>
<p><strong>En desarrollo académico</strong></p>

<hr>

<p style="text-align:center;">© 2026 SACM - Proyecto Académico</p>

</div>
