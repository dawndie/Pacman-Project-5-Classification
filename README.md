# Pacman-Project-5-Classification
## Câu 1:
Với mỗi vòng lặp thì ta sẽ duyệt qua các tập dữ liệu rồi thực hiện predict. Nếu y_pred khác với y thì weight[y] sẽ được cộng thêm X, weights[y_pred] sẽ bị trừ đi X
## Câu 2:
Chúng ta sẽ chạy 100 lần, mỗi lần tìm ra argMax, thêm argMax vào output và update lại weights bằng giá trị âm vô cùng để có thể tìm được giá trị max tiếp theo Sau khi cho chạy thấy giống hình a
## Câu 3:

## Câu 4:
Đếm được số thành phần liên thông của các pixel trắng trong tập dữ liệu đó. Sử dụng thuật toán dfs để tính số thành phần liên thông trong hàm cc. Sau khi tính được số thành phần liên thông ta sẽ thêm ra 3 feature đó là số thành phần lớn hơn 1, lớn hơn 3 và lớn hơn 5, các feature này dạng nhị phân
