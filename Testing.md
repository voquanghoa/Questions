# Bài tập với Testing.

## Rules:

- Tất cả các bài giải đều được viết unit test
- Tất cả các hàm được implement đều được có test case trực tiếp
- Test coverage phải đạt 100%
- Tất cả các test case đều pass

## Bài tập:

1. Một địa chỉ email luôn ở dạng `username@domain`
    - Phần username chỉ được chứa các ký tự thường (chữ và số, dấu gạch dưới) và ký tự đặc biệt `.-`
    - Phần username không được phép chứa 2 ký tự đặc biệt liên tiếp
    - Phần username phải bắt đầu và kết thúc bởi ký tự thường
    - Phần domain chỉ được chứa ký tự thường và dấu chấm (.)
    - Phần domain bắt buộc phải có ít nhất 1 dấu chấm (.) và tối đa 3 dấu chấm (.)
    - Phần domain không được phép để dấu chấm ở đầu và ở cuối, không được phép để 2 dấu chấm liên tiếp nhau.

    Implement method kiểm tra một tham số string có định dạng là một email hay không.

2. Implement method nhận tham số là một số nguyên n, trả về kết quả là tổng của n số fibonacci đầu tiên.

3. Implement method nhận tham số là một string, xóa các ký tự giống nhau liên tiếp và giữ lại một. 
    Ví dụ `abbbbbbccccd eeffffddbc` thành --> `abcd efdbc`

4. Implement method nhận tham số là một mảng số nguyên, trả về kết quả là tổng các số tự nhiên (lớn hơn hoặc = 0) liên tiếp lớn nhất
    Ví dụ mảng [0, 1, -2, 8, 9, 0, 1, -2, 1, 1, 3, 1, 1] thì kết quả là 18

5. Implement method nhận tham số là mảng số nguyên, trả về kết quả là bội chung nhỏ nhất của của các số trong mảng

6. Implement method nhận tham số là mảng số nguyên, trả về kết quả là ước chung lớn nhất của của các số trong mảng

7. Implement method nhận tham số là hai string, kiểm tra 2 chuỗi đó có bộ ký tự giống nhau (có thể khác về thứ tự) hay không

8. Implement method nhận tham số là mảng số nguyên, ở mỗi số nguyên, ta đảo ngược thứ tự các chữ số để thành một số nguyên mới. Cuối cùng tính tổng các số nguyên đó và trả về kết quả