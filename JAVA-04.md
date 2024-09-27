1. 
 ```java
 //这个函数用于判断传入的年份是否为闰年
 //是闰年返回1，不是闰年返回2
static int isLeapYear(int year){  
    if (year%100!=0){  
        if (year%4==0){  
            return 1;  
        }else{  
            return 2;  
        }  
    }else{  
        if (year%400==0){  
            return 1;  
        }else{  
            return 2;  
        }  
    }  
}
```
2. 
 ```java
   static void print(int n){  
        int m=(n-3)/2;  
        int o=1;  
        int count=1;  
        for (int i=1;i<(n+1)/2;i++){  
            Print.print(" ");  
        }  
        Print.print("*");  
       for (int i=1;i<(n+1)/2;i++){  
           Print.print(" ");  
       }  
       Print.print("\n");  
       while(count<=(n-1)/2){  
           count++;  
           for (int i=1;i<=m;i++){  
               Print.print(" ");  
           }  
           Print.print("*");  
           for (int i=1;i<=o;i++){  
               Print.print(" ");  
           }  
           Print.print("*");  
           for (int i=1;i<=m;i++){  
               Print.print(" ");  
           }  
           Print.print("\n");  
           m--;  
           o+=2;  
       }  
       count=1;  
       m++;  
       o-=2;  
       while(count<=(n-3)/2){  
           count++;  
           m++;  
           o-=2;  
           for (int i=1;i<=m;i++){  
               Print.print(" ");  
           }  
           Print.print("*");  
           for (int i=1;i<=o;i++){  
               Print.print(" ");  
           }  
           Print.print("*");  
           for (int i=1;i<=m;i++){  
               Print.print(" ");  
           }  
           Print.print("\n");  
       }  
       for (int i=1;i<(n+1)/2;i++){  
           Print.print(" ");  
       }  
       Print.print("*");  
       for (int i=1;i<(n+1)/2;i++){  
           Print.print(" ");  
       }  
       Print.print("\n");  
   }  
  
}
```
*写的非常非常长，😭不好看*
