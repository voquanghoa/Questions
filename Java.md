Các câu hỏi về Java

# Phần cơ bản

1. Ý nghĩa của lệnh import trong java
2. Lỗi stackoverflow là lỗi gì và thường gặp lúc nào
3. Biến static là gì
4. Stack và Heap là gì và được sử dụng như thế nào
5. Tại sao không nên dùng phép so sánh `==` với hai số thực
6. Trong java, việc so sánh `==` giữa hai chuổi ký tự được thực hiện như thế nào
7. String, StringBuffer và StringBuilder khác gì nhau?
8. Làm thế nào để thay đổi kích thước mảng trong quá trình chạy?
9. Trong câu lệnh `System.out.println("Hello world")` thì `System`, `out` và `println` là gì
10. Khối lệnh finally được sử dụng để làm gì (tại sao mình phải đặt một số lệnh trong khối `finally` thay vì viết trong `try`, `catch` hay đơn giản hơn là ở sau khối `try-catch`)
11. Từ khóa `throw` và `throws` có liên quan gì đến nhau.
12. Cho biết sự khác nhau giữa `++a` và `a++`

# Phần hướng đối tượng

1. Phân biệt sự khác nhau giữa `abstract class` và `interface`. Khi nào thì mình dùng `abstract class`, khi nào mình cần dùng `interface`
2. Tại sao Java không hỗ trợ đa thừa kế nhưng lại hỗ trợ đa `implement`
3. Từ khóa `this` là gì. Cú pháp `this(...)` là gì và lúc nào mình có thể dùng nó (`...` là danh sách tham số - nếu có)
4. Từ khóa `super` và cú pháp `super(...)` là gì và lúc nào mình có thể dùng nó (`...` là danh sách tham số - nếu có)
5. `Constructor` là gì, `Constructor` mặc định là gì
6. Biến/method static là gì
7. Tại sao từ một `static method` không thể gọi trực tiếp tới một `non-static method` trong khi có thể làm điều ngược lại.
8. Lớp `Object` dùng để làm gì
9. Phân biệt `Overloading` và `Override`
10. Có thể tạo được hai phương thức trong 1 class giống nhau về kiểu trả về, tên gọi, khác nhau về danh sách tham số nhưng không thể tạo 2 phương thức cùng tên gọi, cùng danh sách tham số nhưng khác nhau về kiểu trả về?
11. Từ khóa final có tác dụng gì nếu được khai báo cho lớp, method, biến.
12. Đa hình là gì
13. Default method là
14. `abstract method` là gì và tại sao phải sử dụng nó
15. Liệt kê `access level modify` và cho biết ý nghĩa
16. `Anonymous class` là gì
17. `Nested class` là gì
18. `Inner class` là gì
19. `Generic` là gì, tác dụng của nó trong lập trình
20. `Generic constraints` là gì
21. Cho biết b là đối tượng của lớp B. Khi nào thì câu lệnh `A a = (A)b`:
- Có thể sửa thành `A a = b` mà không có vấn đề gì
- Thành công
- Bị lỗi khi chạy
- Bị lỗi khi biên dịch
Những mã nguồn java sau bị lỗi, tìm lỗi đó và cho biết cách khắc phục

22. 
```java
class A extends B, C implements D, E{

}
```
23. 
```java
class A{
    public A(int t){}
    public A(int x, int y){}
}

class B extends A{
    public B(double x){

    }
}
```
24.
```java
interface A{
    void someMethod();
}

class Test{
    public void test(int x){
        new A{
            void someMethod(){
                Sysout.out.println("X = " + x);
            }
        }
    }
}
```

25
```java
private interface B{
    private void method();
}
```










