# Google-TV-on-a-USB-Stick
Ever want a Google Tv in your pocket? No? Too bad! Here's the tutorial!

!!Works on Macs! EVEN WITH A T1 CHIP!!

























Lets start. first you have to have atleast a 8GB USB Stick. Dont? Too bad. it wont fit.

First head to this link to download the iso and the storage files: https://mega.nz/file/PVp3RJKD#Lrx54cvoPsl195aAm6rdCq3sqZqgjQKKd_1kjFoAfLY
Next, download rufus here: https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://rufus.ie/&ved=2ahUKEwi3q93zvP6PAxX-wAIHHaibE6AQFnoECAwQAQ&usg=AOvVaw360qlGZbGE3DcSah5A5ITM

If you have those files. extract the .Zip your going to get from the Mega file. youll have the iso, and a folder called "Storages".
Next, open rufus. click on Choose iSO. choose your downloaded iso. and enter in a 64gb (or whatever the max is) specified.

Now. click flash. and wait. this can take up to 30+ min on older/USB 2.0 sticks. so have patience. IDK. go watch a YT vid or something.

Next. after its done. open disk management. dont select the 3.84gb partition on your usb, the other one. the bigger one in most cases. right click, and then press delete volume.

Then, simply do the same with the now unallocated space and click new volume. Follow the instructions. !!IMPORTANT!! And make it EXFat. !!IMPORTANT!!

(IF THERES NO EXFAT PLEASE USE DISKPART TO FORMAT) Then, Go into the usb drive partition you flashed with rufus. 
and copy the system.csc file to the other (bigger) partition. then wait. takes a little while. 

Next, head to the downloaded folder again. and this time, extract one of the storages. for how much storage you want your "Tv" to have. 16GB=8GB 8GB=4GB Etc.

After that. disable secureboot. and to make sure it works. disable fast boot aswell. if your gonna be running this on a pre T1/T1 Mac. dont worry. just boot it now and your done. 

if your on Apple Silicon, this wont work.
If you have a T2 Mac. your gonna have to go into startup options. Follow this: On Intel-based Macs with an Apple T2 Security Chip, Apple startup options are managed by the Startup Security Utility, which is accessed by booting into macOS Recovery (Command-R) and selecting it from the Utilities menu. 
if you dont? then you dont have to.

Then, Just boot it! See what happens. (Google TV is basically JUST ANDROID. So if that works. Thisll work too. If Wifi doesnt work, thats too bad. i havent found any fixes for it yet. im trying.)

(Edit: there are basically NO drivers for google tv. doesnt work? too bad. does? YIPEE!!)


Credits to: @Techy Druid on Youtube
