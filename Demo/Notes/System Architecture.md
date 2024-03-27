up:: [[Parallel Computing MOC]]
tags:: #on/hust 

# System Architecture
## Kiến trúc Von Neuman

## Kiến trúc song song
- Đặc điểm:
	- Giữ nguyên thiết kế cơ bản của Von Neumann
	- Tập các bộ xử lý (cùng loại) kết nối với nhau theo 1 kiến trúc cùng với giao thức trao đổi dữ liệu và các quy tắc hoạt động.
	- Về cơ bản kiến trúc còn lại giống tuần tự
### Phân loại theo Flynn
- Đặc điểm:
	- Có nhiều cách phân loại máy tính song song, phân loại sử dụng rộng rãi từ năm 1966 được gọi là Flynn’s Taxonomy
	- Theo Flyn phân loại các kiến trúc máy tính bởi cách thực hiện các phép toán (instruction) trên các tập dữ liệu (data)
- Có 4 loại chính:
	- SISD: Single Instruction Single Data 
		- Mô hình máy tính tuần tự (Von-Neuman)
		- Single Instruction: Tại một thời điểm nào đó chỉ có một câu lệnh được thực hiện.
		- Single Data: Tại một thời điểm chỉ có một dữ liệu được thực hiện. Đơn vị dữ liệu do CPU xác định (CPU word)
		- Ví dụ: Máy tính cá nhân (PC), máy trạm (workstation),.. Đều thuộc dạng này
	- SIMD: Single Instruction Multiple Data - 2 kiến trúc phổ biến
		- Processor Arrays: mỗi đơn vị xử lý hoạt động trên data độc lập thông qua dòng lệnh riêng biệt
		- Single data: duy nhất dòng data được đưa vào nhiều units xử lý
		- Nguyên tắc: một data sẽ được thực hiện với nhiều câu lệnh trên các BXL khác nhau
		- Ít ví dụ thực tế
	- MISD: Multiple Instruction Single Data
	- MIMD: Multiple Instruction Multiple Data
