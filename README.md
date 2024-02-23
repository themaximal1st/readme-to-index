# readme-to-index
> Convert a README file into a beautiful website

Mostly useful for The Maximalist open-source project websites.

Create a website, README.md and public dir.

```bash
mkdir website
cd website
touch README.md # edit
mkdir public
cd public
```

Create `build` script

```bash
NAME="llm.js"
DOMAIN="llmjs.themaximalist.com"
TITLE="LLM.js — Simple LLM library for Node.js "
DESCRIPTION="Use dozens of Large Language Models your apps (like GPT-4, Gemini, Claude and more)"
CLASSES="gap-2xl"

readme-to-index "$NAME" "$DOMAIN" "$TITLE" "$DESCRIPTION" "$CLASSES"
```

Then build the README to a website

```bash
chmod +x build
./build
```
