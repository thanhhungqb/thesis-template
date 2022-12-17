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

## Một số gợi ý về sử dụng
- Để đơn giản, demo chỉ bao gồm 1 file `demo-Chapter1.tex` và đặt ngay trong thư mục gốc, tuy nhiên nếu nhiều chương hay mỗi chương lại có nhiều section dài (đủ tách ra nhỏ hơn để viết cho gọn) thì nên tổ chức vào các thư mục con, tuy nhiên cũng không nên tách quá nhỏ vì sẽ rối
- figures nên được để trong 1 thư mục riêng, e.g., `figs`, và trong đó mỗi chapter nên có 1 thư mục con tương ứng (`figs/intro`, `figs/related-word`, etc.)
- Thực sự có chút khác biệt về font `Times New Roman` trên `latex`, setup hiện tại là đủ dùng trong phần lớn trường hợp, có thể tham khảo thêm về font tại đây https://tex.stackexchange.com/questions/270571/latex-12pt-is-different-from-actual-font-size-12-on-microsoft-word . Tuy nhiên, điều đó trong phần lớn các trường hợp là không thực sự cần thiết.

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
