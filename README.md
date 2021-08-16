# test1project

öncelikle sql i çalıştırın,
veya sql i note pad ile açıp
querylerin başlarındaki <"LOCALHOST".> yı siliniz.
sonra sırayla çalıştırınız.
daha sonra db nize kullanıcıları ekleyiniz,
querylerde her alandaki değişiklik için log tutan trigger mevcuttur. 

daha sonra soapservices ın içindeki Service1.svc.cs dosyasının 21. satırındaki db connection link i kendi db nizin 
bilgileri ile değiştiriniz.
ve servisi çalıştırınız.
servisi çalıştırdıktan sonra benim bilgisayarımda "http://localhost:1193/Service1.svc" bu linkte
servisin wsdl bilgileri bulunmaktadır.
Soap UI veya Postman kullanarak ta bu servisi test edebilirsiniz.

daha önce react kullanmadığım için tam olarak ordaki client olayını ve verdiği corse hatasını henüz çözemedim,
boş sayfa yaratıp client i içine yazdım şimdilik
