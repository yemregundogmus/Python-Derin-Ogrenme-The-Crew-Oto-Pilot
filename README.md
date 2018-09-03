# Derin Ogrenme The Crew Oto Pilot

![Serit Takip](serittakip2.gif)

 **Yunus Emre Gündoğmuş - Ağustos 2018**

İçeriğin Anlatıldığı Youtube Videosu : https://youtu.be/HMRx7tgvoAg

- Bu Mödülde Başlangıçta OpenCV Kütüphanesini kullanarak ekranı alıp o ekrandaki şeritleri tanımaya başladık. Ardından bu şeritleri görünce nasıl aksiyon alacağını kodladık. Ve elimizde çok stabil olmasa da şerit tanıyarak ona göre aksiyon alan bir algoritma oluştu. 


- Ardından bu oluşan algoritma ile makineye bir training dataseti oluşturmaya başladık. Bu training dataset'i fotoğraflar ve aksiyonları içeriyordu. Yani virajlar varken W-D tuşları, gibi gibi 19.990 Sample ile toplamda 14.000 Adım eğittimiz model çok stabil olmasa da arabaları yanlayabiliyor, Polislerden Kaçabiliyordu. İlerleyen seviyelerde ise yapmak istediğimiz şey sentdex'inde yaptığı gibi object detection ile arabaları, ağaçları, insanları tanıyarak bunlara göre aksiyon almasını sağlamak.

**Kurduğumuz Model Polisten Kaçıyor.**

![Model Polisten Kaçıyor](poliskacis.gif)


**Modelde Kullanılan Başlıca Kütüphaneler Şunlar**
  - Tensorflow
  - Numpy
  - Pandas
  - Tflearn


Kaynakça: 
- [Python plays Grand Theft Auto V](https://www.youtube.com/watch?v=ks4MPfMq8aQ&list=PLQVvvaa0QuDeETZEOy4VdocT7TOjfSA8a) 
- [How to save and load a neural network in TensorFlow (deep learning tips)](https://lazyprogrammer.me/how-to-save-and-load-a-neural-network-in-tensorflow-deep-learning-tips/)
- [Using Python programming to Play Grand Theft Auto 5](https://github.com/Sentdex/pygta5) 
