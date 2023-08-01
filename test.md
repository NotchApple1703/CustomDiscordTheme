# Part 3 - MHP Key Management Service
## - COLLAB WITH PPP (PYTHON PROTECTION PROJECT) 💖💖💖

Hi, vậy là sau 3 tuần thì Python Protection Project đã phải kết thúc series với 3 phần riêng biệt, cũng là góp phần tri thức nhỏ để giúp mọi người bảo vệ mã nguồn Python của mình tốt hơn. Phần 3 của project này là một thứ hoàn toàn mới, sau khi khảo sát thì mình thấy các bạn đồng tình với việc trả phí nên mình đã quyết định làm project này 💖

### TÍNH NĂNG NỔI BẬT
- Khả năng kiểm soát sản phẩm của bạn dễ dàng.
- Bảo vệ sản phẩm của bạn khỏi bị sử dụng trái phép.
- Build trên Python, API dễ sử dụng.

### SIMPLE INSTALLATION
pip install MHPKMS
hoặc
git clone https://github.com/MHP0920/MHPKMS.git

### HOW IT WORKS?
Được lên ý tưởng và nghiên cứu lâu dài về các công nghệ bảo mật cũng như bảo mật trong Python, MHPKMS quyết định sử dụng công nghệ quản lí key để hướng đến các khách hàng đang làm về app, game, automation, nhưng muốn bán sản phẩm theo thời gian sử dụng. Cơ chế của MHPKMS rất đơn giản, chỉ với thao tác đơn giản là nhập key, bạn có thể giới hạn được người dùng muốn sử dụng sản phẩm của bạn.

### USAGE EXAMPLE
API = Client(client_key="client_key", keys="key", appid="appid", clear=False) # Khởi tạo Client
hoặc
API = Client() # Khởi tạo Client
API.set_client("client_key") # Thêm client key
API.set_keys("key") # Thêm key
API.set_appid("appid") # Thêm appID
API.set_clearmode(False | True) # Set chế độ xóa màn hình

**Tìm hiểu thêm tại trang chủ:**
*https://mhpkms.mhpteam.dev*
*https://github.com/MHP0920/MHPKMS*

*#share #python #keymanagement #mhpkms*
