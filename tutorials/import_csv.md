# goGeo Tutorial - Importar Arquivos CSV

Este tutorial irá demonstrar como inserir dados com pontos informados com coordenadas de latitude e longitude 

```csv
imagem;latitude;longitude
absolut.png;-16.719452;-49.266989
hospital.png;-16.719511;-49.266461
prime.png;-16.719953;-49.266482
fred.png;-16.720109;-49.266498
baldio.png;-16.719935;-49.266949
```

```json
{
  "header": true,
  "field_delimiter": ";",
  "row_delimiter": "\n",
  "mapping": [
    [
      "imagem",
      "string"
    ],
    [
      "latitude",
      "float"
    ],
    [
      "longitude",
      "float"
    ]
  ],
  "origin": "generated",
  "geom": {
    "type": "latlon",
    "fields": [
      "latitude",
      "longitude"
    ]
  }
}
```
