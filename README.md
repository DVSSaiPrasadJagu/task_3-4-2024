# task_3-4-2024
Q1: nested if
public class nested_if {
    public static void main(String[] args) {
        int rows = 5;

        for (int i = 1; i <= rows; ++i) {
            for (int j = 1; j <= i; ++j) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}

output:
*
* *
* * *
* * * *
* * * * * 

Q2: infinite for loop
public class infinite_for {
    public static void main(String[] args) {
        for (;;) {
            System.out.println("This is an infinite loop");
        }
    }
}

Q3:Prime Number 

public class prime_num{
    public static void main(String[] args) {
        int n = 10;
        for (int i = 2; i <= n; i++) {
            if (i % 2 ==0){
                System.out.println("Prime Number is "+i);
            }
    }
}
}
