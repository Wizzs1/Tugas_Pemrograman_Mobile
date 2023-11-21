| 🐻 | DATA MAHASISWA |
| -------- | --- |
| **Nama** | Wisnu Ikhwansyah Saputra|
| **NIM** | 312010305 |
| **Kelas** | TI.22.A3 |
| **Mata Kuliah** | Pemrograman Mobile |

---

### Kodingan AndroidManifest.xml

    <?xml version="1.0" encoding="utf-8"?>
    <manifest xmlns:android="http://schemas.android.com/apk/res/android">
    
        <uses-permission android:name="com.android.alarm.permission.SET_ALARM" />
    
        <application
            android:allowBackup="true"
            android:icon="@drawable/download"
            android:label="Rosé"
            android:roundIcon="@drawable/download"
            android:supportsRtl="true"
            android:theme="@style/Theme.HelloToast">
    
    
            <activity
                android:name=".SplashScreen"
                android:exported="true">
                <intent-filter>
                    <action android:name="android.intent.action.MAIN" />
                    <category android:name="android.intent.category.LAUNCHER" />
                </intent-filter>
            </activity>
    
            <activity android:name=".MainHomePage"></activity>
            <activity android:name=".MainActivity"></activity>
            <activity android:name=".MainScrollice"></activity>
            <activity android:name=".MainToast"></activity>
            <activity android:name=".MainFirstActivity"></activity>
    
        </application>
    </manifest>
