# Ex 1 - calc

# activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#FCF8F8"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.3"
        android:orientation="vertical">

        <TextView
            android:id="@+id/input"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:textColor="@color/black"
            android:textSize="30sp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.3"

        android:orientation="vertical"
        android:background="#EEF2F3">

        <TextView

            android:id="@+id/display"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:textColor="@color/black"
            android:textSize="30sp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"

        android:orientation="horizontal">

        <Button

            android:id="@+id/buttonclr"

            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"



            android:text="Clear"
            android:textSize="20sp"></Button>


        <Button
            android:id="@+id/buttoneql"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"


            android:text="="
            android:textSize="30sp" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"
        android:orientation="horizontal">
        <Button
            android:id="@+id/buttoncos"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="cos"

            android:textSize="20sp" />

        <Button
            android:id="@+id/buttonsin"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="sin"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttontan"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="tan"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonsqrt"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="sqrt"

            android:textSize="20sp" />

    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"
        android:orientation="horizontal">
        <Button
            android:id="@+id/buttonsq"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="x^2"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonpow"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="x^y"

            android:textSize="20sp" />

        <Button
            android:id="@+id/buttonlog"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="log"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonexp"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="e^x"

            android:textSize="20sp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"

        android:orientation="horizontal">
        <Button
            android:id="@+id/button7"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="7"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button8"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="8"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button9"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="9"

            android:textSize="20sp" />

        <Button
            android:id="@+id/buttondiv"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="/"

            android:textSize="30sp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"
        android:orientation="horizontal">
        <Button
            android:id="@+id/button4"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="4"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button5"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="5"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button6"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="6"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonmul"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="*"

            android:textSize="30sp" />

    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"
        android:orientation="horizontal">
        <Button
            android:id="@+id/button1"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="1"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button2"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="2"

            android:textSize="20sp" />
        <Button
            android:id="@+id/button3"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="3"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonsub"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="-"

            android:textSize="30sp" />
    </LinearLayout>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_weight="0.2"
        android:orientation="horizontal">
        <Button
            android:id="@+id/buttondot"

            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="."

            android:textSize="20sp" />
        <Button
            android:id="@+id/button0"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="0"

            android:textSize="20sp" />
        <Button
            android:id="@+id/buttonrem"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="%"
            android:textSize="30sp" />
        <Button
            android:id="@+id/buttonadd"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_margin="1dp"
            android:layout_weight="0.25"
            android:text="+"

            android:textSize="30sp" />
    </LinearLayout>
</LinearLayout>
```
# MainActivity.java
```
package com.example.exp2;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {

    double input1 = 0, input2 = 0;
    TextView edt1,edt2;
    boolean Add, Sub, Mul, Div, Rem, dec, cos, sin, tan, pow, sq, sqrt, log, exp;
    Button button0, button1, button2, button3, button4, button5, button6, button7, button8,
            button9, buttonAdd, buttonSub, buttonMul, buttonDiv, buttonEqual, buttonClr,
            buttonDot, buttonRem, buttonCos, buttonSin, buttonTan, buttonPow, buttonSq,
            buttonSqrt, buttonLog, buttonExp;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        getSupportActionBar().setTitle("Ex-2 Abhijith PV");

        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        button0 = (Button) findViewById(R.id.button0);
        button1 = (Button) findViewById(R.id.button1);
        button2 = (Button) findViewById(R.id.button2);
        button3 = (Button) findViewById(R.id.button3);
        button4 = (Button) findViewById(R.id.button4);
        button5 = (Button) findViewById(R.id.button5);
        button6 = (Button) findViewById(R.id.button6);
        button7 = (Button) findViewById(R.id.button7);
        button8 = (Button) findViewById(R.id.button8);
        button9 = (Button) findViewById(R.id.button9);
        buttonDot = (Button) findViewById(R.id.buttondot);
        buttonAdd = (Button) findViewById(R.id.buttonadd);
        buttonSub = (Button) findViewById(R.id.buttonsub);
        buttonMul = (Button) findViewById(R.id.buttonmul);
        buttonDiv = (Button) findViewById(R.id.buttondiv);
        buttonRem = (Button) findViewById(R.id.buttonrem);
        buttonCos = (Button) findViewById(R.id.buttoncos);
        buttonSin = (Button) findViewById(R.id.buttonsin);
        buttonTan = (Button) findViewById(R.id.buttontan);
        buttonSqrt = (Button) findViewById(R.id.buttonsqrt);
        buttonPow = (Button) findViewById(R.id.buttonpow);
        buttonLog = (Button) findViewById(R.id.buttonlog);
        buttonExp = (Button) findViewById(R.id.buttonexp);
        buttonSq = (Button) findViewById(R.id.buttonsq);
        buttonClr = (Button) findViewById(R.id.buttonclr);
        buttonEqual = (Button) findViewById(R.id.buttoneql);
        edt1 = (TextView) findViewById(R.id.input);
        edt2 = (TextView) findViewById(R.id.display);

        button1.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "1");
            }
        });
        button2.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "2");
            }
        });
        button3.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "3");
            }
        });
        button4.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "4");
            }
        });
        button5.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "5");
            }
        });
        button6.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "6");
            }
        });
        button7.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "7");
            }
        });
        button8.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "8");

            }
        });
        button9.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "9");
            }
        });
        button0.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText(edt1.getText() + "0");
            }
        });
        buttonAdd.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    Add = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonSub.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    Sub = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonMul.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    Mul = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonDiv.setOnClickListener(new View.OnClickListener() {

            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    Div = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonRem.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    Rem = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });

        buttonCos.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1=Float.parseFloat(edt1.getText() + "");
                    cos = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonSin.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1=Float.parseFloat(edt1.getText() + "");
                    sin = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonTan.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1=Float.parseFloat(edt1.getText() + "");
                    tan = true;

                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonPow.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    pow = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonSq.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    sq = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonSqrt.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    sqrt = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });
        buttonLog.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    log = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });

        buttonExp.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (edt1.getText().length() != 0) {
                    input1 = Float.parseFloat(edt1.getText() + "");
                    exp = true;
                    dec = false;
                    edt1.setText(null);
                }
            }
        });

        buttonDot.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (dec) {
//do nothing or you can show the error
                } else {
                    edt1.setText(edt1.getText() + ".");
                    dec = true;
                }
            }
        });
        buttonClr.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                edt1.setText("");
                edt2.setText("");
                input1 = 0.0;
                input2 = 0.0;
            }
        });
        buttonEqual.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                if (Add || Sub || Mul || Div || Rem || pow) {
                    input2 = Float.parseFloat(edt1.getText() + "");
                }
                if (Add) {
                    edt1.setText((int)input1+"+"+(int)input2);
                    double radd=input1+input2;
                    edt2.setText((int)radd+"");
                    Add = false;
                }
                if (Sub) {
                    edt1.setText((int)input1+"-"+(int)input2);
                    double rsub=input1-input2;

                    edt2.setText((int)rsub+"");
                    Sub = false;
                }
                if (Mul) {
                    edt1.setText((int)input1+"*"+(int)input2);
                    double rmul=input1*input2;
                    edt2.setText((int)rmul+"");
                    Mul = false;
                }
                if (Div) {
                    edt1.setText((int)input1+"/"+(int)input2);
                    double rdiv=input1/input2;
                    edt2.setText(rdiv+"");
                    Div = false;
                }
                if (Rem) {
                    edt1.setText((int)input1+"%"+(int)input2);
                    double rrem=input1%input2;
                    edt2.setText((int)rrem+"");
                    Rem = false;
                }
                if(cos){
                    edt1.setText("cos("+(int)input1+")");
                    double ceql=Math.cos(Math.toRadians(input1));
                    edt2.setText(ceql+"");
                    cos = false;
                }
                if(sin){
                    edt1.setText("sin("+(int)input1+")");
                    double seql=Math.sin(Math.toRadians(input1));
                    edt2.setText(seql+"");
                    sin = false;
                }
                if(tan){
                    edt1.setText("tan("+(int)input1+")");
                    double teql=Math.tan(Math.toRadians(input1));
                    edt2.setText(teql+"");
                    tan = false;
                }
                if(sqrt){
                    edt1.setText("sqrt("+(int)input1+")");
                    double sqrteql=Math.sqrt(input1);
                    edt2.setText(sqrteql+"");
                    sqrt = false;
                }
                if(sq){
                    edt1.setText((int)input1+"^2");

                    double sqeql=input1 * input1;
                    edt2.setText(sqeql+"");
                    log = false;
                }
                if(pow){
                    edt1.setText((int)input1+"^"+(int)input2);
                    double peql=Math.pow(input1,input2);
                    edt2.setText(peql+"");
                    pow = false;
                }
                if(log){
                    edt1.setText("log("+(int)input1+")");
                    double lgeql=Math.log10(input1);
                    edt2.setText(lgeql+"");
                    log = false;
                }
                if(exp){
                    edt1.setText("e^"+(int)input1);
                    double expeql=Math.exp(input1);
                    edt2.setText(expeql+"");
                    exp = false;
                }
            }
        });
    }
}
```
# Graphical primitives
# MainActivity.java
``` 
package com.example.shapes; 
import android.app.Activity; 
import android.graphics.Bitmap; 
import android.graphics.Canvas; 
import android.graphics.Color; 
import android.graphics.Paint; 
import android.graphics.drawable.BitmapDrawable; 
import android.os.Bundle; 
import android.widget.ImageView; 
public class MainActivity extends Activity 
{ 
@Override 
public void onCreate(Bundle savedInstanceState) 
{ 
super.onCreate(savedInstanceState); 
setContentView(R.layout.activity_main); 
//Creating a Bitmap 
Bitmap bg = Bitmap.createBitmap(720, 1280, Bitmap.Config.ARGB_8888); 
//Setting the Bitmap as background for the ImageView 
ImageView i = (ImageView) findViewById(R.id.imageView); 
i.setBackgroundDrawable(new BitmapDrawable(bg)); 
//Creating the Canvas Object 
Canvas canvas = new Canvas(bg); 
//Creating the Paint Object and set its color & TextSize 
Paint paint = new Paint(); 
paint.setColor(Color.BLUE);
paint.setTextSize(50); 
//To draw a Rectangle 
canvas.drawText("Rectangle", 420, 150, paint); 
canvas.drawRect(400, 200, 650, 700, paint); 
//To draw a Circle 
canvas.drawText("Circle", 120, 150, paint); 
canvas.drawCircle(200, 350, 150, paint); 
//To draw a Square 
canvas.drawText("Ellipse", 250, 800, paint); 
canvas.drawOval(50, 850, 650, 1150, paint); 
} 
} 

```
# activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?> 
<RelativeLayout 
xmlns:android="http://schemas.android.com/apk/res/android" android:layout_width="match_parent" 
android:layout_height="match_parent"> 
<ImageView 
android:id="@+id/imageView" 
android:layout_width="match_parent" 
android:layout_height="match_parent" /> 
</RelativeLayout>


```

# Android fragment
# activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Students Details using Fragment"
        android:layout_marginLeft="50dp"
        android:layout_marginTop="20dp"
        android:textSize="20dp"
        android:textStyle="bold"
        android:textColor="@color/white"/>
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_marginTop="30dp">
        <fragment
            android:id="@+id/fragment1"
            android:name="com.example.appdev.fragment_student_basic_details"
            android:layout_width="0px"

            android:layout_height="match_parent"
            android:layout_weight="1" />
        <fragment
            android:id="@+id/fragment2"
            android:name="com.example.appdev.fragment_student_mark"
            android:layout_width="0px"
            android:layout_height="match_parent"
            android:layout_weight="1" />
    </LinearLayout>
</LinearLayout>

```
# fragment_student_basic_details.xml
```
<?xml version="1.0" encoding="utf-8"?>
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".fragment_student_basic_details">

    <!-- TODO: Update blank fragment layout -->
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="20dp"
        android:text="Basic Details"
        android:textColor="@color/purple_200"
        android:textSize="15dp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="90dp"
        android:text="Name : Gokul" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="150dp"
        android:text="Roll No : 190701049" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="210dp"
        android:text="Age : 20" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Address : Chennai"
        android:layout_marginTop="270dp"
        android:layout_marginLeft="20dp"/>

</FrameLayout>
```
# Fragment_student_mark.xml
```
<?xml version="1.0" encoding="utf-8"?>
<FrameLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".fragment_student_mark">

    <!-- TODO: Update blank fragment layout -->
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="20dp"
        android:text="Mark Details"
        android:textColor="@color/purple_200"
        android:textSize="15dp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="90dp"
        android:text="Mark 1 : 100" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="150dp"
        android:text="Mark 2 : 99" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="210dp"
        android:text="Mark 3 : 98" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="270dp"
        android:text="Total : 297" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Grade : S"
        android:layout_marginTop="330dp"
        android:layout_marginLeft="20dp"/>
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Status : Pass"
        android:layout_marginTop="400dp"
        android:layout_marginLeft="20dp"/>

</FrameLayout>
```
# MainActivity.java\
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}
```

# StudentBasicDetailsActivity.java
```
package com.example.appdev;

import android.os.Bundle;

import androidx.fragment.app.Fragment;

import android.view.LayoutInflater;
import android.view.View;
import android.view.ViewGroup;

/**
 * A simple {@link Fragment} subclass.
 * Use the {@link fragment_student_basic_details#newInstance} factory method to
 * create an instance of this fragment.
 */
public class fragment_student_basic_details extends Fragment {

    // TODO: Rename parameter arguments, choose names that match
    // the fragment initialization parameters, e.g. ARG_ITEM_NUMBER
    private static final String ARG_PARAM1 = "param1";
    private static final String ARG_PARAM2 = "param2";

    // TODO: Rename and change types of parameters
    private String mParam1;
    private String mParam2;

    public fragment_student_basic_details() {
        // Required empty public constructor
    }

    /**
     * Use this factory method to create a new instance of
     * this fragment using the provided parameters.
     *
     * @param param1 Parameter 1.
     * @param param2 Parameter 2.
     * @return A new instance of fragment fragment_student_basic_details.
     */
    // TODO: Rename and change types and number of parameters
    public static fragment_student_basic_details newInstance(String param1, String param2) {
        fragment_student_basic_details fragment = new fragment_student_basic_details();
        Bundle args = new Bundle();
        args.putString(ARG_PARAM1, param1);
        args.putString(ARG_PARAM2, param2);
        fragment.setArguments(args);
        return fragment;
    }

    @Override
    public void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        if (getArguments() != null) {
            mParam1 = getArguments().getString(ARG_PARAM1);
            mParam2 = getArguments().getString(ARG_PARAM2);
        }
    }

    @Override
    public View onCreateView(LayoutInflater inflater, ViewGroup container,
                             Bundle savedInstanceState) {
        // Inflate the layout for this fragment
        return inflater.inflate(R.layout.fragment_student_basic_details, container, false);
    }
}
```
# Validate the entered username and ID field
# MainActivity.java
``` 
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    EditText editUName, editIDNo;
    Button btnValidate;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        editUName=(EditText)findViewById(R.id.editUName);
        editIDNo=(EditText)findViewById(R.id.editIDNo);
        btnValidate=(Button)findViewById(R.id.btnValidate);
        btnValidate.setOnClickListener(new View.OnClickListener(){
            @Override
            public void onClick(View view) {
                if(editUName.getText().toString().matches("[a-zA-Z ]+") &&
                        (editIDNo.getText().toString().matches("[\\d]+")&&

                                editIDNo.getText().toString().trim().length()==4))
                    Toast.makeText(getApplicationContext(), "Validation Successful",
                            Toast.LENGTH_LONG).show();
                if(editUName.getText().toString().trim().length()==0 ||

                        editIDNo.getText().toString().trim().length()==0)
                    Toast.makeText(getApplicationContext(),"Please enter allvalues",
                            Toast.LENGTH_LONG).show();

                if(!(editUName.getText().toString().trim().matches("[a-zA-Z ]+")))
                    Toast.makeText(getApplicationContext(),"Please enter only alphabets",Toast.LENGTH_LONG).show();

                if(!(editIDNo.getText().toString().trim().matches("[\\d ]+")) ||
                        editIDNo.getText().toString().trim().length()!=4)
                    Toast.makeText(getApplicationContext(),"Please enter only four digit number",
                            Toast.LENGTH_LONG).show();

            }
        });
    }
}
```
# ActivityMain.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_x="30dp"
        android:layout_y="60dp"
        android:text="User Name"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/editUName"
        app:layout_constraintHorizontal_bias="0.522"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.182" />

    <EditText
        android:id="@+id/editUName"
        android:layout_width="150dp"
        android:layout_height="48dp"
        android:layout_x="150dp"
        android:layout_y="50dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.693"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.176"
        tools:ignore="SpeakableTextPresentCheck" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="49dp"
        android:layout_height="17dp"
        android:layout_x="30dp"

        android:layout_y="120dp"
        android:text="ID NO"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toStartOf="@+id/editIDNo"
        app:layout_constraintHorizontal_bias="0.439"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2"
        app:layout_constraintVertical_bias="0.207" />

    <EditText
        android:id="@+id/editIDNo"
        android:layout_width="150dp"
        android:layout_height="48dp"
        android:layout_marginTop="96dp"
        android:layout_x="150dp"
        android:layout_y="110dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.693"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editUName"
        app:layout_constraintVertical_bias="0.0"
        tools:ignore="SpeakableTextPresentCheck" />

    <Button
        android:id="@+id/btnValidate"
        android:layout_width="150dp"
        android:layout_height="48dp"
        android:layout_marginBottom="276dp"
        android:layout_x="30dp"
        android:layout_y="250dp"
        android:text="Validate"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.49"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/editIDNo"
        app:layout_constraintVertical_bias="1.0" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
# Latitude, Longitude
# MainActivity.java
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;
import androidx.core.content.ContextCompat;
import androidx.core.app.ActivityCompat;

import android.content.Context;
import android.location.Address;
import android.location.Geocoder;
import android.os.Bundle;

import android.content.pm.PackageManager;
import android.location.Location;
import android.location.LocationListener;
import android.location.LocationManager;
import android.util.Log;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;
import android.widget.Toast;

import java.util.List;
import java.util.Locale;

public class MainActivity extends AppCompatActivity implements LocationListener {
    TextView t1, t2;
    Button b1;
    LocationManager LM;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        t1 = (TextView)findViewById(R.id.t1);
        t2 = (TextView)findViewById(R.id.t2);
        b1 = (Button)findViewById(R.id.b1);

        if (ContextCompat.checkSelfPermission(getApplicationContext(),
                android.Manifest.permission.ACCESS_FINE_LOCATION) !=
                PackageManager.PERMISSION_GRANTED &&
                ActivityCompat.checkSelfPermission(getApplicationContext(),
                android.Manifest.permission.ACCESS_COARSE_LOCATION) != PackageManager.PERMISSION_GRANTED)
        {
            ActivityCompat.requestPermissions(this, new
                    String[]{android.Manifest.permission.ACCESS_FINE_LOCATION,
                    android.Manifest.permission.ACCESS_COARSE_LOCATION}, 101);
        }
        b1.setOnClickListener(new View.OnClickListener(){
            public void onClick(View v){
                Log.d("MainActivity", "Button Works");
                getLocation();
            }
        });
    }

    void getLocation() {
        try {
            LM = (LocationManager)
                    getSystemService(Context.LOCATION_SERVICE);
            LM.requestLocationUpdates(LocationManager.NETWORK_PROVIDER, 5000,5, this);
        }
        catch(SecurityException e) {
            e.printStackTrace();
        }
    }

    @Override
    public void onLocationChanged(Location location) {
        t1.setText("Latitude: " + location.getLatitude() + "\nLongitude: " + location.getLongitude());
        try {
            Geocoder geocoder = new Geocoder(this, Locale.getDefault());
            List<Address> addresses = geocoder.getFromLocation(location.getLatitude(),
                    location.getLongitude(), 1);
            t2.setText(addresses.get(0).getAddressLine(0)+","+ addresses.get(0).getAddressLine(1)+","+addresses.get(0).getAddressLine(2));
        }
        catch(Exception e)
        {

        }
    }

    @Override
    public void onProviderDisabled(String provider) {
        Toast.makeText(MainActivity.this, "Please Enable GPS and Internet", Toast.LENGTH_SHORT).show();
    }

    @Override
    public void onStatusChanged(String provider, int status, Bundle extras) {

    }

    @Override
    public void onProviderEnabled(String provider) {

    }
}
```
# Activity_main.xml
```
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="GPS Location"
        android:textColor="#9C27B0"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.085" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="16dp"
        android:layout_marginTop="188dp"
        android:text="Longitude and Latitude"
        android:textSize="16sp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="16dp"
        android:layout_marginTop="164dp"
        android:text="GPS Location Address"
        android:textSize="16sp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2" />

    <TextView
        android:id="@+id/t1"
        android:layout_width="308dp"
        android:layout_height="108dp"
        android:layout_marginTop="12dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.495"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2" />

    <TextView
        android:id="@+id/t2"
        android:layout_width="308dp"
        android:layout_height="108dp"
        app:layout_constraintBottom_toTopOf="@+id/b1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.495"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView3"
        app:layout_constraintVertical_bias="0.393" />

    <Button
        android:id="@+id/b1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="140dp"
        android:text="GET LOCATION"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```
# SD card
# MainActivity.java
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.Toast;
import java.io.FileInputStream;
import java.io.FileOutputStream;

public class MainActivity extends AppCompatActivity {

    EditText e1;
    Button b1,b2,b3;
    String data;
    String filename = "mydata.txt";

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        e1 = (EditText) findViewById(R.id.E1);
        b1 = (Button) findViewById(R.id.B1);
        b2 = (Button) findViewById(R.id.B2);
        b3 = (Button) findViewById(R.id.B3);
        e1.setHint("Enter Some Text Here");

        b1.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                writeData();
            }
        });
        b2.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                readData();
            }
        });
        b3.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                e1.setText("");
            }
        });
    }

    public void writeData() {
        data = e1.getText().toString();
        try {
            FileOutputStream fos = openFileOutput(filename, MODE_PRIVATE);
            fos.write(data.getBytes());
            fos.close();
            Toast.makeText(getApplicationContext(), "File Saved: " + filename, Toast.LENGTH_LONG).show();
        } catch (Exception e) {
            Toast.makeText(getApplicationContext(), e.getMessage(), Toast.LENGTH_LONG).show();
        }
    }

    public void readData() {
        int c;
        String temp = "";
        try {
            FileInputStream fis = openFileInput(filename);
            while ((c = fis.read()) != -1) {
                temp = temp + Character.toString((char) c);
            }
            e1.setText(temp);
            Toast.makeText(getApplicationContext(), "File Read: " + filename, Toast.LENGTH_LONG).show();
        } catch (Exception e) {
            Toast.makeText(getApplicationContext(), e.getMessage(), Toast.LENGTH_LONG).show();
        }
    }

}
```
# Activity_main.xml

```
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:text="Read and Write Data in SD Card"
        android:textSize="40px"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.022" />

    <EditText
        android:id="@+id/E1"
        android:layout_width="match_parent"
        android:layout_height="200dp"
        android:layout_marginTop="8dp"
        android:layout_marginBottom="22dp"
        app:layout_constraintBottom_toTopOf="@+id/B1"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView"
        tools:ignore="SpeakableTextPresentCheck" />

    <Button
        android:id="@+id/B1"
        android:layout_width="75dp"
        android:layout_height="wrap_content"

        android:layout_marginTop="264dp"
        android:text="Save"
        app:layout_constraintEnd_toStartOf="@+id/B2"
        app:layout_constraintHorizontal_bias="0.172"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button

        android:id="@+id/B2"
        android:layout_width="75dp"
        android:layout_height="wrap_content"
        android:text="Read"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.389" />

    <Button
        android:id="@+id/B3"
        android:layout_width="86dp"
        android:layout_height="53dp"
        android:layout_marginTop="264dp"
        android:text="Clear"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.804"
        app:layout_constraintStart_toEndOf="@+id/B2"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
# SMS
# MainActivity.java
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.app.AlertDialog;
import android.content.Intent;
import android.widget.Button;
import android.widget.EditText;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {
    Button notify;
    EditText sms;
    AlertDialog.Builder builder;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        notify= findViewById(R.id.button);
        sms= findViewById(R.id.editText);
        builder = new AlertDialog.Builder(this);

        notify.setOnClickListener(v -> {
            final String message = sms.getText().toString();
            if(!message.equals("")) {
                builder.setMessage(message).setTitle("New Message");
                builder.setMessage(message)
                        .setCancelable(false)
                        .setPositiveButton("OK", (dialog, id) -> {
                            Intent smsIntent = new Intent(MainActivity.this, SmsAlert.class);
                            smsIntent.putExtra("sms", message);
                            startActivity(smsIntent);
                            finish();
                        });
                AlertDialog alert = builder.create();
                alert.setTitle("New Message");
                alert.show();
            }

            else{
                Toast.makeText(getApplicationContext(),
                        "Type Message in Message Box",Toast.LENGTH_LONG).show();
            }
        });
    }

}

```
# Activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerHorizontal="true"
        android:text="Alert Box"
        android:textSize="30sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.498"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.108" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="92dp"
        android:text=" Type Message"
        android:textSize="20sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.101"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView" />

    <EditText
        android:id="@+id/editText"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="64dp"
        android:singleLine="true"
        android:textSize="20sp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView2"
        tools:ignore="SpeakableTextPresentCheck" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="164dp"
        android:text="Alert"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

```
# SmsAlert.java
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.TextView;

public class SmsAlert extends AppCompatActivity {

    TextView showmsg;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_sms_alert);

        showmsg = findViewById(R.id.showmsg);
        Bundle extras = getIntent().getExtras();
        showmsg.setText(extras.getString("sms"));
    }
}

```
# Activity_sms_alert.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/showmsg"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.158"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.223" />

</androidx.constraintlayout.widget.ConstraintLayout>

```
# Alarm Manager
# MainActivity.java
```
package com.example.appdev;

import androidx.appcompat.app.AppCompatActivity;

import android.app.Activity;
import android.app.AlarmManager;
import android.app.PendingIntent;
import android.content.Intent;
import android.os.Bundle;
import android.widget.Button;
import android.widget.TimePicker;
import android.widget.Toast;

import java.util.Calendar;

public class MainActivity extends AppCompatActivity {
    TimePicker alarmTimePicker;
    PendingIntent pendingIntent;
    AlarmManager alarmManager;
    Button btnSet, btnStop;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        alarmTimePicker = findViewById(R.id.timePicker);
        btnSet = findViewById(R.id.btnSet);
        btnStop = findViewById(R.id.btnStop);
        alarmManager = (AlarmManager) getSystemService(ALARM_SERVICE);

        btnSet.setOnClickListener(view -> {
            long time;
            Toast.makeText(MainActivity.this, "ALARM ON", Toast.LENGTH_SHORT).show();
            Calendar calendar = Calendar.getInstance();
            calendar.set(Calendar.HOUR_OF_DAY, alarmTimePicker.getCurrentHour());
            calendar.set(Calendar.MINUTE, alarmTimePicker.getCurrentMinute());
            time=(calendar.getTimeInMillis()-(calendar.getTimeInMillis()%60000));
            AlarmManager am = (AlarmManager) getSystemService(Activity.ALARM_SERVICE);

            Intent intent = new Intent(MainActivity.this, AlarmReceiver.class);
            pendingIntent = PendingIntent.getBroadcast(MainActivity.this, 1, intent, 0);

            alarmManager.set(AlarmManager.RTC_WAKEUP, time, pendingIntent);
        });

        btnStop.setOnClickListener(view -> {
            alarmManager.cancel(pendingIntent);
            Toast.makeText(MainActivity.this, "ALARM OFF", Toast.LENGTH_SHORT).show();
        });

    }
}

```
# AlarmReceiver.java
```
package com.example.appdev;

import android.content.BroadcastReceiver;
import android.content.Context;
import android.content.Intent;
import android.media.Ringtone;
import android.media.RingtoneManager;
import android.net.Uri;
import android.widget.Toast;

public class AlarmReceiver extends BroadcastReceiver {


    @Override
    public void onReceive(Context context, Intent intent) {
        Toast.makeText(context, "Alarm! Wake up! Wake up!", Toast.LENGTH_LONG).show();
        Uri alarmUri = RingtoneManager.getDefaultUri(RingtoneManager.TYPE_ALARM);
        if (alarmUri == null) {
            alarmUri = RingtoneManager.getDefaultUri(RingtoneManager.TYPE_NOTIFICATION);
        }
        Ringtone ringtone = RingtoneManager.getRingtone(context, alarmUri);
        ringtone.play();
    }
}

```
# Activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TimePicker
        android:id="@+id/timePicker"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/btnSet"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_gravity="center"
        android:layout_marginStart="40dp"
        android:text="Set Alarm"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/timePicker"
        app:layout_constraintVertical_bias="0.428" />

    <Button
        android:id="@+id/btnStop"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"

        android:layout_gravity="center"
        android:layout_marginEnd="40dp"
        android:text="Stop Alarm"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/timePicker"
        app:layout_constraintVertical_bias="0.428" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
