## Write-up cách giải challenge
Sau khi kiểm tra 1 lượt với các tool cơ bản: file, strings, binwalk, foremost,... không có kết quả thì với zsteg, chúng ta đã thấy có dấu hiệu của flag:<br/>
![Pixel1](2.1.png)<br/>
Sau khi extract file png đó, chúng ta đã nhận được flag:<br/>
![Pixel2](2.2.png)<br/>
>Flag: IceCTF{puT_Th4t_1n_yoUr_cOlOrin9_Book_4nD_5moKe_1T}
## Write-up cách tạo challenge
Chúng ta sẽ sử dụng [StegOnline](https://github.com/Ge0rg3/StegOnline) để tạo chall dạng này.
Upload original file -> Embed Files/Data -> Điều chỉnh thông số và nhập Input Data hoặc Flag file:<br/>
![Pixel3](2.3.png)<br/>
Hoila!<br/>
![Pixel4](2.4.png)<br/>
Kết quả từ zsteg:<br/>
![Pixel5](2.5.png)<br/>
File được zsteg extract:<br/>
![Pixel6](2.6.png)<br/>
## Demo Challenge
[pixels-demo](pixels-demo.png)
