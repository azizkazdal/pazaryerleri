# pazaryerleri
net core / net5+ geliştiriciler için pazaryerler servis ipuçları

n11 servis ipuçları

n11 sipariş servis entegrasyonu

- https://api.n11.com/ws/OrderService.wsdl URL den referans dosyası oluşturduktan sonra ilk testlerinizde eğer orderList null olarak geliyorsa aşağıdaki görsel olduğu gibi Order attributelerini silin. Siparişler servisten doğru olarak deserialize edilecektir. 

![image](https://user-images.githubusercontent.com/4470595/111802897-9000fb00-88df-11eb-9de4-ad4d2eadf68b.png)

![image](https://user-images.githubusercontent.com/4470595/111802920-95f6dc00-88df-11eb-91f7-d6dcce388d1d.png)
