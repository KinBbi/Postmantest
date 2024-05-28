BÁO CÁO KIỂM THỬ API

Ngày Kiểm Thử: 28/05/2024

Người Kiểm Thử: Nguyễn Ngọc Hoàng Anh

Mục Tiêu Kiểm Thử: Sử dụng Postman để kiểm thử một API thực tế

Môi Trường Kiểm Thử: Postman.

Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Postman.

Giới thiệu Postman
Postman là một công cụ phát triển API và kiểm thử API rất phổ biến. Nó cung cấp một giao diện đồ họa dễ sử dụng cho phép bạn tạo, gửi và kiểm tra các yêu cầu HTTP đối với các API.
Các tính năng chính của Postman?
Các tính năng chính của Postman bao gồm: +) Tạo yêu cầu HTTP: Postman cho phép bạn tạo các yêu cầu HTTP như GET, POST, PUT, DELETE và nhiều hơn nữa. Bạn có thể chỉ định các thông số như URL, tham số, tiêu đề, thân yêu cầu và xem các kết quả trả về. +) Quản lý môi trường: Bạn có thể quản lý các biến môi trường để tùy chỉnh các yêu cầu và phản hồi dựa trên các biến này. Điều này rất hữu ích khi bạn phải làm việc với nhiều môi trường như local, development, production, v.v. +) Tạo và chia sẻ bộ sưu tập (collection): Postman cho phép bạn tạo và tổ chức các yêu cầu vào các bộ sưu tập. Bạn có thể chia sẻ bộ sưu tập này với đồng đội hoặc cộng đồng để hỗ trợ cộng tác và tái sử dụng. +) Kiểm thử và xác thực: Postman cung cấp các công cụ để kiểm thử và xác thực API. Bạn có thể thực hiện các bài kiểm tra tự động, kiểm tra mô phỏng và kiểm tra hiệu năng để đảm bảo tính ổn định và chính xác của API.
Cách cài đặt và sử dụng Postman?
Cài đặt: Postman có phiên bản cho Windows, macOS và Linux. Bạn có thể tải xuống và cài đặt Postman từ trang web chính thức của nó: https://www.postman.com/downloads/
Giao diện chính: Sau khi cài đặt, bạn sẽ thấy giao diện chính của Postman với các tab như "Collections", "History", "Environments", "Mocks" và "Runner".
Tạo yêu cầu: Bạn có thể tạo yêu cầu bằng cách chọn phương thức HTTP (GET, POST, PUT, DELETE) và điền URL cần gửi yêu cầu. Bạn có thể thêm tiêu đề, tham số và thân yêu cầu tuỳ theo yêu cầu của API.
Kiểm tra yêu cầu: Sau khi tạo yêu cầu, bạn có thể gửi yêu cầu và xem kết quả trả về từ API. Postman hiển thị các phản hồi trong cửa sổ "Response" và cho phép bạn xem thông tin chi tiết như mã trạng thái, tiêu đề và thân phản hồi.
Quản lý môi trường: Bạn có thể tạo các biến môi trường và sử dụng chúng trong yêu cầu. Điều này giúp bạn tùy chỉnh các yêu cầu dựa trên môi trường như local, development, production, v.v.


 Kịch Bản Kiểm Thử Lần 1:
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://random-data-api.com/api/v2/

Tham Số: users/6

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
<img width="960" alt="Screenshot 2024-05-28 135738" src="https://github.com/KinBbi/Postmantest/assets/96899952/e8711284-4594-4dce-9e88-a2e3aa24865e">

Kết quả kiểm thử chi tiết:
{
    "id": 3804,
    "uid": "7bfcde34-ac59-44d5-aaf5-2cd082853b6c",
    "password": "kC0WOzV35D",
    "first_name": "Timothy",
    "last_name": "Hermann",
    "username": "timothy.hermann",
    "email": "timothy.hermann@email.com",
    "avatar": "https://robohash.org/errorautlaboriosam.png?size=300x300&set=set1",
    "gender": "Male",
    "phone_number": "+687 (192) 996-0723 x2080",
    "social_insurance_number": "494044985",
    "date_of_birth": "1967-02-16",
    "employment": {
        "title": "Lead Mining Director",
        "key_skill": "Technical savvy"
    },
    "address": {
        "city": "New Loganport",
        "street_name": "Lee Pike",
        "street_address": "1950 Merrilee Pines",
        "zip_code": "94931-6151",
        "state": "New York",
        "country": "United States",
        "coordinates": {
            "lat": -52.963237680833686,
            "lng": 97.9205084281989
        }
    },
    "credit_card": {
        "cc_number": "4710921150025"
    },
    "subscription": {
        "plan": "Bronze",
        "status": "Active",
        "payment_method": "Cheque",
        "term": "Full subscription"
    }
}

Kịch Bản Kiểm Thử Lần 2:
Tên Kịch Bản: Kiểm thử cơ bản của một URL với một tham số

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET    

URL: https://random-data-api.com/api/v2/

Tham Số: beers?test=no

Kết Quả Mong Đợi: Gửi yêu cầu thành công 

Kết Quả Thực Tế: Gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
<img width="960" alt="Screenshot 2024-05-28 142434" src="https://github.com/KinBbi/Postmantest/assets/96899952/97170967-687d-4249-9632-626dc621c494">

Kết quả kiểm thử chi tiết:
{
    "id": 9493,
    "uid": "3218d901-5d4c-4db1-a6a0-b76dc73bed76",
    "brand": "Delirium",
    "name": "Founders Kentucky Breakfast",
    "style": "Light Hybrid Beer",
    "hop": "Summit",
    "yeast": "5335 - Lactobacillus",
    "malts": "Pale",
    "ibu": "91 IBU",
    "alcohol": "7.5%",
    "blg": "14.0°Blg"
}

Kịch Bản Kiểm Thử Lần 3:
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL với một tham số truyền vào

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://random-data-api.com/api/v2/

Tham Số: addresses

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
<img width="960" alt="Screenshot 2024-05-28 142827" src="https://github.com/KinBbi/Postmantest/assets/96899952/1080c343-2079-4fcd-83c1-dc78a5711eea">

Kết quả kiểm thử chi tiết:
{
    "id": 9765,
    "uid": "4120ffd3-88e4-45c2-9ef6-dd6a8551de22",
    "city": "Port Weston",
    "street_name": "Turner Cove",
    "street_address": "172 Anton Crest",
    "secondary_address": "Apt. 635",
    "building_number": "59841",
    "mail_box": "PO Box 77",
    "community": "University Village",
    "zip_code": "79475",
    "zip": "50157",
    "postcode": "68758-1492",
    "time_zone": "Europe/London",
    "street_suffix": "Light",
    "city_suffix": "mouth",
    "city_prefix": "Lake",
    "state": "New Mexico",
    "state_abbr": "ME",
    "country": "French Guiana",
    "country_code": "SS",
    "latitude": 56.09197067676752,
    "longitude": 54.507929858395784,
    "full_address": "Suite 521 98889 Koss Harbors, Dainestad, OR 50924-7247"
}


Kịch Bản Kiểm Thử Lần 4:
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL với một tham số truyền vào

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://random-data-api.com/api/v2/

Tham Số: HoangAnh=HA

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
<img width="960" alt="Screenshot 2024-05-28 143100" src="https://github.com/KinBbi/Postmantest/assets/96899952/475184ac-f7a9-407c-bc89-f416e670271c">

Kết quả kiểm thử chi tiết:
{
    "id": 5,
    "uid": "28122d50-0bf1-4770-98dc-ff1cbcc8f2de",
    "city": "East Marcosview",
    "street_name": "Fritsch Trafficway",
    "street_address": "605 Jim Row",
    "secondary_address": "Apt. 987",
    "building_number": "2094",
    "mail_box": "PO Box 252",
    "community": "Summer Court",
    "zip_code": "38540",
    "zip": "82474-4479",
    "postcode": "31738-4486",
    "time_zone": "Asia/Kuwait",
    "street_suffix": "Curve",
    "city_suffix": "fort",
    "city_prefix": "South",
    "state": "New Hampshire",
    "state_abbr": "MA",
    "country": "United Arab Emirates",
    "country_code": "MA",
    "latitude": -62.77801241564397,
    "longitude": -167.63046676170717,
    "full_address": "Suite 866 80050 Barbra Course, New Hoseafort, IA 88500-9434"
}

5. Kết Quả Kiểm Thử: Tóm tắt kết quả kiểm thử, bao gồm số lượng kịch bản kiểm thử đã chạy, số lượng thành công, số lượng thất bại, và tỷ lệ thành công.

Số lượng kịch bản đã kiểm thử: 4

Số lần thành công: 4

Số lần thất bại: 0

Tỉ lệ thành công: 100%

