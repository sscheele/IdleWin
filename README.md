# IdleWin
Locks Windows after idle time

IdleWin is a Java program that locks a Windows workstation after a certain amount of idle time. The regular Windows screensaver can be irritating to people who spend way too much time on Netflix, because it interrupts their shows. When the screensaver is disabled, however, the user is left vulnerable to Rubber Duckies or Teensies. IdleWin is a compromise; after the workstation has been idle for a certain amount of time it remains unlocked until the user types or uses the mouse. Then the workstation locks. This way, the user can watch movies uninterrupted but maintain good security practices. IdleWin uses code from this blog: http://ochafik.com/blog/?p=98 (thanks, zOlive!) and, through that code, functionalities provided by JNA. For explicit instructions on compiling this with JNA, see the linked blog post. Otherwise, simply run the JAR (or, even better, put it in your Startup folder, C:\Users\%USERNAME%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup).
