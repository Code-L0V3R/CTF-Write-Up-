# Guess Me ( 50 )

Guess a number and get the correct flag .

<a href="Guess Me.exe?raw=true">Down the file here</a>

and just open it!
type numbers <br />So you can see bad boy message box!
<br /><br />
<img src="guess_me.png" />

bad boy message ကို မွတ္ထားပါ။
<br />
ျပီးေတာ့ olly debuger မွာ ဖြင့္လိုက္ပါ။<br />
ျပီးရင္ Search For >> All referenced text strings ကိုေရြးလိုက္ပါ။
<br />
<br />
<img src="olly_start.png" />

ျပီးေတာ့
bad boy message မွာ right click  နိုပ္ ျပီးေတာ့
<br />
follow in Disassembler ကိုနိုပ္ ( သို့မဟုတ္ )
<br />
bad boy message မွာ left click နုိပ္ ျပီးေတာ့
Enter ကိုနိုပ္လိုက္ပါ။

အခုလုိမ်ိုး ျမင္ရပါမယ္ 
<br />
<br />
<img src="tracing.png" />

address 00401585 မွာ password ( number ) မွန္ မမွန္ စစ္တယ္
<br />မမွန္ရင္ 004015B4 address ကို jump သြားလိမ့္မယ္။
ဒါဆိုရင္ 
က်ြန္ေတာ္တို့ က method နွစ္ခုနဲ့ flag ကို ရေအာင္ယူလို့ရတယ္။

1) Serial Fishing<br />
2) Adding Nop Bytes ( change code )
<br />
CTF မွာ ဆိုေတာ့ get flag က အဓိကပဲေလ 
<br />ပထမ နည္းကေတာ့ နည္းနည္းခက္တယ္
<br />ဒုတိယနည္းကေတာ့ လြယ္တယ္။
ဒုတိယနည္းနဲ့ပဲ လုပ္ျပသြားမယ္ <br />


Virutal address 00401588 မွာ right click တစ္ခ်က္နိုပ္ <br />
ျပီးေတာ့ Binary >> Fill with NOPs ကိုေရြးလိုက္ပါ။
ဒါဆို ေအာက္က လိုမ်ိုးေျပာင္းသြားပါလိမ့္မယ္။

<br/><br/>
<img src="patched.png" /><br/>
ျပီးရင္ ေတာ့ F9 နိုပ္ျပီး program ကို run လိုက္ပါ။<br/>
ျကိုက္တဲ့ numbers ကို နိုပ္ျပီး Enter နိုပ္လိုက္ပါ။ <br/>
<a href="flag.txt">Flag </a> ရလာပါလိမ့္မယ္ :D <br/><br/>
<img src="flag.png" />
<br/><br/>
# easy right?
# Thanks For Reading
# Time : 12:39 AM / 27.12.2016
