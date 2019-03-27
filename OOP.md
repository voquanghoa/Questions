1. Implement class `Triangle` với constructor chấp nhận 6 số nguyên là tọa độ 3 đỉnh. Class triangle phải có những hàm `getType()` trả về `Thuong`, `Can`, `Vuong`, `Vuong Can` hoặc `Deu`, hàm `getArea()` trả về diện tích và `getPerimeter()` trả về chu vi của tam giác. Viết chương trình nhập thông tin để test class

2. Viêt một chương trình nhập vào nhiều dòng, mỗi dòng có 3, 6 hoặc 8 số nguyên là thông tin của hình tròn, hình chữ nhật hoặc tứ giác như sau:

    - Hình tròn chứa x, y, r với tâm hình tròn (x, y) và bán kính r
    - Hình tam giác chứa 6 số x1, y1, x2, y2, x3, y3 tương ứng là tọa độ của 3 đỉnh
    - Hình tứ giác chứa 8 đỉnh

    Nhập vào số nguyên n và sau đó nhập n dòng như trên, mỗi dòng nhập thành một đối tượng hình học như trên. Cuối cùng, in ra thông tin danh sách đối tượng hình học đã chọn và in ra diện tích, chu vi của hình.

    Yêu cầu:
    - Viết `interface Shape` với các method `showInfo`, `getArea()`, `getPerimeter()`
    - Class `Circle`, `Triangle`, `Quadrilateral` implements `Shape`
    - Lưu danh sách đối tượng vào `ArrayList<Shape>`
    - Implement lớp ShapeFactory để khởi tạo đối tượng từ danh sách tham số

    TIP:
    - Khoảng cách giữa 2 điểm $l=\sqrt{(x_1-x_2)^2+(y_1-y_2)^2}$
    - Diện tích hình tròn $S=\pi r^{2}$
    - Chu vi hình tròn $C=2\pi r$ 
    - Diện tích tam giác $S=\sqrt{p(p-a)(p-b)(p-c)}$ với p là nửa chu vi
    - Diện tích tứ giác: Nếu vẽ đường chéo của tứ giác thì sẽ tạo ra 2 tam giác --> Tính tổng diện tích của 2 tam giác đó. Có tới 2 cách vẽ đường chéo --> có 2 tổng diện tích --> lấy min.

