<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:id="@+id/main"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".MainActivity">
 <Button
 android:id="@+id/buttonsub"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="217dp"
 android:layout_marginBottom="534dp"
 android:text="-"
 android:textSize="16sp"
 tools:layout_editor_absoluteX="116dp"
 tools:layout_editor_absoluteY="153dp" />
 <Button
 android:id="@+id/buttonadd"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="314dp"
 android:layout_marginBottom="532dp"
 android:text="+"
 android:textSize="16sp"
 tools:layout_editor_absoluteX="28dp"
 tools:layout_editor_absoluteY="153dp" />

 <?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
 xmlns:app="http://schemas.android.com/apk/res-auto"
 xmlns:tools="http://schemas.android.com/tools"
 android:id="@+id/main"
 android:layout_width="match_parent"
 android:layout_height="match_parent"
 tools:context=".MainActivity">
 <Button
 android:id="@+id/buttonsub"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="217dp"
 android:layout_marginBottom="534dp"
 android:text="-"
 android:textSize="16sp"
 tools:layout_editor_absoluteX="116dp"
 tools:layout_editor_absoluteY="153dp" />
 <Button
 android:id="@+id/buttonadd"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="314dp"
 android:layout_marginBottom="532dp"
 android:text="+"
 android:textSize="16sp"
 tools:layout_editor_absoluteX="28dp"
 tools:layout_editor_absoluteY="153dp" />
 <TextView
 android:id="@+id/textView5"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="139dp"
 android:layout_marginBottom="666dp"
 android:text="CALCULATOR"
 android:textColor="#512DA8"
 android:textSize="24sp"
 android:textStyle="bold"
 app:layout_constraintBottom_toBottomOf="parent"
 app:layout_constraintEnd_toEndOf="parent"
 app:layout_constraintHorizontal_bias="0.498"
 app:layout_constraintStart_toStartOf="parent"
 app:layout_constraintTop_toTopOf="parent"
 app:layout_constraintVertical_bias="0.022" />
 <Button
 android:id="@+id/buttondiv"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="114dp"
 android:layout_marginBottom="533dp"
 android:text="/"
 android:textSize="16sp"
 tools:layout_editor_absoluteX="290dp"
 tools:layout_editor_absoluteY="153dp" />
 <Button
 android:id="@+id/Randomcolor"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="118dp"
 android:layout_marginBottom="469dp"
 android:text="Generate random color"
 android:textSize="14sp"
 tools:layout_editor_absoluteX="108dp"
 tools:layout_editor_absoluteY="277dp" />
  <TextView
 android:id="@+id/textView4"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="134dp"
 android:layout_marginBottom="339dp"
 android:text="Background Color"
 android:textColor="#512DA8"
 android:textSize="20sp"
 android:textStyle="bold"
 tools:layout_editor_absoluteX="124dp"
 tools:layout_editor_absoluteY="346dp" />
 <TextView
 android:id="@+id/textView4"
 android:layout_width="wrap_content"
 android:layout_height="wrap_content"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="337dp"
 android:layout_marginBottom="411dp"
 android:text="Result"
 android:textColor="#512DA8"
 android:textSize="20sp"
 android:textStyle="bold"
 tools:layout_editor_absoluteX="124dp"
 tools:layout_editor_absoluteY="346dp" />
 <EditText
 android:id="@+id/editTextText"
 android:layout_width="190dp"
 android:layout_height="45dp"
 android:layout_alignParentBottom="true"
 android:layout_marginBottom="606dp"
 android:ems="10"
 android:inputType="text"
 android:text="First Number"
 android:textColor="#512DA8"
 tools:layout_editor_absoluteX="3dp"
 tools:layout_editor_absoluteY="73dp" />
 <EditText
 android:id="@+id/editTextText2"
 android:layout_width="202dp"
 android:layout_height="46dp"
 android:layout_alignParentEnd="true"
 android:layout_alignParentBottom="true"
 android:layout_marginEnd="8dp"
 android:layout_marginBottom="606dp"
 android:ems="10"
 android:inputType="text"
 android:text="Second Number"
 android:textColor="#512DA8"
 android:textColorLink="#512DA8"
 tools:layout_editor_absoluteX="202dp"
 tools:layout_editor_absoluteY="72dp" />

  <RadioGroup
 android:id="@+id/grp"
 android:layout_width="272dp"
 android:layout_height="266dp"
 android:layout_alignParentBottom="true"
 android:layout_marginBottom="47dp" >
 <RadioButton
 android:id="@+id/r1"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:text="Green" />
 <RadioButton
 android:id="@+id/r2"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:text="Yellow" />
 <RadioButton
 android:id="@+id/r3"
 android:layout_width="match_parent"
 android:layout_height="wrap_content"
 android:text="Red" />
 </RadioGroup>
</RelativeLayout>





package com.example.test2;
import android.graphics.Color;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.RadioButton;
import android.widget.RadioGroup;
import android.widget.TextView;
import androidx.appcompat.app.AppCompatActivity;
import java.util.Random;
public class MainActivity extends AppCompatActivity {
 EditText ed1, ed2;
 Button sub, add, multi, div;
 TextView Result;
 RadioGroup grp;
 Button Randomcolor;
 RadioButton r1,r2,r3;
 @Override
 protected void onCreate(Bundle savedInstanceState) {
 super.onCreate(savedInstanceState);
 setContentView(R.layout.activity_main);
 ed1 = findViewById(R.id.editTextText);
 ed2 = findViewById(R.id.editTextText2);
 sub = findViewById(R.id.buttonsub);
 add = findViewById(R.id.buttonadd);
 multi = findViewById(R.id.buttonmutli);
 div = findViewById(R.id.buttondiv);
 Result = findViewById(R.id.textView4);
 Randomcolor = findViewById(R.id.Randomcolor); // Initializing Randomcolor button
 grp = findViewById(R.id.grp);
 r1 = findViewById(R.id.r1);
 r2 = findViewById(R.id.r2);
 r3 = findViewById(R.id.r3);
 add.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View view) {
 int t1, t2, res;
 t1 = Integer.parseInt(ed1.getText().toString());
 t2 = Integer.parseInt(ed2.getText().toString());

 res = t1 + t2;
 Result.setText("Result=" + res);
 }
 });
 sub.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View view) {
 int t1, t2, res;
 t1 = Integer.parseInt(ed1.getText().toString());
 t2 = Integer.parseInt(ed2.getText().toString());
 res = t1 - t2;
 Result.setText("Result=" + res);
 }
 });
 multi.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View view) {
 int t1, t2, res;
 t1 = Integer.parseInt(ed1.getText().toString());
 t2 = Integer.parseInt(ed2.getText().toString());
 res = t1 * t2;
 Result.setText("Result=" + res);
 }
 });
 div.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View view) {
 int t1, t2, res;
 t1 = Integer.parseInt(ed1.getText().toString());
 t2 = Integer.parseInt(ed2.getText().toString());
 res = t1 / t2;
 Result.setText("Result=" + res);
 }
 });
 Randomcolor.setOnClickListener(new View.OnClickListener() {
 @Override
 public void onClick(View view) {
 Random random = new Random();
 int color = Color.argb(220, random.nextInt(256), random.nextInt(256), random.nextInt(256));
 getWindow().getDecorView().setBackgroundColor(color);
 }
 });
 grp.setOnCheckedChangeListener(new RadioGroup.OnCheckedChangeListener() {
 @Override
 public void onCheckedChanged(RadioGroup radioGroup, int i) {
 switch (i){
 case R.id.r1:

 getWindow().getDecorView().setBackgroundColor(Color.GREEN);
 break;
 case R.id.r2:
 getWindow().getDecorView().setBackgroundColor(Color.YELLOW);
 break;
 case R.id.r3:
 getWindow().getDecorView().setBackgroundColor(Color.RED);
 break;
 }
 }
 });
 }







