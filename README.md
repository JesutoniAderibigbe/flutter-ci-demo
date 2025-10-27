# Flutter CI Demo 🚀

A simple Flutter project demonstrating how to set up Continuous Integration (CI) using **GitHub Actions** — including code analysis, testing, and APK builds.

## 🧠 What This Project Demonstrates
- ✅ Automated Flutter setup with GitHub Actions  
- ✅ Static code analysis (`flutter analyze`)  
- ✅ Unit & widget tests (`flutter test`)  
- ✅ Automatic release APK build and artifact upload  

## ⚙️ Workflow Overview
The CI pipeline runs automatically on:
- Pushes to `main`
- Pull requests targeting `main`

### Pipeline Steps
1. Checkout Repository  
2. Install Flutter  
3. Install Dependencies  
4. Analyze Code  
5. Run Tests  
6. Build Release APK  
7. Upload APK Artifact  

## 📦 Download APK
After each successful workflow run, go to the **Actions** tab → Select a run → Download `app-release-apk`.

## 🧰 Tech Stack
- Flutter (stable channel)
- GitHub Actions

## 💡 Next Improvements
- Add cache to speed up builds  
- Add automated release to Firebase App Distribution  
- Include iOS build workflow (using macOS runner)

---

*Built with ❤️ by [Jesutoni Aderibigbe]*