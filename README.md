<h1 align="center">✨ ℝ𝕒𝕕𝕦𝕔𝕠𝕣𝕕 𝕃𝕚𝕓𝕣𝕒𝕣𝕪 ✨</h1>

<p align="center">
  <img src="https://img.shields.io/github/license/H4cK3dR4Du/Epic-Games-X-Discord.svg?style=for-the-badge&labelColor=black&color=c1121f&logo=IOTA"/>
  <img src="https://img.shields.io/github/stars/H4cK3dR4Du/Epic-Games-X-Discord.svg?style=for-the-badge&labelColor=black&color=c1121f&logo=IOTA"/>
  <img src="https://img.shields.io/github/languages/top/H4cK3dR4Du/Epic-Games-X-Discord.svg?style=for-the-badge&labelColor=black&color=c1121f&logo=javascript"/>
</p>

<h2 align="center"> 📝 Description 📝 </h2>

<p align="center">
  The best library for designs, with a wide variety of colors and useful utils for your tools.
</p>

<p align="center">
  <b><big>❤️ Made By H4cK3dR4Du ❤️</big></b>
</p>

<h2 align="center"> 🛠️ Features 🛠️ </h2>

### - Important Features:

- **Custom Logger**
- **Console Utils**
- **Custom Colors**
- **Custom ASCII Banners**
- **Gradient Text**
- **Custom Fonts**
- **Discord Utils**
- **Custom Boxes / Lines**
- **More Soon...**

<h2 align="center"> 🤷‍♂️ Issues / Doubts 🤷‍♂️</h2>

- **If you have any questions do not hesitate to enter my discord: https://discord.gg/raducord**
- **Or if you have any error do not forget to report it in: [issues](https://github.com/H4cK3dR4Du/raducord/issues/new)**

<h2 align="center"> ⚠️ Disclaimer ⚠️ </h2>

- **This program is solely for educational and testing purposes. The use of this program for illegal or unethical activities is strictly prohibited. The user is solely responsible for ensuring compliance with all applicable laws and regulations when using this program.**

- **The author of this program assumes no responsibility for the misuse or illegal use of the program. The user understands and accepts that the use of this program is at their own risk.**

<h2 align="center"> 🚀 How To Install Raducord 🚀 </h2>

### - Requirements And Files For My Library:

- **Download Python [here](https://www.python.org/downloads/)**

### - Library Setup:

*1. Open a terminal or command prompt on your computer.*

*2. Copy and paste the following commands into the terminal to install the library:*
   
```bash
# Install raducord library.
pip install raducord

# Install raducord library custom version
pip install raducord==1.0.0
```

<h2 align="center"> 🪄 How To Use Raducord 🪄 </h2>

### - Console Utils 💻:

```bash
Console.init() # [Allow use of colors]
Console.clear() # [Clear terminal]
Console.size(x, y) # [Set size to your terminal]
Console.execute_command("pip install raducord") # [Execute any cmd command]
Console.title("Raducord Library On Top") # [Set title to your program]
Console.close() # [Close the terminal]
Console.full_screen() # [Full screen your terminal]
```

### - ColorUtils 🌈:

```bash
print(ColorUtils.hex_color("#D00000") + "Raducord Library ColorUtils!") # [Use any color by its HEX code]
print(ColorUtils.rgb_color(208, 0, 0) + "Raducord Library ColorUtils!") # [Use any color by its RGB code]
print(ColorUtils.hsl_color(0, 100, 41) + "Raducord Library ColorUtils!") # [Use any color by its HSL code]

# Example Colors In Variables:

red = ColorUtils.hex_color("#FF0000")
red = ColorUtils.rgb_color(255, 0, 0)
red = ColorUtils.hsl_color(0, 100, 50)

# URL For Colors: https://coolors.co/palettes/trending
```

### - BannerUtils 📋:

```bash
# Boxes:

print(BannerUtils.box_1("Raducord Library!"))
print(BannerUtils.box_2("Raducord Library!"))
print(BannerUtils.box_3("Raducord Library!"))
print(BannerUtils.box_4("Raducord Library!"))
print(BannerUtils.box_5("Raducord Library!"))
print(BannerUtils.box_6("Raducord Library!"))
print(BannerUtils.box_7("Raducord Library!"))
print(BannerUtils.box_8("Raducord Library!"))
print(BannerUtils.box_9("Raducord Library!"))

# Lines:

print(BannerUtils.lines_1("Raducord Library!"))
print(BannerUtils.lines_2("Raducord Library!"))
print(BannerUtils.lines_3("Raducord Library!"))
print(BannerUtils.lines_4("Raducord Library!"))
print(BannerUtils.lines_5("Raducord Library!"))
print(BannerUtils.lines_6("Raducord Library!"))

# Center Text:

print(BannerUtils.center_text("Raducord Library!"))
```

### - TextUtils 🗒️:

```bash
print(TextUtils.fancy_text("Raducord Library"))
print(TextUtils.fraktur_text("Raducord Library"))
print(TextUtils.cursive_text("Raducord Library"))
print(TextUtils.syllabic_text("Raducord Library"))
print(TextUtils.strikethrough_text("Raducord Library"))
print(TextUtils.double_struck_text("Raducord Library"))

# ASCII Banners:

print(TextUtils.make_ascii("Raducord", font="3-d"))
print(TextUtils.make_ascii("Raducord", font="graffiti"))
print(TextUtils.make_ascii("Raducord", font="a_zooloo"))
print(TextUtils.make_ascii("Raducord", font="6x9"))

# URL With ASCII List: https://pastebin.com/raw/wKdnb2n0
```

### - Gradient 🍧:

```bash
# Custom Text/Banner With Gradient Colors (RGB):
# Usage: Gradient.gradient_text_custom(text, (R, G, B), (R, G, B)))

banner = "Raducord Library\nRaducord Library\nRaducord Library\nRaducord Library\nRaducord Library\nRaducord Library"
print(Gradient.gradient_text_custom(banner, (0, 255, 0), (255, 255, 0)))

banner = "Raducord Library\nRaducord Library\nRaducord Library\nRaducord Library\nRaducord Library\nRaducord Library"
print(Gradient.gradient_text_custom(banner, (255, 0, 0), (0, 0, 255)))

# You can use default gradient colors (Over 200) such as:

print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.blue_to_green))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.red_to_blue))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.yellow_to_gray))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.pink_to_orange))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.orange_to_blue))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.gold_to_red))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.silver_to_blue))
print(Gradient.gradient_text("Raducord Text Gradient", GradientColors.cyan_to_green))
```

### - Discord Utils 🥏:

```bash
native_build = Discord.get_native_build()
main_version = Discord.get_main_version()
build_number = Discord.get_build_number()
xsuper_properties = Discord.get_xsuper_properties(native_build, main_version, build_number)
cookies = Discord.get_cookies(proxy)
birthdate = Discord.generate_birthdate()
check_token = Discord.check_token("MTE...") (True/False)
fingerprint = Discord.get_fingerprint(proxy)
```

### - Utils 🪄:

```bash
full_name = Utils.get_full_name() # Example: Claudia, Lemos
uuid_ = Utils.generate_uuid() # Example: d3c23143-f876-1404-45c6-478de1899d0f
user_agent = Utils.generate_user_agent() # Example: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/117.0.0.0 Safari/537.36
timestamp = Utils.get_timestamp() # Example: 1714747956885
current_time = Utils.log_time() # Example: 16:52:36
```

<h2 align="center"> 📹 Showcase 📹 </h2>

![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/1f4ec630-131c-446f-8169-e82881d45e1b)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/0b050fb3-d8dc-4d79-ac79-fdfaa667cf14)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/ebf7e315-63a2-485b-867a-5dfc457b8b29)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/d7d4ef0b-df52-4f94-ab46-3a05ee65cc0d)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/a8db6296-d6d0-4764-8512-8bd09e1f4fe1)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/f2913349-e9fb-46b6-84ba-a5230d479365)
![image](https://github.com/H4cK3dR4Du/raducord/assets/118562174/79c4c427-9eaa-4de2-a992-e196f3eec2d9)
