# Tailwind CSS

Tailwind CSS, basit, özelleştirilebilir ve hafif bir CSS çerçevesidir. CSS yazmanın geleneksel yöntemlerinden farklı olarak, Tailwind CSS, doğrudan HTML içinde sınıfları kullanmanıza olanak tanır, böylece stilleri tanımlamak için ayrı bir CSS dosyasına ihtiyaç duymazsınız.

## Nasıl Başlanır?
Tailwind CSS'yi projenize eklemek için aşağıdaki adımları izleyin:
### 1.Kurulum
Tailwind CSS'yi projenize eklemek için npm veya yarn kullanabilirsiniz. Aşağıdaki komutları terminalinizde çalıştırarak Tailwind CSS'i yükleyin:
 ```
 npm install -D tailwindcss 
 //yada
 yarn add tailwindcss
 ```
 Sonrasında bir tailwindcss dosyası oluşturun:
  ```
 npx tailwindcss init
  ```

 ### 2.Yapılandırma
 Projenizde oluşturduğunuz tailwind.config.js dosyasını htiyaçlarınıza göre özelleştirin. Bu dosya, renk paletleri, fontlar, boşluklar ve daha fazlasını içeren ayarları içerir.
  ```
 // tailwind.config.js
module.exports = {
  theme: {
    extend: {},
  },
  variants: {},
  plugins: [],
}
 ```
### 3.Ekleme Yapma
Tailwind direktiflerini CSS'nize ekleyin:
 ```
@tailwind base;
@tailwind components;
@tailwind utilities;
 ```

### 4.Oluşturma işlemini başlatın:
Şablon dosyalarınızı tarayan ve CSS dosyanızı oluşturan CLI aracını çalıştırın.
 ```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
 ```

### 5.Kullanmaya Başla:
Derlenmiş CSS dosyanızı projenize dahil edin ve Tailwind CSS sınıflarını kullanmaya başlayın!
 ```
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
 ```

## Bu gitHub deposunda Tailwind CSS kullanarak geliştirdiğim projemi sizinle paylaşmak istedim.


Umarım beğenirsiniz! Geri bildirimlerinizi bekliyorum. Teşekkür ederim!


 
