# Thực hành Postman

## 1. Cài đặt thành công(Test collection APIs)

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/0_C%C3%A0i%20%C4%91%E1%BA%B7t%20th%C3%A0nh%20c%C3%B4ng.png)

## 2. Test với đường link: https://ipapi.co/json

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/1_test%20v%E1%BB%9Bi%20link%20json.png)

## 3. Test API: https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/2_test%20api.png

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/2_test%20api.png)

## 4. Test API: https://jsonplaceholder.typicode.com/users

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/3_test%20api%20user.png)

## 5. Test API theo key là "name": https://jsonplaceholder.typicode.com/users?name=Clementine Bauch

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/4_test%20api%20theo%20key%20l%C3%A0%20name.png)

## 6. Check headers: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/5_check%20headers%20.png)

## 7. Test code is 200: 

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});


![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/6_test%20code%20is%20200.png)

## 8. Run collection: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/7_run%20collection.png)

## 9. Run collection APIs: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/8_run%20collection%20apis.png)

## 10. Hiển thị kết quả thành công: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/9_hien%20thi%20ket%20qua%20thanh%20cong%20code%20is%20200.png)

## 11. Test code is 900: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/10_test%20code%20is%20900.png)

## 12. Hiển thị kết quả thành công: 

![jasny-banner](https://github.com/AnhNguyen7303/PostmanApiTesting/blob/main/img/11_hien%20thi%20ket%20qua%20that%20bai%20code%20is%20900.png)
