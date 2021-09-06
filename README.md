# NARKOZ-VIP-SC-2
gg.toast("■□□□□□□□□□10%  ")
  gg.sleep(100)
  gg.toast("■■□□□□□□□□20%  ")
  gg.sleep(100)
  gg.toast("■■■□□□□□□□30%  ")
  gg.sleep(100)
  gg.toast("■■■■□□□□□□40%  ")
  gg.sleep(100)
  gg.toast("■■■■■□□□□□50%  ")
  gg.sleep(100)
  gg.toast("■■■■■■□□□□60%  ")
  gg.sleep(100)
  gg.toast("■■■■■■■□□□70%  ")
  gg.sleep(100)
  gg.toast("■■■■■■■■□□80%  ")
  gg.sleep(100)
  gg.toast("■■■■■■■■■□90%. ")
  gg.sleep(100)
  gg.toast("■■■■■■■■■■100%")
  gg.sleep(300)

gg.alert("✅ BİZİ TERCİH ETTİĞİN İÇİN TEŞEKKÜRLER @NARKOZ42 ✅")


-- -- -- -- -- -- -- -- -- -- Script Language -- -- -- -- -- -- -- -- -- --



HOME1 = 1
BYPDONE = 0
CMENU = 0
function HOME()
LANGHOME = gg.alert("🌐 زمانيك هەڵبژێرە \n🌐 Sᴇʟᴇᴄᴛ Lᴀɴɢᴜᴀɢᴇ\n🌐 اختر لغة السكربت  ", "⟬ كوردي 🇭🇺 ⟭", "⟬ 🇬🇧 English ⟭", "⟬ 🇸🇦 العربية ⟭")
if LANGHOME == nil then
else
if LANGHOME == 1 then
HOME1()
CMENU = 1
end
if LANGHOME == 2 then
HOME2()
CMENU = 2
end
if LANGHOME == 3 then
HOME3()
CMENU = 3
end
end
PUBGMH = -1
end

on = " [❌OFF❌] "
off = " "

------------HOME-----------

flashspplus = off
function HOME1()
ONE = gg.choice({
"️⁩❰🛡 • لیستی بایپاس ( لۆبي ) • ️⁩🛡❱",
"❰☠ • ليستى هاکە سەیڤەکان ( ياری ) • ☠❱",
"❰🔥 • ليستى هاکە بەهێزەکان ( ياری ) • 🔥❱",
"❰💎 • ليستى هاکە ى زياتر ( ياری ) • 💎❱",
"❰⚡ • فلاش ( ᴏɴ/ᴏғғ ) ( ياری ) • ⚡❱"  .. flashspplus,
"⟬ ❌ • دەرچوون • ❌⟭",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @KINGSHOOTER 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if ONE == nil then end
if ONE == 1 then BOOM() end
if ONE == 2 then SAFE() end
if ONE == 3 then NOTSAFE() end
if ONE == 4 then MORE() end
if ONE == 5 then FLASH() end
if ONE == 6 then CLOSING() end
PUBGMH = -1
end

flashspplus = off
function HOME2()
ONEPLUS = gg.choice({
"️⁩❰🛡 • ᴀɴᴛɪʙᴀɴ ᴀʟʟ ᴠᴇʀsɪᴏɴs ( ʟᴏʙʙʏ ) • ️⁩🛡❱",
"❰☠ • sᴀғᴇ ᴍᴇɴᴜ ( ɢᴀᴍᴇ ) • ☠❱",
"❰🔥 • ʙʀᴜᴛᴀʟʟ ᴍᴇɴᴜ ( ɢᴀᴍᴇ ) • 🔥❱",
"❰💎 • ᴍᴏʀᴇ ᴍᴇɴᴜ ( ɢᴀᴍᴇ ) • 💎❱",
"❰⚡ • 𝙵𝙻𝙰𝚂𝙷 ᴏɴ/ᴏғғ ( ɢᴀᴍᴇ ) •⚡❱"  .. flashspplus,
"❰ ❌ • 🅴🆇🅸🆃 • ❌ ❱",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if ONEPLUS == nil then end
if ONEPLUS == 1 then BOOM2() end
if ONEPLUS == 2 then SAFE2() end
if ONEPLUS == 3 then NOTSAFE2() end
if ONEPLUS == 4 then MORE2() end
if ONEPLUS == 5 then FLASH() end
if ONEPLUS == 6 then CLOSING() end
PUBGMH = -1
end

flashspplus = off
function HOME3()
ONEPLUS1 = gg.choice({
"️⁩❰🛡 • قائمة الحماية لكل النسخ ( لوبي ) • ️⁩🛡❱",
"❰🔥 • قائمة التفعيلات الامنة ( قيم ) • 🔥❱",
"❰⛔ • قائمة التفعيلات الغير امنة ( قيم ) • ⛔❱",
"❰💎 • قائمة تفعيلات اخرى ( قيم ) • 💎❱",
"❰⚡ • فلاش ᴏɴ/ᴏғғ ( قيم ) •⚡❱"  .. flashspplus,
"❰ ❌ • خروج من السكربت  • ❌ ❱",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if ONEPLUS1 == nil then end
if ONEPLUS1 == 1 then BOOM3() end
if ONEPLUS1 == 2 then SAFE3() end
if ONEPLUS1 == 3 then NOTSAFE3() end
if ONEPLUS1 == 4 then MORE3() end
if ONEPLUS1 == 5 then FLASH() end
if ONEPLUS1 == 6 then CLOSING() end
PUBGMH = -1
end

------------HOME-----------


------------BYPASS-----------


function BOOM()
BPPLUS = gg.choice({
"️⁩❰🛡 • بایپاسی لۆبی v¹ • ️⁩🛡❱",
"️⁩❰🛡 • بایپاسی لۆبی v² • ️⁩🛡❱",
"️⁩❰🛡 • بایپاسی لۆبی v³ • ️⁩🛡❱",
"️⁩❰🛡 • بایپاسی لۆبی v⁴ • ️⁩🛡❱",
"️⁩❰📵 • ڕێست • ️⁩📵❱",
    "↩ گەڕانەوە️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if BPPLUS == nil then end
if BPPLUS == 1 then NEW1() end
if BPPLUS == 2 then NEW2() end
if BPPLUS == 3 then NEW3() end
if BPPLUS == 4 then NEW4() end
if BPPLUS == 5 then TARSIT() end
if BPPLUS == 6 then HOME1() end
PUBGMH = -1
end


function BOOM2()
BPPLUS = gg.choice({
"️⁩❰🛡 • ᴀɴᴛɪʙᴀɴ ʟᴏʙʙʏ ᴀʟʟ ᴠᴇʀsɪᴏɴs v¹ • ️⁩🛡❱",
"️⁩❰🛡 • ᴀɴᴛɪʙᴀɴ ʟᴏʙʙʏ ᴀʟʟ ᴠᴇʀsɪᴏɴs v² • ️⁩🛡❱",
"️⁩❰🛡 • ᴀɴᴛɪʙᴀɴ ʟᴏʙʙʏ ᴀʟʟ ᴠᴇʀsɪᴏɴs v³ • ️⁩🛡❱",
"️⁩❰🛡 • ᴀɴᴛɪʙᴀɴ ʟᴏʙʙʏ ᴀʟʟ ᴠᴇʀsɪᴏɴs v⁴ • ️⁩🛡❱",
"️⁩❰📵 • ᴅᴀᴛᴀ ᴏɴ-ᴏғғ • ️⁩📵❱",
"↩ ʙ ᴀ ᴄ ᴋ️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if BPPLUS == nil then end
if BPPLUS == 1 then NEW1() end
if BPPLUS == 2 then NEW2() end
if BPPLUS == 3 then NEW3() end
if BPPLUS == 4 then NEW4() end
if BPPLUS == 5 then TARSIT() end
if BPPLUS == 6 then HOME2() end
PUBGMH = -1
end


function BOOM3()
BPPLUS = gg.choice({
"️⁩❰🛡 • حماية لوبي لجميع النسخ v¹ • ️⁩🛡❱",
"️⁩❰🛡 • حماية لوبي لجميع النسخ v² • ️⁩🛡❱",
"️⁩❰🛡 • حماية لوبي لجميع النسخ v³ • ️⁩🛡❱",
"️⁩❰🛡 • حماية لوبي لجميع النسخ v⁴ • ️⁩🛡❱",
"️⁩❰📵 • الترسيت السريع لمنع باند العشر دقايق • ️⁩📵❱",
"↩  رجـــــوع للـــقــــائمــــة  ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if BPPLUS == nil then end
if BPPLUS == 1 then NEW1() end
if BPPLUS == 2 then NEW2() end
if BPPLUS == 3 then NEW3() end
if BPPLUS == 4 then NEW4() end
if BPPLUS == 5 then TARSIT() end
if BPPLUS == 6 then HOME3() end
PUBGMH = -1
end


function NEW1()
gg.toast("بایپاسی 1 چالاک دەکرێت")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(500)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(500)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD)
gg.refineNumber("577252194516992", gg.TYPE_QWORD)
gg.getResults(99999)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("65795~590336;67109633;131330", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("65795~590336", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(56789)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.alert("نتيبان V1 أكتيف✅@Narkoz42")
gg.alert("الآن يمكنك فتح AIMBOTS مع MY KARŞİM")
end

function NEW2() 
gg.toast("بایپاسی 2 چالاک دەکرێت")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(500)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(500)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.refineNumber("620,137,442,967,552", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD)
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.searchNumber("577252194516992;288233678981562368", gg.TYPE_QWORD)
gg.refineNumber("577252194516992", gg.TYPE_QWORD)
gg.getResults(99999)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("65795~590336;67109633;131330", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("65795~590336", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(56789)
gg.editAll("361418272522109953", gg.TYPE_QWORD)
gg.clearResults()
gg.alert("أنتيبان V2 أكتيف✅")
gg.alert("@NARKOZ42شكرا لك لاختيارن")
end

function NEW3() 
gg.toast("بایپاسی 3 چالاک دەکرێت")
gg.clearResults()
gg.setVisible(false)
gg.setRanges(gg.REGION_C_ALLOC) 
gg.searchNumber("70368744177664;288232579469934592", gg.TYPE_QWORD) 
gg.refineNumber("70368744177664", gg.TYPE_QWORD) 
gg.getResults(50000) 
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults() 
gg.setRanges(gg.REGION_C_ALLOC) 
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD) 
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;620137442967552", gg.TYPE_QWORD)
gg.refineNumber("582749752655872", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("565157566611456;566257078239232", gg.TYPE_QWORD)
gg.refineNumber("565157566611456", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("17,592,186,044,416;582749752655872", gg.TYPE_QWORD)
gg.refineNumber("17,592,186,044,416", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("577252194516992;288232579469934592", gg.TYPE_QWORD)
gg.refineNumber("577252194516992", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;578351706144768", gg.TYPE_QWORD)
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("566257078239232;573957954600960", gg.TYPE_QWORD)
gg.refineNumber("566257078239232", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("573953659633664;582749752655872", gg.TYPE_QWORD)
gg.refineNumber("573953659633664", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("572854148005888;620137442967552", gg.TYPE_QWORD)
gg.refineNumber("572854148005888", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("4398046511104;544434349408256", gg.TYPE_QWORD)
gg.refineNumber("4398046511104", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("569,555,613,122,560", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("569,555,613,122,560", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("568,456,101,494,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("568,456,101,494,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("575,053,171,261,440", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("575,053,171,261,440", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("576,152,682,889,216", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("576,152,682,889,216", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("570,655,124,750,336", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("570,655,124,750,336", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("132,866", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("132,866", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("132,610", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("132,610", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setVisible(false)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("132,354", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("132,354", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133,890", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("133,890", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134,146", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("134,146", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("134,402", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("134,402", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("131,970", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("131,970", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setVisible(false)
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("131,458", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("131,458", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("135,426", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("135,426", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("133,121", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("133,121", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("135,938", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("135,938", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_DWORD then
		v.value = "67109633"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0540,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0548,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0550,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0558,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C900,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3C0,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3B8,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3B0,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3A8,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB3475C8,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2B1B3A4,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0540,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0548,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2F024A8,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C910,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB73156C,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3D0,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C3C8,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB34A468,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C980,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB079044,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C920,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x31D38DC,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB07818C,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB37C400,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C998,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x31D480C,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2ED0598,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB732744,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xE24C9A0,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0x2B1A25C,['flags'] = 4,['value'] = 67109633,},})
gg.getRangesList("libUE4.so")
gg.setValues({[1] = {['address'] = 0xB07718C,['flags'] = 4,['value'] = 67109633,},})
gg.clearResults()
gg.alert("V3 أنتيبان أكتيف ✅")
gg.alert("شكرا لك لاختيارنا@Narkoz42")
end

function NEW4() 
gg.toast("بایپاسی 4 چالاک دەکرێت")
gg.clearResults()
gg.setVisible(false)
gg.setRanges(gg.REGION_C_ALLOC) 
gg.searchNumber("70368744177664;288232579469934592", gg.TYPE_QWORD) 
gg.refineNumber("70368744177664", gg.TYPE_QWORD) 
gg.getResults(50000) 
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults() 
gg.setRanges(gg.REGION_C_ALLOC) 
gg.searchNumber("578351706144768;564058054983680", gg.TYPE_QWORD) 
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("582749752655872;620137442967552", gg.TYPE_QWORD)
gg.refineNumber("582749752655872", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("565157566611456;566257078239232", gg.TYPE_QWORD)
gg.refineNumber("565157566611456", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("17,592,186,044,416;582749752655872", gg.TYPE_QWORD)
gg.refineNumber("17,592,186,044,416", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("577252194516992;288232579469934592", gg.TYPE_QWORD)
gg.refineNumber("577252194516992", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("578351706144768;578351706144768", gg.TYPE_QWORD)
gg.refineNumber("578351706144768", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("566257078239232;573957954600960", gg.TYPE_QWORD)
gg.refineNumber("566257078239232", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("573953659633664;582749752655872", gg.TYPE_QWORD)
gg.refineNumber("573953659633664", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("572854148005888;620137442967552", gg.TYPE_QWORD)
gg.refineNumber("572854148005888", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("4398046511104;544434349408256", gg.TYPE_QWORD)
gg.refineNumber("4398046511104", gg.TYPE_QWORD)
gg.getResults(50000)
gg.editAll("288233678981562368", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("569,555,613,122,560", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("569,555,613,122,560", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("568,456,101,494,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("568,456,101,494,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("575,053,171,261,440", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("575,053,171,261,440", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("576,152,682,889,216", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("576,152,682,889,216", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("570,655,124,750,336", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("570,655,124,750,336", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(20000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_QWORD then
		v.value = "288233678981562368"
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
gg.clearResults()
gg.alert("Antiban V3 نشط@Narkoz42 ✅")
gg.alert("شكرا لك لاختيارنا@Narkoz42")
end

function TARSIT() 
gg.clearResults()                   
gg.setRanges(gg.REGION_CODE_APP)                 
gg.searchNumber('220676386071773185', gg.TYPE_QWORD)                  
gg.getResults(69)                 
gg.editAll('220676386036121600', gg.TYPE_QWORD)          
gg.toast("📵 ɪɴᴛᴇʀɴᴇᴛ ᴅɪsᴄᴏɴɴᴇᴄᴛᴇᴅ 📵")        
gg.sleep(6000)                 
gg.editAll('220676386071773185', gg.TYPE_QWORD)                 
gg.clearResults()
gg.toast("🔥 ɪɴᴛᴇʀɴᴇᴛ ᴄᴏɴɴᴇᴄᴛᴇᴅ 🔥")
end


------------BYPASS-----------


function SAFE()
SFPLUS = gg.multiChoice({
"📍 انتينا ", 
"🎯 ايمبوت ", 
"🛑 ڕیکۆیڵ ",
"🔥 هيدشوت ",
"☄ ماجيك بوليت ",
"📽 کامێرە ئایپاد", 
"🌌 ئاسمانی ڕەش ", 
"💥 ئەیملوک ",
"↩ گەڕانەوە️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @KINGSHOOTER 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if SFPLUS == nil then else
if SFPLUS[1] == true then ANTENA() end
if SFPLUS[2] == true then AIMBOT() end
if SFPLUS[3] == true then NORECOIL() end
if SFPLUS[4] == true then HEADSHOT() end
if SFPLUS[5] == true then MAGICBULLET() end
if SFPLUS[6] == true then IPADCAMERA() end
if SFPLUS[7] == true then BLACKSKY() end
if SFPLUS[8] == true then AIMLOCK() end
if SFPLUS[9] == true then HOME1() end
PUBGMH = -1
end
end



function SAFE2()
SFPLUS = gg.multiChoice({
"📍 ᴀɴᴛᴇɴᴀ ",
"🎯 ᴀɪᴍʙᴏᴛ ", 
"🛑 ɴᴏ ʀᴇᴄᴏɪʟ ",
"🔥 ʜᴇᴀᴅsʜᴏᴛ ",
"☄ ᴍᴀɢɪᴄ ʙᴜʟʟᴇᴛ ",
"📽 ɪᴘᴀᴅ ᴠɪᴇᴡ ",
"🌌 ʙʟᴀᴄᴋ sᴋʏ ", 
"💥 ᴀɪᴍʟᴏᴄᴋ ",
"↩ ʙ ᴀ ᴄ ᴋ️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if SFPLUS == nil then else
if SFPLUS[1] == true then ANTENA() end
if SFPLUS[2] == true then AIMBOT() end
if SFPLUS[3] == true then NORECOIL2() end
if SFPLUS[4] == true then HEADSHOT() end
if SFPLUS[5] == true then MAGICBULLET() end
if SFPLUS[6] == true then IPADCAMERA() end
if SFPLUS[7] == true then BLACKSKY() end
if SFPLUS[8] == true then AIMLOCK() end
if SFPLUS[9] == true then HOME2() end
PUBGMH = -1
end
end



function SAFE3()
SFPLUS = gg.multiChoice({
"📍 انتينا ",
"🎯 ايمبوت ", 
"🛑 ثبات سلاح ",
"🔥 هيدشوت ",
"☄ ماجيك بوليت ",
"📽 منظور ايباد ", 
"🌌 سماء سوداء ", 
"💥 ايم لوك ",
"↩ رجـــــوع للـــقــــائمــــة ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if SFPLUS == nil then else
if SFPLUS[1] == true then ANTENA() end
if SFPLUS[2] == true then AIMBOT() end
if SFPLUS[3] == true then NORECOIL3() end
if SFPLUS[4] == true then HEADSHOT() end
if SFPLUS[5] == true then MAGICBULLET() end
if SFPLUS[6] == true then IPADCAMERA() end
if SFPLUS[7] == true then BLACKSKY() end
if SFPLUS[8] == true then AIMLOCK() end
if SFPLUS[9] == true then HOME3() end
PUBGMH = -1
end
end


function ANTENA() 
gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  antenags1 = gg.getResults(6)
  gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
  gg.clearResults()
gg.toast("Anten Activated @Narkoz42 🔥")
end


function AIMBOT() 
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA|gg.REGION_CODE_APP)
gg.searchNumber("2046820354;-336587221:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)--Telegram @VipCodes
gg.searchNumber("2046820354", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("2046820353", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA|gg.REGION_CODE_APP)
gg.searchNumber("2015175168", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("1,324,366,404", gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0, -1)
gg.searchNumber("1,324,366,404", gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(80)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("99", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Aimbot Activated @Narkoz42 🔥")
end


------recoil-------

function NORECOIL()
LS5 = gg.multiChoice({
"🎯 〖 ڕیکۆیڵ 100% v1 〗",
"🎯 〖 ڕیکۆیڵ 100% v2 〗️",
"🕸 〖 ڕیکۆیڵ 50% v1 〗",
"🕸 〖 ڕیکۆیڵ 50% v2 〗",
"🕸 〖 ڕیکۆیڵ 50% v3 〗",
"⚙️ 〖 نەهێشتنی لەرزین 〗",
"💢 〖 نیشانە بچوک کردن 〗",
"↩ • گەڕانەوە ️ • ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if LS5 == nil then else
if LS5 [1] == true then NOREC100() end
if LS5 [2] == true then NOREC1002() end
if LS5 [3] == true then LESSREC1() end
if LS5 [4] == true then LESSREC2() end
if LS5 [5] == true then LESSREC3() end
if LS5 [6] == true then NOSHAKE() end
if LS5 [7] == true then SMALLCROSS() end
if LS5 [8] == true then SAFE() end
end
PUBGMH = -1
end


function NORECOIL2()
LS6 = gg.multiChoice({
"🎯 〖 ɴᴏ ʀᴇᴄᴏɪʟ 100% v1 〗",
"🎯 〖 ɴᴏ ʀᴇᴄᴏɪʟ 100% v2 〗️",
"🕸 〖 ʟᴇss ʀᴇᴄᴏɪʟ v1 〗",
"🕸 〖 ʟᴇss ʀᴇᴄᴏɪʟ v2 〗",
"🕸 〖 ʟᴇss ʀᴇᴄᴏɪʟ v3 〗",
"⚙️ 〖 ᴀɴᴛɪ sʜᴀᴋᴇ 〗",
"💢 〖 sᴍᴀʟʟ ᴄʀᴏssʜᴀɪʀ 〗",
"↩ • ʙ ᴀ ᴄ ᴋ️ • ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if LS6 == nil then else
if LS6 [1] == true then NOREC100() end
if LS6 [2] == true then NOREC1002() end
if LS6 [3] == true then LESSREC1() end
if LS6 [4] == true then LESSREC2() end
if LS6 [5] == true then LESSREC3() end
if LS6 [6] == true then NOSHAKE() end
if LS6 [7] == true then SMALLCROSS() end
if LS6 [8] == true then SAFE2() end
end
PUBGMH = -1
end

function NORECOIL3()
LS7 = gg.multiChoice({
"🎯 〖 ثبات سلاح %100 v1 〗",
"🎯 〖 ثبات سلاح %100 v2 〗️",
"🕸 〖 ثبات سلاح v1 〗",
"🕸 〖 ثبات سلاح v2 〗",
"🕸 〖 ثبات سلاح v3 〗",
"⚙️ 〖 منع إهتزاز السلاح 〗",
"💢 〖 تصغير مؤشر التصويب 〗",
"↩ • رجـــــوع للـــقــــائمــــة️ • ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if LS7 == nil then else
if LS7 [1] == true then NOREC100() end
if LS7 [2] == true then NOREC1002() end
if LS7 [3] == true then LESSREC1() end
if LS7 [4] == true then LESSREC2() end
if LS7 [5] == true then LESSREC3() end
if LS7 [6] == true then NOSHAKE() end
if LS7 [7] == true then SMALLCROSS() end
if LS7 [8] == true then SAFE3() end
end
PUBGMH = -1
end

function NOREC100() --1.3
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1.427811e28;8.5626969e-26", gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0, -1)
gg.searchNumber("-1.427811e28", gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(10)
gg.editAll("0",gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-1.2382424e28;-1.4239333e28;-1.1144502e28;-1.8331474e27;-7.1608877e24::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('-1.1144502e28', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll('90', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(16384)
gg.searchNumber("-2.786982e28;-2.2673448e24;-1.13688735e-13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-2.786982e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("No Recoil 100% Activated 🔥")
end

function NOREC1002() --1.3
function setvalue(address,flags,value)  local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end
so = gg.getRangesList('libUE4.so')[1].start
py = 0x1CA9C44
setvalue(so+py,16,0)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1.427811e28;8.5626969e-26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.427811e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1.2382424e28;-1.4239333e28;-1.1144502e28;-1.8331474e27;-7.1608877e24::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("90", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2.786982e28;-2.2673448e24;-1.13688735e-13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-2.786982e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("No Recoil 100% Activated 🔥")
end


function LESSREC3() --1.3
gg.clearResults()
so=gg.getRangesList('libUE4.so')[1].start
py=0x13C44A0
setvalue(so+py,16,0)
gg.clearResults()
gg.toast("LESS Recoil 50% Activated 🔥")
end

function LESSREC2() --1.3
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1.36203639e28;-5.10804629e27:17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.getResults(99999)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("LESS Recoil 50% Activated 🔥")
end

function LESSREC1() --1.3
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-309056968;-298841599;-309061065", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-298841599", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("LESS Recoil 50% Activated 🔥")
end

function NOSHAKE() --1.3
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
so = gg.getRangesList("libUE4.so")[1].start
py = 30383660
setvalue(so + py, 4, 70)
gg.clearResults()
gg.toast(" Anti Shake Activated 🔥")
end

function SMALLCROSS() --1.3
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2F;2F;1079446077;1.09375F;1F::17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultCount()
gg.searchNumber("1079446077", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Small Crosshair Activated 🔥")
end


------recoil-------


------headshot-------

function HEADSHOT() 
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("0.10000000149;64.50088500977", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("8", gg.TYPE_FLOAT)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-660", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("350", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("-298284466;-1.304566e23F", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-298284466", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("-1,883,348,481,058,764,210", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,883,348,485,055,444,540", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Headshot Activated Successful 🔥")
end


------headshot-------


function MAGICBULLET() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("25;30.5~60.5", gg.TYPE_FLOAT)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.getResults(56)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("15;28;16;26;8;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)--@VipCodes
gg.getResults(56)
gg.editAll("-1339", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet Activated Successful 🔥")
end


function IPADCAMERA() 
function setvalue(address,flags,value) local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end
so=gg.getRangesList('libUE4.so')[1].start
py=0x3A05C20
setvalue(so+py, 16,240)
gg.toast(" Camera iPad Activated Successful 🔥")
end


function BLACKSKY() 
function setvalue(address,flags,value) local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------@code_cheat
so=gg.getRangesList('libUE4.so')[1].start
py=0x3CBA010
setvalue(so+py,4,-1222129996)
gg.toast(" black sky Activated Successful 🔥")
end


function AIMLOCK() 
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("2015175168", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("0", 16)
gg.clearResults()
gg.toast(" Aimlock  Activated 🔥")
end


------nosafe-------

standscoppp = off
function NOTSAFE()
NOTPLUS = gg.multiChoice({
"🔥 • یەک گولەو مردن",
"💣 • انستا هيت",
"❌ • گۆڕینی نیشانە 🆇",
"⬆️ • گادڤیو ( ᴏɴ/ᴏғғ )" .. standscoppp,
"🛐 • گادڤیو 2 ",
"↩ گەڕانەوە ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then oneshot() end
if NOTPLUS[2] == true then INSTAHIT() end
if NOTPLUS[3] == true then HitEffect() end
if NOTPLUS[4] == true then STSCOPE() end
if NOTPLUS[5] == true then SITSCOPE() end
if NOTPLUS[6] == true then HOME1() end
PUBGMH = -1
end
end


standscoppp = off
function NOTSAFE2()
NOTPLUS = gg.multiChoice({
"🔥 • ᴏɴᴇ sʜᴏᴏᴛ",
"💣 • ɪɴsᴛᴀɴᴛ ʜɪᴛ",
"❌ • ʜɪᴛ ᴇғғᴇᴄᴛ 🆇",
"⬆️ • ꜱᴛᴀɴᴅ ꜱᴄᴏᴘᴇ ( ᴏɴ/ᴏғғ )" .. standscoppp,
"🛐 • ꜱɪᴛ sᴄᴏᴘᴇ ",
"↩ ʙ ᴀ ᴄ ᴋ️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then oneshot() end
if NOTPLUS[2] == true then INSTAHIT() end
if NOTPLUS[3] == true then HitEffect() end
if NOTPLUS[4] == true then STSCOPE() end
if NOTPLUS[5] == true then SITSCOPE() end
if NOTPLUS[6] == true then HOME2() end
PUBGMH = -1
end
end


standscoppp = off
function NOTSAFE3()
NOTPLUS = gg.multiChoice({
"🔥 • طلقة واحدة",
"💣 • طلقة سريعة ",
"❌ • تأثير الضرب 🆇",
"⬆️ • ستاند سكوب ( ᴏɴ/ᴏғғ )" .. standscoppp,
"🛐 • سيت سكوب ",
"↩ رجـــــوع للـــقــــائمــــة ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then oneshot() end
if NOTPLUS[2] == true then INSTAHIT() end
if NOTPLUS[3] == true then HitEffect() end
if NOTPLUS[4] == true then STSCOPE() end
if NOTPLUS[5] == true then SITSCOPE() end
if NOTPLUS[6] == true then HOME3() end
PUBGMH = -1
end
end


function oneshot() 
gg.toast("1 Shoot Activated 🔥")
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("0.10000000149;64.50088500977", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("8", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("0.10000000149;64.50088500977", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("8", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("-298284466;-1.304566e23F", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-298284466", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA | gg.REGION_CODE_APP)
gg.searchNumber("-1,883,348,481,058,764,210", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,883,348,485,055,444,540", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.editAll("-1,883,348,485,055,444,540", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("10;45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("10", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" 1 Shoot Activated 🔥")
end

function INSTAHIT() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("16000~99999;3D;0.1;1D::40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("16000~99999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("500000", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0000B040rA;0000803FrA;0000403FrA:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(31)
gg.editAll("1,087,897,600;1,075,838,976;1,075,838,976", gg.TYPE_DWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("400000", gg.TYPE_FLOAT)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("400000", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("400000", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("400000", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("400000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" ɪɴsᴛᴀɴᴛ ʜɪᴛ Activated 🔥")
end

function HitEffect() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("10;45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("10", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Hit Effect 🆇 Activated 🔥")
end

function STSCOPE() 
if standscoppp == off then
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4848124999984742400", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Stand Scope Activated 🔥")
standscoppp = on
else
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4138667321167981973", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Stand Scope Deactivated 🔥")
standscoppp = off
end
end

function SITSCOPE() 
gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("4848124999984742400", gg.TYPE_QWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("-4767057191527907328", gg.TYPE_QWORD)
  gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("18.38787841797;0.53867292404;-3.42232513428;1.77635705e-15:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("18.38787841797", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
fast1 = gg.getResults(2805)
gg.editAll("130.5419921875",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Sit Scope Activated 🔥")
end

----------MORE---------

fly1 = off
function MORE()
NOTPLUS = gg.multiChoice({
"🪂 • خێرا  دابەزین 𝐎𝐍",
"🪂 • خێرا  دابەزین 𝐎𝐅𝐅",
"🛸 •️ فڕينی هەموو سەیارەیەک",
"🏎 •️ خێرای هەموو سەیارەیەک",
"✈ • بازی بەرز ( ᴏɴ/ᴏғғ )" .. fly1,
"🎭 • واڵ‌هاک و ڕەنگ",
"↩ گەڕانەوە️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then faston() end
if NOTPLUS[2] == true then fastoff() end
if NOTPLUS[3] == true then jumpcar() end
if NOTPLUS[4] == true then speedcar() end
if NOTPLUS[5] == true then skyjump() end
if NOTPLUS[6] == true then wallhack() end
if NOTPLUS[7] == true then HOME1() end
PUBGMH = -1
end
end

fly1 = off
function MORE2()
NOTPLUS = gg.multiChoice({
"🪂 • ғᴀsᴛ ᴘᴀʀᴀᴄʜᴜᴛᴇ 𝐎𝐍",
"🪂 • ғᴀsᴛ ᴘᴀʀᴀᴄʜᴜᴛᴇ 𝐎𝐅𝐅",
"🛸 •️ ᴊᴜᴍᴘ ᴀʟʟ ᴄᴀʀs",
"🏎 •️ sᴘᴇᴇᴅ ᴀʟʟ ᴄᴀʀs",
"✈ • 𝚂𝙺𝚈 𝙹𝚄𝙼𝙿 ( ᴏɴ/ᴏғғ )" .. fly1,
"🎭 • ᴡᴀʟʟʜᴀᴄᴋ & ᴄᴏʟᴏʀ",
"↩ ʙ ᴀ ᴄ ᴋ️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then faston() end
if NOTPLUS[2] == true then fastoff() end
if NOTPLUS[3] == true then jumpcar() end
if NOTPLUS[4] == true then speedcar() end
if NOTPLUS[5] == true then skyjump() end
if NOTPLUS[6] == true then wallhack() end
if NOTPLUS[7] == true then HOME2() end
PUBGMH = -1
end
end

fly1 = off
function MORE3()
NOTPLUS = gg.multiChoice({
"🪂 • نزول سريع 𝐎𝐍",
"🪂 • نزول سريع 𝐎𝐅𝐅",
"🛸 •️ القفز جميع السيارات",
"🏎 •️ سرعة جميع السيارات",
"✈ • قفزة السماء ( ᴏɴ/ᴏғғ )" .. fly1,
"🎭 • الول هاك و الألوان",
"↩ رجـــــوع للـــقــــائمــــة️ ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
if NOTPLUS == nil then else
if NOTPLUS[1] == true then faston() end
if NOTPLUS[2] == true then fastoff() end
if NOTPLUS[3] == true then jumpcar() end
if NOTPLUS[4] == true then speedcar() end
if NOTPLUS[5] == true then skyjump() end
if NOTPLUS[6] == true then wallhack() end
if NOTPLUS[7] == true then HOME3() end
PUBGMH = -1
end
end

----------MORE---------

function faston() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("20000;750;0.0001;0.0005 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
S1=gg.getResults(100)
gg.editAll("0.09", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1585267064848315881", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
S2=gg.getResults(100)
gg.editAll("-1585267068834414550", gg.TYPE_QWORD)
gg.clearResults()
gg.toast(" Fast Parachute Activated 🔥") 
end

function fastoff() 
gg.clearResults()
gg.setValues(S1)
gg.setValues(S2)
gg.clearResults()
gg.toast("Fast Parachute Deactivated 🔥")
end

function jumpcar()
gg.toast(" 1 Second")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-980.0F;4,000.0F;0.30000001192F;5.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-980.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("25000", gg.TYPE_FLOAT)
gg.sleep(750)
gg.editAll("-980", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Jump All Cars Activated 🔥")
end

function speedcar() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1000;10;4D;4D;50;5;2;0.01::", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.refineNumber( "0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Speed All Cars Activated 🔥")
end

function skyjump()
if fly1 == off then
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
W1 = gg.getResults(1401)
--
gg.editAll("1,873,498,234,778,812,416", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
gg.refineNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
gg.refineNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
--
W2 = gg.getResults(1401)
--
gg.editAll("403,635,275,035,574,272", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
W3 = gg.getResults(1401)
gg.editAll("-2,044,616,634,647,180,800", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)

gg.refineNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
W4 = gg.getResults(1401)
gg.editAll("-1296744153870237696", gg.TYPE_QWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2188679037581846016", gg.TYPE_QWORD)
--
gg.getResultsCount()
gg.toast("Sky Jump Activated 🔥")
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3000", gg.TYPE_QWORD)
--
gg.getResultsCount()
gg.toast("Sky Jump Activated 🔥")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("5.0000002E-4", gg.TYPE_FLOAT)
--
gg.getResultsCount()
gg.toast("Sky Jump Activated 🔥")
gg.toast("0N")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
--
gg.refineNumber("1;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
--
W5 = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
--
gg.editAll("-9", gg.TYPE_FLOAT)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2188679037581846016", gg.TYPE_QWORD)
--
gg.getResultsCount()
gg.toast("Sky Jump Activated 🔥")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("5.0000002E-4", gg.TYPE_FLOAT)
--
gg.getResultsCount()
gg.toast("Sky Jump Activated 🔥") 
gg.clearResults()
fly1 = on 
 else 
gg.setValues(W1)
gg.setValues(W2)
gg.setValues(W3)
gg.setValues(W4)
gg.setValues(W5)
gg.alert("Sky Jump Dectivated 🔥")
fly1 = off
end
end

function wallhack() 
MN1 = gg.choice({
    "🎭 WALLHACK & COLOR\n╰➥ FOR ALL DEVICE",
    "↩ • گەرانەوە  ʙ ᴀ ᴄ ᴋ️ • ↪",
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
  if MN1 == nil then
  else
    if MN1 == 1 then
      PROFESSOR009()
    end
    if MN1 == 3 then
      PROFESSOR0()
end
end
PUBGMH = -1
end


function PROFESSOR009()
  WALL11 = gg.multiChoice({
    "🎨• Wh Hack Sd 712--855",
    "🎨• Wh & Color Yellow 💛",
    "🎨• Wh & Color Red ❤",
    "🎨• Wh & Color Black 🖤",
    "🎨• Wh & Color Blue 💙",
    "🎨• Wh & Color Green 💚",
    "↩ • گەرانەوە  ʙ ᴀ ᴄ ᴋ️ • ↪"
  }, nil, (os.date("%A, %d %B %Y %H:%M%p 📅\n \n This Script Make By NARKOZ\n \n ᴛʟᴇɢʀᴀᴍ :『 @NARKOZSCKANAL 』\n ᴅᴇᴠᴇʟᴏᴘᴇʀ :『 @NARKOZ42 』")))
  if WALL11 == nil then
  else
  if WALL11 == 1 then
      WHC20000()
    end
  if WALL11 == 2 then
      WHC1000()
    end
    if WALL11 == 3 then
      WHC2000()
    end
    if WALL11 == 4 then
      WHC3000()
    end
    if WALL11 == 5 then
      WHC4000()
    end
    if WALL11 == 6 then
      WHC5000()
    end
    if WALL11 == 7 then
    PROFESSOR00()
end
end
PUBGMH = -1
end


function WHC20000()
gg.setRanges(1048576)
local dataType = 32
local Name ="Wall1"
local tb1 = {{2325053844951662592, 0}, {2316046640328212539, -8}, {4611686018966634534, -4}, {541343783, 4}, {282574488338432, 8}, }
local tb2 = {{2325053845002125312, 0}, }
SearchWrite(tb1, tb2, dataType)
gg.setRanges(1048576)
local dataType = 32
local Name ="Wall2"
local tb1 = {{-4647714814372610048, 0}, {0, -8}, {4611686018427387904, -4}, {3212836864, 4}, {4575657221408423936, 8}, }
local tb2 = {{2325053845002125312, 0}, }
SearchWrite(tb1, tb2, dataType)
gg.toast(" AKTİF 🔥")
end


function WHC1000()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("5.1097599e21;8.2676609e-44;2.0:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("200", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("2.0y;0.69314718246;0.00999999978:29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("9B0", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;8201:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200;8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(550292)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("💛 WallHack AKTİF💛")
end

function WHC2000()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("5.1097599e21;8.2676609e-44;2.0:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("200", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("2.0y;0.69314718246;0.00999999978:29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("9B0", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("8,196D;8,192D;8,200D::", 4, false, 536870912, 0, -1)
gg.searchNumber("8200", 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("7", 4)
gg.clearResults()
gg.setVisible(false)
gg.toast("❤ WallHack AKTİF❤")
end

function WHC3000()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("5.1097599e21;8.2676609e-44;2.0:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("200", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("2.0y;0.69314718246;0.00999999978:29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("9B0", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("🖤 WallHack AKTİF🖤")
end

function WHC4000()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("5.1097599e21;8.2676609e-44;2.0:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("200", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("2.0y;0.69314718246;0.00999999978:29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("9B0", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("537133066;8200;1194344459;8201:13", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("8201", 4, false, 536870912, 0, -1, 0)
gg.getResults(63825)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("💙 WallHack AKTİF💙")
end

function WHC5000()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("5.1097599e21;8.2676609e-44;2.0:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("200", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("2.0y;0.69314718246;0.00999999978:29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.0", 16, false, 536870912, 0, -1)
gg.refineAddress("9B0", -1, 16, 536870912, 0, -1)
gg.getResults(63825)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
gg.searchNumber("537133066;8200;1194344459;8201:13", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
gg.refineNumber("8201", 4, false, 536870912, 0, -1, 0)
gg.getResults(63825)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("💚 WallHack AKTİF 💚")
end


function FLASH()
if flashspplus == off then
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1,328,550,408,728,725,571", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1) 
P1 = gg.getResults(8000000) 
gg.editAll("-1328550408578809999", gg.TYPE_QWORD) 
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
P2 = gg.getResults(1401)
gg.editAll("1,873,498,234,778,812,416", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("403,635,275,035,574,273", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
P3 = gg.getResults(1401)
gg.editAll("403,635,275,035,574,272", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-2,044,616,634,647,180,784", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
P4 = gg.getResults(1401)
gg.editAll("-2,044,616,634,647,180,800", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
P5 = gg.getResults(1401)
gg.editAll("-1296744153870237696", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1,873,498,234,778,812,417", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
P6 = gg.getResults(1401)
gg.editAll("1,873,498,234,778,812,416", gg.TYPE_QWORD)
gg.clearResults()
gg.toast("Flash Speed AKTİF ✅")
flashspplus = on
else
gg.setValues(P1)
gg.setValues(P2)
gg.setValues(P3)
gg.setValues(P4)
gg.setValues(P5)
gg.setValues(P6)
gg.toast("Flash Speed ARTIK AKTİF DEGİL ✅")
flashspplus = off
end
end


function CLOSING() 
gg.alert("\nscrıpt BY Narkoz \n\n  TELEGRAM Channel:『 @NARKOZSCKANAL 』🔔 \n \n MY TELEGRAM ᴜsᴇʀ:『 @NARKOZ42 ")
gg.copyText("https://t.me/NARKOZVIPSCKANAL    https://t.me/NARKOZSCKANAL")
gg.alert(" @NARKOZ42 TELEGRAM@NARLOZSCKANAL  GELMEYİ UNUTMA HAA") 
gg.alert("TELEGRAM KANALIMA GELMEYİ UNUTMAYIN\n GÜLE GÜLE KARŞİM YİNE BEKLERİZ ✅") 
os.exit()
end
while true do
  if gg.isVisible(true) then
PUBGMH = 1
gg.setVisible(false)
  end
if PUBGMH == 1 and CMENU == 0 then
HOME()
  end
  if PUBGMH == 1 and CMENU == 1 then
HOME1()
  end
  if PUBGMH == 1 and CMENU == 2 then
HOME2()
 end
  if PUBGMH == 1 and CMENU == 3 then
HOME3()
  end
end
