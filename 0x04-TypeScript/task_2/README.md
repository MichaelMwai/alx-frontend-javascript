## 0x04-TypeScript
TypeScript checks a program for errors before execution, and does so based on the kinds of values, making it a static type checker. For example, the last example above has an error because of the type of obj. Here’s the error TypeScript found:

***const obj = { width: 10, height: 15 };
const area = obj.width * obj.heigth;
Property 'heigth' does not exist on type '{ width: number; height: number; }'. Did you mean 'height'?***
