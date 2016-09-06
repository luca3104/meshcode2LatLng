# meshcode2LatLng

## Description
メッシュコードから緯度経度に変換するライブラリです。
<img src="https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/screenshot.png" width=512>

## Demo of Google maps api
### 1次メッシュ
![1st](https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/1st.png)
```js
var location =  meshcode2LatLng.first(5339);
new google.maps.Rectangle({
  strokeColor: '#ff0000',
  fillColor: '#ff0000',
  map: map,
  bounds: {
    north: location.north,
    south: location.south,
    west: location.west,
    east: location.east
  }
});
```
### 2次メッシュ
![2nd](https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/2nd.png)
```js
var location =  meshcode2LatLng.second(533946);
new google.maps.Rectangle({
  strokeColor: '#ff0000',
  fillColor: '#ff0000',
  map: map,
  bounds: {
    north: location.north,
    south: location.south,
    west: location.west,
    east: location.east
  }
});
```

### 3次メッシュ
![3rd](https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/3rd.png)
```js
var location =  meshcode2LatLng.third(53394611);
new google.maps.Rectangle({
  strokeColor: '#ff0000',
  fillColor: '#ff0000',
  map: map,
  bounds: {
    north: location.north,
    south: location.south,
    west: location.west,
    east: location.east
  }
});
```

### 1/2メッシュ
![1/2](https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/1:2.png)
```js
var location =  meshcode2LatLng.half(533946113);
new google.maps.Rectangle({
  strokeColor: '#ff0000',
  fillColor: '#ff0000',
  map: map,
  bounds: {
    north: location.north,
    south: location.south,
    west: location.west,
    east: location.east
  }
});
```

### 1/4メッシュ
![1/4](https://github.com/luca3104/meshcode2LatLng/blob/screenshot/screenshots/1:4.png)
```js
var location =  meshcode2LatLng.quater(5339461132);
new google.maps.Rectangle({
  strokeColor: '#ff0000',
  fillColor: '#ff0000',
  map: map,
  bounds: {
    north: location.north,
    south: location.south,
    west: location.west,
    east: location.east
  }
});
```

## Licence

[MIT](https://github.com/luca3104/meshcode2LatLng/blob/master/LICENSE)

## Author

[luca3104](https://github.com/luca3104)
