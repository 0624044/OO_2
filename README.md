# 0624044 施宜揚

## 0624044 施宜揚

### 0624044 `施宜揚`

#### 0624044 施宜揚

##### 0624044 施宜揚

###### 0624044 施宜揚

:rage:
:monkey_face:
:one::eight::u7981:

```早安你好```

> 高雄市
>> 大寮鄉

* 1
* 2
* 3 
***
[高科大](https://www.nkust.edu.tw/)

**改變**成*真* ~~持續發生~~

|靠左   |置中     |靠右  |
|:-----|:------:|-----:|
|:one:|:two:|:three:|
|:four:|:five:|:six:|
|:seven:|:eight:|:nine:|

``` js
public static void quickSort(int[] array, int begin, int end) {
    if (end <= begin) return;
    int pivot = partition(array, begin, end);
    quickSort(array, begin, pivot-1);
    quickSort(array, pivot+1, end);
} 
```

![NKUST](nkust.png "高科大")

[![Everything Is AWESOME](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

###
``` js
abstract class CShape
{
    protected String color;
    public void setColor(String str)
    {
        color=str;
    }
    public abstract void show();
}

 class CTriangle extends Cshape
{
    protected double a,b,c;
    public CTriangle(double a,doucle b,double c)
    {
        this.a=a;
        this.b=b;
        this.c=c;
    }
}

public void show()
{
    System.out.println("color="+color+", ");
    System.out.println("area="+0.5*a*b);
}

public class app11_1
{   
    public static void main(String args[])
    {
        CTriangle tri=new CTriangle(3,4,5);
        tri.setColor("Red");
        tri.show();        
    }
}
```
###
``` js
public interface Shape {
   double getArea();
}

public class Rectangle implements Shape {  
   private double length;
   private double width;

  
   public Rectangle(double length, double width) {
      this.length = length;
      this.width = width;
   }

   @Override
   public String toString() {
      return "Rectangle[length=" + length + ",width=" + width + "]";
   }

   @Override
   public double getArea() {
      return length * width;
   }
}

public class Triangle implements Shape {
   
   private int base;
   private int height;

   public Triangle(int base, int height) {
      this.base = base;
      this.height = height;
   }

   @Override
   public String toString() {
      return "Triangle[base=" + base + ",height=" + height + "]";
   }

   @Override
   public double getArea() {
      return 0.5 * base * height;
   }
}
```
