# 💕 Will You Be My Valentine?

A playfully sweet Valentine's Day invitation page with a cheeky twist! This simple HTML and JavaScript project creates an interactive card that makes it nearly impossible for your loved one to say "no" to being your Valentine.

## ✨ Features

- **URL Link Generator** - Easy-to-use modal to create personalized invitation links
- **Personalization Support** - Customize with receiver's name, sender's name, and profile photo
- **Beautiful Pink-Themed Card** - A romantic card design with hearts and flowers in lovely pinkish colors
- **Animated Decorations** - Floating hearts and beating heart animations for that extra romantic touch
- **Interactive Buttons**:
  - **"Yes" Button** - A lush pink button that's always ready to be clicked
  - **"No" Button** - A plain white outlined button with a playful twist... it runs away when your cursor gets near! 
- **Celebration Animation** - When they finally click "Yes", enjoy a beautiful celebration with exploding hearts and the receiver's photo in the background
- **Automatic Screenshot** - After 5 seconds of clicking "Yes", the page automatically captures and downloads a screenshot as proof that they said yes! 📸
- **Irritatingly Sweet** - The "No" button is practically unclickable, making it hilariously inevitable that they'll say yes!

## 🎯 The Twist

The "No" button isn't just a button - it's a playful escape artist! Whenever the cursor gets within 100 pixels of it, the button jumps to a random location on the screen. It's the perfect mix of romantic and cheeky, making the whole experience memorable and fun.

## 🚀 How to Use

### Creating Your Personalized Invitation

1. Open `index.html` in any web browser
2. A modal will appear asking you to fill in:
   - **Receiver's name** (required) - The person you're inviting
   - **Your name** (required) - Who the invitation is from
   - **Photo URL** (optional) - A photo of the receiver
3. Click **"Generate Link 💌"**
4. Copy the personalized URL that appears
5. Send this link to your special someone!

### What the Receiver Sees

When they open your personalized link:
1. They see a beautiful Valentine card with their name
2. They try (and hilariously fail) to click "No" - it runs away!
3. When they inevitably click "Yes", celebrate! 🎉
4. After 5 seconds, a screenshot automatically downloads as proof! 📸
5. The celebration page shows their photo in the background (if you added one)

### URL Format (Generated Automatically)

The generated link will look like this:

```
index.html?to=Sarah&from=John&photo=https://example.com/photo.jpg
```

**URL parameters:**
- `to` - The receiver's name
- `from` - The sender's name
- `photo` - URL to the receiver's photo (optional)

You can also manually create these URLs if you prefer, but the modal makes it easy!

**Tip for Facebook Photos:** Right-click on the image → "Copy image address" or "Open image in new tab" to get the direct URL.

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
