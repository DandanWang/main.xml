main.xml
========
<?xml version="1.0" encoding="utf-8"?>

<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent"
    android:paddingLeft="16dp"
    android:paddingRight="16dp"
    android:orientation="vertical"
    >  
<TextView
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:text="@string/To"
    />
 
    <EditText 
  	  android:layout_width="fill_parent"
      android:layout_height="wrap_content"
      android:id="@+id/To"
     /> 
  	 <TextView
  	  android:layout_width="fill_parent"
      android:layout_height="wrap_content"
      android:text="@string/edit_message"
  	     />
    
  	<EditText 
      android:layout_width="fill_parent"
  	  android:layout_height="wrap_content"
  	  android:minLines="3"
  	  android:layout_gravity="bottom"
  	  android:id="@+id/edit_message"
  	   />
     
    <Button
       android:layout_width="100dp"
       android:layout_height="wrap_content"
       android:layout_gravity="right"
       android:text="@string/button_send"
       android:onClick="sendMessage"
       />
     </LinearLayout>   
  

    
       
