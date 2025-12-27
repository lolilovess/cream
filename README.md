# 🍦 cream.theme.css 🧶
### the official documentation of the "sturdy-stitch" project

**current version:** `2.2.2` (the "no-trash" update)
**status:** stable & cute
**author:** loli (love & crochet certified) 🏁

---

## 🧸 1. hello! (read this first)
hi!! 👋 welcome to the **cream** repository.

if you are reading this, you are probably tired of your discord looking like a boring corporate spreadsheet or a blinding white flashbang. i get it. i made this theme because i was sitting my bed with **no one**, trying to crochet a complicated pattern, and i realized my screen looked... soulless.

**cream** is not just a color change. it is a **vibe shift**.
it is designed to feel like:
* warm, handmade paper. 📜
* the softest oatmeal-colored wool. 🧶
* a heavy typewriter with fresh ink. 🖋️
* a pro-gamer setup that doesn't try too hard. 💅

if it is pointy, it is wrong. if it is pure white (`#ffffff`), it is trash. if it is not **comic sans**, it is not welcome here.

---

## 📜 2. the history of despair (and why this version exists)
getting to version 2.2.2 was honestly a nightmare. there were tears. there were broken pixels. there was a lot of trial and error in **notepad++**. here is the full saga of how we got here:

### 🥀 v1.0.0: the "mica" tragedy
* **the dream:** i wanted it to look like translucent glass (windows mica style).
* **the reality:** it was a mess. the text went invisible. the background flickered. it looked like a glitchy matrix.
* **the verdict:** **TRASH.** we buried this version and never spoke of it again.

### 👻 v2.0.0: the "white-out" disaster
* **the dream:** a clean, simple light theme.
* **the mistake:** i used `#ffffff` (pure white) for everything.
* **the result:** it burned my retinas. it felt cheap and default. it didn't have that "creamy" texture i needed for the cozy crochet aesthetic.
* **the fix:** i banned the code `#ffffff` from the entire repository. never again.

### 🦴 v2.1.0: the "comic sans" wars
* **the dream:** getting the font to actually load.
* **the struggle:** discord keeps trying to force its boring default font ("gg sans") on us.
* **the victory:** i found the override code. now we use **Comic Sans MS** at weight **800** (extra bold). it looks nerdy, relaxed, and incredibly powerful.

### 🏆 v2.2.2: the "blue-hijack" / sturdy-stitch (CURRENT)
* **the problem:** discord has these annoying "light themes" (like blue, crisp, etc.) that would override my beautiful cream paper.
* **the solution:** **THE HIJACK.** i used `!important` tags on the core variables. now, even if you select the "Light Blue" theme in settings, **cream** takes over. it is unshakeable. it is sturdy. it is perfect.

---

## 🎨 3. the "no-trash" color palette
we do not use default colors here. every single hex code was chosen to match a specific type of cozy material.

| variable name | hex code | what it feels like |
| :--- | :--- | :--- |
| **--paper-main** | `#f3efe0` | high-tier ivory cardstock. warm, expensive, and soft on the eyes. |
| **--paper-side** | `#e6e1cf` | old library book pages. used for the sidebar to give it depth without using ugly shadows. |
| **--ink-bold** | `#3a352f` | typewriter ribbon ink. it’s not black (`#000000`), it’s a very deep, warm charcoal. |
| **--gold-seal** | `#d4af37` | a gold-plated crochet hook. shiny but not tacky. used for borders and "active" items. |

---

## 🧸 4. technical specs (nerdy stuff)
i have 3y experience so i know my way around a config file. here is what makes this theme "good code":

### the black & white integrity 🏁
my character is **black and white**. not "pearl grey." not "off-white." **BLACK AND WHITE.**
to ensure the theme respects this, i wrote specific filters for the icons:
* **home icon:** `filter: grayscale(100%) brightness(0.7);` -> this removes that ugly discord blurple color and makes the icon sharp monochrome.
* **dm avatars:** `border: 2px solid var(--gold-seal);` -> cute gold frames for everyone!

### the rounding logic 🫧
if it is a square, i hate it.
* **standard rounding:** `18px`. this is the "sweet spot." 25px was too bubbly, 10px was too corporate. 18px is just right.
* **chat bubbles:** they have a `5px` gold border on the left side, making them look like sticky notes or a notebook margin.

---

## 🛠 5. installation guide (do not mess this up)
listen, i made this easy for you, but you have to follow the steps.

### step 1: get the file 📥
* download `cream.theme.css` from the top of this page.
* do not just copy-paste the text into a random box. treat the file with respect.

### step 2: the "themes" folder 📂
* open discord.
* go to **user settings** > **vencord** > **themes**.
* click that little button that says **"open themes folder"**.
* drag and drop `cream.theme.css` into that folder.

### step 3: activate the cream 🍦
* go back to discord.
* click **"load missing themes"** (or just restart if you're lazy).
* flip the switch for **cream** to **ON**.

### step 4: THE MOST IMPORTANT PART ☀️
* go to **appearance settings**.
* select **LIGHT MODE**.
* **note:** you can pick the "blue" sub-theme or the "white" sub-theme. it does not matter. my code is stronger than them. it will hijack the colors and force them to be cream.

---

## 🧶 6. final words
this theme was handmade with love, frustration, and a lot of caffeine while traveling with **no one**. it is free for everyone, but please treat it nicely.

* **don't** make it dark mode (you won't be able to read the ink).
* **don't** remove the comic sans (it ruins the vibe).
* **do** crochet while using it.

enjoy the cozy! 🏁✨

**- loli**

---
*end of documentation.*
