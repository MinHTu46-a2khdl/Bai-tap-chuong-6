6.1
print("**    **    ******    **          **       *******")
print("**    **    **        **          **       **   **")
print("********    ******    **          **       **   **")
print("**    **    **        **          **       **   **")
print("**    **    ******    ******      ******   *******")
6.2
def tinh_toan():
  x = 10
  y = 5

  print("x=10 y=5")
  print("Tổng x+y={}".format(x + y))
  print("Hiệu x-y={}".format(x - y))
  print("Tích x*y={}".format(x * y))
  print("Thương x/y={}".format(x / y))

tinh_toan()
6.3
# Nhập dữ liệu
ten_hang = input("Tên hàng: ")
so_luong = int(input("Số lượng: "))
don_gia = int(input("Đơn giá: "))

# Tính tiền phải trả
tien_phai_tra = so_luong * don_gia

# Xuất kết quả
print("Tên hàng:", ten_hang)
print("Số lượng:", so_luong)
print("Đơn giá:", don_gia)
print("Tiền phải trả:", tien_phai_tra)
6.4

#Yêu cầu 1 
print("(5-3)//2=",(5-3)//2)
# yêu câù 2
print("8-3*2-(1+1)",8-3*2-(1+1))
6.5
# Nhập dữ liệu
so_luong = int(input("Nhập số lượng: "))
don_gia = int(input("Nhập đơn giá: "))

# Tính tiền hàng
tien_hang = so_luong * don_gia

# Xuất kết quả
print("Thành tiền:", tien_hang)
6.6
 # Nhập dữ liệu
so_keo = int(input("Nhập số lượng kẹo: "))
so_nguoi = int(input("Nhập số người: "))

# Tính số kẹo mỗi người được chia
so_keo_moi_nguoi = so_keo // so_nguoi

# Tính số kẹo dư
so_keo_du = so_keo % so_nguoi

# Xuất kết quả
print("Số kẹo mỗi người được chia:", so_keo_moi_nguoi)
print("Số kẹo dư:", so_keo_du)
6.7
# Nhập dữ liệu
do_C = float(input("Nhập nhiệt độ C: "))

# Tính nhiệt độ F
do_F = 9 / 5 * do_C + 32

# Xuất kết quả
print("Nhiệt độ F:", do_F)
6.8
# Nhập dữ liệu
s1 = input("Nhập chuỗi s1: ")
s2 = input("Nhập chuỗi s2: ")
s3 = input("Nhập chuỗi s3: ")

# Tính chiều dài của các chuỗi
len_s1 = len(s1)
len_s2 = len(s2)
len_s3 = len(s3)

# Tạo chuỗi s4 từ S1 với nội dung từ index đến hết chuỗi
index = int(input("Nhập chỉ số index: "))
s4 = s1[index:]

# Lặp lại chuỗi S2 : 2 lần
s2_lap = s2 * 2

# Xuất kết quả
print("Chiều dài của chuỗi s1 là:", len_s1)
print("Chiều dài của chuỗi s2 là:", len_s2)
print("Chiều dài của chuỗi s3 là:", len_s3)
print("Chuỗi s4 là:", s4)
print("Chuỗi s2 lặp lại 2 lần là:", s2_lap)
6.9
# Nhập dữ liệu
so_tien_gui = int(input("Nhập số tiền gửi: "))
lai_suat = float(input("Nhập lãi suất: "))
so_thang_gui = int(input("Nhập số tháng gửi: "))

# Tính tiền lãi
tien_lai = so_tien_gui * lai_suat * so_thang_gui / 12

# Tính tổng số tiền nhận được
tong_so_tien = so_tien_gui + tien_lai

# Xuất kết quả
print("Tiền lãi:", tien_lai)
print("Tổng số tiền nhận được:", tong_so_tien)
