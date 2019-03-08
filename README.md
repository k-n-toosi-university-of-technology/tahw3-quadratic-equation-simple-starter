# TA HW3 - Quadratic Equation - 50 Points

Design a class named QuadraticEquation for a quadratic equation

**ax^2 + bx + c = 0**

The class contains:

- **Private** data fields a, b, and c that represent three coefficients.

- A constructor with three parameter to initialize a, b, and c.

- Three getter methods for a, b, and c.

- **Do not create any setter method**

- A method named `getDiscriminant()` that returns the discriminant, which is **b^2-4ac**


- The methods named `getRoot1()` and `getRoot2()` for returning two roots of the equation


<div dir="rtl" align="right">
در صورتی که معادله جواب نداشت و دلتای معادله منفی بود مقدار `Double.NaN` را برگردانید
    
سوال فوق را با رعایت سطوح دسترسی پیاده سازی کنید:
</div>

```java
package ir.ac.kntu;

public class QuadraticEquation{
    //your logic, fields and constructor is here
    //a,b,c data type is double, thus the return type of methods are double
    //all methods should be public: getRoot1,getRoot2,getA,...

}
```


<div dir="rtl" align="right">
پس از پیاده سازی این کلاس، کلاس دیگری برای استفاده و تست قابلیت‌های این کلاس تعریف کنید:

انجام دادن اینکار الزامی نیست و به هر مدلی که دوست دارید توابع کلاس خود را تست کنید و شی بسازید
</div>



```java
package ir.ac.kntu;

public class TestQuadraticEquation{
    public static void main(String[] args){
       //read the parameters from user
       //new QuadraticEquadion(paramters,....)
    }
}
```

<div dir="rtl" align="right">
دقت داشته باشید که همچنان سازنده کلاس معادله درجه 2 سه عدد از جنس double دریافت می کند.  
  
  دقت کنید که فقط یک سازنده تعریف کنید
  
  دقت کنید که در صورت عدم رعایت موارد کد تمییز تکلیف شما تا زمانی که این اشکالات را رفع نکنید قبول نمی شود.
</div>
