## Android布局实验
### 利用线性布局实现如下界面：

![enter description here][1]

代码如下：
linearlayout.xml
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="#000000">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textViewOneOne"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="5px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="One,One" />

            <TextView
                android:id="@+id/textViewOneTwo"
                android:layout_width="30dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="One,Two" />

            <TextView
                android:id="@+id/textViewOneThree"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="One,Three" />

            <TextView
                android:id="@+id/textViewOneFour"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="One,Four" />
        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textViewTwoOne"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="5px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Two,One" />

            <TextView
                android:id="@+id/textViewTwoTwo"
                android:layout_width="30dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Two,Two" />

            <TextView
                android:id="@+id/textViewTwoThree"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Two,Three" />

            <TextView
                android:id="@+id/textViewTwoFour"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Two,Four" />
        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textViewThreeOne"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="5px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Three,One" />

            <TextView
                android:id="@+id/textViewThreeTwo"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Three,Two" />

            <TextView
                android:id="@+id/textViewThreeThree"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Three,Three" />

            <TextView
                android:id="@+id/textViewThreeFour"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Three,Four" />
        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textViewFourOne"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="5px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Four,One" />

            <TextView
                android:id="@+id/textViewFourTwo"
                android:layout_width="30dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Four,Two" />

            <TextView
                android:id="@+id/textViewFourThree"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Four,Three" />

            <TextView
                android:id="@+id/textViewFourFour"
                android:layout_width="1dp"
                android:layout_height="40dp"
                android:layout_weight="1"
                android:layout_marginBottom="5px"
                android:layout_marginLeft="10px"
                android:background="@drawable/textview_border"
                android:gravity="center"
                android:textColor="#FFFFFF"
                android:text="Four,Four" />
        </LinearLayout>
    </LinearLayout>
</LinearLayout>

```

## 结果截图
![enter description here][2]

### 利用相对布局实现如下界面：

![enter description here][3]

relativelayout.xml
```
 <?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#000000">

    <TextView
        android:id="@+id/red"
        android:layout_width="50dp"
        android:layout_height="50dp"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:background="#FF0000"
        android:textColor="#000000"
        android:gravity="center"
        android:text="Red" />

    <TextView
        android:id="@+id/orange"
        android:layout_width="80dp"
        android:layout_height="50dp"
        android:layout_alignParentTop="true"
        android:layout_marginEnd="68dp"
        android:layout_marginRight="68dp"
        android:layout_toLeftOf="@+id/yellow"
        android:layout_toStartOf="@+id/yellow"
        android:background="#FFA600"
        android:gravity="center"
        android:text="Orange"
        android:textColor="#000000" />

    <TextView
        android:id="@+id/yellow"
        android:layout_width="80dp"
        android:layout_height="50dp"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentTop="true"
        android:background="#FFFF00"
        android:textColor="#000000"
        android:gravity="center"
        android:text="Yellow" />

    <TextView
        android:id="@+id/violet"
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:layout_below="@+id/red"
        android:layout_marginTop="88dp"
        android:layout_marginLeft="5dp"
        android:layout_marginRight="5dp"
        android:background="#EF82EF"
        android:gravity="center"
        android:text="Violet"
        android:textColor="#000000" />

    <TextView
        android:id="@+id/green"
        android:layout_width="60dp"
        android:layout_height="50dp"
        android:layout_below="@+id/orange"
        android:layout_marginTop="23dp"
        android:layout_toLeftOf="@+id/orange"
        android:layout_toStartOf="@+id/orange"
        android:background="#00FF00"
        android:gravity="center"
        android:text="Green"
        android:textColor="#000000" />

    <TextView
        android:id="@+id/blue"
        android:layout_width="55dp"
        android:layout_height="50dp"
        android:layout_alignTop="@+id/green"
        android:layout_marginLeft="15dp"
        android:layout_marginStart="15dp"
        android:layout_toEndOf="@+id/green"
        android:layout_toRightOf="@+id/green"
        android:background="#0000FF"
        android:gravity="center"
        android:textColor="#000000"
        android:text="Blue" />

    <TextView
        android:id="@+id/textView16"
        android:layout_width="60dp"
        android:layout_height="50dp"
        android:layout_alignBottom="@+id/blue"
        android:layout_alignTop="@+id/blue"
        android:layout_toLeftOf="@+id/yellow"
        android:layout_toStartOf="@+id/yellow"
        android:background="#4A0084"
        android:gravity="center"
        android:text="TextView"
        android:textColor="#000000" />
</RelativeLayout>

```
## 结果截图
![enter description here][4]

###利用表格布局实现如下界面：

![enter description here][5]

tablelayout.xml
```
<?xml version="1.0" encoding="utf-8"?>
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#242424">

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/textView20"
            android:layout_width="5dp"
            android:layout_height="match_parent" />

        <TextView
            android:id="@+id/open"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:text="Open..."
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/ctrlo"
            android:layout_width="272dp"
            android:layout_height="match_parent"
            android:gravity="right"
            android:text="Ctrl+O"
            android:textColor="#727572"
            android:textStyle="bold" />
    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/textView21"
            android:layout_width="20dp"
            android:layout_height="wrap_content" />

        <TextView
            android:id="@+id/save"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:text="save..."
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/ctrls"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:gravity="right"
            android:text="Ctrl+S"
            android:textColor="#727572"
            android:textStyle="bold" />

    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/textView22"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content" />

        <TextView
            android:id="@+id/saveas"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:text="Save As..."
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/ctrlss"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:gravity="right"
            android:text="Ctrl+Shift+S"
            android:textColor="#727572"
            android:textStyle="bold" />
    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#888788">

        <TextView
            android:id="@+id/textView26"
            android:layout_width="wrap_content"
            android:layout_height="2dp" />
    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/x"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="X"
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/Import"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Import..."
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/textView24"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content" />

    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/x_x"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="X"
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/export"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Export..."
            android:textColor="#727572"
            android:textStyle="bold" />

        <TextView
            android:id="@+id/ctrle"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:gravity="right"
            android:text="Ctrl+E"
            android:textColor="#727572"
            android:textStyle="bold" />

    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:background="#888788">

        <TextView
            android:id="@+id/te"
            android:layout_width="wrap_content"
            android:layout_height="2dp" />
    </TableRow>

    <TableRow
        android:layout_width="match_parent"
        android:layout_height="match_parent">

        <TextView
            android:id="@+id/textView27"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content" />

        <TextView
            android:id="@+id/quit"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Quit"
            android:textColor="#727572"
            android:textStyle="bold" />
    </TableRow>

</TableLayout>

```
## 结果截图
![enter description here][6]

### 4.总结
很少做android,不太会

  [1]: ./1.png "1"
  [2]: ./2.png "2"
  [3]: ./3.png "3"
  [4]: ./4.png "4"
  [5]: ./5.png "5"
  [6]: ./6.png "6"