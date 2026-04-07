<!DOCTYPE html>
<html lang="es">

<body>

<header>
    <h1>🏥 Sistema de Agendamiento de Citas Médicas (SACM)</h1>
    <p>Proyecto de Análisis y Diseño de Sistemas</p>
</header>

<section>
    <h2>📌 Descripción</h2>
    <p>
        El SACM es un sistema diseñado para optimizar la gestión de citas médicas,
        permitiendo organizar la interacción entre pacientes, médicos y personal administrativo.
    </p>
</section>

<section>
    <h2>🎯 Problemática</h2>
    <ul>
        <li>❌ Duplicidad de citas</li>
        <li>❌ Procesos manuales</li>
        <li>❌ Falta de control de horarios</li>
        <li>❌ Dificultad para generar reportes</li>
    </ul>
</section>

<section>
    <h2>💡 Solución</h2>
    <ul>
        <li>✔ Agendamiento en línea</li>
        <li>✔ Disponibilidad en tiempo real</li>
        <li>✔ Notificaciones automáticas</li>
        <li>✔ Generación de reportes</li>
    </ul>
</section>

<section>
    <h2>🧩 Módulos del Sistema</h2>
    <ul>
        <li>👤 Usuarios</li>
        <li>🧑 Pacientes</li>
        <li>🧑‍⚕️ Médicos</li>
        <li>📅 Citas</li>
        <li>⏰ Disponibilidad</li>
        <li>📊 Reportes</li>
    </ul>
</section>

<section>
    <h2>⚙️ Tecnologías</h2>
    <span class="badge">MySQL</span>
    <span class="badge">UML</span>
    <span class="badge">SQL</span>
    <span class="badge">Workbench</span>
</section>

<section>
    <h2>📊 Ejemplo de Consulta SQL</h2>
    <pre>
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
</section>

<section>
    <h2>👥 Equipo</h2>
    <ul>
        <li>Yorbis Blanco</li>
        <li>Wellington Méndez</li>
        <li>Jeffersson Rodríguez</li>
        <li>Hector B. Báez</li>
        <li>Roldyn Espinal</li>
    </ul>
</section>

<section>
    <h2>📌 Estado del Proyecto</h2>
    <p><strong>En desarrollo académico</strong></p>
</section>

<footer>
    <p>© 2026 SACM - Proyecto Académico</p>
</footer>

</body>
</html>
