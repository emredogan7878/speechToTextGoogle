# speechToTextGoogle
Google Api ve Python ile speech to text kullanımı raporu

![githubgoogle1](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/68c38a99-f32e-4cc2-8772-9656c702ceff)

* Google cloud console hesabı açın.
* Cloud Speech-to-Text > Documentation > Cloud Speech-to-Text V1 sekmesine gelin.
* Kırmızı kutucuk içindeki yazıyı yani "pip install google-cloud-speech"i terminale yazın.


![githubgoogle2](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/25fdb71a-3727-4e16-a7cd-e238fb88fedd)

* Kırmızı kutucuk içindeki Credentials sekmesine girin.
* Credentials sekmesinde Create Credentials > Service Account seçeneğine gidin.
* Service account ismine örneğin myservice yazın ve create and continue butonuna tıklayın.
* Rol seçme kısmından Owner'ı seçin ve continue'ye basın.
* Done butonuna tıklayın ve işlemi tamamlayın.

![githubgoogle3](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/6f2edd93-87a0-4150-9f8f-5ef03ea31cf5)

* Kırmızı kutucuk içindeki linke tıklayın.

![githubgoogle4](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/cbba1eab-959a-4dad-bcc3-2f13aeb57dbc)

* KEYS sekmesine gelin. 
* Create new key seçeneğini seçin ve ardından JSON'a tıklayın. Bilgisayarınıza JSON dosyası inecektir.
* JSON dosyasını kopyalayın ve python klasörünüzün içine yapıştırın.
* Ayrıca bir ses dosyası (wav yada mp3 bunu python kodunuzda değiştirebilirsiniz) bulup onuda klasörün içine yapıştırın.

![githubgoogle5](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/17643222-fa7c-44b4-80dc-7e3e26624944)

* Cloud Speech-to-Text API sekmesine gelip Manage butonuna tıklayın
* ✓ API Enabled yazısı gelene kadar bekleyin.
* Python kodunuzu açın.

![githubgoogle6](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/df92dc5f-bdd7-4b3d-ba4e-4f062108884f)

* Kod bloğu ekran resminde görüldüğü kadardır.
* Yüklediğim ses dosyası South Park karakteri olan Craig Tuckerin 50 saniyelik bir konuşması.
* Kırmızı kutucuk içinde  json dosyasını ve ses dosyasını kodun hangi kısmında kullanacağımız gösterildi.

![githubgoogle7](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/2cbbe822-1d90-4a52-877c-55ad65d4a0e7)

* Konsol çıktısında Transcript edildiğini görebilirsiniz.

 
