# Задание 2. Проектирование API

## Request

```http
GET /api/v1/partners
Host: api.petrushka-green.ru
Authorization: Bearer <access_token>
```

## Response

```json
{
  "partners": [
    {
      "name": "METRO",
      "logoUrl": "https://cdn.petrushka-green.ru/partners/metro.png",
      "deliveryInfo": "Ближайшая доставка сегодня с 19:00 до 21:00",
      "externalUrl": "https://online.metro-cc.ru"
    },
    {
      "name": "Ашан",
      "logoUrl": "https://cdn.petrushka-green.ru/partners/auchan.png",
      "deliveryInfo": "Ближайшая доставка сегодня с 20:00 до 22:00",
      "externalUrl": "https://www.auchan.ru"
    },
    {
      "name": "ВкусВилл",
      "logoUrl": "https://cdn.petrushka-green.ru/partners/vkusvill.png",
      "deliveryInfo": "Доставка от 30 минут",
      "externalUrl": "https://vkusvill.ru"
    }
  ]
}
```