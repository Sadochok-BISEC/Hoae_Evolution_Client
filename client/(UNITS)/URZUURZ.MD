NAME                    UrzUUrz
ICON 			U_FrnOf17
ICONEX 0 0 interf3\UnitPortrets\Ursa_back 0
ICONANM 0 0 interf3\UnitPortrets\Ursa_back 1 35 1
ICONANM 0 0 interf3\UnitPortrets\Ursa 1 1 0
USERLC 			0 G\UrsC SHADOW -123 -145
USERLC 			1 G\UrsG SHADOW -123 -145
USERLC 			3 G\UrsU SHADOW -123 -145
USERLC 			4 G\UrsH SHADOW -123 -145
@REST      		16 0 0 59
#STAND     		16 1 0 0
#PSTAND    		16 1 3 0
@MOTION_L  		16 1 0 19
@ATTACK    		16 3 0 39
@DEATH     		16 4 0 40
@SUMMON     		16 4 40 0 
#DEATHLIE1 		16 1 4 40
GEOMETRY 		1 15 35
LIFE     		200
PROTECTION 		3 piercing 3 crushing 2 magical 4
RECTANGLE 		0 2 32 65
ATTACK_RADIUS 		0 0 60
ATTACK_PAUSE 		0 0
ADD_ATTACK_RADIUS 	0 64
SEARCH_ENEMY_RADIUS 	250
DET_RADIUS 		0 0 7000
MATHERIAL 		1 BODY
CANKILL 3 BODY BUILDING WOOD
WEAPONKIND 		0 crushing
DAMAGE   		0 15
SETACTIVEPOINT0		#ATTACK 14
BUILDSTAGES 		220
VISION 			0
STANDGROUND
VES 			30
MOTIONSTYLE 		SINGLESTEP
ROTATE 			16
BREAKANIMATION 		#REST
BREAKANIMATION 		#STAND
MOVEBREAK 		#MOTION_L
EXPA 			90
ZPOINTS	32 32
CANSTORM
COLLISION 24
ADDSHOTRADIUS 24
SELTYPE SelMedium 1 1
KILLERAWARD             GOLD 40
KILLERAWARDRANDOM       GOLD 10
SHADOWLESS
CANTCAPTURE
CYLINDER 20 45
NOFARM
TFACTOR FF8E8E62
CANTCAPTURE
UNITRADIUS 16
NO_HUNGRY
SOUND 5 #DEATH death_urza
SOUND 14 #MOTION_L move_humanoids
SOUNDFRAME2 #MOTION_L 29 move_humanoids
SOUND 14 #ATTACK attack_dubina
SOUNDFRAME2 #ATTACK 30
!TEMP  1 40 models\empty\empty.c2m models\empty\emptya.c2m
ANMEXT #ATTACK #TEMP 0 0 0 1 0
SOUND 16 #TEMP attack_urza
ShadowScaleX 1.5
ShadowScaleY 1.5
NIKAKIXMAM
[END]
