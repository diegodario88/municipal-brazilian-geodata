## Municipal Brazilian Geodata

This repository contains a conglomerate data including boundaries and geolocation – [in geojson format](https://geojson.org/) – of all Brazilian municipalities. The data is divided by states, which are named by it's federative unit initials. For example, Paraná state data is at `data-output/PR.json` file.

## Example
```json
  {
    "codigo_ibge": 1200013,
    "nome": "Acrelândia",
    "uf": "AC",
    "perimetro": {
      "type": "Polygon",
      "coordinates": [
        [
          [
            -66.8103,
            -9.818
          ],
          [
            -66.8771,
            -9.7888
          ],
          [
            -67.0347,
            -9.7198
          ],
          [
            -67.0986,
            -9.6918
          ], // and so on...
        ]
      ]
    },
    "centroide": {
      "type": "Point",
      "coordinates": [
        -66.8972,
        -9.82581
      ]
    },
    "capital": false,
    "codigo_siafi": 643,
    "ddd": 68,
    "fuso_horario": "America/Rio_Branco"
  },
```

## Issues / Pull Requests

If you find any problem with this dataset, please let me know.

If you have a change to propose, create a pull request. 

## TODO list

- Add Topojson data
- Add Check constraint on pipeline

## Source

All this data was generated using [IBGE's geo data](http://www.ibge.gov.br).

## Inspired on
- [Kelvins](https://github.com/kelvins/Municipios-Brasileiros)
- [Luiz Pedone](https://github.com/luizpedone/municipal-brazilian-geodata)

All this data was generated using [IBGE's geo data](http://www.ibge.gov.br).

## License

[MIT License](LICENSE) (c) 2022 Diego Dario