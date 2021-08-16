# Ubiquity-drive-in testing

UBI is a frame for reading Gherkin files such that they are transmogrified 
into a testing focus of your choice.

The general idea is that between TDD, BDD and ATDD there is a common baseline 
of attributes (mental model) to "test" from and for at a given abstraction 
within layered architecture, such that efficiency, equity, learning, training, 
accessibility and agility can be reflected in the metadata interactions 
between kinds of test generated (interdevelopment testing).

## Install

```
$ npm i ubi --save-dev # lmao
```

## Usage

```
ubi generate component tdd test-component
ubi generate route bdd test-component
ubi generate route atdd test-component
```

## Contribute

## License
