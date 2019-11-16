# ExNotifyBalloon
Windows 10 style notifications for Windows Forms. 

![](https://i.imgur.com/A5ia7yw.png)

## For what if exists NotifyIcon? 
- Because notification timeout in fact cannot be changed
- Because notification style  in windows 7 look like shi~
- Because I can't change notification font/color/etc

## Usage example
<pre>var notification = new ExNotifyBalloon(Resources.info, "Title", "Body", 5000);
notification.Show();</pre>
