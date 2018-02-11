# Font resource compat example code :)

```xml
[productsans.xml]
<?xml version="1.0" encoding="utf-8"?>
<font-family xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    tools:ignore="UnusedAttribute">

    <font
        android:font="@font/productsans_regular"
        android:fontStyle="normal"
        android:fontWeight="400"
        app:font="@font/productsans_regular"
        app:fontStyle="normal"
        app:fontWeight="400" />

    <font
        android:font="@font/productsans_bold"
        android:fontStyle="normal"
        android:fontWeight="700"
        app:font="@font/productsans_bold"
        app:fontStyle="normal"
        app:fontWeight="700" />

</font-family>
```

## Usage
```xml
[ activity_main.xml ]
...
<TextView
  android:id="@+id/tv_productsans_regular"
  android:layout_width="wrap_content"
  android:layout_height="wrap_content"
  android:layout_marginBottom="8dp"
  android:fontFamily="@font/productsans"
  android:text="Hello World! Regular"
  android:textStyle="normal" />

<TextView
  android:id="@+id/tv_productans_bold"
  android:layout_width="wrap_content"
  android:layout_height="wrap_content"
  android:layout_marginBottom="8dp"
  android:fontFamily="@font/productsans"
  android:text="Hello World! Bold"
  android:textSize="20sp"
  android:textStyle="bold" />
...
```

### Developed By Thai android developer.


<img src="./picture/profile2_circle.png" width="170">  ![alt text](./picture/thekhaeng_logo.png)


Follow [facebook.com/thekhaeng.io](https://www.facebook.com/thekhaeng.io) on Facebook page.
or [@nonthawit](https://medium.com/@nonthawit) at my Medium blog. :)

For contact, shoot me an email at nonthawit.thekhaeng@gmail.com