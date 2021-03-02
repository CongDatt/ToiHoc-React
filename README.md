# Đây là hành trình học React của tôi
## 1. Giới thiệu về ReactJS 
- React là thư viện JavaScript phổ biến nhất để xây dựng giao diện người dùng (UI). 
- Được phát triển bởi Facebook. Nó được ra mắt như một công cụ JavaScript mã nguồn mở vào năm 2013.
<p text-align="center"> 
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png"
</p>
  
## 2. Components
- React chia nhỏ các phần của trang thành từng phần riêng biệt, gọi là component, ví dụ như các phần: header, footer, sidebar, navigation, itemList,...
- 2 cách viết Function và Class Components:
  - Function `function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}`
  - Class `class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}`
- Render Component với props name có giá trị là "Sara": `const element = <Welcome name="Sara" />;`

## 3. JSX
- **Lưu ý:** Vì JSX gần với JavaScript hơn là so với HTML, React DOM sử dụng chuẩn quy tắc đặt tên camelCase cho thuộc tính thay vì dùng tên thuộc tính gốc của HTML.
- là một cú pháp mở rộng cho JavaScript. Chúng tôi khuyến khích sử dụng JSX với React để mô tả giao diện (UI). JSX có thể trông giống Ngôn ngữ Khuôn mẫu (Template language), nhưng JSX đi kèm với toàn bộ tính năng của JavaScript.
- Expressions in JSX dùng `{ }`
  - Ví dụ: `const myelement = <h1>React is {5 + 5} times better with JSX</h1>;`
- Dùng thẻ con trong JSX `const element = <img src={user.avatarUrl} />;`

## 4. Props
-
