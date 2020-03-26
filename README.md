# "hola mundo" js + jest + travis

<figure>
 <img src="https://pbs.twimg.com/media/DTWeg6DVMAE2Em1.png" height="64" width="64">
  <figcaption> <img src="https://travis-ci.com/GeeksHubsAcademy/hola-mundo-testing-js-jest.svg?branch=master" heigth="20" witdh="40" href="https://travis-ci.com/GeeksHubsAcademy/hola-mundo-testing-js-jest"> </figcaption>
</figure>

Pequeña prueba de concepto para lanzar un test usando js w/Jest en travis.


Test
```
test('adds 1 + 2 to equal 3', () => {
  expect(sum(1, 2)).toBe(3);
});
```

Source
```
function sum(a, b) {
  return a + b;
}
```
