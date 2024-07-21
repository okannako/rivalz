![1](https://github.com/user-attachments/assets/008d6f16-d4f3-4808-b92f-7b118b7c8d18)

## Tavsiye Edilen Sistem Gereksinimleri
- CPU: 4+ ÇEKİRDEK
- RAM: 4+ GB
- SSD: 50 GB

## Kurulum Adımları ve Kodları
- rClient kurulumu için gerekli kodları hazırladım. Kolaylıkla kurulum yapabilirsiniz. Daha ayrıntılı kurulum videoda mevcut. Kurulumdan önce yaptığım uyarılar önemli lütfen dinleyiniz. Daha sonra karar verirseniz sırayla kodları girebilirsiniz.

```
sudo apt install tmux
tmux
sudo apt install nodejs
node -v
sudo apt install npm
npm -v
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v20.15.1
npm i -g rivalz-node-cli
rivalz run
```

- tmux ekranındayken ```ctrl+b``` sonra ```d``` ye basarak ekrandan çıkıp ```tmux ls``` yazıp tmux ekranımızın adına baktıp daha sonradan ```tmux attach -t tmuxadı``` koduyla ilgili ekrana girebiliriz.

- İlgili yüklemeler bittikten sonra ```rivalz run```sırayla sorduğu sorular şu cevapları veriyoruz; 
  1 > Siteye bağladığınız cüzdanın Evm adresi
  2 > Vps'in işlemcilerinden kaç tanesini kullanmasını istiyorsanız o sayıyı girin
  3 > Vps'in ram'inden ne kadarını kullanmak istiyorsanız o miktarı girin
  4 > Disk tipi aynı ise enter
  5 > Enter
  6 > Taoplam disk miktarından kullandırmak istediğiniz miktarı girin

- Daha sonra yazılar akmaya başlayacak, sonraki işlemi videoyu izleyerek görebilirsiniz. Teşekkürler.
