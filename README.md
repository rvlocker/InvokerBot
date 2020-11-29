#Region ;**** Directives created by AutoIt3Wrapper_GUI ****
#AutoIt3Wrapper_Icon=Papirus-Team-Papirus-Apps-Dota-2.ico
#AutoIt3Wrapper_UseX64=n
#AutoIt3Wrapper_Res_Comment=code by rvlocker
#EndRegion ;**** Directives created by AutoIt3Wrapper_GUI ****

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;Code by rvlocker
#include <SendMessage.au3>
#include <MsgBoxConstants.au3>
#include <ButtonConstants.au3>
#include <GUIConstantsEx.au3>
#include <StaticConstants.au3>
#include <WindowsConstants.au3>
HotKeySet("{F1}","_Exit")
HotKeySet("`","_GoldSnap")
HotKeySet("1","_Ghost")
HotKeySet("2","_IceWall")
HotKeySet("3","_Smap")
HotKeySet("z","_Tornado")
HotKeySet("x","_FireMonster")
HotKeySet("c","_RangInkman")
HotKeySet("4","_Atash")


While 1
	Sleep(50)
	WEnd
;;;--->code by rvlocker
;;;--->mrzerooo000ooo000ooo@gmail.com
;;;;---->Power Q W E D F R
;--> Q ---> QUAS  Q+Q+Q+R --->GOLDSNAP ---> ICE
;--> W ---> WEX   Q+Q+W+R --->GHOST ---->HIDE
;--> E ---> EXORT Q+Q+E+R ----> ICEWALL
;--> D --->       W+W+W+R --->SMAP --->PANTER BOMB
;--> F --->       W+W+Q+R --->TORNADO --->GERDBAD
;                 W+W+E+R --->FIREMONSTER
;                 Q+W+E+R --->RANGINKAMAN
;--> R --->  INVOKE --->Spell

Func _Atash()
	Send("{E}{E}{E}{R}")

	EndFunc
Func _GoldSnap()
Send("{Q}{Q}{Q}{R}")		 ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;Send("{Q}{Q}{Q}{R}")  ;                               ;
;Send("{Q}")  ;                               ;
;("{Q}")                                     ; Q+Q+Q+R --->GOLDSNAP ---> ICE ;
;Send("{R}")  ;

EndFunc      ;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
Func _Ghost()


Send("{Q}{Q}{W}{R}")
;Send("{Q}")
;Send("{W}")   ;Q+Q+W+R --->GHOST ---->HIDE
;Send("{R}")

EndFunc
Func _IceWall()

Send("{Q}{Q}{E}{R}")
;Send("{Q}")
;Send("{E}")   ;Q+Q+E+R ----> ICEWALL
;Send("{R}")
EndFunc
Func _Smap()

Send("{W}{W}{W}{R}")
;Send("{W}")    ;W+W+W+R --->SMAP --->PANTER BOMB
;Send("{W}")
;Send("{R}")
EndFunc
Func _Tornado()

Send("{W}{W}{Q}{R}")
;Send("{W}")
;Send("{Q}")    ;W+W+Q+R --->TORNADO --->GERDBAD
;Send("{R}")
EndFunc
Func _FireMonster()

Send("{W}{W}{E}{R}")
;Send("{W}")
;Send("{E}")     ;W+W+E+R --->FIREMONSTER
;Send("{R}")
EndFunc
Func _RangInkman()

Send("{Q}{W}{E}{R}")
;Send("{W}")
;Send("{E}")      ;Q+W+E+R --->RANGINKAMAN
;Send("{R}")
EndFunc

Func _Exit()
	Exit


EndFunc
