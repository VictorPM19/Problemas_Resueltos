# Problemas_Resueltos
Codigos corregidos

-------
# Ejercicio 1
```ts
(() => {

  const addTwoNumbers = (a: number, b: number): number => {
    return a + b;
  };

  console.log(addTwoNumbers(2, 4));// 6
  console.log(addTwoNumbers(10, 10));  // 20
})();

----------
# Ejercicio 2

```ts
(() => {
  const addTwoNumbers = (params: { first: number; second: number }): number => {
    return params.first + params.second;
  };

  console.log('R1=',
    addTwoNumbers({
      first: 2,
      second: 4,
    }),
  );

  console.log('R2=',
    addTwoNumbers({
      first: 10,
      second: 20,
    }),
  );
})();


