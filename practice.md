<h5>Print squares</h5>
<p>Write a program to output the squares (using multiplication) of numbers from 1 to 5 on separate lines.</p>
<P>[Note: Print the output in the exact same format as given below.]</P>
<h5>Output</h5>

```
1 - 1
2 - 4
3 - 9
4 - 16
5 - 25
```
<p>Java solution:</p>

```Java
class Hello {
    public static void main(String[] args) {
        
        for (int i = 1; i <= 5; i++) {
            int squares = i * i;
            System.out.println(i + " - " + squares);
        }
    }
}
```
<h5>Divide two variables</h5>
<ul>
    <li>Declare two integer variables x and y, and assign 20 to x and 6 to y.</li>
    <li>Divide x by y (i.e., perform integer division x/y) and print the result.</li>
</ul>
<p>Java solution:</p>

```Java
public class Main {
    public static void main(String[] args) {
        // Write your code here
        int a = 20;
        int b = 6;
        System.out.println(a / b);
        
    }
}
```
<h5>Convert temperature</h5>
<p>Declare a variable "temperature" and initialise it with a value of 25.5 (in Celsius) and Print it in Celsius and Kelvin(add 273 to temperature in Celsius).
Print the output in the same format as given below.</p>
<h5>Output</h5>

```
Celsius - 25.5  
Kelvin - 298.5
```
<p>Java solution:</p>

```Java
public class Main {
    public static void main(String[] args) {
        // Your code goes here
        float celsius = 25.5f;
        int kelvin = 273;
        float temperature = (float) celsius + kelvin;
        System.out.println("Celsius - " + celsius);
        System.out.println("Kelvin - " + temperature);
    }
}
```
