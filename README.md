#Küçük resmin içindeki imgeye tıkladığımızda büyümesini istiyorsak "lightbox" kullanırız. Bunun için https://lokeshdhakar.com/projects/lightbox2/ sitesine giderek
GETTING STARTED
Download a zip of the latest release (or any previous one) from the Github Releases page. yazan kısımdan son sürümünü bilgisayarımıza indiririz bizi ilgilendiren iki kısım vardır
lightbox.min.css
lightbox.min.js ikisini de bootstrap klasörümüzün içerisindeki css ve js alt klasörlerine yerleştiririz
js kısmını body kısmımızın altında yer alan ve js kodlarının yer aldığı bölüme <script src="bootstrap/js/lightbox.min.js"></script> şeklinde ekleriz.
css kısmını ise head alanına <link rel="stylesheet" href="Bootstrap/css/lightbox.min.css"> şeklinde ekleriz. Daha sonra 
INITIALIZE WITH HTML
Single images. Add a data-lightbox attribute to any image link to enable Lightbox. For the value of the attribute, use a unique name for each image. For example:
<a href="images/image-1.jpg" data-lightbox="image-1" data-title="My caption">Image #1</a> kısmını kopyalayarak üstüne tıkladığımızda büyütmesini istediğimiz ikonu Image#1 yazan kısma ekleriz href kısmı ise eklediğimiz görselin büyük halinin yer aldığı dosyadır.
#<input type="text" placeholder="Your name..."> Form alanı yapılırken kullanılır "placeholder" kutucuğun içerisine veri girişi olduğunda kaybolan yazıdır.#   U d e m y - P r o j e 2  
 