# "hola mundo" js + jest + travis
[![Build Status](https://travis-ci.com/GeeksHubsAcademy/hola-mundo-testing-js-jest.svg?branch=master)](https://travis-ci.com/GeeksHubsAcademy/hola-mundo-testing-js-jest)

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
