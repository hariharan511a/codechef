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
