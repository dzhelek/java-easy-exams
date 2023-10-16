## 🌟 Примерна Задача
#### Инструкции
Създайте клас `Animal` с поле `name` и метод `makeSound()`. Създайте клас `Dog`, който наследява `Animal` и переопределя метода `makeSound()` да отпечатва "Woof".

#### Примерен Код
```java
class Animal {
  String name;

  void makeSound() {
    System.out.println("Animal Sound");
  }
}

class Dog extends Animal {

  @Override
  void makeSound() {
    System.out.println("Woof");
  }
}

public class Main {
  public static void main(String[] args) {
    Animal myAnimal = new Animal();
    Dog myDog = new Dog();

    myAnimal.makeSound();  // Output: Animal Sound
    myDog.makeSound();     // Output: Woof
  }
}
```

## 📝 Допълнителни Задачи (Лесни)

### 🚗 Задача 1
#### Инструкции
Създайте клас `SimpleCar` с поле `speed`. Добавете метод `accelerate()`, който увеличава скоростта с 10.

#### Примерен Изход
```java
Speed after accelerate: 10
```

---

### 🚗 Задача 2
#### Инструкции
Създайте клас `FamilyCar`, който наследява `SimpleCar` и добавя поле `seats`. Добавете метод `addSeat()`, който увеличава броя на седалките с 1.

#### Примерен Изход
```java
Seats after adding one: 5
```

---

### 🚗 Задача 3
#### Инструкции
Създайте интерфейс `Honkable` с метод `honk()`. Имплементирайте го в `SimpleCar` така, че да отпечатва "Honk!"

#### Примерен Изход
```java
Honk!
```

---

### 🚗 Задача 4
#### Инструкции
Създайте абстрактен клас `Vehicle` с метод `move()`. Нека `SimpleCar` наследява `Vehicle`.

#### Примерен Изход
```java
Vehicle is moving
```

---

### 🚗 Задача 5
#### Инструкции
Създайте клас `Bicycle` който също наследява `Vehicle`. Добавете метод `pedal()`.

#### Примерен Изход
```java
Pedaling the bicycle
```

---

### 🚗 Задача 6
#### Инструкции
Създайте клас `MainCars` и създайте няколко обекта от тип `SimpleCar` и `FamilyCar`. Използвайте `instanceof` за да проверите типа на обектите.

#### Примерен Изход
```java
This is a SimpleCar
This is a FamilyCar
```

---

### 🕺 Задача 7
#### Инструкции
Създайте клас `DanceMove` с полета `name` и `duration`. Добавете метод `perform()`.

#### Примерен Изход
```java
Performing the moonwalk for 5 seconds
```

---

### 🕺 Задача 8
#### Инструкции
Създайте клас `BreakDanceMove`, който наследява `DanceMove` и добавя поле `complexity`.

#### Примерен Изход
```java
Performing the windmill with complexity level 8
```

---

### 🕺 Задача 9
#### Инструкции
Създайте интерфейс `Danceable` с метод `dance()`. Имплементирайте го в `DanceMove`.

#### Примерен Изход
```java
Dancing the salsa
```

---

### 🕺 Задача 10
#### Инструкции
Създайте абстрактен клас `Performance` с метод `start()`. Нека `DanceMove` наследява `Performance`.

#### Примерен Изход
```java
Starting the performance
```

---

### 🕺 Задача 11
#### Инструкции
Създайте клас `Song` който също наследява `Performance`. Добавете метод `sing()`.

#### Примерен Изход
```java
Singing 'Bohemian Rhapsody'
```

---

### 🕺 Задача 12
#### Инструкции
Създайте клас `MainDance` и създайте няколко обекта от тип `DanceMove` и `BreakDanceMove`. Използвайте `instanceof` за да проверите типа на обектите.

#### Примерен Изход
```java
This is a DanceMove
This is a BreakDanceMove
```

---

### 🕺 Задача 13
#### Инструкции
Създайте клас `DJ` с метод `playSong(Song song)`. Добавете интерфейс `Playable` с метод `play()` и имплементирайте го в `DJ`.

#### Примерен Изход
```java
Playing 'Bohemian Rhapsody'
```

---

### 🕺 Задача 14
#### Инструкции
Създайте клас `MainPerformance` и създайте няколко обекта от тип `DanceMove`, `BreakDanceMove` и `Song`. Използвайте полиморфизъм за да ги стартирате.

#### Примерен Изход
```java
Starting the moonwalk
Starting the windmill
Starting 'Bohemian Rhapsody'
```

---

### 🕺 Задача 15
#### Инструкции
Създайте клас `Party` който има масив от `Performance` обекти. Добавете метод `startParty()` който стартира всички performances.

#### Примерен Изход
```java
Starting the moonwalk
Starting the windmill
Starting 'Bohemian Rhapsody'
Party started!
```
