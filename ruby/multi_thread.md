# Concurrency != parallelism
1. Concurrency: Lam viec vs nhieu task cung luc
=> Bai toan diem danh.
  - ban dau:
     Theo tuan tu Diem danh theo danh sach a,b,c
     Neu `b` chua den thi hoc sinh c phai cho cho den khi `b` ket thuc.
  - Concurrency: 
    Hoc sinh nao den truoc thi diem danh truoc.
    Xu ly bat dong bo.
2. Parallelism: Xu ly nhieu task cung luc.
  - Paralleism:
    Lop co 50 hoc sinh => co 50 tap va 50 cay viet cho hoc sinh diem danh.
# Luu y
1. Tai 1 thoi diem chi 1 Thread duoc quyen truy cap du lieu chung
2. Ket qua cua chuong trinh da luong phai chinh xac nhu khi chay chuong trinh don luong.

# Problem
  - Deadlock
     la chuyen xay ra khi 2 ung dung doi tai nguyen lan nhau => loop vo tan. 
  - Convoying problem
    Khi mot loat process phu thuoc chung vao mot tai nguyen,i
    nhung process chay cham nhat lai giu lock dau tien. Khien nhung thang nhanh hon phai cho.



