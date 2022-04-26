# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min.required Artic Fox)

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
Developed by: ASHWIN A O
Registeration Number : 212220230005
*/
```

### MainActivity.java
```
package com.example.proj1;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnCreate Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnStart Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnResume Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnPause Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnStop Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnRestart Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),
                "OnDestroy Invoked",Toast.LENGTH_LONG);
                toast.show();
    }
}

```

### activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World"
        android:textAlignment="center"
        android:textColor="#2196F3"
        android:textSize="48sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```

## OUTPUT

![proj1 – MainActivity java  proj1 app  26-04-2022 09_30_56](https://user-images.githubusercontent.com/75235601/165219690-bf108a8f-744e-4186-a3f1-d8880156e9c8.png)
![proj1 – MainActivity java  proj1 app  26-04-2022 09_30_59](https://user-images.githubusercontent.com/75235601/165219719-3f2f2c17-a922-4847-970f-12edb553b4c2.png)
![proj1 – MainActivity java  proj1 app  26-04-2022 09_31_28](https://user-images.githubusercontent.com/75235601/165219736-614dddd6-94a3-458d-8379-7cbdf9381443.png)
![proj1 – MainActivity java  proj1 app  26-04-2022 09_31_39](https://user-images.githubusercontent.com/75235601/165219764-009fb0e5-6baf-40a3-bc65-dac49d76806f.png)
![proj1 – MainActivity java  proj1 app  26-04-2022 09_35_32](https://user-images.githubusercontent.com/75235601/165219785-815c5de0-826e-4e07-9148-b09e3c9dce41.png)
![proj1 – MainActivity java  proj1 app  26-04-2022 09_32_52](https://user-images.githubusercontent.com/75235601/165219807-c54a91ea-0fd7-49c8-b411-621a370069d6.png)

## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
