# JAVA Примери

## ОПЕРАТОРИ И ИЗРАЗИ

### Аритметични оператори:
```java
int a = 5;
int b = 3;
int сума = a + b;      // 8
int разлика = a - b;   // 2
int произведение = a * b; // 15
int частно = a / b;       // 1
int остатък = a % b;      // 2
```
Обяснение: Освен основните аритметични оператори, имаме и оператора `%`, който връща остатъка при деление.

### Оператори за сравнение:
```java
boolean равни = (a == b);  // false
boolean различни = (a != b); // true
boolean по_голямо = (a > b);  // true
boolean по_малко = (a < b);   // false
```

## СТАНДАРТЕН ВХОД И СТАНДАРТЕН ИЗХОД ОТ КОНЗОЛАТА

### Вход от конзолата:
```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Моля, въведете вашето име: ");
        String име = scanner.nextLine();
        System.out.print("Моля, въведете вашата възраст: ");
        int възраст = scanner.nextInt();
        System.out.println("Здравей, " + име + "! Ти си на " + възраст + " години.");
    }
}
```

## ЦИКЛИ

### For цикъл:
```java
for (int i = 0; i < 5; i++) {
    System.out.println("Числото е: " + i);
}
```

### While цикъл:
```java
int i = 0;
while (i < 5) {
    System.out.println("Числото е: " + i);
    i++;
}
```

### Do-While цикъл:
```java
int i = 0;
do {
    System.out.println("Числото е: " + i);
    i++;
} while (i < 5);
```

## МАСИВИ

### Декларация и инициализация:
```java
int[] числа = {1, 2, 3, 4, 5};
```

### Достъп до елементи:
```java
int първоЧисло = числа[0];  // 1
```

### Проход по масив с for цикъл:
```java
for (int i = 0; i < числа.length; i++) {
    System.out.println("Число на индекс " + i + " е: " + числа[i]);
}
```
