trails-ms



// ====================================================================================================================
// ====================================================================================================================
// ====================================================================================================================



--> TRAER TODAS LAS RUTAS DE LA BASE DE DATOS
    |
    |-->   (GET)  -- http://192.168.99.101:3002/trails 




--> TRAER TODAS LAS RUTAS DE UN USUARIO (usertrail --> es el ID del usuario)
    |
    |-->   (GET)  -- http://192.168.99.101:3002/categories/user/{ usertrail }




--> CREA UNA RUTA
    |
    |-->   (POST)  -- http://192.168.99.101:3002/categories
    |
    |-->   (BODY)   |
                    V
                    {
                        "usertrail": 111,
	                    "nametrail": "RUTA333",
	                    "origintrail": 111111,
	                    "destinytrail": 111444   
                    }




--> TRAE LA RUTA DE UN ID EN ESPECIFICO (ID --> es el ID de la base de datos ejemplo = 5d013616fb689d0001d1ccd9)
    |
    |-->   (POST)  -- http://192.168.99.101:3002/categories/{ ID }




--> TRAE LA RUTA DE UN ID EN ESPECIFICO (ID --> es el ID de la base de datos ejemplo = 5d013616fb689d0001d1ccd9)
    |
    |-->   (GET)  -- http://192.168.99.101:3002/categories/{ ID }




--> BORRAR LA RUTA DE UN ID EN ESPECIFICO (ID --> es el ID de la base de datos ejemplo = 5d013616fb689d0001d1ccd9)
    |
    |-->   (DELETE)  -- http://192.168.99.101:3002/categories/{ ID }




// ====================================================================================================================
// ====================================================================================================================
// ====================================================================================================================