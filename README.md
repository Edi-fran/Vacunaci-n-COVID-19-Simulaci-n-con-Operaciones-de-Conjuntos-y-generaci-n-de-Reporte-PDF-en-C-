VacunacionCovid-ConjuntosPDF

Descripción: Este proyecto es una aplicación en C# que simula una campaña de vacunación contra el COVID-19 utilizando la teoría de conjuntos. Se genera un conjunto ficticio de 500 ciudadanos, de los cuales se asignan aleatoriamente 75 ciudadanos vacunados con la vacuna Pfizer y 75 ciudadanos vacunados con la vacuna AstraZeneca.

Operaciones realizadas:

Listado de ciudadanos sin vacunación: se obtiene eliminando del conjunto total a los ciudadanos que han recibido alguna vacuna.
Listado de ciudadanos que han recibido ambas vacunas: se determina mediante la intersección de los conjuntos de ciudadanos vacunados con Pfizer y con AstraZeneca.
Listado de ciudadanos vacunados solo con Pfizer: se obtiene mediante la diferencia entre el conjunto de Pfizer y el de AstraZeneca.
Listado de ciudadanos vacunados solo con AstraZeneca: se obtiene mediante la diferencia entre el conjunto de AstraZeneca y el de Pfizer.
Reporte PDF: El proyecto genera un reporte en formato PDF usando la librería iTextSharp. Este reporte incluye la información institucional y los listados de ciudadanos obtenidos mediante las operaciones de conjuntos.

Características:

Generación de 500 ciudadanos ficticios con nombres secuenciales (Ciudadano 1, Ciudadano 2, ..., Ciudadano 500).
Selección aleatoria de 75 ciudadanos para cada tipo de vacuna.
Uso de operaciones de conjuntos en C# (ExceptWith e IntersectWith) para obtener los diferentes listados.
Generación de un archivo PDF (Reporte_Vacunacion.pdf) con los resultados de la campaña.
Requisitos:

.NET Framework o .NET Core.
Librería iTextSharp (se puede instalar vía NuGet con el comando: Install-Package iTextSharp).
Instrucciones para ejecutar el proyecto:

Clonar el repositorio: git clone https://github.com/TuUsuario/CampañaVacunacionCovid-ConjuntosPDF.git
Abrir la solución en Visual Studio o el IDE de tu preferencia.
Restaurar las dependencias (incluyendo iTextSharp).
Compilar y ejecutar el proyecto.
Al finalizar la ejecución, se generará un archivo llamado Reporte_Vacunacion.pdf en la carpeta del proyecto y se mostrará en la consola un resumen de la campaña.
Autor: Desarrollado por: Edilson Guillin
