<?php
$servername = "localhost";
$username = "julio";
$password = "9202571";
$dbname = "base de datos"; // Cambia al nombre de tu base de datos

// Crear conexión
$conn = new mysqli($servername, $username, $password, $dbname);

// Verificar conexión
if ($conn->connect_error) {
    die("Conexión fallida: " . $conn->connect_error);
}

// Recibir datos del formulario
$nombre = $_POST['nombre'];
$email = $_POST['email'];

// Preparar consulta SQL
$sql = "INSERT INTO usuarios (nombre, email) VALUES ('$nombre', '$email')";

if ($conn->query($sql) === TRUE) {
    echo "Datos guardados correctamente. <a href='index.html'>Volver</a>";
} else {
    echo "Error al guardar los datos: " . $conn->error;
}

// Cerrar la conexión
$conn->close();
?>
