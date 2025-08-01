# AsteriskFarsiSounds

# 🎧 Persian Asterisk Sounds | فایل‌های صوتی فارسی برای استریسک

پروژه رسمی VoipIran برای بومی‌سازی حرفه‌ای سیستم‌های تلفنی متن‌باز Asterisk به زبان فارسی

---

##  هدف پروژه چیست؟

ما در تیم [VoipIran](https://voipiran.io) تصمیم گرفتیم یک پکیج کامل و حرفه‌ای از پیام‌های صوتی فارسی برای Asterisk آماده کنیم تا تجربه کاربران فارسی‌زبان در مراکز تماس، صف‌ها، صندوق صوتی و منوهای صوتی به طرز چشم‌گیری ارتقاء یابد.

---

##  ویژگی‌ها

-  ترجمه روان، طبیعی و حرفه‌ای همه پیام‌های مهم سیستم تلفنی
-  دسته‌بندی بر اساس کاربرد: صف تماس، صندوق صوتی، کنفرانس، خطاها، اعداد
-  مناسب برای مراکز تماس فارسی‌زبان، استارتاپ‌ها، سازمان‌ها و توسعه‌دهندگان VoIP
-  طراحی شده برای نصب آسان در مسیر `sounds/fa/`
-  قابلیت توسعه توسط جامعه آزاد


🗂 لیست جامع پیام‌های Asterisk (به جز digits)

filename,english_text,persian_translation
agent-user.gsm,Agent login. Please enter your agent number followed by the pound key.,برای ورود اپراتور، شماره اپراتور خود را وارد و کلید # را فشار دهید.
agent-pass.gsm,Please enter your password followed by the pound key.,لطفاً رمز عبور خود را وارد و کلید # را فشار دهید.
agent-incorrect.gsm,Login incorrect. Please enter your agent number followed by the pound key.,ورود نامعتبر است. لطفاً شماره اپراتور را وارد و کلید # را فشار دهید.
agent-loginok.gsm,Agent logged in.,اپراتور وارد سیستم شد.
agent-loggedoff.gsm,Agent logged off.,اپراتور از سیستم خارج شد.
agent-newlocation.gsm,Please enter a new extension, followed by pound.,لطفاً داخلی جدید را وارد و کلید # را فشار دهید.

queue-youarenext.gsm,Your call is now first in line and will be answered by the next available representative.,تماس شما اکنون نفر اول صف است و به‌زودی توسط نماینده موجود پاسخ داده می‌شود.
queue-thankyou.gsm,Thank you for your patience.,از شکیبایی شما سپاسگزاریم.
queue-thereare.gsm,There are currently,در حال حاضر
queue-callswaiting.gsm,waiting to speak with a representative,تماس در صف انتظار برای صحبت با نماینده هستند.
queue-periodic-announce.gsm,All of our representatives are currently busy. Please stay on the line...,تمامی نمایندگان هم‌اکنون مشغول هستند. لطفاً در خط بمانید...
queue-reporthold.gsm,Hold time,زمان انتظار
queue-holdtime.gsm,The estimated hold time is currently,زمان تقریبی انتظار شما...
queue-minutes.gsm,minutes.,دقیقه است.
queue-seconds.gsm,seconds.,ثانیه است.
queue-less-than.gsm,less than,کمتر از
queue-quantity1.gsm,You are number,شما شماره
queue-if-correct.gsm,If this is correct, press 1.,اگر این صحیح است، عدد یک را فشار دهید.

vm-leavemsg.gsm,Please leave your message after the tone.,لطفاً پس از شنیدن بوق، پیام خود را ضبط کنید.
vm-youhave.gsm,You have,شما
vm-oneold.gsm,one old message.,یک پیام قدیمی دارید.
vm-onenew.gsm,one new message.,یک پیام جدید دارید.
vm-messages.gsm,messages.,پیام
vm-intro.gsm,First, press 1 to listen to your messages.,ابتدا جهت شنیدن پیام‌ها، عدد ۱ را فشار دهید.
vm-opts.gsm,Press 2 to change folders, press 3 for advanced options, press 0 for mailbox options.,برای تغییر پوشه عدد ۲، برای گزینه‌های پیشرفته عدد ۳، برای تنظیمات صندوق عدد ۰ را فشار دهید.
vm-delete.gsm,Press 7 to delete.,برای حذف پیام عدد ۷ را فشار دهید.
vm-replay.gsm,Press 8 to replay.,برای پخش مجدد عدد ۸ را ضربه بزنید.
vm-next.gsm,Press 9 to go to the next message.,برای رفتن به پیام بعد عدد ۹ را فشار دهید.
vm-prev.gsm,Press 4 to go to the previous message.,برای بازگشت به پیام قبلی عدد ۴ را فشار دهید.
vm-passchanged.gsm,Your passwords have been changed.,رمز عبور شما تغییر یافت.
vm-password.gsm,password,رمز عبور
vm-onefor.gsm,Press 1 for,برای انتخاب عدد ۱
vm-num-i-have.gsm,the number I have is,شماره من...

conf-adminmenu.gsm,Please press 1 to mute or unmute yourself, 2 to lock or unlock...,برای بی‌صدا/فعال‌سازی میکروفون عدد ۱، برای قفل/بازکردن کنفرانس عدد ۲...
conf-enteringno.gsm,You are entering conference number,شما به کنفرانس شماره ... وارد می‌شوید.
conf-getchannel.gsm,Please enter the channel number followed by the pound key.,لطفاً شماره کانال را وارد و کلید # را فشار دهید.
conf-getconfno.gsm,Please enter your conference number followed by the pound key.,شماره کنفرانس خود را وارد و کلید # را فشار دهید.
conf-getpin.gsm,Please enter the conference pin number.,رمز کنفرانس را وارد کنید.
conf-hasjoin.gsm,is now in the conference.,هم‌اکنون در کنفرانس حضور دارد.
conf-hasleft.gsm,has left the conference.,کنفرانس را ترک کرد.
conf-kicked.gsm,You have been kicked from this conference.,شما از این کنفرانس حذف شدید.
conf-start.gsm,The conference will now begin.,کنفرانس اکنون شروع می‌شود.
conf-end.gsm,The conference has ended.,کنفرانس پایان یافت.
conf-muted.gsm,You are now muted.,میکروفون شما بی‌صدا شد.
conf-unmuted.gsm,You are now unmuted.,میکروفون شما فعال شد.
conf-onlyone.gsm,You are currently the only person in this conference.,در حال حاضر تنها فرد حاضر هستید.
conf-otherinparty.gsm,There is currently one other participant in the conference.,یک شرکت‌کننده دیگر نیز حضور دارد.
conf-invalid.gsm,Invalid choice.,انتخاب نامعتبر است.

invalid.gsm,I'm sorry, that's not a valid extension.,متأسفم، این داخلی معتبر نیست.
no-service.gsm,That service is not available.,این سرویس در حال حاضر در دسترس نیست.
privacy-unident.gsm,Sorry, we do not accept calls from anonymous numbers.,متأسفیم، تماس‌های ناشناس پذیرفته نمی‌شوند.
ss-noservice.gsm,The number you have dialed is not in service. Please check the number and try again.,شماره‌ای که تماس گرفته‌اید در سرویس نیست. لطفاً مجدداً بررسی و تلاش کنید.
call-forwarding.gsm,The extension is set to forward your call.,این داخلی به شماره دیگری منتقل شده است.
please-try-again.gsm,Please try again later.,لطفاً بعداً دوباره تلاش کنید.
after-the-tone.gsm,After the tone, please say your name.,پس از شنیدن بوق، نام خود را بگویید.
your-call-is-important.gsm,Your call is important to us.,تماس شما برای ما ارزشمند است.
hold-please.gsm,Please hold.,لطفاً منتظر بمانید.
thank-you-for-calling.gsm,Thank you for calling.,از تماس شما سپاسگزاریم.
goodbye.gsm,Goodbye.,خداحافظ.
sorry.gsm,I'm sorry.,متأسفم.
all-circuits-busy-now.gsm,All circuits are busy now.,همه خطوط در حال حاضر مشغول هستند.
that-was-an-invalid.gsm,That was an invalid entry.,ورودی نامعتبر بود.




🔢 لیست اعداد، روزهای هفته و ماه‌ها برای copy/paste

filename,english_text,persian_translation
digits/0.gsm,zero,صفر
digits/1.gsm,one,یک
digits/2.gsm,two,دو
digits/3.gsm,three,سه
digits/4.gsm,four,چهار
digits/5.gsm,five,پنج
digits/6.gsm,six,شش
digits/7.gsm,seven,هفت
digits/8.gsm,eight,هشت
digits/9.gsm,nine,نه
digits/10.gsm,ten,ده
digits/11.gsm,eleven,یازده
digits/12.gsm,twelve,دوازده
digits/13.gsm,thirteen,سیزده
digits/14.gsm,fourteen,چهارده
digits/15.gsm,fifteen,پانزده
digits/16.gsm,sixteen,شانزده
digits/17.gsm,seventeen,هفده
digits/18.gsm,eighteen,هجده
digits/19.gsm,nineteen,نوزده
digits/20.gsm,twenty,بیست
digits/30.gsm,thirty,سی
digits/40.gsm,forty,چهل
digits/50.gsm,fifty,پنجاه
digits/60.gsm,sixty,شصت
digits/70.gsm,seventy,هفتاد
digits/80.gsm,eighty,هشتاد
digits/90.gsm,ninety,نود
digits/hundred.gsm,hundred,صد
digits/thousand.gsm,thousand,هزار
digits/day-0.gsm,Sunday,یک‌شنبه
digits/day-1.gsm,Monday,دوشنبه
digits/day-2.gsm,Tuesday,سه‌شنبه
digits/day-3.gsm,Wednesday,چهارشنبه
digits/day-4.gsm,Thursday,پنج‌شنبه
digits/day-5.gsm,Friday,جمعه
digits/day-6.gsm,Saturday,شنبه
digits/mon-0.gsm,January,فروردین
digits/mon-1.gsm,February,اردیبهشت
digits/mon-2.gsm,March,خرداد
digits/mon-3.gsm,April,تیر
digits/mon-4.gsm,May,مرداد
digits/mon-5.gsm,June,شهریور
digits/mon-6.gsm,July,مهر
digits/mon-7.gsm,August,آبان
digits/mon-8.gsm,September,آذر
digits/mon-9.gsm,October,دی
digits/mon-10.gsm,November,بهمن
digits/mon-11.gsm,December,اسفند
