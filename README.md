# Contexly

Contexly is a website that makes researching and working with large amounts of information easier. Upload your files and data, ask questions about them, and find the information you need without manually going through everything.

## Features

- Upload files and work with your information in one place.
- Ask questions about your uploaded data.
- Make large amounts of research easier to understand.
- Get information from your files without searching through every document manually.

## Setup

To use Contexly, you need to download two files:

- `index.html` — the main website.
- `.env.js` — the configuration file where you add your Groq API key.

### 1. Download the files

Download both `index.html` and `.env.js` from this repository and save them in the **same folder**.

### 2. Get a Groq API key

1. Go to the [Groq Console](https://console.groq.com/).
2. Sign in or create an account.
3. Open the [API Keys page](https://console.groq.com/keys).
4. Create a new API key and copy it.

Keep your API key private. Do not share it or upload it to a public repository.

### 3. Add your API key

Open `.env.js` using a text editor such as Notepad or VS Code.

Find this line:

```javascript
window.GROQ_API_KEY = "{GROQ API KEY";
```

Replace the placeholder with your actual Groq API key, keeping the quotation marks. For example:

```javascript
window.GROQ_API_KEY = "gsk_your_actual_api_key_here";
```

**Do not use the example key above.** Replace it with the key you generated in the Groq Console.

Leave the other settings unchanged unless you know what you are changing:

```javascript
window.GROQ_BASE_URL = "https://api.groq.com/openai/v1";
window.GROQ_MODEL = "openai/gpt-oss-120b";
```

Save the file.

### 4. Run Contexly

Make sure both files are in the same folder, then open `index.html` in your browser.

Your API key should now be configured, allowing Contexly to use Groq for its AI features.


## Built with

- HTML, CSS and JavaScript
- Groq API
- `openai/gpt-oss-120b`

## About

Contexly is an individual project built to make research and working with large amounts of information simpler, faster and more practical.
