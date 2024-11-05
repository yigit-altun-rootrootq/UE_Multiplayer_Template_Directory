# UE_Multiplayer_Template_Directory
This template is designed to allow players on different networks to connect and play the game easily in Unreal Engine. The template uses a **standard subsystem** and offers two connection methods:

1. **VPN Connection (Recommended Method)**
2. **Port Forwarding (Alternative Method)**

## Connection Methods

### 1. Connecting via Radmin VPN or Hamachi
This is the easiest and most reliable option. Using virtual private network (VPN) programs such as **Radmin VPN** or **Hamachi**, players can connect to each other as if they were on the same local network. These programs provide low latency and simple setup.

#### Using Radmin VPN
1. Download and install [Radmin VPN](https://www.radmin-vpn.com/).
2. Create a new network in the program or join an existing network.
3. Share the network details with other players and start the Unreal Engine game.

![Radmin VPN Image](https://github.com/yigit-altun-rootrootq/UE_Multiplayer_Template_Directory/blob/main/Radmin.png)

#### Using Hamachi
1. Download and install [Hamachi](https://vpn.net/).
2. Use the "Create Network" or "Join Network" options to connect.
3. Share the network information with other players and start the game.

![Hamachi Image](https://www.vpn.net/images/screenshots/windows.png)

### 2. Connecting via Port Forwarding (Alternative Method)
This method should be used **as a last resort**. Port forwarding is done through router settings and is a bit more complex.

#### Port Forwarding Process
1. Access your router’s IP address through a browser.
2. Once logged in, navigate to the **Port Forwarding** or **NAT Settings** menu.
3. Open the required port for Unreal Engine (e.g., `7777`) and select your device's IP.
4. Share your IP address with other players so they can join the game.

> **Note:** Port forwarding settings vary by router model, so consult your router's manual for assistance.

![Port Forwarding Image](https://example.com/portforwarding.png)

---

This template enables players to connect to the game quickly and reliably. The VPN method is safer and more convenient, while port forwarding should only be used if other methods are unsuccessful.

**Happy gaming!**

