## Ejercicio Banco
    Clientes
        dni
        nombre
        apellido
        correo
        telefono
        
    Tipo Productos
        codigoProducto
        descripcion
        TasaInteres

    Movimientos
        numeroMovimiento
        Monto 
        fecha
        numeroProductos

    Cliente_Productos
        dni - FK
        codigoProducto - PK
        NumeroProducto - FK
        fechaApertura
        Estado
        Saldo

    Direccion
    idDireccion - PK
    Departamento
    Ciudad
    Calle

## Procedimiento Ejercicio

### Crear base de datos

    Manejador de BD -> MySQL WorkBench
    
    Para crear una tabla se utilizara el comando "create table"
    y luego se procede a agregar los atributos de la tabla:

    create table nombreBD.NombreTabla(
        atrib1 varchar(cantidad) primary key,
        atrib2 integer(),

    );


