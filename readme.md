# Các thẻ HTML và CSS cơ bản

## 1. Các thẻ HTML cơ bản

### 1.1. Thẻ tiêu đề

- Thẻ tiêu đề HTML được sử dụng để tạo tiêu đề cho trang web của bạn.
- Có 6 cấp độ tiêu đề từ h1 đến h6, trong đó h1 là tiêu đề lớn nhất và h6 là tiêu đề nhỏ nhất.
- Cú pháp:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

### 1.2. Thẻ đoạn văn

- Thẻ đoạn văn được sử dụng để tạo đoạn văn trong trang web của bạn.
- Cú pháp:

```html
<p>This is a paragraph.</p>
```

### 1.3. Thẻ định dạng văn bản

- Thẻ định dạng văn bản được sử dụng để định dạng văn bản trong trang web của bạn.
- Cú pháp:

```html
<b>This text is bold</b> 
<strong>This text is strong</strong>
<i>This text is italic</i>
<em>This text is emphasized</em>
<mark>This text is marked</mark>
<small>This text is small</small>
<del>This text is deleted</del>
<ins>This text is inserted</ins>
<sub>This text is subscripted</sub>
<sup>This text is superscripted</sup>
```

### 1.4. Thẻ danh sách

- Thẻ danh sách được sử dụng để tạo danh sách trong trang web của bạn.
- Có 3 loại danh sách: danh sách không sắp xếp, danh sách sắp xếp và danh sách định nghĩa.
- Cú pháp:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>

<dl>
  <dt>Item 1</dt>
  <dd>Description 1</dd>
  <dt>Item 2</dt>
  <dd>Description 2</dd>
  <dt>Item 3</dt>
  <dd>Description 3</dd>
</dl>

```

### 1.5. Thẻ liên kết

- Thẻ liên kết được sử dụng để tạo liên kết đến trang web khác hoặc tài liệu khác.
- Cú pháp:

```html
<a href="https://www.google.com">Visit Google</a>
```

### 1.6. Thẻ hình ảnh

- Thẻ hình ảnh được sử dụng để hiển thị hình ảnh trong trang web của bạn.
- Cú pháp:

```html
<img src="image.jpg" alt="Image">
```

### 1.7. Thẻ bảng

- Thẻ bảng được sử dụng để tạo bảng trong trang web của bạn.
- Cú pháp:

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>

```

### 1.8. Thẻ biểu mẫu

- Thẻ biểu mẫu được sử dụng để tạo biểu mẫu trong trang web của bạn.
- Cú pháp:

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">
  <input type="submit" value="Submit">
</form>

```

## 2. Các thẻ CSS cơ bản

### 2.1. Thẻ định dạng văn bản

- Thẻ định dạng văn bản CSS được sử dụng để định dạng văn bản trong trang web của bạn.
- Cú pháp:

```css
p {
  color: red;
  font-size: 16px;
  font-family: Arial, sans-serif;
}
```

### 2.2. Thẻ định dạng hình ảnh

- Thẻ định dạng hình ảnh CSS được sử dụng để định dạng hình ảnh trong trang web của bạn.
- Cú pháp:

```css
img {
  width: 100%;
  height: auto;
  border-radius: 50%;
}
```

### 2.3. Thẻ định dạng bảng

- Thẻ định dạng bảng CSS được sử dụng để định dạng bảng trong trang web của bạn.
- Cú pháp:

```css
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}
th {
  background-color: #f2f2f2;
}
```

### 2.4. Thẻ định dạng biểu mẫu

- Thẻ định dạng biểu mẫu CSS được sử dụng để định dạng biểu mẫu trong trang web của bạn.
- Cú pháp:

```css
form {
  width: 50%;
  margin: 0 auto;
}
label {
  display: block;
  margin-bottom: 5px;
}
input[type="text"], input[type="email"], input[type="submit"] {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
}
input[type="submit"] {
  background-color: #4CAF50;
  color: white;
  border: none;
}
```

## 3. Kết luận

- Trên đây là một số thẻ HTML và CSS cơ bản mà bạn cần biết khi bắt đầu học lập trình web.
- Hy vọng rằng bài viết này sẽ giúp ích cho bạn trong quá trình học tập và làm việc.
- Chúc các bạn thành công!

## Các cách viết CSS

### 1. Inline CSS

- Inline CSS được viết bên trong thẻ HTML.
- Cú pháp:

```html
<p style="color: red;">This is a paragraph.</p>
```

### 2. Internal CSS

- Internal CSS được viết bên trong thẻ `<style>` trong phần `<head>` của trang HTML.
- Cú pháp:

```html
<!DOCTYPE html>
<html>
<head>
<style>
p {
  color: red;
}
</style>

</head>
<body>

<p>This is a paragraph.</p>

</body>
</html>
```

### 3. External CSS

- External CSS được viết trong một tệp CSS riêng biệt và được liên kết với trang HTML bằng thẻ `<link>`.
