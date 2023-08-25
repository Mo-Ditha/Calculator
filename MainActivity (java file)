package com.example.calculator;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.EditText;
import android.widget.TextView;


public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    public void Add(View view){
        EditText num1 = (EditText) findViewById(R.id.txtnum1);
        EditText num2 = (EditText) findViewById(R.id.txtnum2);
        TextView display = (TextView) findViewById(R.id.txtdisplay);

        float n1 = getFloatValue(num1);
        float n2 = getFloatValue(num2);
        float result = n1 +n2;

        display.setText("SUM Value: "+result);
    }

    public void Sub(View view){
        EditText num1 = (EditText) findViewById(R.id.txtnum1);
        EditText num2 = (EditText) findViewById(R.id.txtnum2);
        TextView display = (TextView) findViewById(R.id.txtdisplay);

        float n1 = getFloatValue(num1);
        float n2 = getFloatValue(num2);
        float result = n1 - n2;

        display.setText("Sub Value: "+result);
    }

    public void Mul(View view){
        EditText num1 = (EditText) findViewById(R.id.txtnum1);
        EditText num2 = (EditText) findViewById(R.id.txtnum2);
        TextView display = (TextView) findViewById(R.id.txtdisplay);

        float n1 = getFloatValue(num1);
        float n2 = getFloatValue(num2);
        float result = n1 * n2;

        display.setText("Mul Value: "+result);
    }




    public void Div(View view){
        EditText num1 = (EditText) findViewById(R.id.txtnum1);
        EditText num2 = (EditText) findViewById(R.id.txtnum2);
        TextView display = (TextView) findViewById(R.id.txtdisplay);

        float n1 = getFloatValue(num1);
        float n2 = getFloatValue(num2);
        float result = n1 / n2;

        display.setText("Div Value: "+result);
    }


    public void clear(View view){
        EditText num1 = (EditText) findViewById(R.id.txtnum1);
        EditText num2 = (EditText) findViewById(R.id.txtnum2);
        TextView display = (TextView) findViewById(R.id.txtdisplay);

        num1.setText("");
        num2.setText("");
        display.setText("");

    }
    private float getFloatValue(EditText editText) {
        String text = editText.getText().toString();
        if (!text.isEmpty()) {
            return Float.parseFloat(text);
        } else {
            return 0.0f; // Default value if the EditText is empty
        }
    }


}
