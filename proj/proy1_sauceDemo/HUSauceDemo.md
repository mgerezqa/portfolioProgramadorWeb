

[TOC]



### Historia de Usuario 1: Iniciar Sesión

**Descripción:** Como usuario registrado, quiero poder iniciar sesión en saucedemo.com para acceder a mi cuenta y realizar compras.

**Criterios de Aceptación:**

```
DADO que estoy en la página de inicio de sesión
CUANDO ingreso mi nombre de usuario y contraseña válidos
ENTONCES debo ser redirigido a mi dashboard personal
Y debo ver un mensaje de bienvenida con mi nombre de usuario
```

### Historia de Usuario 2: Realizar Compra de Producto

**Descripción:** Como usuario autenticado, quiero poder agregar productos a mi carrito de compras y realizar una compra en saucedemo.com.

**Criterios de Aceptación:**

```
DADO que estoy en la página de productos
CUANDO selecciono un producto y lo agrego a mi carrito
ENTONCES  debo ser redirigido a la página de los productos en mi carrito
Y selecciono proceder al pago
ENTONCES debo ser redirigido a la página de completar mi información de comprador
Y selecciono continuar
ENTONCES debo ser redirigido a la página de pago
Y debo poder completar la compra

```

### Historia de Usuario 3: Ver Productos en Dashboard

**Descripción:** Como usuario autenticado, quiero poder ver los productos disponibles en saucedemo.com en mi dashboard.

**Criterios de Aceptación:**

```
DADO que estoy en mi dashboard personal
CUANDO accedo a la sección de productos
ENTONCES debo ver una lista de productos disponibles
Y debo poder ver detalles de cada producto, como nombre, precio, y descripción
```

### Historia de Usuario 4: Ordenar Productos Según Criterio

**Descripción:** Como usuario autenticado, quiero poder ordenar la lista de productos según diferentes criterios en saucedemo.com.

**Criterios de Aceptación:**

```
DADO que estoy en la página de productos
CUANDO selecciono un criterio de ordenamiento (por ejemplo, precio, nombre)
ENTONCES los productos deben reordenarse de acuerdo con el criterio seleccionado
Y debo poder cambiar entre diferentes criterios de ordenamiento
```

### Historia de Usuario 5: Cerrar Sesión

**Descripción:** Como usuario autenticado, quiero poder cerrar sesión en saucedemo.com cuando haya terminado de usar la plataforma.

**Criterios de Aceptación:**

```
DADO que estoy en mi dashboard personal
CUANDO selecciono la opción de cerrar sesión
ENTONCES debo ser redirigido a la página de inicio de sesión
Y no debo poder acceder a las funcionalidades de usuario autenticado sin volver a iniciar sesión
```