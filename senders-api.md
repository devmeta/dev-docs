# Primero
Solicitar acceso al API para empresas a info@senders.com.ar

Vas a recibir un email con un **CLIENT_ID** y una **KEY**

# Uso
Para generar un envío generar el siguiente HTTP request:


**POST** - https://waaws-api.herokuapp.com/senders/api/v1/shipments

**Headers**

```sh
ClientId: XXXXXXX

Key: XXXXXXX
```

**Body**

```json
{
  "shipper_fullname": "juan garcia",
  "shipper_email": "juan@gmail.space",
  "shipper_phone": "1155552222",
  "created_at": 1477665818578,
  "pickup_address_line_1": "rivadavia 1234",
  "pickup_address_between_streets": "calle 1 y calle 2",
  "pickup_address_postal_code": "1234",
  "pickup_address_neighborhood": "Colegiales",
  "pickup_time_range": "13 a 15",
  "receiver_email": "jorge@gmail.com",
  "receiver_fullname": "jorge perez",
  "destination_address_line_1": "corrientes 1234",
  "destination_address_between_streets": "montevideo y callao",
  "destination_address_postal_code": "2345",
  "destination_address_neighborhood": "Parque chas",
  "destination_time_range": "15 a 17"
}
```
