# wdl fork

uhhh, ummm... just wanna see if i can get swell-based stuff like [reaper](https://www.reaper.fm/) to work natively on wayland

## cool!!!

back up libSwell.so!
```
sudo cp /usr/lib/REAPER/libSwell.so /usr/lib/REAPER/libSwell.so.bak
```

go to the swell library
```
cd WDL/swell
```

make changes wherever and run these three commands to see if you get it working lol
```bash
make
sudo cp libSwell.so /usr/lib/REAPER/libSwell.so
reaper
```


## issues

i haven't been able to run reaper with my configuration (i've got some themes and stuff i guess).
so i just made a bogus config folder `mkdir reaperblah` and started launching the program with `reaper -cfgfile reaperblah` :)