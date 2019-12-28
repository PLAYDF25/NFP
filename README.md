function alert()
gg.alert("Welcome to the exclusive NFP script!\n•  •  •  •  •  •  •  Version 1.0")
HOME()
end

HOME=1
function HOME()
HM = gg.choice({
  '⬜ Menu Wallhack/Colors/Nature ⚪️',
  '⬜ Menu Weapons/Player ⚪',
  '⬜ Clearing Logs ⚪',
  '🔚 EXIT 🔚'
},nil, 
   '                   ⬜  NFP Version 1.0  ⬜\n                     PUBG MOBILE: 0.16.0')
if HM == 1 then MWCN() end
if HM == 2 then MW() end
if HM == 3 then CL() end
if HM == 4 then exit() end
HOMEDM=-1
end

function MWCN()
          MWCNM = gg.multiChoice({
  "🟩 WallHack 🟢\n  〰️ game/island 〰️ once",
  "🟩 Red Color 🟢\n  〰️ game/island 〰️ once",
  "🟩 Yellow Color 🟢\n  〰️ game/island 〰️ once",
  "🟩 Black Sky 🟢\n  〰️ game 〰️ every",
  "🟩 No Grass 🟢\n  〰️ lobby 〰️ once",
  "🟩 No Fog 🟢\n  〰️ lobby 〰️ once",
  "⬛ Menu Deactivate Functions ⚫",
  "⚪ BACK ⚪",
}, nil, 
   "🟩  Menu Wallhack/Colors/Nature  🟩   •  •  • NFP")
if MWCNM == nil then
else
if MWCNM[1] == true then WH() end
if MWCNM[2] == true then RC() end
if MWCNM[3] == true then YC() end
if MWCNM[4] == true then BS() end
if MWCNM[5] == true then NG() end
if MWCNM[6] == true then NF() end
if MWCNM[7] == true then DMWCN() end
if MWCNM[8] == true then HOME() end
end
end
function DMWCN()
          DMWCNM = gg.multiChoice({
  "⬛ Deactivate WallHack ⚫",
  "⬛ Deactivate Black Sky ⚫",
  "🟢 BACK 🟢",
}, nil, 
   "⬛  Menu Deactivate Functions  ⬛   •  •  • NFP")
if DMWCNM == nil then
else
if DMWCNM[1] == true then DWH() end
if DMWCNM[2] == true then DBS() end
if DMWCNM[3] == true then MWCN() end
end
end

function MW()
          MWM = gg.multiChoice({
  "🟥 No Recoil 🔴\n  〰️ lobby 〰️ once",
  "🟥 Menu Magic Bullet 🔴\n  〰️ lobby 〰️ once",
  "🟥 Menu HeadShot 🔴\n  〰️ lobby 〰️ once",
  "🟥 AimLock 🔴\n  〰️ lobby 〰️ once",
  "🟥 Menu Antenna 🔴\n  〰️ game 〰️ every",
  "🟥 Sit Scope 🔴\n  〰️ game 〰️ every",
  "⬛ Menu Deactivate Functions ⬛",
  "⚪ BACK ⚪",
}, nil, 
   "🟥  Menu Weapons/Player  🟥   •  •  • NFP")
if MWM == nil then
else
if MWM[1] == true then NR() end
if MWM[2] == true then MB() end
if MWM[3] == true then HS() end
if MWM[4] == true then AL1() end
if MWM[5] == true then ANN() end
if MWM[6] == true then SS() end
if MWM[7] == true then DMW() end
if MWM[8] == true then HOME() end
end
end

function DMW()
          DMWM = gg.multiChoice({
  "⬛ Deactivate No Recoil ⚫",
  "⬛ Deactivate Menu Magic Bullet ⚫",
  "⬛ Deactivate Menu HeadShot ⚫",
  "⬛ Deactivate AimLock ⚫",
  "⬛ Deactivate Menu Antenna ⚫",
  "⬛ Deactivate Sit Scope ⚫",
  "🔴 BACK 🔴",
}, nil, 
   "⬛  Menu Deactivate Functions  ⬛   •  •  • NFP")
if DMWM == nil then
else
if DMWM[1] == true then DNR() end
if DMWM[2] == true then DMB() end
if DMWM[3] == true then DHS() end
if DMWM[4] == true then DAL1() end
if DMWM[5] == true then DANN() end
if DMWM[6] == true then DSS() end
if DMWM[7] == true then MW() end
end
end

function CL()
gg.toast("Clearing Logs ...")
os.remove("/mnt/shell/0/emulated/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.tmgp.pubgmhd/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.tmgp.pubgmhd/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.igce/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.igce/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.iglite/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.iglite/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
gg.toast("Clearing Logs ...... ✓")
end
function WH()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;2;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack activated ✓")
end
function RC()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("328")
gg.getResults(20)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Color activated ✓")
end
function YC()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("328", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Yellow Color activated ✓")
end
function DWH()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;120;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("2", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("120;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("2", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack deactivated ✓")
end
function BS()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("000", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-90", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Black Sky activated ✓")
end
function DBS()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-90", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("000", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Black Sky deactivated ✓")
end
function NG()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__MaterialExpressionLandscapeGrassOutput", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.toast("No Grass activated ✓")
end
function NF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__ExponentialHeightFog", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.toast("No Fog activated ✓")
end
function SS()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-4767057191527907328", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Sit Scope activated ✓")
end
function DSS()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-4767057191653227520", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Sit Scope deactivated ✓")
end
function ANN()
          AM = gg.multiChoice({
  "🟥 Head Antenna 🔴\n  〰️ game 〰️ every",
  "🟥 Flare Gun Antenna 🔴\n  〰️ game 〰️ every",
  "🟥 3 lvl Item Antenna 🔴\n  〰️ game 〰️ every",
  "🟥 M4 Antenna 🔴\n  〰️ game 〰️ every",
  "🟥 SCAR-L Antenna 🔴\n  〰️ game 〰️ every",
  "🔴 BACK 🔴",
}, nil, 
   "🟥  Menu Antenna  🟥   •  •  • NFP")
if AM == nil then
else
if AM[1] == true then HA() end
if AM[2] == true then FGA() end
if AM[3] == true then LIA() end
if AM[4] == true then M4A() end
if AM[5] == true then SLA() end
if AM[6] == true then MW() end
end
end
function DANN()
          DAM = gg.multiChoice({
  "⬛ Deactivate Head Antenna ⚫",
  "⬛ Deactivate Flare Gun Antenna ⚫",
  "⬛ Deactivate 3 lvl Item Antenna ⚫",
  "⬛ Deactivate M4 Antenna ⚫",
  "⬛ Deactivate SCAR-L Antenna ⚫",
  "⚫ BACK ⚫",
}, nil, 
   "⬛  Menu Deactivate Antenna  ⬛   •  •  • NFP")
if DAM == nil then
else
if DAM[1] == true then DHA() end
if DAM[2] == true then DFGA() end
if DAM[3] == true then DLIA() end
if DAM[4] == true then DM4A() end
if DAM[5] == true then DSLA() end
if DAM[6] == true then DMW() end
end
end
function HA()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.98900693655~0.98900723457", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("16000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Head Antenna activated ✓")
end
function FGA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.7576~0.7579", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.7576~0.7579", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99599", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Flare Gun Antenna activated ✓")
end
function LIA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("7.1689529418945", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("98989", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("7.4993133544922", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("97979", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("18.46202087402", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("96969", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("3 lvl Item Antenna activated ✓")
end
function M4A()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.7593~0.7594", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("99989", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("M4 Antenna activated ✓")
end
function SLA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.7636~0.7636", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99979", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("SCAR-L Antenna activated ✓")
end
function DHA()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("16000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.98900693655", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Head Antenna deactivated ✓")
end
function DFGA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("99599", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("99599", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.7576", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Flare Gun Antenna deactivated ✓")
end
function DLIA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("98989", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("7.1689529418945", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("97979", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("7.4993133544922", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("96969", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("18.46202087402", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("3 lvl Item Antenna deactivated ✓")
end
function DM4A()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("99989", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0.7593", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("M4 Antenna deactivated ✓")
end
function DSLA()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("99979", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.7636", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("SCAR-L Antenna deactivated ✓")
end

function NR()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1D;0.05000000075F;0.10000000149F;0.55000001192F;9.5F;15.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("No Recoil activated ✓")
end
function MB()
          MBM = gg.multiChoice({
  "🟥 Magic Bullet 50% 🔴\n  〰️ lobby 〰️ once",
  "🟥 Magic Bullet 100% 🔴\n  〰️ lobby 〰️ once",
  "🔴 BACK 🔴",
}, nil, 
   "🟥  Menu Magic Bullet  🟥   •  •  • NFP")
if MBM == nil then
else
if MBM[1] == true then MB1() end
if MBM[2] == true then MB2() end
if MBM[3] == true then MW() end
end
end
function HS()
          HSM = gg.multiChoice({
  "🟥 HeadShot 50% 🔴\n  〰️ lobby 〰️ once",
  "🟥 HeadShot 100% 🔴\n  〰️ lobby 〰️ once",
  "🔴 BACK 🔴",
}, nil, 
   "🟥  Menu HeadShot  🟥   •  •  • NFP")
if HSM == nil then
else
if HSM[1] == true then HS1() end
if HSM[2] == true then HS2() end
if HSM[3] == true then MW() end
end
end
function MB1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("44", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("34", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("44", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 50% activated ✓")
end
function HS1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("125", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;125;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("152", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 50% activated ✓")
end
function AL1()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AimLock activated ✓")
end
function MB2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("98", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("68", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("88", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 100% activated ✓")
end
function HS2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;250;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("305", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 100% activated ✓")
end
function DMB()
          DMBM = gg.multiChoice({
  "⬛ Deactivate Magic Bullet 50% ⚫",
  "⬛ Deactivate Magic Bullet 100% ⚫",
  "⚫ BACK ⚫",
}, nil, 
   "⬛  Menu Deactivate Magic Bullet  ⬛   •  •  • NFP")
if DMBM == nil then
else
if DMBM[1] == true then DMB1() end
if DMBM[2] == true then DMB2() end
if DMBM[3] == true then DMW() end
end
end
function DHS()
          DHSM = gg.multiChoice({
  "⬛ Deactivate HeadShot 50% ⚫",
  "⬛ Deactivate HeadShot 100% ⚫",
  "⚫ BACK ⚫",
}, nil, 
   "⬛  Menu Deactivate HeadShot  ⬛   •  •  • NFP")
if DHSM == nil then
else
if DHSM[1] == true then DHS1() end
if DHSM[2] == true then DHS2() end
if DHSM[3] == true then DMW() end
end
end
function DMB1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("15", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;34", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("34", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("16", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;44;44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("27.25;18", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 50% deactivated ✓")
end
function DHS1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;125;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("125", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("25", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;125;152", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("152", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("30.5", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 50% deactivated ✓")
end
function DAL1()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;9999;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("9999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("0.0001", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AimLock deactivated ✓")
end
function DMB2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;98", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("98", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("15", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;68", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("68", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("16", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;88;88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("27.25;18", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 100% deactivated ✓")
end
function DHS2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;250;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("250", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("25", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;250;305", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("305", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("30.5", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 100% deactivated ✓")
end

function exit()
gg.setVisible(true)
os.exit()
end

alert()

while true do
 if gg.isVisible(true) then
   HOMEDM = 1
   gg.setVisible(false)
 end
 if HOMEDM == 1 then
   HOME()
 end
end
