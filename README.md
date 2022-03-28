- 👋 Hi, I’m @HumnaZaheer
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
HumnaZaheer/HumnaZaheer is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<?xml version="1.0" encoding="utf-8"?>
<androidx.coordinatorlayout.widget.CoordinatorLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <com.google.android.material.appbar.AppBarLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:theme="@style/Theme.MyApplication.AppBarOverlay">

    </com.google.android.material.appbar.AppBarLayout>

    <com.google.android.material.floatingactionbutton.FloatingActionButton
        android:id="@+id/fab"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="bottom|end"
        android:layout_marginEnd="@dimen/fab_margin"
        android:layout_marginBottom="16dp"
        app:srcCompat="@android:drawable/ic_dialog_email" />

    <Button
        android:id="@+id/button2"
        android:layout_width="match_parent"
        android:layout_height="171dp"
        android:fontFamily="sans-serif-condensed"
        android:text="Humna Zaheer 19-Arid-1191" />

    <androidx.constraintlayout.widget.ConstraintLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#A366AE">

        <TextView
            android:id="@+id/textView3"
            android:layout_width="111dp"
            android:layout_height="32dp"
            android:layout_marginBottom="384dp"
            android:background="#7C6691"
            android:text="&quot; HELLO WORLD&quot;"
            app:layout_constraintBottom_toBottomOf="parent"
            tools:layout_editor_absoluteX="150dp" />
    </androidx.constraintlayout.widget.ConstraintLayout>

