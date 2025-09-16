# Anoma-ID Generator 
Each ID carries your chosen rank, from Apprentice to Wizard


<h3> https://speedevs.github.io/Anoma-ID/</h3>

<h3>Anomage Island Passport </h3>

An interactive web-based passport generator themed around the **Anomage Island** universe. This project allows users to create a personalized mage passport with dynamic ranks, overlay effects, theme toggles, and export options.

---

##  Features

### 🎨 UI & Design
- **Dark/Light Theme Toggle**: Switch between dark mode and light mode with one click.
- **Responsive Layout**: Forced desktop-like layout for consistent design.
- **Custom Branding**: Includes Anoma logo at the top-right and watermark in the background.

###  Passport Details
- **Full Name Input**: Enter a mage’s name to display on the passport.
- **Mage Ranks**: Select from different ranks such as `Intent`, `Seeker`, `Master`, `Acolyte`, `Apprentice`, `Grandmaster`, and `Wizard`. Each rank has its own color highlight.
- **Passport ID**: Auto-generates an ID starting with `MAGE-XXXXX`, with option to randomize.
- **Issue & Expiry Dates**: Select validity period using date pickers.
- **Avatar Upload**: Upload an avatar photo, displayed as a circular profile image on the top-left of the passport.

###  Dynamic Overlay Effects
- When applying, the passport displays a rank-specific overlay message:
  - **Seeker** → "Seeker Still seeking" (with green tint)
  - **Master** → "GrandMaster Awaits you Mage"
  - **Grandmaster** → "Wizard soon twin 67" (with golden aura)
  - Default → "WELCOME MAGE"

### 💾 Export Options
- **Save as PNG**
- **Save as JPG**
- **Save as PDF**

### 🖼 Branding & Watermark
- **Anoma Logo** pinned to the top-right corner.
- **Subtle Watermark** background for added authenticity.

---

## 🛠 Tech Stack
- **HTML5**
- **CSS3** (with custom variables for colors & theming)
- **JavaScript (Vanilla)**
- **Libraries**:
  - [html2canvas](https://html2canvas.hertzen.com/) → for image/PDF capture
  - [jsPDF](https://github.com/parallax/jsPDF) → for PDF export


## Demo Website

[Live Demo](https://speedevs.github.io/Anoma-ID/)

## Screenshots
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://raw.githubusercontent.com/Speedevs/Anoma-ID/refs/heads/main/passport.png)


## 📖 How to Use
1. Clone this repo
2. Open the `index.html` file in any modern web browser.
3. Fill in your mage details:
   - Enter **Full Name**
   - Select **Mage Rank**
   - Generate/enter **Passport ID**
   - Pick **Issue & Expiry Dates**
   - Upload **Avatar Photo**
4. Click **Apply** to see your passport.
5. Export as **PNG, JPG, or PDF**.

## Credits : Mages Corner

