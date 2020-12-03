<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#dfe"
    android:orientation="vertical"
    android:gravity="center"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="50dp"
        android:textSize="18sp"/>

    <Button
        android:id="@+id/button_start"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:layout_margin="10dp"
        android:text="@string/start" />

    <Button
        android:id="@+id/button_cancel"
        android:layout_width="200dp"
        android:layout_height="wrap_content"
        android:layout_margin="10dp"
        android:text="@string/cancel" />

</LinearLayout>
