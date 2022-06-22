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
