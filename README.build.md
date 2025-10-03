# Robotik Project v3

## Cara build di Android Studio
1. Ekstrak ZIP ini
2. Buka folder `Robotik_Project_v3` di Android Studio
3. Tunggu Gradle sync selesai
4. Pilih menu **Build > Build APK(s)**
5. Hasil APK ada di: `app/build/outputs/apk/debug/app-debug.apk`

## Cara build lewat terminal (Linux/macOS)
```bash
./gradlew assembleDebug
```
Hasil ada di: `app/build/outputs/apk/debug/app-debug.apk`

## Cara build lewat GitHub Actions
- Push isi folder ke repo GitHub
- Workflow ada di `.github/workflows/android-build.yml`
- Lihat tab Actions untuk download APK
