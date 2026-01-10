# ShipWr3ck Web Browser - Complete User Guide

Welcome to ShipWr3ck Web Browser, a powerful privacy-focused browser with advanced customization and built-in tools. 

## TEASER: https://youtu.be/XxQKFL1Tcug

## 📋 Table of Contents

- [Browser Overview]
- [User Interface]
- [Tab Management]
- [Privacy & Security Features]
- [Built-in Tools & Apps]
- [EditWhat (C0D3LYF3) - Advanced Text Editor]
- [AI Assistant - Integrated AI Chat]
- [Terminal - Logical Terminal]
- [Encrypted Notes]
- [Code Bank (MyRepos) - Repository Browser]
- [Settings & Customization]
- [Dashboard & Speed Dial]
- [Downloads & Files]
- [Tips & Tricks]

---

## 🌐 Browser Overview

ShipWr3ck Web Browser is a privacy-focused web browser built on Electron/Chromium technology. It combines the power of Chromium's rendering engine with advanced privacy controls, built-in tools, and a customizable interface.

### Key Features

- **Privacy-First:** Advanced fingerprinting protection and tracking prevention
- **Customizable:** Full control over appearance, behavior, and privacy settings
- **Built-in Tools:** Access to games, utilities, and developer tools without leaving the browser
- **Session Management:** Automatic tab restoration when you restart the browser
- **Vertical Tabs:** Modern sidebar-based tab layout for better organization

---

## 🖥️ User Interface

### Layout Components

- **Left Sidebar:** Contains your tabs in a vertical list. Click the toggle button to collapse/expand it.
- **Top Bar:** Navigation buttons (back, forward, reload), address bar, and quick action buttons
- **Secondary Menu:** Toggle buttons for privacy features and access to built-in apps (click the menu icon to show/hide)
- **Status Bar:** Shows connection status, network activity, and loading indicators (can be hidden)

### Address Bar

The address bar (also called URL bar) is where you type website addresses or search terms. It supports:

- Direct URL entry (e.g., `https://example.com`)
- **Localhost Support:** Direct access to local servers (e.g., `localhost`, `127.0.0.1`, `localhost:3000`)
- Search queries (searches using your default search engine)
- Quick navigation shortcuts
- **Loading Indicator:** Visual spinner appears in the address bar while pages are loading

### Navigation Controls

Located in the top bar:

- **Back:** Navigate to the previous page
- **Forward:** Navigate to the next page
- **Reload:** Refresh the current page (appears when page is not loading)
- **Stop:** Stop loading the current page (appears while page is loading)

### Zoom Controls

Located in the top-right corner:

- **Zoom In (+):** Increase page zoom
- **Zoom Out (-):** Decrease page zoom
- **Reset:** Return to 100% zoom

---

## 📑 Tab Management

### Creating Tabs

- Click the **+** button at the top of the sidebar to create a new tab
- Press `Ctrl+T` (Windows/Linux) or `Cmd+T` (Mac) to create a new tab
- Right-click a link and select "Open in New Tab"

### Switching Between Tabs

- Click any tab in the sidebar to switch to it
- Use `Ctrl+Tab` to cycle through tabs
- Use `Ctrl+1` through `Ctrl+9` to jump to specific tab positions

### Closing Tabs

- Click the **×** button on a tab
- Press `Ctrl+W` to close the current tab
- Right-click a tab and select "Close Tab"

### Tab Features

**Tab Initials Badge:** When the sidebar is collapsed and a website doesn't have a favicon, the browser displays 1-2 letter initials from the page title to help you identify tabs.

**Session Restoration:** When you close and reopen the browser, all your open tabs are automatically restored. This happens automatically - no need to configure anything.

**Tab Blur:** Enable "Blur Tab Titles" from the secondary menu to blur tab titles for privacy when others can see your screen.

**Page Content Blur:** Enable "Blur Page Content" from the secondary menu to blur all text and images on the current page for privacy. This is useful when you need to quickly hide sensitive content from others viewing your screen.

---

## 🔒 Privacy & Security Features

ShipWr3ck Web Browser includes extensive privacy controls to protect your identity and prevent tracking. All privacy features can be toggled from the secondary menu (click the menu icon in the top bar).

### Privacy Toggles

| Feature | Description | When to Use |
|---------|-------------|-------------|
| **Tor Proxy** | Routes all traffic through the Tor network for maximum anonymity | When you need complete anonymity |
| **Popup Blocker** | Blocks unwanted popup windows (enabled by default) | Always enabled for better browsing experience |
| **Ad Blocker** | Blocks advertisements using filter lists | Enable to reduce ads and improve page load times |
| **YouTube Ad Blocker** | Specifically blocks YouTube video ads | Enable when watching YouTube videos |
| **Do Not Track (DNT)** | Sends DNT header to websites requesting not to track you | Enable for basic privacy signal (websites may ignore it) |
| **HTTPS Only Mode** | Forces all connections to use HTTPS encryption | Enable for maximum security on all sites |
| **JavaScript Toggle** | Disables JavaScript execution on all pages | Use when visiting untrusted sites or for maximum security |
| **CSS Toggle** | Disables CSS styling on all pages | Use for testing or accessibility purposes |
| **Autoplay Block** | Prevents videos and audio from auto-playing | Enable to prevent annoying auto-play content |
| **Redirect Blocking** | Blocks automatic redirects and prompts before allowing them (enabled by default) | Always enabled to prevent malicious redirects |
| **Cookie Toggle** | Enable or disable all cookies. When disabled, cookies are blocked from being set or sent | Enable for privacy, disable if you need cookies for website functionality |
| **History Toggle** | Enable or disable navigation history tracking. When disabled, browser history is not saved | Disable for privacy, enable if you want to use browser history features |
| **Blur Page Content** | Blurs all text and images on the current page for privacy | Enable when you need to quickly hide sensitive content from others viewing your screen |
| **Accessibility Widget** | Adds accessibility tools to web pages | Enable for enhanced accessibility features |

### Advanced Privacy Settings

Access advanced privacy settings by clicking the Settings (gear) icon in the secondary menu:

**User-Agent Spoofing:** Change the browser identification string sent to websites. This can help you appear as a different browser or device.

**Screen Resolution Spoofing:** Fake your screen dimensions to prevent fingerprinting. Set custom width and height values.

**Language Spoofing:** Change the language preferences sent to websites. Useful for accessing region-specific content.

**Referrer Policy:** Control what referrer information is sent with requests. Choose from:
- `no-referrer` - Send no referrer (most private)
- `no-referrer-when-downgrade` - Default behavior
- `origin` - Send only the origin
- `same-origin` - Send referrer only for same-origin requests

**Fingerprint Randomization:** Randomizes browser fingerprinting properties (screen size, timezone, language, WebGL, etc.) per domain. Each domain sees a consistent fingerprint, but different domains see different values. This makes it harder for trackers to link your visits across different websites.

**Network Information Spoofing:** Spoof your connection type, download speed, and latency. Useful for testing or preventing tracking based on network characteristics.

**Cookie Management:**
- **Cookie Toggle:** Quickly enable or disable all cookies from the secondary menu
- **Cookie Settings:** Access detailed cookie management in Settings
- **Individual Cookie Control:** View, edit, and delete cookies one by one
- **Cookie Editing:** Edit cookie name, domain, path, value, expiration date, secure flag, and HTTP-only flag
- **Real-time Save:** Changes to cookies are saved immediately using AJAX

**History Management:**
- **History Toggle:** Enable or disable navigation history tracking from the secondary menu
- **Privacy Control:** When disabled, your browsing history is not saved
- **History Settings:** View and manage your browsing history in Settings

### Proxy Configuration

Configure proxy settings in Settings:

- **Single Proxy:** Enter a proxy URL (e.g., `socks5://127.0.0.1:9050` or `http://proxy:8080`)
- **Proxy List:** Upload a list of proxies and enable automatic rotation every 5 minutes
- **Tor Integration:** Use the Tor toggle in the secondary menu for easy Tor access

> ⚠️ **Important:** Some privacy features may break website functionality. If a site doesn't work properly, try disabling specific privacy features one at a time to identify the issue.

---

## 🛠️ Built-in Tools & Apps

ShipWr3ck Web Browser includes several built-in applications accessible from the secondary menu:

### Available Apps

- **Dashboard:** Your home page with speed dial sites and network activity
- **Settings:** Configure all browser settings and privacy options
- **Download Manager:** View and manage your downloads
- **Terminal:** Built-in terminal/command line interface
- **Chess:** Play chess directly in the browser
- **Game:** Access built-in games
- **DNS Mate:** DNS lookup and network tools
- **Dev Toolkit:** Developer utilities and tools
- **Cards Pro:** Card game utilities
- **Editor (EditWhat):** Advanced text editor with 100+ built-in commands and integrated AI Assistant
- **Code Bank (MyRepos):** GitHub-like repository browser for local folders
- **Notes:** Encrypted notes with password protection

---

## 📝 EditWhat (C0D3LYF3) - Advanced Text Editor

![editwhat](https://i.ibb.co/gZCY9VLP/04.png)

EditWhat is a powerful code editor built into ShipWr3ck, featuring CodeMirror with syntax highlighting, multiple themes, 100+ built-in commands, and an integrated AI Assistant for rapid development.

### Key Features

- **CodeMirror Integration:** Full-featured code editor with syntax highlighting
- **AI Assistant:** Integrated AI chat panel for code editing, explanations, and assistance
- **Multiple Themes:** 60+ CodeMirror themes (Monokai, Dracula, Material, etc.)
- **Multi-file Support:** Tab-based file management
- **Terminal Commands:** 100+ commands accessible via terminal input
- **Code Templates:** 30+ website templates (landing pages, portfolios, dashboards, etc.)
- **Text Utilities:** 70+ text manipulation and formatting commands
- **Live Preview:** HTML preview functionality
- **Customizable:** Custom CSS/JS injection support
- **Font Selection:** Google Fonts integration
- **Dark Mode:** Toggle between light and dark themes

### Accessing EditWhat

EditWhat can be accessed through the browser's interface. It provides a full-featured code editing experience with terminal-style commands.

### Using Commands

1. **Open EditWhat** in the browser
2. **Type a command** in the terminal input at the bottom
3. **Press Enter** to execute
4. Most commands work on **selected text** if available, or on the **entire editor** if nothing is selected

> 💡 **Tip:** Use the `help` command to see all available commands. Commands are case-insensitive.

### Command Categories

#### 🌐 Website Templates (30+ commands)

Create complete website templates instantly. Type the command to insert a full Bootstrap-based template:

| Command | Description |
|---------|-------------|
| `landing` | Modern landing page template |
| `portfolio` | Portfolio website template |
| `blog` | Blog template |
| `ecommerce` | E-commerce store template |
| `restaurant` | Restaurant website template |
| `photography` | Photography portfolio template |
| `corporate` | Corporate website template |
| `saas` | SaaS landing page template |
| `dashboard` | Admin dashboard template |
| `login` | Login page template |
| `signup` | Signup page template |
| `contactform` | Contact form template |
| `about` | About page template |
| `services` | Services page template |
| `pricing` | Pricing page template |
| `faq` | FAQ page template |
| `testimonials` | Testimonials section template |
| `gallery` | Image gallery template |
| `team` | Team page template |
| `product` | Product page template |
| `checkout` | Checkout page template |
| `thankyou` | Thank you page template |
| `error404` | 404 error page template |
| `comingsoon` | Coming soon page template |
| `newsletter` | Newsletter signup template |
| `footer` | Footer template |
| `header` | Header template |
| `sidebar` | Sidebar template |
| `multicolumn` | Multi-column layout template |
| `singlepage` | Single page app template |
| `admindash` | Admin dashboard template |
| `profile` | User profile page template |
| `event` | Event page template |
| `realestate` | Real estate website template |
| `fitness` | Fitness website template |
| `education` | Education website template |

#### ✏️ Text Transformation (40+ commands)

Transform text in various ways:

- `uppercase` - Convert text to uppercase
- `lowercase` - Convert text to lowercase
- `titlecase` - Convert text to title case
- `camelcase` - Convert text to camelCase
- `snakecase` - Convert text to snake_case
- `kebabcase` - Convert text to kebab-case
- `pascalcase` - Convert text to PascalCase
- `invertcase` - Invert case (uppercase ↔ lowercase)
- `swapcase` - Swap case of each character
- `capitalize` - Capitalize first letter of each word
- `reverse` - Reverse the order of lines
- `reversechars` - Reverse characters in selected text
- `rot13` - Apply ROT13 cipher to text

#### 🎨 Code Formatting & Cleanup (20+ commands)

Format and clean up your code:

- `beautify` - Format/beautify HTML/CSS/JS code
- `minify` - Minify HTML/CSS/JS code
- `jsonformat` - Format/validate JSON code
- `removeduplicates` - Remove duplicate lines
- `sortlines` - Sort lines alphabetically
- `removelines` - Remove empty lines
- `trim` - Trim whitespace from start/end of lines
- `trimall` - Remove all whitespace from text
- `tabs2spaces` - Convert tabs to spaces
- `spaces2tabs` - Convert spaces to tabs
- `indent` - Indent selected lines
- `unindent` - Unindent selected lines
- `comment` - Comment out selected lines
- `uncomment` - Uncomment selected lines
- `removehtml` - Remove all HTML tags

#### 📄 Line Manipulation (10+ commands)

Manipulate lines in your code:

- `duplicateline` - Duplicate the current line
- `deleteline` - Delete the current line
- `movelineup` - Move current line up
- `movelinedown` - Move current line down
- `joinlines` - Join selected lines into one
- `splitlines` - Split long lines at commas or spaces
- `shuffle` - Randomly shuffle lines
- `unique` - Show only unique lines
- `addlinenumbers` - Add line numbers to code
- `removelinebreaks` - Remove all line breaks

#### 🔍 Text Filtering & Extraction (10+ commands)

Filter and extract specific content:

- `removenumbers` - Remove all numbers from text
- `removespecial` - Remove all special characters
- `keepnumbers` - Keep only numbers from text
- `keepalphanumeric` - Keep only alphanumeric characters
- `extractnumbers` - Extract all numbers from text
- `extracturls` - Extract all URLs from text
- `extractemails` - Extract all email addresses from text
- `countoccurrences` - Count occurrences of selected word/phrase
- `highlight` - Highlight all occurrences of selected text

#### 🔗 Prefix/Suffix Operations (4 commands)

Add or remove prefixes/suffixes from lines:

- `addprefix PREFIX` - Add a prefix to each line (e.g., `addprefix //`)
- `addsuffix SUFFIX` - Add a suffix to each line (e.g., `addsuffix ;`)
- `removeprefix PREFIX` - Remove a prefix from each line
- `removesuffix SUFFIX` - Remove a suffix from each line

#### 🔐 Encoding/Decoding (8+ commands)

Encode and decode text:

- `urlencode` - URL encode selected text
- `urldecode` - URL decode selected text
- `htmlencode` - HTML encode selected text
- `htmldecode` - HTML decode selected text
- `escape` - Escape special characters for regex
- `unescape` - Unescape special characters

#### 🎲 Data Generation (10+ commands)

Generate random data and values:

- `randomcolor` - Generate a random hex color code
- `randomnumber` - Generate a random number (1-100)
- `randomdate` - Generate a random date
- `randomstring` - Generate a random string
- `uuid` - Generate a UUID
- `guid` - Generate a GUID/UUID
- `password` - Generate a secure password
- `lorem` - Generate Lorem Ipsum placeholder text
- `timestamp` - Insert current timestamp
- `qrcode` - Generate QR code data URL for text

#### 🔄 Format Conversion (5+ commands)

Convert between different formats:

- `csv2table` - Convert CSV data to HTML table
- `markdown` - Convert selected HTML to Markdown
- `html2text` - Convert HTML to plain text
- `hexcolor #ffffff` - Convert HEX color to RGB
- `age YYYY-MM-DD` - Calculate age from birthdate

#### ✅ Validation & Analysis (3+ commands)

Validate and analyze content:

- `validateemail` - Validate email addresses in text
- `wordcount` - Count words, characters, and lines
- `jsonformat` - Format/validate JSON code

#### ⚡ Advanced Operations (5+ commands)

Advanced text operations:

- `transpose` - Transpose text (rows to columns)
- `wordwrap` - Wrap text at 80 characters
- `wraptext` - Wrap text at 80 characters
- `center` - Center align text
- `justify` - Justify text alignment

#### 🌐 API & Web Commands (50+ commands)

Access various APIs and web services. Examples:

- `duck QUERY` - Search DuckDuckGo
- `wiki QUERY` - Wikipedia search
- `joke` - Fetch a random joke
- `cats` - Fetch a random cat fact
- `poke POKEMON` - Fetch Pokémon data
- `recipe` - Fetch a random recipe
- `define WORD` - Get word definition
- `synonym WORD` - Get synonyms
- `antonym WORD` - Get antonyms
- `my ip` - Get your public IP address
- `bitcoinprice` - Get Bitcoin price
- `npmsearch PACKAGE` - Search NPM packages
- And many more...

### Example Usage

```bash
# Create a landing page
landing

# Convert text to camelCase
camelcase

# Format JSON code
jsonformat

# Generate a random password
password

# Extract all URLs from text
extracturls

# Add prefix to all lines
addprefix //

# Search DuckDuckGo
duck where is mexico
```

### Customization

- **Themes:** Select from 60+ CodeMirror themes via dropdown
- **Font Size:** Adjustable font size (10-24px)
- **Font Family:** Choose from Google Fonts
- **Custom CSS/JS:** Inject custom styles and scripts
- **Background Image:** Set custom background image
- **Dark Mode:** Toggle dark/light mode

> 💡 **Pro Tip:** Use `help` command to see all available commands. Many commands work on selected text, so select text first for targeted operations. Commands with parameters use space-separated syntax (e.g., `addprefix //`).

---

## 🤖 AI Assistant - Integrated AI Chat

EditWhat includes a powerful AI Assistant panel that integrates seamlessly with the code editor, allowing you to get AI-powered help with code editing, explanations, and general assistance.

### Key Features

- **Integrated Chat Panel:** AI chat panel on the right side of the editor (can be toggled on/off)
- **Multiple Chat Modes:** Choose from Single, Compare, Ensemble, or A/B Test modes
- **Model Selection:** Select from available AI models or use multiple models simultaneously
- **Code Integration:** Select code in the editor and ask the AI to edit, explain, or improve it
- **Streaming Responses:** Real-time streaming of AI responses for faster interaction
- **Chat History:** Multiple chat sessions with tab-based organization
- **Export Chats:** Export chat conversations for reference or sharing

### Accessing the AI Assistant

1. **Open EditWhat** in the browser
2. **Toggle the Chat Panel:** Click the chat icon (💬) button in the toolbar, or use the close button (✕) in the chat panel header to hide/show it
3. **Start Chatting:** Type your question or request in the message input at the bottom of the chat panel

### Chat Panel Layout

The AI chat panel is located on the right side of the editor and includes:

- **Header Section:**
  - AI Assistant title with connection status indicator
  - Close button (✕) to hide the panel
- **Control Section:**
  - **Mode Selector:** Choose chat mode (Single, Compare, Ensemble, A/B Test)
  - **Model Selector:** Select AI model(s) to use
  - **Toggle Controls Group:** Speed, Auto, and Code toggles grouped together
  - **Settings Button:** Access AI fine-tuning settings
- **Chat Area:**
  - Chat tabs for managing multiple conversations
  - Message history display
  - Input field for typing messages

### Chat Modes

| Mode | Description | Use Case |
|------|-------------|----------|
| **Single** | Use one AI model for responses | Standard chat and code assistance |
| **Compare** | Compare responses from multiple models side-by-side | Evaluating different model outputs |
| **Ensemble** | Combine responses from multiple models | Getting consensus or diverse perspectives |
| **A/B Test** | Test different models with the same prompt | Model performance comparison |

### Toggle Controls

The toggle controls are grouped together under the model selector:

- **Speed Mode:** Keeps streaming responsive by optimizing response delivery (enabled by default)
- **Auto Continue:** Automatically continues when a reply stops early (enabled by default)
- **Code Mode:** Prepends "Only provide code" to all messages, useful for code-only responses

### Using the AI Assistant

#### Basic Chat

1. Type your question or request in the message input
2. Press `Ctrl+Enter` or click Send to submit
3. The AI will respond in real-time (streaming response)

#### Code Editing

1. **Select code** in the editor that you want to modify
2. **Type a request** like:
   - "Refactor this code"
   - "Add error handling"
   - "Optimize this function"
   - "Explain what this does"
3. The AI will work with the selected code and provide suggestions or edits

#### Multiple Chats

- **New Chat:** Click the "+" button in the chat tabs area or press `Ctrl+N` to start a new conversation
- **Switch Between Chats:** Click on different chat tabs to switch conversations
- **Export Chat:** Click the export button (📥) to save a chat conversation

### AI Settings

Click the settings button (⚙️) in the chat panel header to access fine-tuning options:

- **Temperature:** Control randomness in responses (lower = more focused, higher = more creative)
- **Max Tokens:** Set maximum response length
- **Top P:** Nucleus sampling parameter
- **Frequency Penalty:** Reduce repetition in responses
- **Presence Penalty:** Encourage new topics in responses

### Connection Status

The status indicator in the chat panel header shows:

- **Connecting...** - Establishing connection to AI service
- **Connected** - Ready to chat
- **Disconnected** - Connection lost, check your AI service

### Tips for Best Results

> 💡 **Tip:** Select code before asking questions to get context-aware responses

> 💡 **Tip:** Use Code Mode toggle when you only want code output without explanations

> 💡 **Tip:** Enable Speed Mode for faster streaming responses during long conversations

> 💡 **Tip:** Use Compare or Ensemble modes to get multiple perspectives on complex problems

> 💡 **Tip:** Export important chat conversations for future reference

> 💡 **Tip:** Toggle the chat panel off when you need more editor space - it remembers your preference

### Keyboard Shortcuts

- `Ctrl+Enter` - Send message
- `Ctrl+N` - New chat
- Chat panel toggle button - Show/hide chat panel

---

## 💻 Terminal - Logical Terminal v1.0.0

![terminal](https://i.ibb.co/tPFJhFFn/03.png)

The Terminal is a powerful command-line interface built into ShipWr3ck, providing access to 50+ utility commands, games, API tools, and more. Access it from the secondary menu or by opening a new tab.

### Key Features

- **Native Command Prompt Integration:** Uses your system's native command prompt (cmd on Windows, terminal on macOS/Linux) for executing system commands
- **Current Working Directory:** Displays and tracks your current directory path in the terminal prompt
- **File System Navigation:** Use `cd` command to change directories and navigate your file system
- **Enhanced Directory Listing:** `dir` command displays files and folders in a beautiful grid view with:
  - Clickable directory buttons for quick navigation
  - Human-readable file sizes (KB, MB, GB)
  - File type indicators and modification dates
  - Clickable files to open in EditWhat.html editor
- **Command-Line Interface:** Terminal-style command input with instant execution
- **50+ Commands:** Extensive command library for various tasks
- **AI Assistant Integration:** Chat with AI models directly from the terminal using Ollama
- **API Integration:** Access external APIs and web services
- **Games & Entertainment:** Built-in games and fun commands
- **Text Utilities:** Text manipulation and encoding/decoding tools
- **Information Lookup:** Dictionary, IP lookup, food info, and more
- **Notes System:** Save and manage notes directly in the terminal
- **Visual Effects:** Matrix, candle, and Christmas animations
- **Google Translate:** Built-in translation widget

### Using the Terminal

1. **Open Terminal:** Click the Terminal button in the secondary menu
2. **Type Command:** Enter a command in the input field (prefixed with `>`)
3. **Press Enter:** Execute the command
4. **View Results:** Output appears in the terminal window above
5. **Get Help:** Type `help` to see all available commands

> 💡 **Tip:** The terminal input cycles through example placeholders to give you ideas of what commands to try. Commands are case-insensitive.

### Command Categories

#### 🎮 Games & Entertainment

| Command | Description |
|---------|-------------|
| `pong` | Play classic Pong game |
| `rps` | Play Rock, Paper, Scissors |
| `matrix` | Display colorful Matrix effect animation |
| `candle` | Display animated candle effect |
| `christmas` | Display Christmas animation |
| `joke` | Display a random joke |
| `puns` | Display a random pun |
| `giphy QUERY` | Search and display a random GIF (e.g., `giphy cats`) |
| `pokemon NAME` | Get Pokémon information (e.g., `pokemon ditto`) |
| `show NAME` | Get TV show information (e.g., `show sheldon`) |
| `show-people NAME` | Get actor/person information (e.g., `show-people tom hanks`) |
| `mudduck` | Display a duck emoji 🦆 |

#### 📝 Text Manipulation & Encoding

| Command | Description |
|---------|-------------|
| `bkw TEXT` | Reverse text (e.g., `bkw dog` → "god") |
| `capit TEXT` | Convert text to UPPERCASE (e.g., `capit hello`) |
| `binary CODE` | Convert binary to text (e.g., `binary 01001000 01000101`) |
| `hex CODE` | Convert hex to text (e.g., `hex 48 65 6c 6c 6f`) |
| `octal CODE` | Convert octal to text (e.g., `octal 110 145 154 154 157`) |
| `morse TEXT` | Convert text to Morse code |
| `rainbow TEXT` | Display text with rainbow color effect |
| `say TEXT` | Display text in random colors |
| `bacon` | Generate Bacon Ipsum placeholder text |
| `metaphor NUMBER` | Generate paragraphs in PDF format (e.g., `metaphor 3`) |

#### 🔐 Data Generation & Security

| Command | Description |
|---------|-------------|
| `uuid` | Generate a UUID |
| `pwd LENGTH` | Generate random password (default: 12 characters) |
| `color` | Display a random color with hex code |
| `emoji` | Display a random emoji |
| `fakem` | Generate a fake person image |
| `genbot TEXT` | Generate a robot image based on text |
| `passtest` | Open password strength tester |

#### 🔍 Information Lookup

| Command | Description |
|---------|-------------|
| `dictionary WORD` | Look up word definition with examples |
| `iplookup IP` | Look up IP address information (e.g., `iplookup 8.8.8.8`) |
| `exip` | Display your external IP address |
| `food BARCODE` | Get food product information by barcode (e.g., `food 737628064502`) |
| `fda-drug DRUG` | Search FDA drug information (e.g., `fda-drug IBUPROFEN`) |
| `github USERNAME` | Display user's GitHub repositories (e.g., `github codelyfe`) |
| `population` | Display United States current population data |
| `btc` | Display current Bitcoin price |

#### 📅 Time & Calendar

| Command | Description |
|---------|-------------|
| `time` | Display current time |
| `date` | Display current date |
| `calendar` | Display interactive calendar |
| `timer TIME` | Start countdown timer (format: HH:MM:SS, e.g., `timer 00:00:30`) |

#### 🛠️ Utilities & Tools

| Command | Description |
|---------|-------------|
| `qrcode TEXT` | Generate QR code (e.g., `qrcode https://google.com`) |
| `barcode CODE` | Generate barcode (e.g., `barcode 423423425`) |
| `domain DOMAIN` | Take screenshot of website (e.g., `domain google.com`) |
| `pdf URL` | Convert webpage to PDF (e.g., `pdf https://google.com`) |
| `fetch URL` | Fetch and display CDN code for local saving |
| `api URL` | Test API endpoint (e.g., `api https://api.example.com`) |
| `rss URL` | Display RSS feed (e.g., `rss https://api.adviceslip.com/daily_adviceslip.rss`) |
| `math EXPRESSION` | Perform calculations (e.g., `math 2+8`) |
| `simp` | Open simple text editor |
| `codeit` | Open code playground |
| `txt2spk` | Open text-to-speech converter |
| `data` | Display localStorage data |

#### 📝 Notes Management

| Command | Description |
|---------|-------------|
| `note TEXT` | Save a note |
| `note-all` | Display all saved notes |
| `note-delete INDEX` | Delete a specific note by index (e.g., `note-delete 1`) |
| `note-delete-all` | Delete all notes |

#### 🤖 AI Assistant

| Command | Description |
|---------|-------------|
| `ai MESSAGE` | Chat with AI assistant using Ollama (e.g., `ai explain this code`, `ai help me with JavaScript`) |

**AI Assistant Features:**
- **Ollama Integration:** Connects to local Ollama instance (default: http://127.0.0.1:11434)
- **Automatic Model Selection:** Automatically uses available models if the selected model isn't installed
- **Streaming Responses:** Real-time streaming of AI responses directly in the terminal
- **Model Support:** Works with any Ollama-compatible model (llama3.2, deepseek-r1, qwen3-coder, etc.)
- **Settings Integration:** Uses AI settings from EditWhat if available, or defaults to sensible values

**Requirements:**
- Ollama must be installed and running on your system
- At least one AI model must be installed in Ollama
- Default Ollama port: 11434 (configurable via EditWhat AI settings)

**Example Usage:**
```bash
# Ask a question
ai what is JavaScript?

# Get code help
ai explain this code

# Request assistance
ai help me write a function to sort an array
```

#### 💻 System Commands

The terminal integrates with your system's native command prompt, allowing you to execute any system command:

| Command | Description |
|---------|-------------|
| `cd PATH` | Change directory (e.g., `cd C:\Users`, `cd ~`, `cd ..`) |
| `dir` | List directory contents in a grid view (Windows) |
| `ls` | List directory contents (macOS/Linux) |
| `clear` | Clear the terminal output |
| Any system command | Execute any command available in your system's command prompt |

**Directory Navigation:**
- Use `cd` to change directories (e.g., `cd Documents`, `cd C:\Users\YourName`)
- Use `cd ..` to go up one directory level
- Use `cd ~` to go to your home directory
- The current directory path is displayed in the terminal prompt

**Directory Listing:**
- The `dir` command (Windows) displays files and folders in a responsive grid view
- Each directory has a green "Open →" button to navigate into it
- Each file has a blue "Open in Editor →" button to open it in EditWhat.html
- File sizes are automatically converted to human-readable format (KB, MB, GB)
- Click on directory buttons to instantly navigate and view their contents

**Opening Files:**
- Click the "Open in Editor →" button on any file in the `dir` output
- The file will open in EditWhat.html in a new tab (or switch to existing editor tab)
- Supports all text-based files (code files, config files, etc.)

#### 🎨 Special Commands

| Command | Description |
|---------|-------------|
| `clear` | Clear the terminal output |
| `help` | Display all available commands |
| `copyright` | Display copyright information |
| `look` | Fun response: "What are you looking for?" |

### Example Usage

```bash
# Generate a password
pwd 16

# Get a random joke
joke

# Look up a word
dictionary computer

# Generate QR code
qrcode https://shipwr3ck.com

# Search for GIFs
giphy dancing cats

# Get Pokémon info
pokemon pikachu

# Start a timer
timer 00:05:00

# Chat with AI assistant
ai explain how JavaScript closures work
```

### Special Features

**Google Translate Integration:** The terminal includes a Google Translate widget in the top-right corner, allowing you to translate the terminal interface to any language.

**Auto-Scrolling:** The terminal automatically scrolls to show the latest output, ensuring you always see the most recent command results.

**Dynamic Placeholders:** The input field cycles through example placeholders every 3 seconds to give you ideas of commands to try.

**Native System Integration:** The terminal uses your system's native command prompt, so you can run any command that works in your regular terminal/command prompt. This includes:
- File system operations (`cd`, `dir`, `ls`, `mkdir`, etc.)
- System utilities and tools
- Script execution
- Environment variable access
- All standard command-line tools

**Grid View Directory Listing:** The `dir` command displays files and folders in a modern grid layout with:
- Visual distinction between files (blue border) and directories (green border)
- Clickable buttons for quick navigation
- Formatted file sizes and dates
- Summary statistics (file count, directory count, free space)

> 💡 **Pro Tip:** Use `clear` to clear the terminal output when it gets cluttered. The terminal maintains a scrollable history of all commands and outputs.

> 💡 **Pro Tip:** Click on directory buttons in the `dir` output to quickly navigate through your file system without typing `cd` commands.

> 💡 **Pro Tip:** Click on file buttons in the `dir` output to instantly open files in EditWhat.html for editing.

---

## 🔐 Encrypted Notes

ShipWr3ck Web Browser includes a built-in encrypted notes feature that allows you to securely store notes with optional password protection. Access it by clicking the Notes button in the secondary menu.

### Getting Started

- Click the **Notes** button (📝) in the secondary menu to open the notes page
- If no password is set, you can start typing immediately
- If a password is set, you'll see a password modal - enter your password to unlock

### Setting a Password

1. Open the Notes page and make sure your notes are unlocked
2. Click the **🔐 Set Password** button next to the Save button
3. Enter your new password in the "New Password" field
4. Confirm your password in the "Confirm Password" field
5. Click **💾 Set Password** to save

**Password Protection:**
- **Optional Password:** You can use notes without a password, but they won't be encrypted
- **Encryption:** When a password is set, notes are encrypted using AES-256-GCM encryption
- **Automatic Locking:** After setting a password, your notes are automatically locked and require the password to unlock
- **Removing Password:** You can remove password protection by checking "Remove password" in the Set Password section

### Using Notes

- **Auto-Save:** Notes are automatically saved 2 seconds after you stop typing
- **Manual Save:** Click the **💾 Save** button to save immediately
- **Status Indicator:** The status shows "✓ Saved" when saved, or "● Unsaved changes" when there are unsaved changes
- **Unlocking:** When locked, enter your password in the modal to unlock and view/edit your notes

> ⚠️ **Important:** If you forget your password, you cannot recover your notes. You must use the "Clear All Data" button to reset, which will permanently delete all notes and password data. Make sure to remember your password or keep it in a secure password manager.

### Security Features

**Encryption Details:**
- **Algorithm:** AES-256-GCM (Advanced Encryption Standard with Galois/Counter Mode)
- **Key Derivation:** Uses scrypt for password-based key derivation
- **Storage:** Encrypted data is stored locally using electron-store
- **No Cloud Sync:** All data stays on your device - nothing is sent to servers

### Managing Notes

- **Clear All Data:** Click the **🗑️ Clear All Data** button to permanently delete all notes and password (requires double confirmation)
- **Changing Password:** Click "Set Password" again and enter a new password to change it
- **Removing Password:** Check "Remove password" in the Set Password section to save notes without encryption

> 💡 **Tip:** Use encrypted notes to store sensitive information like passwords, personal notes, or any data you want to keep private. The encryption ensures that even if someone gains access to your computer, they cannot read your notes without the password.

---

## 📁 Code Bank (MyRepos) - Repository Browser

Code Bank is a GitHub-like repository browser built into ShipWr3ck that allows you to browse local folders and files with a beautiful, modern interface. Access it by clicking the Code Bank button (vault icon) in the secondary menu.

### Key Features

- **Folder Selection:** Select any folder on your computer to browse
- **GitHub-like Interface:** Clean, modern UI similar to GitHub's repository view
- **File Browsing:** Navigate through directories with breadcrumb navigation
- **Code Preview:** View code files with syntax highlighting using CodeMirror
- **Image Preview:** Peek at images directly in the browser
- **Search & Filter:** Search files and folders, filter by type (All, Folders, Files, Images, Code)
- **Sorting & Pagination:** Sort by name, type, size, or modified date with pagination support
- **Grid & List Views:** Toggle between grid and list view modes
- **Persistent Storage:** Remembers your selected folder between sessions
- **File Metadata:** View file sizes, modification dates, and file types
- **Quick Actions:** Copy file paths, download files, view raw content

### Getting Started

1. **Open Code Bank:** Click the Code Bank button (vault icon) in the secondary menu
2. **Select Folder:** Click "Select Folder" to choose a directory on your computer
3. **Browse:** Navigate through folders and files using the breadcrumb navigation or by clicking folder/file names
4. **View Files:** Click on any file to view its contents (if supported)

### Features

#### Folder Selection

- Click "Select Folder" to open a folder selection dialog
- The selected folder is automatically saved and restored when you reopen Code Bank
- Navigate to the home folder by clicking the "Code Bank" title

#### File Browsing

- **Breadcrumb Navigation:** Use breadcrumbs at the top to quickly navigate to parent folders
- **Folder Navigation:** Click on any folder to enter it
- **File Viewing:** Click on any file to view its contents in the viewer

#### Viewing Files

- **Code Files:** Files with code extensions (JS, PHP, CSS, HTML, etc.) are displayed with syntax highlighting
- **Image Files:** Images can be previewed directly in the browser
- **Large Files:** Files larger than 2MB show a message to use Raw or Download instead
- **Unsupported Files:** Files that can't be previewed show a message with options

#### Search & Filter

- **Search:** Type in the search box to filter files and folders by name
- **Filters:** Use filter buttons to show only:
  - **All:** All items
  - **Folders:** Only directories
  - **Files:** Only files
  - **Images:** Only image files
  - **Code:** Only code files
- **Extension Filter:** Click on top file extensions to filter by specific file type
- **Show Hidden:** Toggle to show/hide hidden files (files starting with `.`)

#### Sorting & View Options

- **Sort By:** Choose to sort by Name, Type, Size, or Modified date
- **Order:** Toggle between Ascending and Descending order
- **View Mode:** Switch between List view (table) and Grid view (cards)
- **Items Per Page:** Choose how many items to display per page (24, 48, 96, or 150)

#### File Actions

- **Peek:** Click "Peek" on code or image files to preview them inline without leaving the list
- **Copy Path:** Copy the full file path to clipboard
- **Copy Raw Link:** Copy a link to the raw file content
- **Download:** Download files directly
- **Raw View:** View raw file content in a new tab

#### Code Viewer

When viewing code files, you can:
- **Syntax Highlighting:** Automatic syntax highlighting based on file type
- **Line Numbers:** View line numbers for easy reference
- **Word Wrap:** Toggle word wrapping for long lines
- **Copy Options:** Copy file path or raw link to clipboard

### Statistics

The interface displays helpful statistics:
- Total number of items
- Number of folders
- Number of files
- Total size of all files
- Top file extensions in the current directory

### Tips

> 💡 **Tip:** Use the search feature to quickly find files in large directories

> 💡 **Tip:** Enable "Show hidden" to see configuration files and other hidden files

> 💡 **Tip:** Use the Peek feature to quickly preview files without opening them in the viewer

> 💡 **Tip:** Filter by file type to focus on specific file types (e.g., only code files)

> 💡 **Tip:** The selected folder is remembered between sessions, so you can quickly return to your project

---

## ⚙️ Settings & Customization

Access Settings by clicking the gear icon in the secondary menu or from the Dashboard.

### Appearance Settings

- **Theme:** Choose between dark and light themes
- **Colors:** Customize accent colors, backgrounds, and text colors
- **Fonts:** Adjust font family and sizes

### Privacy Settings

All privacy features mentioned above can be configured in Settings. You can also:

- Configure popup blocker allowlists and blocklists
- Set up custom popup filter rules
- Manage fingerprint randomization whitelist
- Configure cookie blocking rules
- Manage individual cookies (view, edit, delete)
- View and clear browsing history

### Cookie Management in Settings

In the Cookies tab of Settings, you can:

- **View All Cookies:** See all cookies stored by websites
- **Filter Cookies:** Search cookies by domain, name, or value
- **Edit Cookies:** Click on any cookie field to edit it:
  - Name, Domain, Path, and Value are editable
  - Expiration date can be set using a date picker
  - Secure and HTTP-only flags can be toggled
- **Save Changes:** A "Save Changes" button appears when you modify a cookie. Click it to save your changes
- **Delete Individual Cookies:** Click the "Delete" button on any cookie to remove it
- **Clear All Cookies:** Use the "Clear All Cookies" button to remove all cookies at once

### Network Settings

- Configure proxy settings
- Set up proxy rotation
- Configure Tor integration
- Set network information spoofing values

### Data Management

- **Clear Browsing Data:** Delete cookies, cache, history, and other stored data
- **Export/Import:** Export settings and data for backup

---

## 📊 Dashboard & Speed Dial

The Dashboard is your home page, accessible by clicking the Dashboard icon or opening a new tab. It provides system information, network activity monitoring, and a customizable speed dial for quick access to your favorite sites.

> 💡 **Quick Access:** Click the **📖 User Guide** button in the top-right corner of the Dashboard to open this user guide in a new tab.

### System Information Card

The System Info card displays real-time system information that updates every 5 seconds:

- **OS:** Operating system type and release version
- **Arch:** System architecture (x64, arm64, etc.)
- **CPUs:** Number of CPU cores
- **Memory:** Used and total system memory (formatted in KB, MB, or GB)
- **Uptime:** System uptime in hours and minutes
- **Hostname:** Computer hostname

### Network Activity Feed

The Network Activity Feed provides real-time monitoring of all network requests made by the browser.

**Activity Grouping:** Network requests are grouped by domain (not individual URLs), making it easy to see which websites are making the most requests. Each entry shows:

- **Domain:** The website domain making requests
- **Count Badge:** Shows ×N+ when multiple requests are made to the same domain
- **Status:** Color-coded status indicators:
  - **OK** - Successful requests
  - **ERROR** - Failed requests
  - **BLOCKED** - Blocked by ad blocker or privacy features
  - **PENDING** - Requests in progress
- **Method:** HTTP method (GET, POST, etc.)
- **Data Size:** Total data transferred per domain
- **Timestamps:** Relative time ("just now", "5s ago", "2m ago") or absolute time for older entries
- **Request Count:** Total number of requests to that domain

**Export Network Activity:** Click the **📥 Export** button in the Network Activity card to export all network activity to a text file. The export includes:

- Export date and time
- Total unique domains tracked
- For each domain: URL, request count, status, method, data size, and timestamps

The feed tracks up to 100 unique domains and automatically removes the oldest entries when the limit is reached.

### Speed Dial

Speed Dial provides quick access to your favorite websites, organized in folders. All speed dial items are stored locally and persist between browser sessions.

#### Adding Items

- **Add Site:** Click "+ Add Site" to add a website. Enter:
  - URL (required) - Automatically adds `https://` if no protocol is specified
  - Title (optional) - Custom name for the site
  - Description (optional) - Additional information about the site
- **Add Folder:** Click "+ Folder" to create a folder for organizing sites. Enter a folder name.
- **Add HTML Page:** Click "+ HTML Page" to create a custom HTML page that opens in a tab. Enter:
  - Page Title (required)
  - Description (optional)
  - HTML Code (required) - Full HTML document code

HTML pages are saved locally and can be accessed from speed dial like regular websites.

#### Organizing Speed Dial

- **Drag to Reorder:** Hover over any speed dial card to see the sort handle (⋮⋮) in the top-left corner. Drag cards to reorder them.
- **Move to Folders:** Drag any site or folder card onto a folder card to move it into that folder. You can create nested folder structures.
- **Move to Root:** When inside a folder, a drop zone appears at the bottom. Drag items here to move them back to the root level.
- **Folder Navigation:** Click a folder to open it. Use the "← Back" button to navigate back to the parent folder. The current folder name is displayed in the navigation bar.
- **Remove Items:** Hover over any card to see the remove button (×) in the top-right corner. Click it to remove the item (requires confirmation).

**Speed Dial Features:**
- **Favicon Display:** Websites automatically display their favicon. If unavailable, a default icon is shown.
- **HTML Page Icons:** User-created HTML pages display a special document icon to distinguish them from regular websites.
- **Hover Effects:** Cards highlight on hover, showing sort and remove controls.
- **Folder Highlighting:** Folders have a blue border and highlight when you drag items over them.
- **Empty State:** When a folder or the root is empty, a helpful message guides you to add items.
- **Prevent Circular References:** The system prevents moving folders into themselves or their child folders.

> 💡 **Pro Tip:** Organize your speed dial into folders by category (e.g., "Work", "Social Media", "Tools") for faster access. You can create nested folders for even better organization.

---

## 📥 Downloads & Files

### Download Manager

Access the Download Manager from the secondary menu to:

- View all downloads
- Open downloaded files
- Clear download history
- Manage download locations

### Download Behavior

- Downloads are saved to your default download folder
- You can choose a custom location when downloading
- Download progress is shown in the status bar

---

## 💡 Tips & Tricks

> 💡 **Tip:** Use the vertical sidebar tabs for better organization. Collapse it when you need more screen space.

> 💡 **Tip:** Enable fingerprint randomization for maximum privacy, but add trusted sites to the whitelist to prevent issues.

> 💡 **Tip:** Use proxy rotation for enhanced privacy when browsing multiple sites. The browser automatically switches proxies every 5 minutes.

> 💡 **Tip:** Create custom HTML pages in the Dashboard for quick access to frequently used tools or information.

> 💡 **Tip:** Use the "Download All Images" feature to quickly save all images from a page while ensuring they're safe (sanitized through canvas conversion).

> 💡 **Tip:** Enable HTTPS Only mode for maximum security, especially on public Wi-Fi networks.

> 💡 **Tip:** Use the session restoration feature - your tabs are automatically saved and restored when you restart the browser.

> ⚠️ **Security Note:** While ShipWr3ck includes many privacy features, remember that complete anonymity online is difficult to achieve. Always be cautious about what information you share online.

---

## 🆘 Getting Help

If you encounter issues:

- Check Settings to ensure privacy features aren't blocking necessary functionality
- Try disabling privacy features one at a time to identify conflicts
- Clear browsing data if experiencing cache-related issues
- Check the Download Manager if downloads aren't working

---

## Tor Proxy Setup

To use the Tor proxy feature:

1. **Install Tor:** Download and install Tor from [torproject.org](https://www.torproject.org/)
2. **Start Tor:** Make sure Tor is running (default SOCKS port: 9050)
3. **Enable in Browser:** Click the Tor button in the navigation bar to enable proxy mode
4. **Verify:** Visit [check.torproject.org](https://check.torproject.org) to verify Tor is working

**Note:** The Tor proxy uses the default configuration (localhost:9050). You can modify `tor-config.js` to use custom proxy settings.

## License

MIT

---

**ShipWr3ck Web Browser - The Best Damn Browser**  
Version 1.0.0 - Beta


Terminal - CMDS

- mudduck: 🦆
- ai: Chat with AI assistant. ("ai explain this code")
- api: Test API url. ("api https://aztro.sameerkumar.website?sign=aries&day=today")
- bacon: Creates Bacon Ipsum
- barcode: Create a barcode for your text. ("barcode 423423425")
- bkw: Types everything you say backwards ("bkw dog")
- binary: Converts Binary to text ("binary 01001000 01000101 01001100 01001100 01001111")
- btc: Current BitCoin Price
- calendar: Display a Calendar
- capit: Displays your text all UPPERCASE ("capit randal")
- clear: Clear the terminal
- codeit: Display Code Playground
- color: Displays a random color and its hex code
- copyright: Displays "Copyright © 2024 ShipWr3ck.com"
- date: Display the current date
- dictionary: Look up word in dictionary ("dictionary dog")
- domain: Display screenshot of website ("domain google.com")
- exip: Display the external IP address
- fakem: Create a fake person IMG ("fakem")
- fetch: Displays CDN code to slim the name down and save local ("fetch URL")
- food: Display Food Info using barcode ("food 737628064502")
- genbot: Generates a random cat image. ("genbot text")
- github: Display Users latest Repos ("github codelyfe")
- giphy: Displays a random Gif from your search ("giphy dog")
- help: Show available commands
- hex: Converts Hex to text ("hex 48 65 6c 6c 6f")
- iplookup: Lookup IP information. ("iplookup 8.8.8.8")
- joke: Displays a random joke
- math: Divide, Add, Subtract, Multiply ("math 2+8")
- matrix: Displays Colorful Matrix Effect
- metaphor: Generates number of paragraphs in a PDF ("metaphor 3")
- morse: Converts text to morse code (.-. / .- / -. / -.. / .- / .-.. /)
- note: Save a Note
- note-all: Display all Notes
- note-delete: Delete a Single Notes ("note-delete 1")
- note-delete-all: Delete all Notes
- octal: Converts Octal to text ("octal 110 145 154 154 157")
- passtest: Test how strong your password is.
- pdf: Display PDF of website ("pdf https://google.com")
- pokemon: Displays Pokemon Info ("pokemon ditto")
- pong: Play classic Pong
- population: Display United States Current Population
- pwd : Generate a random password with specified length
- qrcode: Create a QR code for your text. ("qrcode https://google.com")
- rainbow: Generates a rainbow effect with your text
- rps: Play Rock, Paper, Scissors
- rss: Display RSS feed ("rss https://api.adviceslip.com/daily_adviceslip.rss")
- say : Display text in random colors
- show: Displays TV show info ("show sheldon")
- show-people: Displays TV show people info ("show-people tom hanks")
- simp: Open a simple text editor
- opentabedit: Open or switch to the code editor tab
- web: Open a URL in a new browser tab ("web google.com" or "web https://example.com")
- time: Display the current time
- timer: Starts a timer ("timer 00:00:30") HR:MIN:SEC
- txt2spk: Text to speak.
- uuid: Generates a UUID
- weather: Get weather info for a city ("weather London")
- quote: Get a random quote
- catfact: Get a random cat fact
- dogfact: Get a random dog fact
- fact: Get a random fact
- advice: Get random advice
- cat: Get a random cat image
- dog: Get a random dog image
- news: Get news headlines from RSS feeds ("news" or "news bbc" or "news nytimes" or "news wsj" or "news aljazeera")
- base64encode: Encode text to base64 ("base64encode hello")
- base64decode: Decode base64 text ("base64decode aGVsbG8=")
- urlencode: URL encode text ("urlencode hello world")
- urldecode: URL decode text ("urldecode hello%20world")
- md5: Generate MD5 hash ("md5 hello")
- sha256: Generate SHA-256 hash ("sha256 hello")
- wordcount: Count words and characters ("wordcount hello world")
- charcount: Count characters ("charcount hello")
- lorem: Generate Lorem Ipsum ("lorem 3")
- synonym: Get synonyms for a word ("synonym happy")
- antonym: Get antonyms for a word ("antonym happy")
- translate: Translate text ("translate hello es")
- currency: Convert currency ("currency 100 USD EUR")
- nasa: NASA image of the day
- space: Get a random space fact
- meme: Get a random meme
- dadjoke: Get a random dad joke
- chuck: Get a Chuck Norris joke
- kanye: Get a Kanye West quote
- trump: Get a Donald Trump quote
- inspire: Get an inspirational quote
- reverse: Reverse text ("reverse hello")
- shuffle: Shuffle text characters ("shuffle hello")
- palindrome: Check if text is palindrome ("palindrome racecar")
- anagram: Find anagrams of a word ("anagram listen")
- password-strength: Check password strength ("password-strength MyP@ssw0rd")
- email-validator: Validate email address ("email-validator test@example.com")
- ipv4: Validate IPv4 address ("ipv4 192.168.1.1")
- ipv6: Validate IPv6 address ("ipv6 2001:0db8::1")
- domain-check: Check domain information ("domain-check example.com")
- whois: WHOIS lookup ("whois example.com")
- ping: Ping a hostname or IP ("ping google.com")
- timezone: Get timezone information ("timezone UTC")
- age: Calculate age from birthdate ("age 1990-01-01")
- countdown: Start countdown timer ("countdown 30")
- stopwatch: Start/stop stopwatch ("stopwatch")
- reminder: Set a reminder ("reminder Call mom")
- todo: Manage todo list ("todo add Task", "todo list", "todo delete 1", "todo clear")
- bookmark: Manage bookmarks ("bookmark add Name URL", "bookmark list", "bookmark delete 1")
- history: Display command history
- calc: Advanced calculator ("calc 2+2*3", "calc sin(30)")
- unit-convert: Convert units ("unit-convert 100 km miles")
- color-picker: Interactive color picker
- gradient: Generate CSS gradient ("gradient #ff0000 #0000ff")
- font-preview: Preview text in different fonts ("font-preview Hello")
- emoji-search: Search emojis ("emoji-search smile")
- ascii-art: Generate ASCII art ("ascii-art hello")
- wordle: Wordle game helper ("wordle hello")
- speedtest: Test connection speed
- sort: Sort lines alphabetically ("sort apple\nbanana\ncherry")
- unique: Remove duplicate lines ("unique apple\nbanana\napple")
- lines: Count lines in text ("lines text\nwith lines")
- uppercase: Convert text to uppercase ("uppercase hello")
- lowercase: Convert text to lowercase ("lowercase HELLO")
- titlecase: Convert text to title case ("titlecase hello world")
- camelcase: Convert text to camelCase ("camelcase hello world")
- snakecase: Convert text to snake_case ("snakecase hello world")
- kebabcase: Convert text to kebab-case ("kebabcase hello world")
- rot13: Apply ROT13 cipher ("rot13 hello")
- caesar: Apply Caesar cipher ("caesar 3 hello")
- vowels: Count vowels in text ("vowels hello")
- consonants: Count consonants in text ("consonants hello")
- remove-spaces: Remove all spaces ("remove-spaces hello world")
- add-spaces: Add spaces between characters ("add-spaces hello")
- extract-numbers: Extract numbers from text ("extract-numbers abc123")
- extract-letters: Extract letters from text ("extract-letters abc123")
- remove-numbers: Remove numbers from text ("remove-numbers abc123")
- remove-letters: Remove letters from text ("remove-letters abc123")
- capitalize: Capitalize first letter ("capitalize hello")
- swapcase: Swap case of letters ("swapcase HeLLo")
- wrap: Wrap text at specified width ("wrap 20 long text")
- unwrap: Remove line breaks ("unwrap text\nwith breaks")
- indent: Add indentation ("indent 4 hello\nworld")
- dedent: Remove indentation ("dedent text")
- extract-urls: Extract URLs from text ("extract-urls Visit https://example.com")
- extract-emails: Extract email addresses ("extract-emails Contact test@example.com")
- extract-phone: Extract phone numbers ("extract-phone Call 555-123-4567")
- format-json: Format JSON string ("format-json {"name":"John"}")
- minify-json: Minify JSON string ("minify-json {"name":"John"}")

Math Commands:
- add: Add numbers ("add 5 10 15")
- subtract: Subtract numbers ("subtract 10 5")
- multiply: Multiply numbers ("multiply 5 10 2")
- divide: Divide numbers ("divide 10 5")
- power: Raise to power ("power 2 8")
- sqrt: Square root ("sqrt 16")
- factorial: Calculate factorial ("factorial 5")
- fibonacci: Generate Fibonacci sequence ("fibonacci 10")
- prime: Check if prime ("prime 17")
- gcd: Greatest Common Divisor ("gcd 48 18")
- lcm: Least Common Multiple ("lcm 4 6")
- sin: Sine function ("sin 30")
- cos: Cosine function ("cos 60")
- tan: Tangent function ("tan 45")
- log: Logarithm ("log 10" or "log 100 10")
- mean: Calculate mean ("mean 5 10 15 20")
- median: Calculate median ("median 5 10 15 20 25")
- mode: Find mode ("mode 5 10 5 20 10 5")
- range: Calculate range ("range 5 10 15 20")
- to-binary: Convert to binary ("to-binary 42")
- to-hex: Convert to hexadecimal ("to-hex 255")
- to-octal: Convert to octal ("to-octal 64")
- from-binary: Convert from binary ("from-binary 101010")
- from-hex: Convert from hex ("from-hex FF")
- from-octal: Convert from octal ("from-octal 100")
- round: Round number ("round 3.14159 2")
- ceil: Ceiling function ("ceil 3.7")
- floor: Floor function ("floor 3.7")
- abs: Absolute value ("abs -42")
- random: Random number ("random 1 100")
- percent: Calculate percentage ("percent 25 100")

Science Commands:
Physics:
- velocity: Calculate velocity ("velocity 100 10")
- acceleration: Calculate acceleration ("acceleration 0 20 5")
- force: Calculate force F=ma ("force 10 9.8")
- kinetic-energy: Calculate kinetic energy ("kinetic-energy 5 10")
- potential-energy: Calculate potential energy ("potential-energy 10 5")
- density: Calculate density ("density 1000 1")
- pressure: Calculate pressure ("pressure 100 0.5")
- wavelength: Calculate wavelength from frequency ("wavelength 1000000")
- frequency: Calculate frequency from wavelength ("frequency 300")
- energy-photon: Calculate photon energy ("energy-photon 5e14")
Chemistry:
- ph: Calculate pH from H+ concentration ("ph 0.001")
- molar-mass: Calculate molar mass ("molar-mass 18 1")
- moles: Calculate number of moles ("moles 18 18")
- kelvin: Convert Celsius to Kelvin ("kelvin 25")
- celsius: Convert Kelvin to Celsius ("celsius 298.15")
- fahrenheit-to-celsius: Convert Fahrenheit to Celsius ("fahrenheit-to-celsius 98.6")
- celsius-to-fahrenheit: Convert Celsius to Fahrenheit ("celsius-to-fahrenheit 37")
- half-life: Calculate remaining amount ("half-life 100 10 5")
Biology:
- dna-complement: Get DNA complement ("dna-complement ATGCGCTA")
- rna-transcribe: Transcribe DNA to RNA ("rna-transcribe ATGCGCTA")
- codon: Translate codon to amino acid ("codon AUG")
Astronomy:
- light-year: Convert light-years to km ("light-year 1")
Constants:
- planck: Show Planck constant
- speed-of-light: Show speed of light
- avogadro: Show Avogadro's number
- gravitational-constant: Show gravitational constant
- electron-charge: Show elementary charge
Other:
- scientific-notation: Convert to scientific notation ("scientific-notation 1234567")
- ideal-gas: Ideal gas law PV=nRT ("ideal-gas 101325 0.0224 273.15")
- ohms-law: Ohm's law V=IR ("ohms-law 12 2")

More Math Commands:
Trigonometry:
- asin: Arcsine function ("asin 0.5")
- acos: Arccosine function ("acos 0.5")
- atan: Arctangent function ("atan 1")
- sinh: Hyperbolic sine ("sinh 1")
- cosh: Hyperbolic cosine ("cosh 1")
- tanh: Hyperbolic tangent ("tanh 1")
Exponentials & Logarithms:
- exp: e to the power of x ("exp 2")
- ln: Natural logarithm ("ln 10")
- log10: Base 10 logarithm ("log10 100")
- log2: Base 2 logarithm ("log2 8")
Roots:
- cbrt: Cube root ("cbrt 27")
- nth-root: Nth root ("nth-root 16 4")
Statistics:
- variance: Calculate variance ("variance 5 10 15 20")
- std-dev: Standard deviation ("std-dev 5 10 15 20")
- percentile: Calculate percentile ("percentile 10 20 30 40 50 75")
- quartiles: Calculate quartiles ("quartiles 1 2 3 4 5 6 7 8 9")
Operations:
- mod: Modulo operation ("mod 17 5")
- max: Maximum value ("max 5 10 15 3")
- min: Minimum value ("min 5 10 15 3")
- sum: Sum of numbers ("sum 5 10 15")
- product: Product of numbers ("product 2 3 4")
Conversions:
- degrees-to-radians: Convert degrees to radians ("degrees-to-radians 180")
- radians-to-degrees: Convert radians to degrees ("radians-to-degrees 3.14159")
Constants:
- pi: Show pi constant
- e: Show Euler's number
- tau: Show tau constant (2π)
Number Theory:
- factors: List all factors ("factors 12")
- is-even: Check if even ("is-even 42")
- perfect-number: Check if perfect number ("perfect-number 6")
- prime-numbers: List primes up to limit ("prime-numbers 50")

More Science Commands:
Physics:
- momentum: Calculate momentum ("momentum 5 10")
- impulse: Calculate impulse ("impulse 100 0.5")
- work: Calculate work ("work 50 10")
- power-physics: Calculate power ("power-physics 1000 10")
- torque: Calculate torque ("torque 10 0.5")
- angular-velocity: Calculate angular velocity ("angular-velocity 6.28 1")
- bernoulli: Bernoulli's equation ("bernoulli 101325 1000 5 10")
- continuity: Continuity equation ("continuity 0.1 5 0.05")
Chemistry:
- molarity: Calculate molarity ("molarity 0.5 1")
- molality: Calculate molality ("molality 0.5 500")
- mass-percent: Calculate mass percent ("mass-percent 25 100")
- volume-percent: Calculate volume percent ("volume-percent 10 100")
- stoichiometry: Stoichiometric calculations ("stoichiometry 2 2 1")
- joule-to-calorie: Convert joules to calories ("joule-to-calorie 4184")
- calorie-to-joule: Convert calories to joules ("calorie-to-joule 1000")
Biology:
- gc-content: Calculate GC content ("gc-content ATGCGCTA")
- reverse-complement: Get reverse complement ("reverse-complement ATGCGCTA")
- protein-mass: Calculate protein molecular mass ("protein-mass MKTAY")
Astronomy:
- parsec: Convert parsecs to other units ("parsec 1")
- astronomical-unit: Convert AU to other units ("astronomical-unit 1")
- redshift: Calculate redshift ("redshift 656.5 656.3")
Constants:
- boltzmann: Show Boltzmann constant
- stefan-boltzmann: Show Stefan-Boltzmann constant
- rydberg: Show Rydberg constant
- fine-structure: Show fine-structure constant

Medical Commands:
Body Measurements:
- bmi: Body Mass Index ("bmi 70 1.75")
- bsa: Body Surface Area ("bsa 70 175")
- ideal-weight: Ideal body weight ("ideal-weight 175 female")
Renal Function:
- creatinine-clearance: CrCl calculation ("creatinine-clearance 50 70 1.0 male")
- gfr: Estimated GFR ("gfr 1.0 50 male black")
- fena: Fractional excretion of Na ("fena 20 140 50 1.0")
- fractional-excretion-urea: FEUrea ("fractional-excretion-urea 200 20 50 1.0")
- free-water-clearance: Free water clearance ("free-water-clearance 100 300 280")
Cardiovascular:
- map: Mean Arterial Pressure ("map 120 80")
- pulse-pressure: Pulse pressure ("pulse-pressure 120 80")
- heart-rate-zones: HR training zones ("heart-rate-zones 30")
- shock-index: Shock index ("shock-index 120 100")
- stroke-volume: Stroke volume ("stroke-volume 120 50")
- ejection-fraction: Ejection fraction ("ejection-fraction 120 50")
- cardiac-output: Cardiac output ("cardiac-output 70 72")
- cardiac-index: Cardiac index ("cardiac-index 5.0 1.8")
- systemic-vascular-resistance: SVR ("systemic-vascular-resistance 90 5.0")
- pulmonary-vascular-resistance: PVR ("pulmonary-vascular-resistance 25 10 5.0")
Respiratory:
- fraction-inspired: Partial pressure O₂ ("fraction-inspired 0.21")
- a-a-gradient: Alveolar-arterial gradient ("a-a-gradient 0.21 40 100")
- oxygen-content: Arterial O₂ content ("oxygen-content 15 98 100")
- oxygen-delivery: O₂ delivery ("oxygen-delivery 5.0 20")
- oxygen-consumption: O₂ consumption ("oxygen-consumption 5.0 20 15")
- oxygen-extraction: O₂ extraction ratio ("oxygen-extraction 20 15")
- alveolar-ventilation: Alveolar ventilation ("alveolar-ventilation 12 500 150")
- dead-space-ratio: Vd/Vt ratio ("dead-space-ratio 150 500")
- minute-ventilation: Minute ventilation ("minute-ventilation 12 500")
Electrolytes & Acid-Base:
- anion-gap: Anion gap ("anion-gap 140 100 24")
- ferrari: Ferrari gap ("ferrari 140 4 100")
- osmolal-gap: Osmolal gap ("osmolal-gap 290 140 100 20")
- urine-osmolal-gap: Urine osmolal gap ("urine-osmolal-gap 600 50 20 200 0")
- corrected-calcium: Corrected Ca for albumin ("corrected-calcium 9.5 3.0")
- corrected-sodium: Corrected Na for glucose ("corrected-sodium 140 200")
- corrected-magnesium: Corrected Mg for albumin ("corrected-magnesium 2.0 3.5")
- calcium-phosphate: Ca×PO₄ product ("calcium-phosphate 10 5")
- transtubular-gradient: TTKG ("transtubular-gradient 140 50 600 300")
- winters-formula: Winter's formula ("winters-formula 20")
ECG:
- corrected-qt: Corrected QT interval ("corrected-qt 400 1000")
- corrected-qt-bazett: QTc Bazett ("corrected-qt-bazett 400 1000")
- corrected-qt-fridericia: QTc Fridericia ("corrected-qt-fridericia 400 1000")
- corrected-qt-hodges: QTc Hodges ("corrected-qt-hodges 400 1000")
Drug Calculations:
- drug-dose: Drug dosage calculation ("drug-dose 10 70")
- iv-rate: IV infusion rate ("iv-rate 1000 8 20")
- pediatric-dose: Pediatric dose (Young's) ("pediatric-dose 500 8")
- pediatric-dose-clark: Pediatric dose (Clark's) ("pediatric-dose-clark 500 50")
Scoring Systems:
- apgar: APGAR score ("apgar 2 2 1 1 2")
- glasgow-coma: Glasgow Coma Scale ("glasgow-coma 4 5 6")
- wells-pe: Wells PE score ("wells-pe 1 3 1 1 0 0 0")
- chads2: CHADS₂ score ("chads2 1 1 65 1 0")
- child-pugh: Child-Pugh score ("child-pugh 2.0 3.0 1.5 1 0")
- meld: MELD score ("meld 2.0 1.5 1.2")
- wells-dvt: Wells DVT score ("wells-dvt 0 0 1 1 0 0 0 0 0")
- curb-65: CURB-65 score ("curb-65 0 8 28 85 70")
- has-bled: HAS-BLED score ("has-bled 1 0 0 0 0 0 1 0 0")
- qsofa: qSOFA score ("qsofa 0 24 95")
Fluid Management:
- parkland-formula: Parkland burn formula ("parkland-formula 70 20")
- maintenance-fluids: Daily maintenance fluids ("maintenance-fluids 25")
Additional ECG:
- corrected-qt-framingham: QTc Framingham ("corrected-qt-framingham 400 1000")
- corrected-qt-rr: QTc from HR ("corrected-qt-rr 400 60")
ARDS:
- permeability-index: P/F ratio for ARDS ("permeability-index 100 0.5")

Engineering Commands:
Structural Engineering:
- stress: Calculate stress ("stress 1000 0.01")
- strain: Calculate strain ("strain 0.001 1")
- youngs-modulus: Young's modulus ("youngs-modulus 200e9 0.001")
- beam-deflection: Beam deflection ("beam-deflection 1000 5 200e9 0.0001")
- bending-moment: Bending moment ("bending-moment 1000 2")
- shear-stress: Shear stress ("shear-stress 5000 0.005")
- buckling-load: Euler buckling load ("buckling-load 200e9 0.0001 3 1")
- column-buckling: Column buckling ("column-buckling 200e9 0.0001 3 1")
- slenderness-ratio: Slenderness ratio ("slenderness-ratio 3 0.05")
- stress-concentration: Stress concentration ("stress-concentration 100e6 2.5")
- fatigue-life: Fatigue analysis ("fatigue-life 50e6 100e6 200e6")
- poissons-ratio: Poisson's ratio ("poissons-ratio -0.0003 0.001")
- shear-modulus: Shear modulus ("shear-modulus 200e9 0.3")
- bulk-modulus: Bulk modulus ("bulk-modulus 1e6 -0.001")
- torsion: Torsional shear stress ("torsion 1000 0.05 0.0001")
- strain-energy: Strain energy ("strain-energy 200e6 0.001 0.001")
- safety-factor: Safety factor ("safety-factor 400e6 200e6")
- deflection-ratio: Deflection ratio ("deflection-ratio 0.01 2.5")
Thermal Engineering:
- thermal-expansion: Thermal expansion ("thermal-expansion 1 12e-6 50")
- thermal-stress: Thermal stress ("thermal-stress 200e9 12e-6 50")
- heat-transfer: Heat transfer rate ("heat-transfer 0.04 10 20 0.1")
- convection-coefficient: Convection coefficient ("convection-coefficient 1000 1 50")
- heat-capacity: Heat capacity ("heat-capacity 1 4186 10")
- fourier-number: Fourier number ("fourier-number 1e-5 3600 0.1")
- biot-number: Biot number ("biot-number 100 0.1 0.04")
- nusselt-number: Nusselt number ("nusselt-number 100 0.1 0.04")
- prandtl-number: Prandtl number ("prandtl-number 4186 0.001 0.6")
Fluid Mechanics:
- reynolds-number: Reynolds number ("reynolds-number 1000 2 0.1 0.001")
- bernoulli-equation: Bernoulli's equation ("bernoulli-equation 101325 1000 5 10")
- flow-rate: Volumetric flow rate ("flow-rate 2 0.01")
- pressure-drop: Pressure drop ("pressure-drop 0.02 100 1000 2 0.1")
- froude-number: Froude number ("froude-number 5 2")
- mach-number: Mach number ("mach-number 340 340")
- drag-force: Drag force ("drag-force 0.47 1.2 20 1")
- lift-force: Lift force ("lift-force 1.2 1.2 20 10")
Electrical Engineering:
- ohms-law-eng: Ohm's law ("ohms-law-eng 12 2")
- power-electrical: Electrical power ("power-electrical 120 5")
- power-resistance: Power I²R ("power-resistance 5 10")
- capacitance: Capacitance ("capacitance 0.001 10")
- inductance: Inductance ("inductance 12 100")
- impedance: Impedance ("impedance 10 5")
- resonant-frequency: Resonant frequency ("resonant-frequency 0.001 0.000001")
- power-factor: Power factor ("power-factor 800 1000")
- three-phase-power: Three-phase power ("three-phase-power 400 10 0.9")
Mechanical Engineering:
- moment-of-inertia: Moment of inertia ("moment-of-inertia 10 0.5")
- angular-momentum: Angular momentum ("angular-momentum 2 10")
- centrifugal-force: Centrifugal force ("centrifugal-force 1 10 0.5")
- coriolis-force: Coriolis force ("coriolis-force 1 5 0.0000727")
- natural-frequency: Natural frequency ("natural-frequency 10000 100")
- damping-ratio: Damping ratio ("damping-ratio 100 100 10000")
- transmission-ratio: Transmission ratio ("transmission-ratio 3000 1000")
- mechanical-advantage: Mechanical advantage ("mechanical-advantage 1000 100")
- efficiency: Efficiency ("efficiency 800 1000")
Additional Fluid Mechanics:
- shear-rate: Shear rate ("shear-rate 1 0.001")
- viscosity: Viscosity ("viscosity 10 1000")
- weber-number: Weber number ("weber-number 1000 5 0.01 0.072")
- strouhal-number: Strouhal number ("strouhal-number 10 0.1 5")
- grashof-number: Grashof number ("grashof-number 0.003 20 0.1 1e-5")
- rayleigh-number: Rayleigh number ("rayleigh-number 1e6 0.7")
- pump-power: Pump power ("pump-power 0.01 100000 0.8")

Finance Commands:
- compound-interest: Compound interest ("compound-interest 1000 5 10 12")
- present-value: Present value ("present-value 10000 5 10")
- future-value: Future value ("future-value 1000 5 10")
- loan-payment: Loan payment ("loan-payment 200000 4.5 360")
- roi: Return on investment ("roi 1200 1000")
- amortization: Amortization summary ("amortization 200000 4.5 360")
Probability & Combinatorics:
- permutation: Permutation ("permutation 10 3")
- combination: Combination ("combination 10 3")
- probability: Probability ("probability 3 10")
- expected-value: Expected value ("expected-value 10 20 0.3,0.7")
- binomial-probability: Binomial probability ("binomial-probability 10 3 0.5")
Statistics:
- normal-distribution: Normal distribution ("normal-distribution 100 100 15")
- z-score: Z-score ("z-score 115 100 15")
- correlation-coefficient: Correlation coefficient ("correlation-coefficient 1,2,3,4,5 2,4,6,8,10")
- linear-regression: Linear regression ("linear-regression 1,2,3,4,5 2,4,6,8,10")
Color Theory:
- rgb-to-hsl: RGB to HSL ("rgb-to-hsl 255 0 0")
- hsl-to-rgb: HSL to RGB ("hsl-to-rgb 0 100 50")
- hex-to-rgb: Hex to RGB ("hex-to-rgb FF0000")
- rgb-to-hex: RGB to Hex ("rgb-to-hex 255 0 0")
Geometry:
- area-circle: Area of circle ("area-circle 5")
- area-rectangle: Area of rectangle ("area-rectangle 10 5")
- area-triangle: Area of triangle ("area-triangle 10 5")
- volume-sphere: Volume of sphere ("volume-sphere 5")
- volume-cylinder: Volume of cylinder ("volume-cylinder 3 10")
- volume-cone: Volume of cone ("volume-cone 3 10")
- surface-area-sphere: Surface area of sphere ("surface-area-sphere 5")
- pythagorean: Pythagorean theorem ("pythagorean 3 4")
- distance-2d: 2D distance ("distance-2d 0 0 3 4")
- distance-3d: 3D distance ("distance-3d 0 0 0 3 4 5")
- midpoint: Midpoint ("midpoint 0 0 10 10")
- slope: Slope ("slope 0 0 10 5")
Computer Science:
- sha256-hash: SHA-256 hash ("sha256-hash hello")
- xor: XOR operation ("xor 5 3")
- and: AND operation ("and 5 3")
- or: OR operation ("or 5 3")
- not: NOT operation ("not 5")
- left-shift: Left shift ("left-shift 5 2")
- right-shift: Right shift ("right-shift 20 2")
- hamming-distance: Hamming distance ("hamming-distance 5 3")
- parity: Parity check ("parity 5")
Network & IT:
- bandwidth: Bandwidth calculation ("bandwidth 1048576 1")
- latency: Network latency ("latency 1000")
- throughput: Throughput calculation ("throughput 100 50")
- file-size: File size conversion ("file-size 1024 bytes")
- compression-ratio: Compression ratio ("compression-ratio 1000 500")
Audio & Video:
- bitrate: Bitrate calculation ("bitrate 1048576 60")
- sample-rate: Sample rate ("sample-rate 1411200 16 2")
- aspect-ratio: Aspect ratio ("aspect-ratio 1920 1080")
- resolution: Resolution info ("resolution 1920 1080")
- frame-rate: Frame rate ("frame-rate 1800 60")
Photography:
- focal-length: Focal length ("focal-length 36 50")
- depth-of-field: Depth of field ("depth-of-field 50 2.8 5")
- exposure-value: Exposure value ("exposure-value 2.8 125")
- sunny-16: Sunny 16 rule ("sunny-16 100")
Additional Finance:
- npv: Net Present Value ("npv 10 -1000 300 300 300")
- irr: Internal Rate of Return ("irr -1000 300 300 300")
- payback-period: Payback period ("payback-period -1000 300 300 300")
Additional Statistics:
- geometric-mean: Geometric mean ("geometric-mean 2 8 32")
- harmonic-mean: Harmonic mean ("harmonic-mean 2 3 4")
- chi-square: Chi-square statistic ("chi-square 10,20,30 15,15,30")

Network Administrator Commands:
Subnetting & IP Calculations:
- subnet: Subnet calculation ("subnet 192.168.1.0 24")
- cidr-to-mask: CIDR to subnet mask ("cidr-to-mask 24")
- mask-to-cidr: Subnet mask to CIDR ("mask-to-cidr 255.255.255.0")
- network-address: Calculate network address ("network-address 192.168.1.100 24")
- broadcast-address: Calculate broadcast address ("broadcast-address 192.168.1.100 24")
- host-range: Calculate host range ("host-range 192.168.1.0 24")
- hosts-available: Calculate available hosts ("hosts-available 24")
- ip-range: IP range calculation ("ip-range 192.168.1.1 192.168.1.10")
- vlsm: VLSM subnetting ("vlsm 192.168.1.0 24 50 30 10")
- supernet: Supernetting calculation ("supernet 192.168.1.0/24 192.168.2.0/24")
- ip-to-long: IP to long integer ("ip-to-long 192.168.1.1")
- long-to-ip: Long integer to IP ("long-to-ip 3232235777")
- wildcard-mask: Calculate wildcard mask ("wildcard-mask 24")
- next-ip: Get next IP address ("next-ip 192.168.1.1")
- previous-ip: Get previous IP address ("previous-ip 192.168.1.1")
- ip-class: Determine IP class ("ip-class 192.168.1.1")
IP Type Checks:
- private-ip: Check if private IP ("private-ip 192.168.1.1")
- public-ip: Check if public IP ("public-ip 8.8.8.8")
- multicast-ip: Check if multicast IP ("multicast-ip 224.0.0.1")
- link-local: Check if link-local IP ("link-local 169.254.1.1")
- loopback-ip: Check if loopback IP ("loopback-ip 127.0.0.1")
Ports & Protocols:
- port-range: Port range calculation ("port-range 1024 2048")
- well-known-ports: Well-known port lookup ("well-known-ports 80" or "well-known-ports")
Network Analysis:
- mtu: MTU analysis ("mtu 1500")
- jumbo-frame: Jumbo frame check ("jumbo-frame 9000")
- tcp-header: TCP header information ("tcp-header 20" or "tcp-header")
- udp-header: UDP header information ("udp-header")
- ip-header: IP header information ("ip-header 20" or "ip-header")
- ethernet-frame: Ethernet frame size ("ethernet-frame 1500")
- packet-size: Packet size calculation ("packet-size 1460")
- window-size: TCP window size ("window-size 100 50")
- bandwidth-delay: Bandwidth-delay product ("bandwidth-delay 100 50")
