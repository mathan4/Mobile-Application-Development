![265255132-37b6b016-0af4-48da-be8b-be7a93a8525f](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/64e73118-867a-4034-aaab-c94400ad67ea)# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


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
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:tools="http://schemas.android.com/tools" android:layout_width="match_parent" android:layout_height="match_parent" tools:context=".MainActivity">
```
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:textSize="40dp"
    android:text="Hello World!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toTopOf="parent" />
```
MainActivity.java:
```
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle; import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStart() {
    super.onStart();
    Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
    toast.show();
}
@Override
protected void onRestart() {
    super.onRestart();
    Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onPause() {
    super.onPause();
    Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onResume() {
    super.onResume();
    Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onStop() {
    super.onStop();
    Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
    toast.show();
}
protected void onDestroy() {
    super.onDestroy();
    Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
    toast.show();
}
```
Developed by: Mathan S

Registeration Number : 212221040103

## OUTPUT

![265255045-a2482c99-ac97-4470-97a7-70a742b84435](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/9b914f4d-d194-475f-b80d-ded15fd9a0d6)

![265255110-a85ee5ea-0b2b-4055-b0c5-104151bbc0bd](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/be0fde59-94f0-41d3-9c71-c41481a0c8e2)
![265255132-37b6b016-0af4-48da-be8b-be7a93a8525f](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/b9120abb-4d48-43be-b3c2-79553ff8e1c4)



![265255235-70d48e7a-e006-45f3-8bee-cb1d7590c018](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/9a15cb0f-f308-4a8f-aa01-45d76459fab7)

![265255282-592b9026-153f-4958-886c-411a44032dc3](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/e78399f3-f5fe-4c43-86b0-8bea2908c941)

![265255290-69b02f5c-6ed4-4b6e-af9c-82bf0b1f752c](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/640d3d1b-7027-4c65-a7ac-a5517b79d171)
![265255335-79e6335f-774c-43e5-ad0b-d323ff545eb4](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/96b7da55-2687-4731-9ebd-2f66d03a34a8)

![265255353-a3514219-a312-4259-a32a-e5dfed6f2c29](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/6e11d47d-f4d8-4769-a290-5435863c4249)

![265255357-872f57fc-7aa1-446f-b59f-6b098827a398](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/ac4048fa-d898-4f80-b8ee-d58374d98653)
![265255372-1e24b153-c6be-44b9-8f75-6882a41129df](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/5a039b35-2946-43b2-a9e0-f0fd9e283761)
![265255383-681c5a9a-af98-49dd-b002-05011013fbb4](https://github.com/mathan4/Mobile-Application-Development/assets/109868924/f5a3526b-d383-4867-9f98-af63f3d25990)


## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
