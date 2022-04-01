#INSERTAR DATOS EN ORACLE

#### Creamos la Tabla Empleados
```sql
create table empleado(
id_empleado int not null,
nombre varchar2(20),
direccion varchar2(50),
id_documento varchar2(10),
sueldo number(6,2),
fecha_nacimiento date
);
```

#### Insertamos los datos a la tabla
```sql
insert into empleado values(001,'Ana','Avenida Petit thouars','0002312345',3500,00,to_date('01/04/2022', 'dd/mm/yyyy');
```

#### Nuestra tabla
 | id_empleado    | nombre      | Direccion           | id_documento |  sueldo   | FECHA_NACIMIENTO   |
 | ---------------|:-----------:|--------------------:|-------------:|----------:|-------------------:|
 | 001            |   Ana       |Avenida Petit thouars|0002312345    |  3500,00  |01/04/2022          |
