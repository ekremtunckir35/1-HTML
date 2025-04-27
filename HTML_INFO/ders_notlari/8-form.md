# Form oluşturma
-Kullanıcıdan bilgi almak için kullanılan yapılara form denir.
-Form içinde textbox , button , radio button , checkbox vb elemanlar olabilir.

-form -->Tüm form elemanlarını içinde barındıran taşıyıcıdır.

-input -->Kullanıcıdan bilgi almak için kullanılan form
elemanlarının genel ismi 

-label -->Kullanıcıya form elemanı ile ilgili bilgi vermek için kullanılan eleman

# Form tagının sahip olduğu çeşitli attribute lar vardır.

<form method post " action users update " >

-action -->
Form bilgileri ile sunucudaki hangi endpoint ilgilenecekse o belirlenir.

-method ==> Genellikle post veya get değeri alır. Formdaki
bilgilerin sunucuya hangi yöntemle gönderileceğini belirler.

<form method ="post" action users update "
enctype
multipart /form data " novalidate >

--enctype(Encode type)
  Gönderilecek datanın nasıl şifreleneceği (
encode )
belirlenir. Dosya upload işlemlerinde multipart /form
data değerini alması gerekir.

-novalidate --> HTML5 ile gelen form
handler ı devre dışı bırakır.

# Button
<input type="button | submit | reset " name="btn" value=">

button
submit
reset