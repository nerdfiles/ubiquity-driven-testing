# Ubiquity-drive-in testing

UBI is a frame for reading Gherkin files such that they are transmogrified 
into a testing focus of your choice.

The general idea is that between TDD, BDD and ATDD there is a common baseline 
of attributes (mental model) to "test" from and for at a given abstraction 
within layered architecture, such that efficiency, equity, learning, training, 
accessibility and agility can be reflected in the metadata interactions 
between kinds of test generated (interdevelopment testing). Even a "service" has 
a behavioral component and an acceptance test minimum requirement to be passed.

Since developments do not like cross-functional testing, the purpose is to make 
it easier to do that: CFT = interdevelopment testing. I want this to be platform 
pluralistic, for reasons, once and for all.

## Install

```
$ npm i ubi --save-dev # lmao
```

## Usage

```
ubi generate component tdd react test-component
ubi generate route bdd angular test-route
ubi generate service atdd angular test-service
```

## Contribute

## License
