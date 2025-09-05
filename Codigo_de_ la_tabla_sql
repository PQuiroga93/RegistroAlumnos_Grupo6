
CREATE TABLE Usuario (
  id_usuario INT AUTO_INCREMENT PRIMARY KEY,
  nombre VARCHAR(100) NOT NULL,
  apellido VARCHAR(100) NOT NULL,
  dni VARCHAR(15) NOT NULL UNIQUE,
  email VARCHAR(100) UNIQUE,
  telefono VARCHAR(15),
  direccion VARCHAR(255),
  rol INT NOT NULL COMMENT '0=admin, 1=docente, 2=alumno'
);

CREATE TABLE TipoCarrera (
  id_tipo_carrera INT AUTO_INCREMENT PRIMARY KEY,
  tipo VARCHAR(50) NOT NULL UNIQUE
);

CREATE TABLE Carrera (
  id_carrera INT AUTO_INCREMENT PRIMARY KEY,
  nombre VARCHAR(100) NOT NULL,
  id_tipo_carrera INT NOT NULL,
  descripcion TEXT,
  FOREIGN KEY (id_tipo_carrera) REFERENCES TipoCarrera(id_tipo_carrera)
);

CREATE TABLE Alumno (
  id_alumno INT AUTO_INCREMENT PRIMARY KEY,
  id_usuario INT NOT NULL UNIQUE,
  id_carrera INT NOT NULL,
  legajo VARCHAR(20) NOT NULL UNIQUE,
  fecha_ingreso DATE,
  FOREIGN KEY (id_usuario) REFERENCES Usuario(id_usuario),
  FOREIGN KEY (id_carrera) REFERENCES Carrera(id_carrera)
);

CREATE TABLE Docente (
  id_docente INT AUTO_INCREMENT PRIMARY KEY,
  id_usuario INT NOT NULL UNIQUE,
  id_carrera INT NOT NULL,
  titulo VARCHAR(100),
  fecha_ingreso DATE,
  FOREIGN KEY (id_usuario) REFERENCES Usuario(id_usuario),
  FOREIGN KEY (id_carrera) REFERENCES Carrera(id_carrera)
);
