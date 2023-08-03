# change Default Xsession
sch: https://www.google.com/search?q=x11+user+change+default+session

Doc: https://help.gnome.org/admin/system-admin-guide/stable/session-user.html.en

## Solution:
https://unix.stackexchange.com/questions/367294/how-do-i-change-my-default-session/367706#367706

>With GDM, have you tried modifying your ~/.dmrc file? You can set gnome classic as your default session like this:
>```
>[Desktop]
>Session=gnome-classic
>```