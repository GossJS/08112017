3. x - тестируемое число в виде октета
x && 0b00000001
Если результирующее число будет равно 0 - число чётное, если 1 - нечётное.

const even = testedValue => testedValue  & 0b00000001;
const even2 = testedValue => testedValue | 0b11111110;

4.
const even3 = (testedValue,n) => testedValue & 2**n
