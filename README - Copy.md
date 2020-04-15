HTML, CSS HERO
PHẦN 1: GIỚI THIỆU
PHẦN 2: CHUẨN BỊ
    1. Visual studio code - live server
    2. Page ruler

PHẦN 3: KIẾN THỨC CỐT LÕI
 1. Attribute là thuộc tính của thẻ html và nằm trong thẻ mở
 2. Có 3 cách sử dụng css trong html: internal, external, inline
 3. Id và class là attribute dùng định danh cho đối tượng để sử dụng css. Trong 1 văn bản html id chỉ được định danh trong 1 đối tượng. Class có thể sử dụng tại nhiều đối tượng.
 4. Độ ưu tiên trong css:
    - internal, external
    - Inline
    - #id
    - .class
    - tag
    - equal specificity: 
    #sample-id.sapmple-class sẽ được ưu tiên hơn #sample-id
    - Universal selector and inherited
 5. Đặt tên biến trong css:
    - Cách đặt: —text-color
    - Sử dụng: color: var(—text-color);
 6. Đơn vị trong css
    - Có 2 loại: relative units (đv tương đối) như %, rem, em, vw, vh… và absolute units (đv tuyệt đối) như px, pt, cm….
    - 1px ở màn hình độ phân giải thấp có thể là 1 điểm ảnh nhưng ở màn hình độ phân giải cao có thể là rất nhiều điểm ảnh.
    - relative units sẽ phải phụ thuộc vào thẻ chứa nó. Độ rộng, dài của nó sẽ không cố định và sẽ bị thay đổi khi kích thước đối tượng nó phụ thuộc thay đổi
    - rem sẽ phụ thuộc vào thẻ html
    - em sẽ phụ thuộc vào thẻ gần nhất chứa nó mà có định dạng kích thước.
    - vw(viewport width): phần trăm độ rộng hiển thị của trình duyệt
    - vh(viewport height): phần trăm độ dài hiển thị của trình duyệt
    - Mặc định font-size: 100% = 16px
7. Padding, border sẽ làm thay đổi kích thước của element, là lớp gần content nhất
   Mặc định của border: solid là 2px.
   Các cách viết tắt:   
      /* 4 direction */
      padding: 10px;
      /* top, bottom and left, right */
      padding: 10px 10px;
      /* top and left, right and bottom */
      padding: 10px 12px 8px;
      /* top right bottom left */
      padding: 7px 8px 9px 10px;
8. Box-sizing: khi muốn sử dụng padding và border mà không muốn thay đổi kích thước của element.
   - box-sizing: border-box;
9. Background-clip: giới hạn phần đổ màu nền từ danh giới nào cho element.
   - background-clip: content-box. Chỉ đổ màu nền phần content.
   - background-clip: padding-box. Chỉ đổ màu nền phần content + padding.
   - Mặc định background-clip: border-box. Đổ màu content + padding + border.
10. 