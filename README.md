# Assistant-Database

Proje akıllı asistan uygulaması. Asistana sorduğunuz soruları ve karşılığında aldığınız cevapları veri tabanına kaydeden bir uygulama. SQLServer kullandım bunu değiştirebilirsiniz. Ayrıca ben örnek olsun diye paylaştım ama proje içerisindeki migrations dosyasını terminalde kendiniz oluşturmalısınız. 
"dotnet ef migrations add InitialCreate" , "dotnet ef database update" kodları ile migration dosyanızı oluşturabilirsiniz. Lütfen buna dikkat edin. Daha sonrasında localhost olarak deneyebilirsiniz. Eğer localhostta sorun olursa swagger olarak deneyebilirsiniz. Ben ilk öncesinde bu şekilde çalıştırdığım için kodlar sorun yaratabilir. 

PROJE İÇERİSİNDE KULLANDIĞIM KÜTÜPHANELER BUNLAR BELKİ UNUTTUĞUM OLABİLİR LÜTFEN KONTROL EDİN!!!

"dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Swashbuckle.AspNetCore
dotnet add package Microsoft.AspNetCore.Mvc.NewtonsoftJson
"

C# VE VİSUAL STUDİO ÜZERİNDE İLERLEDİM İSTERSENİZ VİSUAL STUDİO CODE KULLANABİLİRSİNİZ!!!
