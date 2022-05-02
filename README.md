![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fadtitas%2Fngrok-rdp%2F&labelColor=%2314213d&countColor=%23e5e5e5&style=flat-square)

## Description
**What is RDP?**<br>
* RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.

**How long does this RDP stay active?**<br>
* This RDP stays active for up to 6 hours.<br>

## How to use it?

* Press the **fork** button  
* Login or signup to ngrok: https://ngrok.com
* Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
> You'll get token from here. It'll be needed to the next step.
* In your forked repo: **Go to Settings > Secrets > Action > New Repository Secret**
* In the name section, enter this text: **NGROK_AUTH_TOKEN**
* In the value section, enter the **ngrok token**
* Then press **Add Secret**
* Now go to **Action > AWS > Run Workflow**
* Refresh the page and go to **build** option
* Go to **AWS > build** you'll get IP, Username & Password from **Connect to RDP** section.
* Search **Remote Desktop Connection** from Windows Start Menu and open.
* Put the IP, username and press start. Later on, put the password for auth.

## Screenshots
<img src="https://i.imgur.com/vgD2owk.png" alt="ss" width="90%"/>
<img src="https://i.imgur.com/8XBLUqf.png" alt="ss" width="90%"/>

## License
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT License](LICENSE.md).
