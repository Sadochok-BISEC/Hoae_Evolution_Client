NAME EffSpark
ICON U_FrnOf17
!STAND 60 0.001 Models\Effects\Weapons\Acid\!acid_blow_01.c2m none
ADDHDIR #STAND 0 0
!MOTION_L 60 0.001 Models\Effects\Weapons\Acid\!acid_blow_01.c2m none
ADDHDIR #MOTION_L 0 0
!ATTACK 15 0.001 Models\Effects\Weapons\Acid\!acid_blow_01.c2m none
ADDHDIR #STAND 0 128
GEOMETRY 1 10 110
LIFE     65000
ATTACK_RADIUS 0 0 60
ATTACK_PAUSE 0 0
CANKILL 3 BODY BUILDING WOOD 
DET_RADIUS 0 0 16000
RECTANGLE 0 2 32 40
MATHERIAL 1 IRON
PRICE 1 FOOD 1
BUILDSTAGES 1
VISION 1
STORMFORCE 30
CANSTORM
UNITRADIUS 24
BREAKANIMATION #STAND
MOTIONSTYLE SINGLESTEP
ROTATE 14
MOVEBREAK #MOTION_L
NOFARM
ABILITY UA_aMagicImmunity
NOALTINFO
NOCOLLISION
CANTCAPTURE
NOTSELECTABLE
MOTIONSTYLE FLY
FLYPARAM 20 20
ABILITY MC_aFireRing_Model
NO_HUNGRY
IMMORTAL
[END]
