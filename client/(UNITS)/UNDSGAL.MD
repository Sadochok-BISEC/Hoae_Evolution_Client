NAME UndSGal
ICON U_FrnOf17
ICONEX 0 0 interf3\UnitPortrets\UndSGal 0
ICONANM 0 0 interf3\UnitPortrets\UndSGal 1 72 1
MEDIA WATER
MOTIONSTYLE SHEEPS  
!STAND   100 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #STAND 1 128
SOUND 255 #STAND move_ship
!PSTAND   1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #PSTAND 1 128
!ATTACK   1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #ATTACK 1 128
*DEATH   2 160 0.35 Models\Ships\UnsSSh3M_death1.C2M Models\Ships\UnsSSh3A_death1.C2M 0 0.0 1.0 1000 0.35 Models\Ships\UnsSSh3M_death1.C2M Models\Ships\UnsSSh3A_death1.C2M 0 1.0 1.0
ADDHDIR #DEATH 1 128 
SOUND 5 #DEATH death_ship
!BUILDLO_0 1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #BUILDLO_0 1 128
!BUILDLO_1 1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #BUILDLO_1 1 128
!BUILDLO_2 1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #BUILDLO_2 1 128
!BUILDLO_3 1 0.35   Models\Ships\UnsSSh3M.C2M Models\Ships\UnsSSh3A_stand1.C2M
ADDHDIR #BUILDLO_3 1 128
LOCATION -1 -1 1000 1000
GEOMETRY 1 80 40
LIFE     600
PRICE 2 IRON 300 GOLD 300 
MATHERIAL 1 IRON
RECTANGLE 0 30 160 120
ZPOINTS   60 60
BUILDSTAGES 500
VISION 8
NO25
ROTATE 12
EXPLMEDIA BOAT 100
DAMAGE   0 50
WEAPONKIND 0 magical
ATTACK_RADIUS 0 0 800
ATTACK_PAUSE 0 50
DET_RADIUS 0 0 8000
ADD_ATTACK_RADIUS 0 64
SEARCH_ENEMY_RADIUS 800
PROTECTION 4 chopping 0 magical 0 piercing 0 crushing 0
CANKILL   5 BODY WOOD BUILDING FLY IRON
SHOWDELAY
BREAKANIMATION #STAND
BREAKANIMATION #ATTACK
MAXINDEPO 10 1
ABILITY UndTurret201
ABILITY	UA_aMagicImmunity
CANTCAPTURE
CYLINDER 110 50
SELTYPE SelShip 5 3
NOFARM
NO_HUNGRY
FORMFACTOR 652
TFACTOR FF707070
DAMAGEONBUILDINGMULTIPLICATOR 5
ABILITY sled_na_vode
[END]
