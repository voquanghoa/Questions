# Bài tập Java/Kotlin

## I. Cấu trúc vòng lặp, hàm

1. Viết chương trình tìm ước số chung lớn nhất, bội số chung nhỏ nhất của hai số tự nhiên
2. Viết chương trình tìm tổng các chữ số của một số nguyên
3. Viết chương trình nhận vào một số nguyên và trả về cách phân tích số đó ra tích của thừa số nguyên tố. Ví dụ nhập vào 600 thì cần phải trả về `2 * 2 * 2 * 3 * 5 * 5`
4. Tương tự bài 3 nhưng cần in 600 thành `2^3 * 3 * 5^2`
5. Số fibonaci là dãy số bắt đầu từ 1 1 và sau đó, số tiếp theo bằng 2 số trước cộng lại. Tức là `1 1 2 3 5 8 ....`. Nhập vào số nguyên n, in ra danh sách những số fibonaci không lớn hơn n.
6. Viết phương trình giải phương trình bậc 2: 

    ![Phương trình bậc 2](https://latex.codecogs.com/gif.latex?ax^{2}&plus;bx&plus;c=0)

7. Viết phương trình nhập vào n và in ra tổng của dãy số
    ![Dãy số](https://latex.codecogs.com/gif.latex?1*2&plus;2*3&plus;3*4&plus;...&plus;n(n&plus;1))

8. Viết phương trình tính giai thừa `n!` của một số
9. Viết chương trình tính pi với độ sai số 0.0001 bằng công thức
    ![Pi](https://wikimedia.org/api/rest_v1/media/math/render/svg/e9e3959cd2d0ec735e7a6a1917df784842b76706)
9. Viết chương trình tính pi với độ sai số 0.00001 bằng công thức
    ![Pi](https://wikimedia.org/api/rest_v1/media/math/render/svg/fdafa8bd24ce2b6fd518a3cf253ad1ef409388a6)
10. Một ngân hàng trả lãi 100% sau 1 năm. Ví dụ mình gửi tiết kiệm 100 đồng thì sau 1 năm mình nhận về 200 đồng. Chia 1 năm thành n khoảng thời gian bằng nhau và tính lãi lũy tiến 100/n. Ví dụ n = 2 thì mình sẽ có mỗi khoảng thời gian là 6 tháng và lãi lũy tiến 50%. Lúc đó số tiền mình nhận được là 225 đồng. (Gốc 100 đồng, sau 6 tháng thành 100 + 50%= 150 đồng, sau 1 năm thành 150 + 50% = 225 đồng)


    Viết chương trình nhận vào số nguyên dương n là số khoảng thời gian, tính số tiền mình sẽ được nhận sau 1 năm.
11. Tính biểu thức sau đây với n nhập từ bàn phím
    ![Biểu thức](https://latex.codecogs.com/gif.latex?s=\frac{1}{0!}&plus;\frac{1}{1!}&plus;\frac{1}{2!}&plus;\frac{1}{3!}&plus;...&plus;\frac{1}{n!})

12. Tính e với độ chính xác 0.00001 với công thức
    ![E](https://wikimedia.org/api/rest_v1/media/math/render/svg/39a1c93d6f1fda7f20a9e45cd3e6f0c35a5eeb36)
13. Nhập vào a từ bàn phím, tính căn bậc hai của a với độ chính xác 0.0001 bằng công thức
    ![Căn](https://latex.codecogs.com/gif.latex?e=\sum_{n=0}^{\infty&space;}&space;=&space;\frac{1}{0!}&plus;\frac{1}{1!}&plus;\frac{1}{2!}&plus;\frac{1}{3!}&plus;\frac{1}{4!}...)

14. Nhập a, b, c là 3 cạnh của một tam giác. Kiểm tra tam giác có hợp lệ hay không, nếu tam giác hợp lệ thì in tiếp các thông tin:
    - Diện tích tam giác
    - Chu vi tam giác
    - Kiểu tam giác (vuông, cân hay bình thường)
15. Làm lại câu 14 nhưng đầu vào là x1, y1, x2, y2, x3, y3 là tọa độ 3 đỉnh.

16. Tìm những số nguyên n có m chữ số thỏa mãn điều kiện: tổng của các chữ số của n khi lũy thừa hệ số m thì đúng bằng n. Ví dụ n=153 là hợp lệ vì m=3, 1^3 + 5^3 + 3^3 = 153 (Giới hạn 2<=m<=5).

17. Số 23 khi viết nhị phân sẽ là 10111 khi viết ngược lại thành 11101 và nó thành số 29. Nhập số nguyên n và tìm số m bằng cách viết ngược thứ tự số binary như trên.

18. Nhập vào số nguyên n, in ra dòng thứ n của tam giác pascal [Tam giác pascal](https://vi.wikipedia.org/wiki/Tam_gi%C3%A1c_Pascal)

## II. Mãng số học

1. Viết chương trình tìm những số xuất hiện trên 2 lần trong một mảng số nguyên

2. Viết chương trình tìm tìm tổng của 3 số lớn nhất trong một mảng số nguyên

3. Viết chương trình tìm tổng của các số chẵn và trừ đi tổng các số lẻ trong một mảng số nguyên

4. Viết chương trình sắp xếp một mảng số nguyên sao cho các số chẵn ở bên trái, các số lẻ ở bên phải. Các số chẵn sắp xếp tăng dần, các số lẻ sắp xếp giảm dần

5. Viết chương trình tính tổng của các số nguyên tố trong một mảng số nguyên

6. Viết chương trình sắp xếp một mảng sao các số chẵn tăng dần, các số lẻ giảm dần. Ví dụ `2 11 4 6 7 10 3 14 1`

7. Viết chương trình tìm mãng con liên tiếp tăng dần dài nhất từ một mảng số nguyên

8. Viết chương trình tìm hiệu giữa số lớn nhất và số nhỏ nhất từ một mảng số nguyên

9. Viết chương trình sử dụng phương pháp tìm kiếm nhị phân để tìm kiếm một số nguyên từ một mảng số nguyên đã sắp xếp (tăng dần hoặc giảm dần), trả về vị trí nếu tìm thấy hoặc -1 nếu không tìm thấy

10. Viết chương trình chia một mảng số nguyên thành n mảng con có số lượng phần tử bằng nhau (Riêng mảng cuối cùng có thể có số phần tử ít hơn)

11. Viết chương trình tìm ra mãng con bằng cách đảo ngược các số lẻ với nhau và các số chẵn với nhau. Ví dụ `1 2 4 5 6 7 8 10` thành `7 10 8 5 6 1 4 2`

12. Viết chương trình chèn một số nguyên x vào một mảng số nguyên đã sắp xếp theo thứ tự tăng dần mà vẫn đảm bảo mảng kết quả tăng dần

13. Viết chương trình nhận vào một mảng 2 chiều, thực hiện việc quay mảng 90 độ theo chiều kim đồng hồ

14. Viết chương trình chuyển đổi một mảng 2 chiều thành mảng 1 chiều bằng cách đi theo hình xoắn ốc cùng chiều kim đồng hồ. 

Ví dụ ta có mảng

| 1  | 2  | 3  | 4  | 5  |
|----|----|----|----|----|
| 6  | 7  | 8  | 9  | 10 |
| 11 | 12 | 13 | 14 | 15 |

Kết quả mảng một chiều là 1 2 3 4 5 10 15 14 13 12 11 6 7 8 9

17. Viết chương trình tạo ma trận xoắn ốc có n dòng n cột và được điền các số từ 1 đến n*n. Ví dụ dưới đây với n = 5

| 1  | 2  | 3  | 4  | 5 |
|----|----|----|----|---|
| 16 | 17 | 18 | 19 | 6 |
| 15 | 24 | 25 | 20 | 7 |
| 14 | 23 | 22 | 21 | 8 |
| 13 | 12 | 11 | 10 | 9 |

18. Viết chương trình sắp xếp một ma trận số nguyên theo tứ tự tăng dần từ trên xuống dưới, phải qua trái

19. Viết chương trình sắp xếp một ma trận số nguyên theo tứ tự tăng dần từ hình xoắn ốc

20. Viết chương trình tạo ma trận con từ một ma trận các số nguyên ở vị trí x, y và kéo dài n cột, b dòng

21. Viết chương trình tính [định thức](https://vi.wikipedia.org/wiki/%C4%90%E1%BB%8Bnh_th%E1%BB%A9c) của một ma trận vuông

22. Viết chương trình xóa đi dòng thứ x và cột thứ y từ một ma trận và trả về ma trận con


## III. Xử lý chuỗi

Viết chương trình xử lý một chuổi ký tự (String)

1. Liệt kê các câu. (Các câu cách nhau bởi dấu chấm `.`, chấm hỏi `?`, chấm than `!` và xuống dòng `\n`)

2. Liệt kê các từ (một từ chỉ chứa a-z,0-9)

3. Kiểm tra chuỗi ký tự có đối xứng hay không. (Ví dụ abcdcba là đối xứng)

4. Tính tổng của các số nguyên trong chuỗi. Ví dụ `abc 123 def 33 mn 3.221` sẽ in ra 380 với 380 = 123+33+3+221

5. Tìm các từ xuất hiện trên 2 lần.

6. Xử lý chuỗi bằng cách biến các ký tự hoa thành ký tự thường, các ký tự thường thành ký tự hoa

7. Không sử dụng hàm tìm kiếm có sẵn, tìm vị trí một chuỗi con.

8. Chuẩn hóa chuỗi bằng các thao tác
    - Viết hoa tất cả các chữ cái đầu câu
    - Viết thường tất cả các chữ cái không phải đầu câu
    - Bỏ tất cả các khoảng trống dư thừa
    - Thêm khoảng trắng vào sau các dấu `.,?!`

9. Nhập vào một chuổi ký tự chứa toàn các chữ cái (a-z, A-Z). Rút gọn chuỗi bằng cách ở những nơi chữ cái lặp lại, ta viết số lần lặp. Ví dụ `abcccceeeeeefd` sẽ viết thành `abc4e6fd`, `abbbbbbbbbbbbbc` viết là `ab13c`

10. Nhập vào chuổi đã được viết gọn ở câu 22, dịch nó thành chuỗi lúc đầu.

