# Handwritten Digit Recognition

## Mô tả
Đây là ứng dụng **Nhận diện số viết tay theo thời gian thực** có thể dự đoán đầu ra tương ứng với hình ảnh viết tay. Tôi đã sử dụng CNN (Mạng Neural tích chập) để tạo mô hình dự đoán này. Tôi đã huấn luyện mô hình với tập dữ liệu MNIST.

Giao diện được tạo bằng cách sử dụng Pygame. Quá trình xử lý hình ảnh là quan trọng nhất trong dự án này mà tôi đã thực hiện bằng cách sử dụng Scipy và OpenCV.

## Bộ dữ liệu
MNIST là bộ dữ liệu được sử dụng rộng rãi cho nhiệm vụ phân loại chữ số viết tay. Nó bao gồm 70.000 hình ảnh 28x28 pixel được dán nhãn của các chữ số viết tay. Bộ dữ liệu được chia thành 60.000 hình ảnh huấn luyện và 10.000 hình ảnh thử nghiệm. Có 10 lớp (một lớp cho mỗi chữ số trong số 10 chữ số). Nhiệm vụ là huấn luyện một mô hình bằng cách sử dụng 60.000 hình ảnh huấn luyện và sau đó kiểm tra độ chính xác phân loại của nó trên 10.000 hình ảnh thử nghiệm.

## Dữ liệu minh họa
Dưới đây là một số hình ảnh mẫu của ký tự viết tay từ tập dữ liệu MNIST:

![alt text](https://github.com/Raggza/hinh/blob/main/MNIST/mnist_sample_digits.png)

## Cách sử dụng:
1. Download hoặc clone repository này.
2. Giải nén.
3. Chạy chương trình **app.py**. Màn hình Pygame sẽ hiện ra như thế này:

![alt text](https://github.com/Raggza/hinh/blob/main/MNIST/app.png)

**Lưu ý:** Thay đổi đường dẫn đến mô hình **MNIST_model.h5**.

4. Vẽ số ở màn hình bên trái và sau đó chương trình sẽ nhận diện và đưa ra kết quả ở màn hình bên phải.
5. Các thao tác xử lý:
   - Chuột trái: Sử dụng để vẽ số.
   - Chuột phải: Reset lại màn hình của chương trình.

## Kết quả:

![alt text](https://github.com/Raggza/hinh/blob/main/MNIST/result.png)

 
