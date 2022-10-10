# classes-constructors
//classes- #1
class Cat {
    constructor(name, food, hobbies) {
          this.name = name;
          this.food = food;
          this.hobbies = hobbies;


    }
}

var cat1 = new Cat('Arrow', 'chicken', 'meow');
let cat2 = new Cat('Furry', 'milk', 'sleep');

console.log(cat1)
console.log(cat2)


//classes- #2
class Pirate {
    constructor(name, experience, ship1, ship2) {
          this.name = name;
          this.experience = experience
          this.ship1 = ship1;
          this.ship2 = ship2;

    

    }
}

var pirate1 = new Pirate('Mojo', '3-Years', 'jollyRoger', 'blackPearl');
let pirate2 = new Pirate('Yoshi','5-Years', 'jollyRoger', 'blackPearl');

console.log(pirate1)
console.log(pirate2)



