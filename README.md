# Laravel RESTful API

Bu proje, Laravel framework'ünü kullanarak basit bir RESTful API oluşturmanın örneğini sunmaktadır.

## Endpointler

-   Tüm gönderileri al: `GET /api/posts`
    
-   Tek bir gönderiyi al: `GET /api/posts/{id}`
    
-   Yeni bir gönderi oluştur: `POST /api/posts`
    
-   Bir gönderiyi güncelle: `PUT /api/posts/{id}`
    
-   Bir gönderiyi sil: `DELETE /api/posts/{id}`
    

## Açıklama

Bu projede, Laravel framework'ünün sunduğu güçlü özelliklerden yararlanarak basit bir RESTful API uygulaması oluşturulmuştur. API, "posts" kaynakları üzerinde standart CRUD (Create, Read, Update, Delete) işlemlerini gerçekleştirmek için gerekli endpointleri sunmaktadır.

**Get all posts**

`GET /api/posts`

Bu endpoint kullanılarak tüm gönderilerin listesi alınabilir. Bu istek yapıldığında, API tüm gönderilerin bir koleksiyonunu döndürür.

**Get a single post**

`GET /api/posts/{id}`

Bu endpoint ile belirli bir gönderinin detaylarına erişilebilir. `{id}` parametresi, istenen gönderinin benzersiz kimliğini temsil eder.

**Create a new post**

`POST /api/posts`

Bu endpoint kullanılarak yeni bir gönderi oluşturulabilir. İstek gövdesinde gönderiyle ilgili bilgiler bulunmalıdır. API, başarılı bir oluşturma işleminden sonra oluşturulan gönderinin ayrıntılarını döndürür.

**Update a post**

`PUT /api/posts/{id}`

Bu endpoint ile bir gönderinin güncellenmesi sağlanabilir. `{id}` parametresi, güncellenecek gönderinin benzersiz kimliğini belirtir. İstek gövdesinde güncellenmiş gönderi bilgileri yer almalıdır. API, başarılı bir güncelleme işleminden sonra güncellenen gönderinin ayrıntılarını döndürür.

**Delete a post**

`DELETE /api/posts/{id}`

Bu endpoint kullanılarak bir gönderi silinebilir. `{id}` parametresi, silinecek gönderinin benzersiz kimliğini belirtir. API, başarılı bir silme işleminden sonra ilgili gönderiyle ilgili bilgileri döndürmez.

Bu RESTful API örneği, Laravel'in güçlü yeteneklerini kullanarak temel CRUD işlemlerini gerçekleştirmek için bir temel sağlamaktadır. Bu proje, Laravel ile API geliştirme konusunda daha fazla bilgi edinmek isteyenler için başlangıç noktası olarak kullanılabilir.

## İletişim

bahadironal3@gmail.com
