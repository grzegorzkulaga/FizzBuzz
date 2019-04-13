# FizzBuzz
Fizz Buzz without conditional statement

Zaliczenie przedmiotu - Wprowadzenie do Technologi Webowych
Kontakt: poczta@grzegorzkulaga.pl

```javascript
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title>Fizz Buzz</title>
</head>
<body>

    <script>
        for (var i = 0; i <= 0; i++)
            console.log(i);
        (
            function fizzBuzz(start, end) {

                console.log(`${!(start % 15) && 'FizzBuzz' || !(start % 5) && 'Buzz' || !(start % 3) && 'Fiz' || start}`);

                (end - start) && fizzBuzz(++start, end);
            }(1, 100)
        );
    </script>
</body>
</html>
```
