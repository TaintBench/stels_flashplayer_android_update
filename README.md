# Installation:
![ICON](icon.png)
# General Information:
- **fileName**: stels_flashplayer_android_update.apk
- **packageName**: android.systempack.ins
- **targetSdk**: 15
- **minSdk**: 4
- **maxSdk**: undefined
- **mainActivity**: app.opera.MainActivity
# Behavior Information:
## BroadcastReceivers:
- MainReceiver monitors incoming SMS messages. 
## Services:
- MainService performs C&C commands and collected data such as SMS messages and contact information to a remote server. 
# Detail Information:
## Activities: 1
	app.opera.MainActivity
## Services: 1
	ru.stels2.MainService
## Receivers: 1
	ru.stels2.MainReceiver
## Permissions: 12
	android.permission.SEND_SMS
	android.permission.RECEIVE_SMS
	android.permission.READ_CONTACTS
	android.permission.CALL_PHONE
	android.permission.INTERNET
	android.permission.CALL_PRIVILEGED
	android.permission.ACCESS_NETWORK_STATE
	android.permission.INSTALL_PACKAGES
	android.permission.RECEIVE_BOOT_COMPLETED
	android.permission.READ_PHONE_STATE
	android.permission.WRITE_EXTERNAL_STORAGE
	android.permission.DELETE_PACKAGES
## Sources: 37
	<android.telephony.SmsManager: android.telephony.SmsManager getDefault()>: 2
	<org.json.JSONObject: int getInt(java.lang.String)>: 4
	<java.io.BufferedReader: java.lang.String readLine()>: 2
	<java.lang.String: byte[] getBytes(java.lang.String)>: 3
	<android.content.ContentResolver: android.database.Cursor query(android.net.Uri,java.lang.String[],java.lang.String,java.lang.String[],java.lang.String)>: 1
	<org.json.JSONArray: java.lang.String getString(int)>: 1
	<android.net.Uri: android.net.Uri parse(java.lang.String)>: 5
	<org.json.JSONObject: org.json.JSONObject getJSONObject(java.lang.String)>: 2
	<android.telephony.SmsMessage: java.lang.String getOriginatingAddress()>: 1
	<android.app.PendingIntent: android.app.PendingIntent getBroadcast(android.content.Context,int,android.content.Intent,int)>: 2
	<java.net.HttpURLConnection: int getResponseCode()>: 6
	<android.os.Environment: java.io.File getExternalStorageDirectory()>: 1
	<android.content.Intent: java.lang.String getAction()>: 1
	<android.telephony.TelephonyManager: java.lang.String getDeviceId()>: 2
	<android.telephony.SmsMessage: java.lang.String getMessageBody()>: 1
	<java.lang.reflect.Field: java.lang.Object get(java.lang.Object)>: 4
	<android.telephony.SmsMessage: android.telephony.SmsMessage createFromPdu(byte[])>: 1
	<android.webkit.WebView: void loadUrl(java.lang.String)>: 1
	<android.net.ConnectivityManager: android.net.NetworkInfo getNetworkInfo(int)>: 2
	<org.json.JSONObject: java.lang.String getString(java.lang.String)>: 30
	<java.lang.Class: java.lang.String getCanonicalName()>: 3
	<org.json.JSONObject: boolean getBoolean(java.lang.String)>: 5
	<java.lang.Class: java.io.InputStream getResourceAsStream(java.lang.String)>: 2
	<java.lang.String: byte[] getBytes()>: 1
	<java.lang.Class: java.lang.Class[] getClasses()>: 3
	<java.lang.Class: java.lang.reflect.Field getField(java.lang.String)>: 4
	<android.telephony.TelephonyManager: java.lang.String getLine1Number()>: 2
	<java.lang.Long: long parseLong(java.lang.String)>: 1
	<android.app.PendingIntent: android.app.PendingIntent getActivity(android.content.Context,int,android.content.Intent,int)>: 1
	<java.util.Vector: java.lang.Object get(int)>: 5
	<android.content.Intent: android.os.Bundle getExtras()>: 4
	<android.os.Bundle: java.lang.Object get(java.lang.String)>: 6
	<java.lang.Integer: int parseInt(java.lang.String)>: 2
	<android.telephony.TelephonyManager: java.lang.String getSubscriberId()>: 2
	<android.webkit.WebView: android.webkit.WebSettings getSettings()>: 1
	<org.json.JSONObject: org.json.JSONArray getJSONArray(java.lang.String)>: 6
	<org.json.JSONArray: org.json.JSONObject getJSONObject(int)>: 7
## Sinks: 26
	<org.json.JSONObject: org.json.JSONObject put(java.lang.String,int)>: 2
	<android.content.Intent: android.content.Intent setData(android.net.Uri)>: 1
	<java.lang.String: boolean startsWith(java.lang.String)>: 4
	<android.app.NotificationManager: void notify(int,android.app.Notification)>: 1
	<java.lang.StringBuffer: void setLength(int)>: 1
	<android.telephony.SmsManager: void sendTextMessage(java.lang.String,java.lang.String,java.lang.String,android.app.PendingIntent,android.app.PendingIntent)>: 1
	<android.content.Intent: android.content.Intent setAction(java.lang.String)>: 2
	<android.net.Uri: android.net.Uri parse(java.lang.String)>: 5
	<java.io.FileOutputStream: void write(byte[],int,int)>: 1
	<android.webkit.WebView: void setScrollBarStyle(int)>: 1
	<android.app.AlarmManager: void setRepeating(int,long,long,android.app.PendingIntent)>: 1
	<android.content.Intent: android.content.Intent setDataAndType(android.net.Uri,java.lang.String)>: 1
	<android.app.AlarmManager: void set(int,long,android.app.PendingIntent)>: 1
	<android.app.ProgressDialog: void setMessage(java.lang.CharSequence)>: 1
	<android.app.Notification: void setLatestEventInfo(android.content.Context,java.lang.CharSequence,java.lang.CharSequence,android.app.PendingIntent)>: 1
	<android.content.Intent: android.content.Intent putExtra(java.lang.String,java.lang.String)>: 7
	<java.net.URL: java.net.URLConnection openConnection()>: 5
	<android.webkit.WebSettings: void setJavaScriptEnabled(boolean)>: 1
	<android.webkit.WebView: void setWebViewClient(android.webkit.WebViewClient)>: 1
	<org.json.JSONObject: org.json.JSONObject put(java.lang.String,java.lang.Object)>: 8
	<java.lang.Long: long parseLong(java.lang.String)>: 1
	<java.lang.Integer: int parseInt(java.lang.String)>: 2
	<android.app.Activity: void onCreate(android.os.Bundle)>: 1
	<android.app.ProgressDialog: void setProgressStyle(int)>: 1
	<android.content.Intent: android.content.Intent putExtras(android.os.Bundle)>: 2
	<java.net.HttpURLConnection: void setRequestMethod(java.lang.String)>: 3
