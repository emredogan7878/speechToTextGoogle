# speechToTextGoogle
Google Api ve Python ile speech to text kullanımı raporu

![githubgoogle1](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/6a44bae8-6310-404c-8623-d3ce58e8e7f7)
* Google cloud console hesabı açın.
* Cloud Speech-to-Text > Documentation > Cloud Speech-to-Text V1 sekmesine gelin.
* Kırmızı kutucuk içindeki yazıyı yani "pip install google-cloud-speech"i terminale yazın.


![githubgoogle2](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/275eb970-8c45-415c-bc31-3fa148b8d0d7)
* Kırmızı kutucuk içindeki Credentials sekmesine girin.
* Credentials sekmesinde Create Credentials > Service Account seçeneğine gidin.
* Service account ismine örneğin myservice yazın ve create and continue butonuna tıklayın.
* Rol seçme kısmından Owner'ı seçin ve continue'ye basın.
* Done butonuna tıklayın ve işlemi tamamlayın.

![githubgoogle3](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/d1bff075-01eb-4f14-8907-c644a235dfef)
* Kırmızı kutucuk içindeki linke tıklayın.

![githubgoogle4](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/7264a241-5fca-478a-aa3b-6136968393e5)
* KEYS sekmesine gelin. 
* Create new key seçeneğini seçin ve ardından JSON'a tıklayın. Bilgisayarınıza JSON dosyası inecektir.
* JSON dosyasını kopyalayın ve python klasörünüzün içine yapıştırın.
* Ayrıca bir ses dosyası (wav yada mp3 bunu python kodunuzda değiştirebilirsiniz) bulup onuda klasörün içine yapıştırın.

![githubgoogle5](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/0d3c6386-ac4d-48c0-bbb1-deefe77481c4)
* Cloud Speech-to-Text API sekmesine gelip Manage butonuna tıklayın
* ✓ API Enabled yazısı gelene kadar bekleyin.
* Python kodunuzu açın.

![githubgoogle6](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/7caf4639-67a1-49d3-9507-b2267b216c2a)
* Kod bloğu ekran resminde görüldüğü kadardır.
* Yüklediğim ses dosyası South Park karakteri olan Craig Tuckerin 50 saniyelik bir konuşması.
* Kırmızı kutucuk içinde  json dosyasını ve ses dosyasını kodun hangi kısmında kullanacağımız gösterildi.

![githubgoogle7](https://github.com/emredogan7878/speechToTextGoogle/assets/112003747/9388dccd-cc6b-488e-8092-f447ede79681)
* Konsol çıktısında Transcript edildiğini görebilirsiniz.

 
