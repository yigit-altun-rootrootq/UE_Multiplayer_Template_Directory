# UE_Multiplayer_Template_Directory
Bu template, Unreal Engine’de farklı ağlarda bulunan oyuncuların kolayca bağlantı kurarak oyunu oynamalarını sağlamak için tasarlanmıştır. Template, **standart subsystem** kullanır ve iki farklı bağlantı yöntemi sunar: 

1. **VPN Bağlantısı (Tavsiye Edilen Yöntem)**
2. **Port Forwarding (Alternatif Yöntem)**

## Bağlantı Yöntemleri

### 1. Radmin VPN veya Hamachi ile Bağlantı
Bu yöntem, en kolay ve güvenilir seçenek olarak önerilir. **Radmin VPN** veya **Hamachi** gibi sanal özel ağ (VPN) programları kullanarak oyuncular, aynı yerel ağdaymış gibi birbirlerine bağlanabilir. Bu programlar, düşük gecikme ve basit kurulum ile bağlantı sağlar. 

#### Radmin VPN Kullanımı
1. [Radmin VPN](https://www.radmin-vpn.com/) indirip kurun.
2. Programda yeni bir ağ oluşturun veya mevcut bir ağa katılın.
3. Ağ bilgilerini diğer oyuncularla paylaşın ve Unreal Engine oyununu başlatın.
   
![Radmin VPN Görseli](https://www.radmin-vpn.com/images/overview.png)

#### Hamachi Kullanımı
1. [Hamachi](https://vpn.net/) indirip kurun.
2. "Ağ Oluştur" veya "Ağa Katıl" seçeneklerini kullanarak bağlantı kurun.
3. Ağ bilgilerini diğer oyuncularla paylaşarak oyunu başlatabilirsiniz.

![Hamachi Görseli](https://www.vpn.net/images/screenshots/windows.png)

### 2. Port Forwarding ile Bağlantı (Alternatif Yöntem)
Bu yöntem, **son çare** olarak tercih edilmelidir. Port forwarding, yönlendirici ayarlarıyla yapılır ve biraz daha karmaşık bir işlemdir. 

#### Port Forwarding İşlemi
1. Yönlendiricinizin IP adresine tarayıcı üzerinden gidin.
2. Giriş yaptıktan sonra **Port Forwarding** veya **NAT Ayarları** menüsüne gidin.
3. Unreal Engine için gerekli portu (örneğin, `7777`) açın ve cihaz IP’nizi seçin.
4. Bağlantı için IP adresinizi diğer oyuncularla paylaşarak oyuna katılmalarını sağlayın.

> **Not:** Port forwarding ayarları her yönlendiricide farklılık gösterebilir, yönlendirici kılavuzundan destek alabilirsiniz.

![Port Forwarding Görseli](https://example.com/portforwarding.png)

---

Bu template, oyuncuların oyuna hızlı ve güvenilir bir şekilde bağlanmasını sağlar. VPN yöntemi daha güvenli ve kullanışlı olup, port forwarding yalnızca diğer yöntemler başarısız olursa kullanılmalıdır.

**İyi oyunlar!**
