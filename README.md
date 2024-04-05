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
Q4:
i)
without condition:
public class App{
    public static void main(String[] args) throws Exception {
        int i = 90;
        for (;;) {
            System.out.println(i);
            i++;
        }
        
    }
}
Output:
infinite loop which never end

ii)
public class ForLoop {
    public static void main(String[] args) {
   
    int i = 90;
    for (; i < 100; i++) {
        System.out.println(i);
    }
    }
}
Output:
90
91
92
93
94
95
96
97
98
99

iii)
public class ForLoop {
    public static void main(String[] args) {
  

    int i = 90;
for (; i < 100; i += 2) {
    System.out.println(i);
}

    }
}
output:
90
92
94
96
98
iv)
public class ForLoop {
    public static void main(String[] args) {
   
int i=90;
for(;i>100;i--){
    System.out.println(i);
}

    }
}

output:
[{
	"resource": "/C:/Users/Jagu'$/Desktop/condition.java",
	"owner": "_generated_diagnostic_collection_name_#2",
	"code": "16",
	"severity": 4,
	"message": "condition.java is a non-project file, only syntax errors are reported",
	"source": "Java",
	"startLineNumber": 1,
	"startColumn": 1,
	"endLineNumber": 1,
	"endColumn": 1
}]
