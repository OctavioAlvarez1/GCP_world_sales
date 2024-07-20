<h1 align="center">PROYECTO VENTAS MUNDIALES</h1>
<br>
<p align="center">
  <img src="https://github.com/OctavioAlvarez1/GCP_world_sales/blob/main/Images/sales.png" alt="Imagen" width="800" height="500">
</p>
<h1>Herramientas</h1>
Este proyecto de <strong>Data Analytics</strong> fue creado utilizando <strong> Python y las tecnologías proporcionadas por la nube de Google (GCP)</strong>.
<br>
<br>
<h1>Requerimientos</h1>
<ul>
  <li><strong>Desarrollar un portal que permita subir los archivos</strong> que contienen los datos de diferentes países y verificar si la carga fue exitosa.</li>
  <li><strong>Disponibilizar los datos en Google GCP </strong> para poder realizar cargas incrementales de los mismos y consultas que deriven en el dashboard.</li>
  <li><strong>Crear un dashboard en Looker Studio </strong> que permita mostrar relaciones relevantes entre los datos.</li>
</ul>
<br>
<br>
<h2>Visión General</h2>
<ul>
  <li><strong>Portal Web:</strong> Construido con Python Flask para permitir a los usuarios subir archivos de datos de ventas.</li>
  <li><strong>Almacenamiento:</strong> Los archivos subidos se almacenan en un bucket de GCS.</li>
  <li><strong>Función en la Nube:</strong> Se activa automáticamente cuando se sube un archivo al bucket de GCS, extrae los datos del archivo y los carga en BigQuery.</li>
  <li><strong>Proceso ETL:</strong> Proceso de Extraer, Transformar y Cargar implementado para manejar los datos desde el estado bruto hasta el estado procesado.</li>
  <li><strong>Reportes:</strong> Vistas resumidas y dashboards en Looker Studio para métricas clave, con capacidades de filtrado y profundización.</li>
</ul>
