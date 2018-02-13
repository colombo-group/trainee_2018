- Tạo 1 jquery plugin để áp dụng hiệu ứng cho 1 thành phần div bên trong 1 div cha như hình vẽ. 

![normal](imgs/jquery_normal.png)
- div cha có chiều cao được định sẵn, khi kéo trình duyệt lên nhưng chưa qua điểm cuối của div cha thì div con trôi dọc theo và cố định cách viền trên của trình duyệt 1 khoảng `a px`

![normal](imgs/jquery_scroll_1.png)
- khi kéo trang web đi qua điểm cuối của trình duyệt thì cả 2 div đều bị kéo theo

![normal](imgs/jquery_scroll_2.png)
- Giả sử div con có id `almost-show` thì chỉ cần gọi
```
$('#almost-show').inner_float({
    top: "10px"
});
```

- Sau khi thực hiện, paste js và css của bạn vào đây để test [jsfiddle](https://jsfiddle.net/vuthaihoc/waru6d83/)