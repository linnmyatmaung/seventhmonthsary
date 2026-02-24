# 🎂 Happy Birthday Card Template 🎈

A beautiful, interactive, and highly customizable web-based birthday card. Perfect for sending a digital surprise to your loved ones!

---

## ✨ Features

- 📱 **Fully Responsive**: Looks great on mobile, tablet, and desktop.
- 🎨 **Customizable**: Personalize names, messages, and photos via environment variables.
- ⏳ **Countdown/Date Lock**: Set a specific date for the card to be "openable".
- 📜 **Scroll Message**: Include a long, heartfelt message that scrolls beautifully.
- 🚀 **Vercel Ready**: Deploy to the web in seconds.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AnshumanMahato/Happy-Birthday-Card.git
cd Happy-Birthday-Card
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Configure Environment
Copy the example environment file and fill in your details:
```bash
cp example.env .env
```

> [!IMPORTANT]
> Make sure to update the `.env` file with the recipient's name and your chosen photo!

---

## ⚙️ Configuration (.env)

| Variable | Description | Example |
| :--- | :--- | :--- |
| `NAME` | **(Mandatory)** Recipient's name | `Jane` |
| `PIC` | **(Mandatory)** Path to the main photo (in `src/assets/`) | `my-photo.jpg` |
| `NICKNAME` | A cute nickname for personalization | `Sunshine` |
| `HBD_MSG` | Short birthday greeting | `Have a blast!` |
| `SCROLL_MSG` | Path to a `.txt` file with a long message | `message.txt` |
| `OPEN_DATE` | Date when the card becomes active (YYYY-MM-DD) | `2024-12-25` |

---

## 🛠️ Development

To start the development server with live reloading:
```bash
npm run watch
```

> [!TIP]
> This command will automatically initialize your local data and start the Parcel bundler.

---

## 📦 Build & Deploy

### Local Build
To create a production-ready build on your machine:
```bash
npm run build:local
```

### ☁️ Vercel Deployment
This project is pre-configured for Vercel.

1. **Push** your code to GitHub.
2. **Import** the project into Vercel.
3. **Environment Variables**: Add your `.env` variables in the Vercel project settings.
4. **Deploy!** 🚀

> [!NOTE]
> The build command on Vercel is automatically detected as `npm run build:local` based on `vercel.json`.

---

## 📂 Project Structure

- `src/`: Source code (HTML, CSS, JS).
- `builder/`: Scripts to generate the final index file based on config.
- `local/`: Local data storage for assets.
- `dist/`: Generated production build files.

---

## 🤝 Contributing
Feel free to fork this project and add more themes or animations!

**Original Author**: [Anshuman Mahato](https://github.com/AnshumanMahato)
