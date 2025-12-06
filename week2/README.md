# Giai đoạn 3: CSS – Làm đẹp và tạo layout trang web

---

## Phần 1: CSS cơ bản

1. **Hiểu CSS và cách tích hợp**
   - CSS là gì và vai trò trong việc tạo giao diện web
   - 3 cách tích hợp CSS: Inline, Internal, External
   - Cú pháp CSS cơ bản: `selector { property: value; }`
   - Sử dụng External CSS file (khuyến khích)

2. **CSS Selectors**
   - Element selector: `h1`, `p`, `div`
   - Class selector: `.class-name`
   - ID selector: `#id-name`
   - Descendant selector: `div p`
   - Grouping selector: `h1, h2, h3`

---

## Phần 2: Styling cơ bản

3. **Typography (Kiểu chữ)**
   - `font-family`: Chọn font chữ
   - `font-size`: Kích thước chữ
   - `font-weight`: Độ đậm nhạt (normal, bold)
   - `color`: Màu chữ
   - `text-align`: Căn chỉnh văn bản (left, center, right)
   - `line-height`: Khoảng cách dòng

4. **Background & Colors**
   - `background-color`: Màu nền
   - `background-image`: Hình nền
   - `background-size`: Kích thước hình nền
   - `background-position`: Vị trí hình nền
   - `background-repeat`: Lặp lại hình nền

5. **Box Model**
   - `width` và `height`: Kích thước phần tử
   - `padding`: Khoảng cách bên trong
   - `margin`: Khoảng cách bên ngoài
   - `border`: Viền phần tử
   - `box-sizing`: Cách tính kích thước (content-box, border-box)

---

## Phần 3: Layout và Positioning

6. **Display Property**
   - `display: block`: Hiển thị dạng khối
   - `display: inline`: Hiển thị dạng nội tuyến
   - `display: inline-block`: Kết hợp block và inline
   - `display: none`: Ẩn phần tử

7. **Positioning**
   - `position: static`: Vị trí mặc định
   - `position: relative`: Vị trí tương đối
   - `position: absolute`: Vị trí tuyệt đối
   - `position: fixed`: Vị trí cố định
   - `top`, `right`, `bottom`, `left`: Định vị phần tử

8. **Flexbox Layout**
   - `display: flex`: Tạo flex container
   - `flex-direction`: Hướng sắp xếp (row, column)
   - `justify-content`: Căn chỉnh theo trục chính
   - `align-items`: Căn chỉnh theo trục phụ
   - `flex-wrap`: Xuống dòng khi cần
   - `flex-grow`, `flex-shrink`, `flex-basis`: Thuộc tính flex item

---

## Phần 4: Responsive Design

9. **Media Queries**
   - `@media screen and (max-width: 768px)`: Responsive cho mobile
   - `@media screen and (min-width: 1024px)`: Responsive cho desktop
   - Breakpoints phổ biến: 320px, 768px, 1024px, 1200px

10. **Responsive Units**
    - `px`: Pixel (cố định)
    - `%`: Phần trăm (tương đối)
    - `em`: Tương đối với font-size của phần tử cha
    - `rem`: Tương đối với font-size của root element
    - `vw`, `vh`: Viewport width/height

---

## Phần 5: CSS Effects và Animations

11. **CSS Transitions**
    - `transition`: Chuyển đổi mượt mà
    - `transition-property`: Thuộc tính áp dụng transition
    - `transition-duration`: Thời gian transition
    - `transition-timing-function`: Hàm timing (ease, linear, ease-in-out)

12. **CSS Transforms**
    - `transform: translate()`: Di chuyển phần tử
    - `transform: scale()`: Thay đổi kích thước
    - `transform: rotate()`: Xoay phần tử
    - `transform: skew()`: Nghiêng phần tử

13. **CSS Animations**
    - `@keyframes`: Định nghĩa animation
    - `animation-name`: Tên animation
    - `animation-duration`: Thời gian animation
    - `animation-iteration-count`: Số lần lặp
    - `animation-direction`: Hướng animation

---

## Phần 6: Thực hành

14. **Styling lại trang Profile từ tuần 1**
    - Tạo file CSS external riêng biệt
    - Áp dụng typography đẹp mắt
    - Tạo layout responsive với Flexbox
    - Thêm màu sắc và background phù hợp
    - Tạo hiệu ứng hover cho các liên kết và button
    - Responsive design cho mobile và desktop

15. **Tạo trang Portfolio đơn giản**
    - Header với navigation menu
    - Hero section với giới thiệu
    - Skills section với các skill cards
    - Projects section với grid layout
    - Contact section với form styling
    - Footer với thông tin liên hệ
    - Responsive design hoàn chỉnh

16. **Bài tập bổ sung**
    - Tạo loading animation với CSS
    - Tạo card component với hover effects
    - Tạo responsive navigation menu
    - Tạo image gallery với CSS Grid
    - Tạo button với các trạng thái khác nhau

---

## Mục tiêu tuần 2

Sau khi hoàn thành tuần 2, trainee sẽ có thể:
- ✅ Hiểu và sử dụng CSS selectors cơ bản
- ✅ Styling typography, colors, và backgrounds
- ✅ Nắm vững Box Model và cách tính toán layout
- ✅ Sử dụng Flexbox để tạo layout responsive
- ✅ Áp dụng Media Queries cho responsive design
- ✅ Tạo hiệu ứng và animations cơ bản
- ✅ Tạo được trang web đẹp mắt và responsive

---

## Tài liệu tham khảo

- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Responsive Design Patterns](https://responsivedesign.is/)
