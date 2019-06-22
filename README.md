# DCT-Compression

Code này được tách ra làm thành 3 file riêng biệt, code này đã được chuyển về đầu ra có định dang .jpg 

**Cách chạy : run từng file zigzag.py -> image2RLE -> RLE2image**

Trong đó : 
- imange2RLE : đọc hình ảnh và biểu diễn thuật giải, áo dụng bước lượng tử hoá và mã hoá nó bằng việc sử dụng Run Length Encoding ( RLE ) 
- Dự liệu đã được mã hoá sẽ được ghi vào file text ( image.txt ) 
- RLE2image sẽ đọc dữ liệu từ file image.txt và giải mã nó thành hình ảnh, sau đó sẽ tự tạo hình ảnh đã nén trong cùng 1 folder 
