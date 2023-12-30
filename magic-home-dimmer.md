https://github.com/RavenSystem/esp-homekit-devices/wiki/Lightbulb

## W Dimmer

| Component | GPIO |
| --- | --- |
| W | GPIO 12 |

```json
{
  "c": {
    "io": [[[12], 7], [[0], 6]],
    "b": [[0, 5]]
  },
  "a": [{
    "t": 30,
    "b": [[0]],
    "g": [12]
  }]
}
```

```json
{"c":{"io":[[[12],7],[[0],6]],"b":[[0,5]]},"a":[{"t":30,"b":[[0]],"g":[12]}]}
```

## RGB Dimmer

| Component | GPIO |
| --- | --- |
| R | GPIO 15 |
| G | GPIO 13 |
| B | GPIO 12 |

```json
{
  "c": {
    "b": [
      {
        "g": 0,
        "t": 5
      }
    ]
  },
  "a": [
    {
      "t": 30,
      "b": [
        {
          "g": 0
        }
      ],
      "g": [5, 12, 13]
    }
  ]
}
```

```json
{"c":{"b":[{"g":0,"t":5}]},"a":[{"t":30,"b":[{"g":0}],"g":[5,12,13]}]}
```

## RGBW Dimmer

| Component | GPIO |
| --- | --- |
| R | GPIO 15 |
| G | GPIO 12 |
| B | GPIO 13 |
| W | GPIO 14 |

```json
{
  "c": {
    "b": [
      {
        "g": 0,
        "t": 5
      }
    ]
  },
  "a": [
    {
      "t": 30,
      "b": [
        {
          "g": 0
        }
      ],
      "g": [15, 13, 12, 14]
    }
  ]
}
```

```json
{"c":{"b":[{"g":0,"t":5}]},"a":[{"t":30,"b":[{"g":0}],"g":[15,13,12,14]}]}
```
