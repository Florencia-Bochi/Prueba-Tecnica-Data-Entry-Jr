# Prueba Tecnica Data Entry Jr

Aquí se encuentra la documentación de mi prueba tecnica. 


# Pasos realizados

1. Descarga de archivos
   - Se realizó la descarga completa de los archivos en un repositorio local.
  
2. Revisión de archivos
   - Inspección de archivos descargados, identificando su tipo y desglozando la información de los mismos.

3. Planificación de Tareas.
   - Se realiza un plan de ejecución general para abordar los distintos casos, que se detallarán en el punto siguiente, teniendo en cuenta las instrucciones generales recibidas. 
  
4. Inicio de Tareas.
     
 ### _Caso 1 'Anaerobicos'_ 

 Se detalla a continuación los pasos aplicados: 
   - A) Se importa el documento 'Anaerobicos trabajar.xlsx', a Google Sheets.
   - B) Lectura de instrucciones 'NOTAS.docx'.
   - C) Identificación en el documento de la columna 'Producto'.
   - D) Se utiliza fórmula 'SPLIT', dividiendo columnas de código y descripción (Agregando columnas necesarias para todos los campos).
   - E) Se crean nuevas hojas dentro del mismo documento, donde se copia solo información sin fórmulas, generando el encabezado correspondiente ('Código, Descripción y Precio').
   - F) Se ordenan las tablas de mayor a menor, teniendo como criterio la columna 'c' que corresponde a 'Precio'.
   - G) Se realiza el resguardo, y se exporta como archivo 'Anaerobicos.xlsx' (Teniendo en cuenta la configuración regional de la hoja de cálculo quede en Argentina).


 ### _Caso 2 'Ford'_ 

 Se detalla a continuación los pasos aplicados: 
   - A) Se importan los documentos 'ford modelo_.xlsx' y 'ford TRABAJAR.xlsx', a Google Sheets.
   - B) Lectura de instrucciones 'NOTAS.docx'.
   - C) Identificación en el documento la columna 'Códigos'.
   - D) Se utiliza la fórmula 'SUSTITUIR', para quitar los espacios en blancos, de la columna 'Códigos'. 
   - E) Se utiliza la fórmula 'SUSTITUIR', para reemplazar el "." (Punto), por "," (Coma), de la columna 'Precio'.
   - F) Se crean nuevas hojas dentro del mismo documento, donde se copia solo información sin fórmulas, generando el encabezado correspondiente ('Código, Descripción y Precio').
   - G) Se ordenan las tablas de mayor a menor, teniendo como criterio la columna 'c' que corresponde a 'Precio'.
   - H) Se realiza el resguardo, y se exporta como archivo 'Ford.xlsx' (Teniendo en cuenta la configuración regional de la hoja de cálculo quede en Argentina).

 ### _Caso 3 'Hard'_ 

 Se detalla a continuación los pasos aplicados: 
   - A) Se importan los documentos 'hurl 25.09.xlsx MODELO_.xlsx' y 'hurl.csv TRABAJAR.csv', a Google Sheets.
   - B) A la hora de importar el archivo 'hurl.csv TRABAJAR.csv' se selecciona 'tipo de separador: Coma'.
   - C) Lectura de instrucciones 'DATOS.docx' y ejemplo del modelo 'hurl 25.09.xlsx MODELO_.xlsx'.
   - D) Identificación de columnas con su respectivo título.
   - E) Cambio correspondiente de formato en columna 'Precio'.
   - F) Se utiliza la fórmula de 'CONCATENACIÓN', para generar la columna 'Descripción'.
   - G) Se ordenan las tablas de mayor a menor, teniendo como criterio la columna 'Precio'.
   - H) Se realiza el resguardo, y se exporta como archivo 'Hard.xlsx' (Teniendo en cuenta la configuración regional de la hoja de cálculo quede en Argentina).

 ### _Caso 4 'Rasa'_ 

 Se detalla a continuación los pasos aplicados: 
   - A) Se importan los documentos 'rasa 1 rbs MODELO.xlsx' y 'LP_RASA_001 (1).txt TRABAJAR.txt', a Google Sheets.
   - B) A la hora de importar el archivo 'LP_RASA_001 (1).txt TRABAJAR.txt' se selecciona 'tipo de separador: Tabulador'.
   - C) Lectura de instrucciones 'NOTAS.docx' y ejemplo del modelo 'rasa 1 rbs MODELO.xlsx'.
   - D) Se utilizaron las fórmulas 'REGEXEXTRACT, REGEXMATCH, SI' para separar números de letras de la columna 'a' y así obtener un código de solo números enteros.
   - E) Se utiliza la formula de 'CONCATENACIÓN', para generar la columna 'DESCRIPCIÓN'.
   - F) Se utiliza la formula de 'CONCATENACIÓN', para generar una nueva columna donde se encuentre la información de las columnas A y B.
   - G) Se realiza el resguardo, y se exporta como archivo 'Hard.xlsx' (Teniendo en cuenta la configuración regional de la hoja de cálculo quede en Argentina).

   - Detalle: No se encontro una lógica para poder resolver y obtener la columna 'Precio'.


      
      
