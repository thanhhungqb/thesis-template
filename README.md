# HCMUT Thesis/Dissertation Template

Đây là template sử dụng trong trình bày báo cáo luận văn tốt nghiệp cũng như thực tập tốt nghiệp. Ngoài ra, template này cũng có thể được sử dụng cho các báo cáo khác.

Mẫu này được thiết kế sử dụng cho sinh viên khoa máy tính ở Đại học Bách Khoa, Đại học Quốc Gia Hồ Chí Minh. Các sinh viên khác cũng có thể sử dụng nếu thấy mẫu trình bày hữu ích.

GitHub link: https://github.com/thanhhungqb/thesis-template

Overleaf link: https://www.overleaf.com/read/mhtyqqdbdbmg

# Sử dụng template này
Nếu bạn thấy mẫu này hữu ích và bắt đầu muốn sử dụng chúng thì bạn có thể làm theo hai cách:

1) Clone từ github theo đường link ở trên

2) Tạo từ template ở Overleaf: https://www.overleaf.com/latex/templates/hcmut-thesis-slash-dissertation-template/zsbhtnzktbsy

3) Clone Overleaf project:
- Đăng nhập Overleaf (có thể dùng tài khoản Gmail để đăng nhập hoặc [tạo mới tài khoản ](https://www.overleaf.com?r=2f24873e&rm=d&rs=b))
- Vào lại Overleaf project (refresh trang: https://www.overleaf.com/read/mhtyqqdbdbmg) và tạo bản copy để bắt đầu làm việc

## Điều chỉnh lại (số) thứ tự trích dẫn

Thường được làm khi đã hoàn thiện báo cáo, sắp in ra và muốn tự điều chỉnh lại thứ thứ theo mong muốn/quy định hơi khác biệt mà các style có sẵn chưa có:
 ví dụ, `trích dẫn tiếng Việt đưa lên trước` rồi mới tới các tài liệu tiếng Anh

(áp dụng với Overleaf, nếu build offline thì cũng tìm file tương tự)

- vào `Logs and output files` để tìm và lấy về file `output.bbl`
- copy toàn bộ nội dung file đó, lưu lại với tên mới (e.g., `manually.bbl`)
- Điều chỉnh lại theo thứ tự mình muốn/quy định, ví dụ, trích dẫn tiếng Việt đưa lên trước
- mở file `thesisdemo.tex` (hoặc file main mà bạn đã `đổi tên`)
- comment 2 dòng bibliography tự động sau:

    	\bibliographystyle{plain} % ieeetr
    	\bibliography{refs} 
- bỏ comment cho dòng sau để dùng chế độ manually
        
        \input{manually.bbl}


Hoan nghênh mọi góp ý cũng như đóng góp của các bạn.
