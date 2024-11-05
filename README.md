

<h1>🍪 Mango.Services.CouponAPI</h1>

<p>Este proyecto es parte de la plataforma Mango y proporciona una API para la gestión de cupones. Está diseñado para ser ligero y eficiente, con un enfoque en el manejo de cupones mediante una arquitectura limpia.</p>

<h2>✨ Funcionalidades</h2>
<ul>
    <li>🎟️ <strong>API de Cupones</strong>: Gestión completa de cupones a través de endpoints dedicados.</li>
    <li>🔄 <strong>Configuración de Mapeo</strong>: Mapeo de modelos de datos para facilitar la interacción con la base de datos.</li>
    <li>🛠️ <strong>Gestión de Migraciones</strong>: Migraciones completadas para asegurar la estructura de la base de datos.</li>
</ul>

<h2>📂 Estructura del Proyecto</h2>
<ul>
    <li><strong>Controllers</strong>: Controladores de la API que manejan las solicitudes relacionadas con cupones.</li>
    <li><strong>Data</strong>: Implementación completa de la API de cupones.</li>
    <li><strong>Migrations</strong>: Migraciones que permiten la evolución de la base de datos.</li>
    <li><strong>Models</strong>: Definiciones de modelos de datos utilizados en la API.</li>
    <li><strong>Properties</strong>: Configuraciones del proyecto, incluyendo el archivo <code>launchSettings.json</code>.</li>
    <li><strong>MappingConfig.cs</strong>: Configuración de mapeo para el manejo de datos.</li>
</ul>

<h2>⚙️ Configuración</h2>

<h3>🔑 Archivos de Configuración</h3>
<p>Los archivos <code>appsettings.json</code> y <code>appsettings.Development.json</code> contienen las configuraciones necesarias para el funcionamiento de la API.</p>

<h2>📋 Requisitos Previos</h2>
<ul>
    <li><strong>.NET SDK 8.0</strong> o superior.</li>
    <li><strong>SQL Server</strong> o un sistema de base de datos compatible (si es necesario para almacenar los datos de cupones).</li>
</ul>

<h2>🚀 Instalación</h2>
<ol>
    <li>Clonar el repositorio:
        <pre><code>git clone https://github.com/tu-usuario/Mango.Services.CouponAPI.git</code></pre>
    </li>
    <li>Restaurar los paquetes de NuGet:
        <pre><code>dotnet restore</code></pre>
    </li>
    <li>Configurar la base de datos (si es aplicable) y realizar las migraciones necesarias:
        <pre><code>dotnet ef database update</code></pre>
    </li>
    <li>Ejecutar el proyecto:
        <pre><code>dotnet run</code></pre>
    </li>
</ol>

<h2>🌐 Principales Endpoints</h2>
<p>La API de cupones ofrece diversos endpoints para la creación, lectura, actualización y eliminación (CRUD) de cupones.</p>

<h2>⏳ Pendiente</h2>
<p>⚠️ Se están realizando cambios menores para mejorar la estabilidad y el rendimiento de la API.</p>

<h2>💬 Contacto</h2>
<p>Este proyecto forma parte de la plataforma Mango. Si tienes alguna pregunta o deseas contribuir, por favor, crea un issue o realiza un pull request.</p>

</body>
</html>
