# Code-Test
A ={"NNLT Python", "Đại số tuyến tính", "Tiếng Anh chuyên ngành", "Thể dục"}
print(A)
B = {"NNLT Python", "Đại số tuyến tính", "Tối ưu hóa", "Học Máy", "Học sâu", "Computer vision", "Natural Language Processing", "Recommender Systems"}
print(B)
#C=A giao B
C=A.intersection(B)
print('Kết quả A giao B là',C)
#D=A hợp B
D=A.union(B)
print('Kết quả của A hợp B',D)
#E=A/B và F=B/A
E = A.difference(B)
F = B.difference(A)
print('kết quả A/B',E)
print('Kết quả B/A',F)
x = [1, 1, 1, 2, 2, 3, 3 ,3, 4 ,5 ,6, 7]
x=set(x)
print(x)
