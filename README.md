<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textviewTieude"
        android:textColor="#f20"
        android:textAppearance="f20"
        android:textSize="40sp"
        android:text="Dang nhap tai khoan"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
  <EditText
      android:hint="Nhap tai khoan"
      android:layout_margin="10dp"
      android:layout_below="@id/textviewTieude"
      android:id="@+id/edittextTaikhoan"
      android:layout_width="match_parent"
      android:layout_height="wrap_content" />
    <EditText
        android:hint="Nhap mat khau "
        android:layout_margin="10dp"
        android:layout_below="@id/edittextTaikhoan"
        android:id="@+id/edittextMatkhau"
        android:layout_width="match_parent"
        android:layout_height="wrap_content" />
    <CheckBox
        android:text="Lưu mật khẩu"
        android:layout_margin="10dp"
        android:layout_below="@id/edittextMatkhau"
        android:id="@+id/checkboxSave"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
    <Button
        android:layout_marginTop="100dp"
        android:text="Đăng nhập"
        android:layout_centerHorizontal="true"
        android:layout_below="@id/checkboxSave"
        android:id="@+id/buttonDangnhap"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
</RelativeLayout>
