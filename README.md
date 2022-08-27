0: library
-universal-cookie
-react-hook-form

1: props

- attribute, destructuring
- prop " key " đặc biệt
- truyền hàm là callback
- props là campalCase
- khi nhiều props quá thì truyền nguyên 1 cục qua, đỡ xấu code
- tranformer trong dự án lớn ( xem sau )
  2 : DOM envent
- dùng function nào cũng được , miễn là dễ hiểu là được
- là gì ? là click click : onClick = ()=> {} => nếu nó dài thì xuống dòng
- UI k nên có logic
- xử lý là handleClick
- truyền function xong rồi lấy name truyền vào function đó trong component con
  3: dynamic component
- https://www.youtube.com/watch?v=5SU6P-cqoJw&t=626s
- check ở đây logic in render
- create function as component
- Component phải viết hoa , const Component = object[value] để tránh báo lỗi
  2:
- đọc về reactNode, reactElement , JSX.Elememnt
- https://blog.logrocket.com/using-react-children-prop-typescript/
