# kindle-2i-notes
Notes about Kindle 2 international

### System info

```
# cat /etc/prettyversion.txt
Kindle 2.5.2 (~~otaVersion~~)
```

### Screensavers

Screensavers are loaded from the folders `/opt/amazon/screen_saver/`. Pictures live in subdirectories `600x800` and `824x1200`.

It appears that a picture is chosen at random every time kindle sleeps. I don't know what'd happen if some of the pictures are missing or renamed. Replacing all pictures of each size by one picture of that size results in Kindle sleeping displaying the same screen saver every time.

Inside `600x800` are the following files:
```
00_42-20711832_600.gif
01_kindle_def_600.gif
02_IH045799_600.gif
03_HU013742_600.gif
04_BE041723_600.gif
05_BE088162_600.gif
06_HU061820_600.gif
07_SF125_600.gif
08_BE061039_600.gif
09_AABR001007_600.gif
10_F10017_600.gif
11_IH179062_600.gif
12_BE002022_600.gif
13_42-16782682_600.gif
14_42-18591552_600.gif
15_BE042583_600.gif
16_DECC36-20_600.gif
17_HT009114_600.gif
18_HU061735_600.gif
19_IH169760_600.gif
20_IH198376_600.gif
21_HU001525_600.gif
22_PG8373_600.gif
23_feedback_600.gif
```

Inside `824x1200` are the following files:
```
00_42-20711832_824.gif
01_kindle_def_824.gif
02_IH045799_824.gif
03_HU013742_824.gif
04_BE041723_824.gif
05_BE088162_824.gif
06_HU061820_824.gif
07_SF125_824.gif
08_BE061039_824.gif
09_AABR001007_824.gif
10_F10017_824.gif
11_IH179062_824.gif
12_BE002022_824.gif
13_42-16782682_824.gif
14_42-18591552_824.gif
15_BE042583_824.gif
16_DECC36-20_824.gif
17_HT009114_824.gif
18_HU061735_824.gif
19_IH169760_824.gif
20_IH198376_824.gif
21_HU001525_824.gif
22_PG8373_824.gif
23_feedback_824.gif
```
