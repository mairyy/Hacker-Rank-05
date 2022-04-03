# Hacker-Rank-05

Bài 1
Pointer
Tóm tắt: Viết hàm void update(int* a, int* b). Đầu vào là hai con trỏ tới hai biến kiểu nguyên.
Hàm cần cập nhật chính 2 biến nguyên đó bằng giá trị là tổng và trị tuyệt đối hiệu của hai số đó.

Bài 2
Vector-Sort
Tóm tắt: Dữ liệu vào gồm số n, và tiếp theo là n số nguyên. Hãy sắp xếp các số theo thứ tự
tăng dần và in ra. (Nên sử dụng hàm sort có sẵn để sắp xếp.)

Bài 3
Vector-Erase
Tóm tắt: Dữ liệu vào gồm số n ở dòng 1, và tiếp theo là n số nguyên ở dòng 2. Chú ý các số
nguyên được tính chỉ số từ 1. Dòng thứ 3 là chỉ số của phần từ cần bị xoá. Dòng thứ 4 gồm 2
số a và b, với yêu cầu là xoá đi phần tử a , a+1, …, b-1 (không xoá phần từ thứ b) của dãy kết
quả sau khi đã xoá phần tử ở dòng 3. In ra dãy số còn lại.

Bài 4
Lower Bound-STL
Tóm tắt: Dữ liệu vào gồm số n ở dòng 1, và tiếp theo là n số nguyên ở dòng 2. Chú ý các số
nguyên được tính chỉ số từ 1 và các số đã được sắp tăng dần.
Dòng thứ 3 là Q - số các test phải làm.
Mỗi test ở dòng tiếp theo gồm 1 giá trị nguyên Y. Yêu cầu với mỗi Y:
- Nếu Y có trong dãy số thì in ra
Yes - chỉ số tính từ 1 của số Y trong dãy.
- Nếu Y không có trong dãy thì in ra
No - chỉ số của giá trị nhỏ nhất nhưng lớn hơn Y (cận trên) trong dãy
Khi có nhiều giá trị bằng nhau thoả mãn điều kiện, chỉ cần in ra chỉ số nhỏ nhất.

Bài 5
Sets-STL
Tóm tắt: Cho Q thao tác (query). Mỗi thao tác thuộc 1 trong 3 loại:
- 1 x: Thêm x vào tập
- 2 x: Loại x khỏi tập (Nếu x không có, không làm gì cả)
- 3 x: Nếu x trong tập, in ra “Yes” còn nếu không in ra “No"
Dữ liệu vào gồm dòng đầu là Q - số lượng thao tác. Tiếp sau là Q dòng, mỗi dòng là một thao
tác với loại thao tác và x.
Hãy in ra Yes hay No phù hợp trên một dòng khi gặp thao tác loại 3.

Bài 6
Maps-STL
Tóm tắt: Khi xử lý điểm của sinh viên, cần làm một trong 3 loại thao tác:
- 1 X Y: cộng thêm điểm Y vào trong tổng điểm của sinh viên X
- 2 X: xoá đi điểm của sinh viên X
- 3 X: in ra tổng điểm của sinh viên X. (Nếu sinh viên X không có điểm thì in ra 0).
Dữ liệu vào gồm dòng đầu là Q - số lượng thao tác. Tiếp theo là Q dòng, mỗi dòng là một thao
tác với loại thao tác và tham số tương ứng.
Hãy in ra kết quả phù hợp trên một dòng khi loại thao tác là 3
