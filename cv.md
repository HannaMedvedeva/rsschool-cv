# My CV

 **name**: Anna Medvedeva
 **email**: fyzania@gmail.com, telegram: <https://t.me/Fyzania>
 I am 24 years old. Today I am an ophthalmologist, working in a Regional Clinical Hospital for Children, 1st year after my graduation from Belarusian State Medical University.
 Unfortunately, I was disappointed in our medical system, and after much thought made a decision to start learning programming. Last year I studied Java on my own about 5 month, in present time I started learning JavaScript. I can study on my own, I am sure of this after studying 6 years at our medical university :) and **I have good motivation to develop**.
 **My skills**: Java basics, JavaScript basics, HTML basics, OOP basics.
 **Code examples**:

```javascript
<script>
    function Calculator() {
        this.read = function () {
            this.x = +prompt("enter first number", "");
            this.y = +prompt("enter second number", "");
        };
        this.sum = function () {
            return this.x + this.y;
        };
        this.mul = function () {
            return this.x * this.y;
        }
    }
    let calculator = new Calculator();
    calculator.read();

    alert("Sum=" + calculator.sum());
    alert("Mul=" + calculator.mul());


    function Accumulator(startingValue) {
        this.read = function () {
            this.value += +prompt("enter a number", "");
        }
        this.value = +startingValue;
    }
    let accumulator = new Accumulator(1);

    accumulator.read();
    accumulator.read();

    alert(accumulator.value);
</script>
```

 **Experience**: for today, is only a self education programming (javarush, codewars.com , learn.javascript.ru , some tasks from my friends - developers :))
 **Education**: BSMU, self education
 **English**: B1, studied in school, university, self education.
