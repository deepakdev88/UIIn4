# UIIn4

A simple and visually appealing Jetpack Compose Android app demonstrating four core composable functions: **Text**, **Image**, **Row**, and **Column**—perfect for beginners learning about layouts in Compose!

---

## 📱 Preview

![Screenshot_20250623_093221_UIIn4](https://github.com/user-attachments/assets/bd87ad12-5d7d-46ca-bca5-e5029dec3332)


---

## ✨ Features

- **Modern Jetpack Compose UI:** Built entirely with Jetpack Compose for a smooth, declarative experience.
- **Clean 2x2 Quadrant Layout:** Each composable gets its own colorful section for easy learning.
- **Material Design:** Follows Material guidelines for a polished look.
- **Beginner-Friendly:** Concise explanations of each composable make it perfect for new Android developers.

---

## 🧩 What’s Inside

| Composable        | Description                                                                   |
|-------------------|-------------------------------------------------------------------------------|
| **Text**          | Displays text and follows Material Design guidelines.                         |
| **Image**         | Lays out and draws a given `Painter` class object.                            |
| **Row**           | A layout composable that places its children in a horizontal sequence.        |
| **Column**        | A layout composable that places its children in a vertical sequence.          |

---

## 🚀 Getting Started

1. **Clone this repo:**
   ```bash
   git clone https://github.com/deepakdev88/UIIn4.git
   ```
2. **Open in Android Studio**
3. **Build & Run on your device or emulator**

---

## 🛠️ Main Code Example

```kotlin
@Composable
fun ComposeQuadrantApp(){
    Column(modifier = Modifier.fillMaxWidth()) {
        Row (modifier = Modifier.weight(1f)){
            ComposableInfoCard(
                title = stringResource(R.string.text_1),
                description = stringResource(R.string.text_2_1),
                backgroundColor = Color(0xFFEADDFF),
                modifier = Modifier.weight(1f)
            )
            ComposableInfoCard(
                title = stringResource(R.string.text_3),
                description = stringResource(R.string.text_4_3),
                backgroundColor = Color(0xFFD0BCFF),
                modifier = Modifier.weight(1f)
            )
        }
        Row (modifier = Modifier.weight(1f)) {
            ComposableInfoCard(
                title = stringResource(R.string.text_5),
                description = stringResource(R.string.text_6_5),
                backgroundColor = Color(0xFFB69DF8),
                modifier = Modifier.weight(1f)
            )
            ComposableInfoCard(
                title = stringResource(R.string.text_7),
                description = stringResource(R.string.text_8_7),
                backgroundColor = Color(0xFFF6EDFF),
                modifier = Modifier.weight(1f)
            )
        }
    }
}
```

---

## 💡 Why this project?

- Great reference for beginners to understand Jetpack Compose layouts.
- Simple, colorful UI makes learning fun!
- Can be extended with more composables or interactive examples.

---

## 🤝 Contributing

Contributions, ideas, and suggestions are welcome! Feel free to fork the repo, open an issue, or submit a pull request.

---

## 📃 License

This project is open source. Please add a license if you want others to use/contribute!

---

**Made with ❤️ by [deepakdev88](https://github.com/deepakdev88)**
