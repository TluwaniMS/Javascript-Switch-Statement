# Javascript-Switch-Statement

The javascript `switch` statement is used to execute/trigger specific functions depending on the conditions that have been given.

```
const animal = "Cat";

switch (animal) {
  case "Cat":
    console.log(`Meow`);
    break;
  case "Dog":
    console.log(`Woof`);
    break;
  case "Cow":
    console.log(`Mooo`);
    break;
  default:
    console.log(`Woof Meow Mooo!!`);
    break;
}
```

```
const number = 5;

switch (number) {
  case 1:
  case 3:
    console.log(`required odds`);
    break;
  case 2:
  case 4:
    console.log(`required evens`);
    break;
  default:
    console.log(`not required`);
    break;
}
```

```
const animal = "Dog";
const age = 11;

switch (true) {
  case animal === "Dog" && age >= 12:
    console.log(`Hyena`);
    break;
  case animal === "Dog" && age < 12:
    console.log(`Wolf`);
    break;
  case animal === "Cat" && age >= 12:
    console.log("Lion");
    break;
  case animal === "Cat" && age < 12:
    console.log("Cheetah");
    break;
}
```
