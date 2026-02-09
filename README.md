# 💕 Will You Be My Valentine?

A playfully sweet Valentine's Day invitation page with a cheeky twist! This simple HTML and JavaScript project creates an interactive card that makes it nearly impossible for your loved one to say "no" to being your Valentine.

## ✨ Features

- **Personalization Support** - Customize the invitation with the receiver's name, sender's name, and even a profile photo using URL parameters!
- **Beautiful Pink-Themed Card** - A romantic card design with hearts and flowers in lovely pinkish colors
- **Animated Decorations** - Floating hearts and beating heart animations for that extra romantic touch
- **Interactive Buttons**:
  - **"Yes" Button** - A lush pink button that's always ready to be clicked
  - **"No" Button** - A plain white outlined button with a playful twist... it runs away when your cursor gets near! 
- **Celebration Animation** - When they finally click "Yes", enjoy a beautiful celebration with exploding hearts
- **Automatic Screenshot** - After 5 seconds of clicking "Yes", the page automatically captures and downloads a screenshot as proof that they said yes! 📸
- **Irritatingly Sweet** - The "No" button is practically unclickable, making it hilariously inevitable that they'll say yes!

## 🎯 The Twist

The "No" button isn't just a button - it's a playful escape artist! Whenever the cursor gets within 100 pixels of it, the button jumps to a random location on the screen. It's the perfect mix of romantic and cheeky, making the whole experience memorable and fun.

## 🚀 How to Use

### Basic Usage
1. Simply open `index.html` in any web browser
2. If you haven't added URL parameters, a personalization modal will appear where you can enter:
   - Receiver's name
   - Your name (sender)
   - Photo URL (optional)
3. Fill in the details or click "Skip" to use the default message
4. Share the page or send the link to your special someone
5. Watch them try (and hilariously fail) to click "No"
6. Celebrate when they inevitably click "Yes"! 🎉
7. Wait 5 seconds and a screenshot will automatically download as proof! 📸

### Personalization with URL Parameters (Alternative Method)

You can also pre-fill the information by adding URL parameters instead of using the modal:

```
index.html?to=Sarah&from=John&photo=https://example.com/photo.jpg
```

**Available parameters:**
- `to` - The receiver's name (appears in the title)
- `from` - Your name (appears as a signature at the bottom)
- `photo` - URL to the receiver's photo (displays as a circular profile picture)

**Examples:**

Just name:
```
index.html?to=Sarah&from=John
```

With photo:
```
index.html?to=Emma&from=Michael&photo=https://i.imgur.com/example.jpg
```

Single parameter:
```
index.html?to=My Love
```

**Tip:** If hosting online, use URL-encoded values for spaces and special characters!

## 💝 Perfect For

- Valentine's Day proposals
- Asking someone to be your Valentine
- A fun and romantic gesture
- Making your loved one smile (and maybe laugh a little)

## 🛠️ Tech Stack

- Pure HTML5
- CSS3 (with animations and transitions)
- Vanilla JavaScript
- html2canvas library (for screenshot capture)

## 📱 Responsive

Works on desktop browsers. Best experienced with a mouse cursor for the full "chase the No button" effect!

---

Made with 💕 and a bit of mischief!
