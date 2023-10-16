[karstendev](https://github.com/devkarsten)  ```Lead Developer / Back-end```

[Miracle](https://github.com/miraclesven) ```Contributor / Front-end```

<br>


> [!WARNING]
> # 📢 **Important Update**: Panel Change
> We're switching panels due to DNS issues and performance. Pterodactyl served us well, but we're moving on for a smoother experience. Thanks for your support, and stay tuned for updates!

<br>


# **Project Roadmap**

1. # 📌 **Panel Transition (1-2 weeks)**
   - Research and select an alternative panel.
   - Install and configure the new panel on the server.
   - Migrate existing server data and configurations.

2. 🔜 **Security and Authentication (1-2 weeks)**
   - Implement user authentication for the web panel.
   - Ensure secure communication with the Minecraft server VM.
   - Set up SSL/TLS for secure data transmission.

3. 🔜 **Web Panel Development (2-3 weeks)**
   - Design and develop the web panel user interface.
   - Implement features like command input and output display.
   - Test user interaction and functionality.

4. 🔜 **Server API (1-2 weeks)**
   - Create an API on the Minecraft server VM to receive commands.
   - Establish WebSocket or REST API communication for command execution.

5. 🔜 **Access Control (1 week)**
   - Set up firewall rules to restrict access to the VM.
   - Define user roles and permissions for the web panel.

6. 🔜 **Logging and Monitoring (1-2 weeks)**
   - Implement logging to track panel actions and command history.
   - Set up server monitoring to track performance and resource usage.

7. 🔜 **Testing and Debugging (2 weeks)**
   - Test the entire system thoroughly.
   - Identify and resolve any issues or bugs.

8. 🔜 **Documentation (1 week)**
   - Create user documentation for the web panel.
   - Document how to interact with the server through the panel.

9. 🔜 **Deployment (1 week)**
   - Deploy the web panel to the web server.
   - Ensure it's accessible to users.

10. 🔜 **Community Announcement (1 day)**
    - Announce the panel transition and the new web panel to the community.

11. 🟢 **Feedback and Iteration (Ongoing)**
    - Gather feedback from users.
    - Iterate on the web panel and server setup as needed.







# About AltLoader

AltLoader is a comprehensive solution for managing and controlling Alt Accounts, particularly for AFK gaming in Minecraft. Our open-source repository offers a peek into the inner workings of our powerful panel. While the primary purpose is to serve our customers, we also welcome the curious and the contributors to explore the code that powers this innovative tool for the Minecraft community.

<br>

> [!IMPORTANT]
> We started working on this project since 13 Oct 2023.
> This means that this repo will be updated regularly, so the osc might be unstable at some times!

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



<img src="https://gratospo.sirv.com/altloader/Screenshot%202023-10-13%20185021.png" width="426" height="185" alt="">


<br>
<br>

> [!WARNING]
> # Outdated!

## Pterodactyl and Docker Integration

Discover our repository where we've customized Pterodactyl and Docker to improve integration. Our enhancements are designed to optimize these tools for efficient server resource management.
> [!NOTE]
> Please check the sources for pterodactyl / docker below.

- Docker's official [GitHub repo](https://github.com/jenkinsci/docker)
- Pterodactyl's official panel [GitHub osc repo](https://github.com/pterodactyl/panel)


> Also please make sure to check the documentations of both repositories!
