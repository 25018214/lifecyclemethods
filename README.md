# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by:AKASH A
Registeration Number :212225230008
*/
```

Main Activity.java
```
package com.example.test1;

import android.os.Bundle;
import android.widget.Toast;

import androidx.activity.EdgeToEdge;
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.graphics.Insets;
import androidx.core.view.ViewCompat;
import androidx.core.view.WindowInsetsCompat;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "OnCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "OnStart Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "OnResume Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "OnPause Called", Toast.LENGTH_LONG);
        toast.show();

    }
    @Override
    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "OnStop Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "OnDestroy Called", Toast.LENGTH_LONG);
        toast.show();
    }
    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "OnRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }
}
```
activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="236dp"
        android:background="#FF0000"
        android:fontFamily="sans-serif-smallcaps"
        android:shadowColor="#FEF7FF"
        android:text="welcome to android studio!!"
        android:textAlignment="center"
        android:textColor="#000000"
        android:textSize="24sp"
        android:textStyle="bold"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.558"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:background="#F2B0CA"
        android:fontFamily="monospace"
        android:text="Life cycle activity"
        android:textAlignment="center"
        android:textColor="#100A0A"
        android:textSize="24sp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2"
        app:layout_constraintVertical_bias="0.271"
        tools:ignore="MissingConstraints" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT

<img width="1356" height="716" alt="Screenshot 2026-11-01 182858" src="https://github.com/user-attachments/assets/dd2dba1b-6ed3-4520-ad4c-35795f6ae40c" />

<img width="1357" height="702" alt="Screenshot 2026-11-01 183002" src="https://github.com/user-attachments/assets/2628f634-50e2-4ba8-8549-54bdac969d67" />

<img width="1362" height="696" alt="Screenshot 2026-11-01 183122" src="https://github.com/user-attachments/assets/c743667f-1852-4996-ba1f-17798446c144" />

<img width="1351" height="697" alt="Screenshot 2026-11-01 184022" src="https://github.com/user-attachments/assets/3c1cf4e8-9bef-4626-a6ed-798b6f624c36" />

<img width="1349" height="695" alt="Screenshot 2026-11-01 183235" src="https://github.com/user-attachments/assets/c1350ef0-3c70-4537-a64a-d7c500db0361" />


<img width="1366" height="720" alt="Screenshot 2026-11-01 184240" src="https://github.com/user-attachments/assets/4e00bf6d-ec3f-4636-b7e8-65fd62b67073" />



## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
