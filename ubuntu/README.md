# KeyboardLayout
Using Ubuntu
Add it to you systems keyboard and restart your computer.
```
cp real-prog-canary >> ~/.config/xkb/real-prog-canary
```
Then you have to update the sudo vim /usr/share/X11/xkb/rules/evdev.xml with the following, add it near the other English keyboards

```
<variant>
    <configItem>
        <name>real-prog-canary</name>
        <description>English (Real Programmers Canary)</description>
        <vendor>Fate</vendor>
    </configItem>
</variant>
```
