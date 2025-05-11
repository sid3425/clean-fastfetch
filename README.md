A simple Fastfetch configuration that does not overwhelm the user with information like the default configuration, but still gets the job done and is minimal while looking cool. The accent adapts to your distribution's primary logo color, like in my case for Fedora its blue(as per the screenshot below) while for OpenSUSE its green and for Ubuntu its red and so on.

![fastfetch-screenshot](https://github.com/user-attachments/assets/2ff40b20-7362-4d26-a2d9-ef07578e0c82)

### Setup
1. Install Fastfetch: Follow the instructions on the main Fastfetch [GitHub repository](https://github.com/fastfetch-cli/fastfetch)
2. Download this configuration by either directly downloading it through the "Code" button and downloading the ZIP file and extracting it or using Git by running the command `git clone https://github.com/sid3425/clean-fastfetch`.
3. Once installed, generate a Fastfetch configuration since by default one does not exist by running the command `fastfetch --gen-config` in the CLI.
4. The configuration will be located at `C:\Users\<YourUsername>\.config\fastfetch\config.jsonc` for Windows and `~/.config/fastfetch/config.jsonc` for Linux and macOS. Replace th `config.jsonc` file with the one in this repo and voila! The configuation is now installed.

Optional step: Load the configuration on shell startup by adding Fastfetch to your shell configuration file as follows-

* Bash and ZSH(Linux and macOS): Append `fastfetch` at the end of the `.bashrc` or `.zshrc` files located within your Home directory, followed by `source ~/.bashrc` or `source ~/.zshrc` to immediately reload the changes.

* Powershell(Windows): Type `notepad $PROFILE` in Powershell followed by `& C:\path\to\fastfetch.exe` replacing \path\to with your particular location of the installed files.
