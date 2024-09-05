package com.example.helloworld;

import android.app.Activity;
import android.os.Bundle;
import android.widget.TextView;

public class MainActivity extends Activity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);

        // Create a TextView object
        TextView textView = new TextView(this);
        textView.setText("Hello, World!");
        textView.setTextSize(24);

        // Set the TextView as the activity layout
        setContentView(textView);
    }
}
