NAME 			OrcUOrcx2
ICON 			U_FrnOf17
ICONEX 0 0 interf3\UnitPortrets\Orc_back 0
ICONANM 0 0 interf3\UnitPortrets\Orc_back 1 29 1
ICONANM 0 0 interf3\UnitPortrets\Orc 1 1 0
USERLC 			0 G\OrcC SHADOW -91 -116
USERLC 			1 G\OrcG SHADOW -91 -116
USERLC 			3 G\OrcU SHADOW -91 -116
USERLC 			4 G\OrcH SHADOW -91 -116
@REST      		16 0 0 79
#STAND     		16 1 0 0
#PSTAND    		16 1 3 0
@MOTION_L  		16 1 0 19
@ATTACK    		16 3 0 39
@DEATH     		16 4 0 59
@SUMMON     		16 4 59 0 
#DEATHLIE1 		16 1 4 59
GEOMETRY 		1 15 50
LIFE     		75
RECTANGLE 		0 2 32 60
ATTACK_RADIUS 		0 0 70
ATTACK_PAUSE 		0 45
SEARCH_ENEMY_RADIUS 	250
DET_RADIUS 		0 0 7000
MATHERIAL 		1 BODY
CANKILL 3 BODY BUILDING WOOD 
WEAPONKIND 		0 chopping
DAMAGE   		0 7
SETACTIVEPOINT0		#ATTACK 19
BUILDSTAGES 		50
PRICE 			3 FOOD 10 GOLD 5 IRON 50
VISION 			0
STANDGROUND
VES 			30
MOTIONSTYLE 		SINGLESTEP
ROTATE 			16
MOVEBREAK 		#MOTION_L
PROTECTION 		4 piercing 2 magical 0 chopping 2 crushing 2
BREAKANIMATION 		#REST
BREAKANIMATION 		#STAND
MOVEBREAK 		#MOTION_L
EXPA 			50
CANSTORM
COLLISION 18
ADDSHOTRADIUS 18
SELTYPE SelMedium 1 1
KILLERAWARD             GOLD 22
KILLERAWARDRANDOM       GOLD 5
ZPOINTS 25 25
SHADOWLESS
CYLINDER 30 50
TFACTOR FF809480
SOUND 5 #DEATH death_orc
SOUND 19 #ATTACK hit_orcchief
SOUND 10 #MOTION_L move_humanoids
SOUNDFRAME2 #MOTION_L 19 move_humanoids
!TEMP  1 40 models\empty\empty.c2m models\empty\emptya.c2m
ANMEXT #ATTACK #TEMP 0 0 0 1 0
SOUND 16 #TEMP attack_orc
CANTCAPTURE
UNITRADIUS 16
NO_HUNGRY
[END]
