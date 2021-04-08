# Comparison and logical operators
1. ### == : to compares tow value to see if they are the same.
  * Example
    * `'Hi' == 'Bye'` return false because they aren't the same data type.
    * `''Hi == 'Hi'` return true because they are the same data type.

1. ### != : to compares tow value to see if they are not the same.
  * Example
    * `'Hi' != 'Bye'` return true because they aren't the same data type.
    * ` 'Hi' == 'Hi'` return false because they are the same data type.
1. ### === : to compares tow value to check that both the data type and value are the same.
  * Example
    * `'11' === 11` return false because they aren't the same data type or value.
    * `'12' === '12'` return true because they are the same data type and value.
1. ### !== : to compares tow value to check that both the data type and value are not the same.
   * Example
    * `'11' !== 11` return true because they aren't the same data type or value.
    * `'12' === '12'` return false because they are the same data type and value.
# logical operator:
## There are three logical operators in JavaScript: || (OR), && (AND), ! (NOT),
  1. `||` OR : This operator tests at least one condition.
  * Example 
    > * true || true  // true
    > * false || true  // true
    > * true || false // true
    > * false || false // false
2. `'&&'` AND : This operator tests more than one condition.
   * Example 
    > * true && true  // true
    > * false && true  // false
    > * true && false // false
    > * false && false // false
1. `!` NOT : This operator takes a single Boolean value and inverts it.
  * Example 
    > * !true  // false
    > * !false // true

# Loops
## For loop : 
### if you need to run code a specific number of times.
  * Example 
     ```javascript
     for (i = 0; i < 10; i++) {
        document.write(i);
    }
    ```
## While loop : 
### if you don't know how many times the code should run.
  * Example 
     ```javascript
     while (i < 10) {
        text = text + "The number is " + i;
        i++;
    }
    ```
# *  in the condition need to be false to brake the loop.



    
   