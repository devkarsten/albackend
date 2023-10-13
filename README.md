# About AltLoader

AltLoader is a comprehensive solution for managing and controlling Alt Accounts, particularly for AFK gaming in Minecraft. Our open-source repository offers a peek into the inner workings of our powerful panel. While the primary purpose is to serve our customers, we also welcome the curious and the contributors to explore the code that powers this innovative tool for the Minecraft community.
<br>
> [!IMPORTANT]
> We started working on this project since 13 Oct 2023.
> This means that this repo will be updated regularly, so the osc might be unstable at some times!

<br>
<br>

## Console Client for MCC Integration

Our repository houses a customized console client, tailored for seamless integration within the Pterodactyl panel and Docker environment. Leveraging MCC's open-source code, we've optimized this console client to offer the best user experience.
> https://github.com/MCCTeam/Minecraft-Console-Client

```ruby
start /min MinecraftClient.exe admin@altloader.com adminpassword play.yourserver.com
timeout 1
```
- This simple line starts our console client with the rented alt, log-in and join your server you want to AFK on.
> This can be fully customized!

<br>
<br>

## In-game command support

We provide full control on the account trough our panel. 
> You can control what servers to join, what version and prompt all in-game commands!



![MCCscreenshot](https://github.com/devkarsten/albackend/blob/main/Screenshot%202023-10-13%20185021.png)


<br>
<br>

## Pterodactyl and Docker Integration

Discover our repository where we've customized Pterodactyl and Docker to improve integration. Our enhancements are designed to optimize these tools for efficient server resource management.
> [!NOTE]
> Please check the sources for pterodactyl / docker below.

- Docker's official [GitHub repo](https://github.com/jenkinsci/docker)
- Pterodactyl's official panel [GitHub osc repo](https://github.com/pterodactyl/panel)


> Also please make sure to check the documentations of both repositories!
