# Pc java


```java
class Slope {
    static int slope(int y2,int y1,int x2,int x1) {
        return (y2/y1)/(x2-x1);
    }
}
```
```java
class Slope {
    static int slope(int[] arr) {
        return (arr[0]-arr[1])/(arr[2]-arr[3]);
    }
}
```
```java
class Slope {
  Slope();
       0: aload_0
       1: invokespecial #1                  // Method java/lang/Object."<init>":()V
       4: return


  static int slope(int, int, int, int);
       0: iload_0
       1: iload_1
       2: isub
       3: iload_2
       4: iload_3
       5: isub
       6: idiv
       7: ireturn

}
```
```java
class Slope {
  Slope();
       0: aload_0
       1: invokespecial #1                  // Method java/lang/Object."<init>":()V
       4: return


  static int slope(int[]);
       0: aload_0
       1: iconst_0
       2: iaload
       3: aload_0
       4: iconst_1
       5: iaload
       6: isub
       7: aload_0
       8: iconst_2
       9: iaload
      10: aload_0
      11: iconst_3
      12: iaload
      13: isub
      14: idiv
      15: ireturn

}
```
# andriod java
```java
class Slope {
    static int slope(int y2,int y1,int x2,int x1) {
        return (y2/y1)/(x2-x1);
    }
}
```
```java
// Type your code here, or load an example.
class Slope {
    static int slope(int[] arr) {
        return (arr[0]-arr[1])/(arr[2]-arr[3]);
    }
}
```
```java
.class LSquare;
.super Ljava/lang/Object;
.source "example.java"


# direct methods
.method constructor <init>()V
    .registers 1

    .line 2
    invoke-direct {p0}, Ljava/lang/Object;-><init>()V

    return-void
.end method

.method static slope(IIII)I
    .registers 4

    .line 4
    sub-int/2addr p3, p2

    sub-int/2addr p1, p0

    div-int/2addr p3, p1

    return p3
.end method
```
```java
.class LSlope;
.super Ljava/lang/Object;
.source "example.java"


# direct methods
.method constructor <init>()V
    .registers 1

    .line 2
    invoke-direct {p0}, Ljava/lang/Object;-><init>()V

    return-void
.end method

.method static slope([I)I
    .registers 4

    .line 4
    const/4 v0, 0x0

    aget v0, p0, v0

    const/4 v1, 0x1

    aget v1, p0, v1

    sub-int/2addr v0, v1

    const/4 v1, 0x2

    aget v1, p0, v1

    const/4 v2, 0x3

    aget p0, p0, v2

    sub-int/2addr v1, p0

    div-int/2addr v0, v1

    return v0
.end method
```