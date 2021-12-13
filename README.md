# cl.bci.user
Prueba Postulación BCI

gradlew bootRun

Para revisar la documentación de la API por favor ingresar al link: http://localhost:8080/swagger-ui.html#/

El end point que crea usuario y entrega el token para consumir el resto de la API es localhost:8080/api/login

Además indicar que para consumir la API se debe enviar el header Authorization con valor Bearer + token entregado por end point login


{
  "email": "victor@gmail.com",
  "name": "victorassa",
  "password": "QQprue$CASAba@854__",
    "phones": [
    {
      "citycode": "string",
      "contrycode": "string",
      "id_phone": 0,
      "number": "string"
    }
  ]
}
