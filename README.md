# Face-Completion

## İnsan yüzlerinde ki eksik bölgelerin GAN yöntemi kullanılarak tamamlanması.

Projede hedeflenen,bir resimde insan görüntüsün deki eksik yüzlerin GAN kullanarak tamamlanmasıdır.
Yapay sinir ağlarına verilen verilerde görüntünün hem eksik hem de tam olarak yüzünün göründüğü resimler kullanılmıştır.
Sinir ağının eğitiminde 2000'e yakın GAN ile çizilmiş gerçeğe yakın insan görüntüsü kullanılmıştır. 
Kullanılan resimer gerçek insan resmi değildir.

## Model Test Süreci
Eğitilen modele giriş görüntüsü olarak belli bir kısmı kesilmiş görüntü verilmiştir. Model girdi görüntüyü belli kıstaslar kullanarak,
daha önce veri setinde bulunan görüntüleri de temel alarak girdi görüntüsündeki eksik parça tespit edip,ten rengi,göz ve saç rengi gibi
özellikleri baz alarak tamamlamaktadır.

![Proje Tanıtım Resmi](https://github.com/aliciplak95/Face-Completion/blob/master/result/img.png)
