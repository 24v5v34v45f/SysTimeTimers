# SysTimeTimers
Alternative to the timer.* library in Garry's Mod

originally created to work during server timeout (on the client) as we use SysTime not CurTime

Ensure `sv_hibernate_think` is set to `1` or the timers will not work when your server is empty!
If you don't want to, you can use `stt_ignore_hibernation_warning 1`, to diable the warning about hibernation on timer creation!
