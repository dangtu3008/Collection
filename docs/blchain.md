## Blockchain

### 5 điều sẽ phát triển mạnh sẽ cùng với sự phổ biến của Blockchain từ nay về sau
- Các dịch vụ phi tập trung.
- Gửi và lưu trữ giá trị.
- Quản lý quyền sở hữu.
- Sự gia tăng của dữ liệu công khai và đáng tin cậy.
- Giao dịch “trustless”.

### Dịch vụ phi tập chung
- Một ví dụ cơ bản cho khái niệm phi tập trung là chúng ta có thể mượn một thứ gì đó mà không có ai kiểm soát dữ liệu của chúng ta (không có bên trung gian).
- Tại sao `Blockchain` có thể thực hiện hóa việc đó?
  + Đó là vì chúng ta có thể khẳng định những dữ liệu được trao đổi thông qua Blockchain là đúng.
  + Thực ra thì từ trước đến giờ chúng ta vẫn có những “dữ liệu đúng”. Tuy nhiên thường có những mối e ngại về việc chúng bị làm giả hay bị ghi đè lên. Blockchain có những cơ chế để không chấp nhận những dạng dữ liệu không chính xác như vậy.
- Blockchain với những cơ chế xác nhận tính đúng đắn của dữ liệu, có thể loại bỏ sự cần thiết của bên những thứ ba này. Qua đó hiện thực hoá sự phi tập trung (decentralized).
- Vậy Blockchain làm điều đó như thế nào?
  + Ví dụ về một giao dịch trong Bitcoin. Trong đó có ghi chép đầy đủ các thông tin như là số tiền hay là thời gian giao dịch. Những dữ liệu này được lưu vào một “sổ cái” duy nhất trên toàn thế giới. Những thông tin về lịch sử giao dịch được lưu vào trong các khối (block) như hình trên và được nối liền với nhau thành một chuỗi (chain) nên chúng ta có khái niệm Chuỗi khối hay là Blockchain. Tuy nhiên nếu chỉ đơn giản như thế thì rõ ràng là dữ liệu hoàn toàn có thể bị làm giả. Blockchain có một giải pháp, nếu không tìm ra một con số ma thuật tên là số Nonce thì sẽ không thể nào ghi dữ liệu vào sổ cái được. Một máy tính “thông minh” với tốc độ xử lý cao cũng phải mất tầm 10 phút để tìm ra con số này. Do việc tìm ra con số Nonce này có thể nhận thù lao từ Blockchain, do đó rất nhiều người trên thế giới tham gia vào qua trình tìm kiếm này. Quá trình này được gọi tên là mining và người tham gia được gọi là miner. Hiện tại chúng ta đang có hàng triệu miner trên toàn thế giới. 
  + Mọi thứ diễn ra theo trình tự như hình trên. Khi có một giao dịch nào đó được tạo ra, yêu cầu ghi giao dịch đó vào sổ cái sẽ bắt đầu. Chỉ khi thông tin giao dịch được ghi vào sổ cái thì lúc đó nó mới chính thực được xác nhận và thực thi. Lúc này trên toàn thế giới các miner bắt đầu nhảy vào tìm số Nonce để xác thực và lưu dữ liệu trên vào sổ cái. Và sau khi một miner tìm ra số này, thì các miner khác sẽ kiểm chứng xem con số đó có đúng hay không. Chỉ trong trường hợp con số đó đúng thì dữ liệu về giao dịch mới được ghi vào trong sổ cái. Theo cách làm trên, nếu một người xấu muốn đưa một dữ liệu sai vào sổ cái thì phải lừa được vài triệu người. Thực hiện việc này là không thể. Với cơ chế này mà những dữ liệu được ghi vào trong Blockchain luôn được đảm bảo là đúng!
- Vậy thì cụ thể hơn, một giao dịch trong một hệ thống phi tập trung là gì, và những điều gì có thể được hiện thực hoá trong cuộc sống?
  + Hãy cũng lấy ví dụ về mô hình chia sẻ ô tô – Car share ở Nhật Bản. Từ trước đến này có một vài dịch vụ như vậy, nhưng luôn có công ty đứng ở giữa để vận hành quản lý xe và các thông tin liên quan. Tuy nhiên, nếu dùng Blockchain, chúng ta có thể xây dựng được một hệ thống Car share cho một vùng nào đó mà không cần đến bên thứ ba. Ví dụ chúng ta sẽ có một dịch vụ mà những người sử dụng sẽ cùng mua token và thống nhất với nhau về việc sử dụng token đó để mua và sử dụng xe. 

>Source: [Hiểu nhanh về Blockchain trong 10 phút](https://techtalk.vn/hieu-nhanh-ve-blockchain-trong-10-phut.html)
