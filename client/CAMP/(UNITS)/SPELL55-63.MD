NAME Spell55-63

ICON U_FrnOf17
ICONEX 0 0 interf3\UnitPortrets\Ranger 0
ICONSET 3 0 0 interf3\UnitPortrets\Ranger1 0 100 1
ICONSET 1 0 0 interf3\UnitPortrets\Ranger2 0 100 1

!STAND          1 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_stand1.C2M
ADDHDIR #STAND 0 128
!REST          60 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_stand1.C2M
ADDHDIR #REST 0 128
!REST          60 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_stand2.C2M
ADDHDIR #REST 0 128
*MOTION_L      1 20 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_walk1.C2M 128 0.0 0.5
/ADDHDIR #MOTION_L 0 128
/!MOTION_L      160 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_run1.C2M
/ADDHDIR #MOTION_L 0 128
/!MOTION_R      80 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_walk1.C2M
/ADDHDIR #MOTION_R 0 128
!MOTION_R      80 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_run1.C2M
ADDHDIR #MOTION_R 0 128
/!MOTION_L0      70 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_run1.C2M
/ADDHDIR #MOTION_L0 0 128
/!MOTION_L1      70 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_run1.C2M
/ADDHDIR #MOTION_L1 0 128
!PSTAND        1  0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_attack1.C2M
ADDHDIR #PSTAND 0 128 
!PATTACK        15  0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_pattack1.C2M
ADDHDIR #PATTACK 0 128
!PATTACK1        15  0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_pattack1.C2M
ADDHDIR #PATTACK 0 128 
*UATTACK      1 1 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_pattack1.C2M 128 1.0 0.0
!ATTACK        25 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_attack1.C2M
ADDHDIR #ATTACK 0 128
/!ATTACK       70 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_spell1.C2M
/ADDHDIR #ATTACK 0 128
/!ATTACK        85 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_spell2.C2M
/ADDHDIR #ATTACK 0 128
!DEATH         35 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_death1.C2M
ADDHDIR #DEATH 0 128
!DEATH         55 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_death2.C2M
ADDHDIR #DEATH 0 128
/!TALK         200 0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_talk1.C2M
/ADDHDIR #TALK 0 128
!CASTPREPARE   50  0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_spell2.C2M
ADDHDIR #CASTPREPARE 0 128
!CASTDIRECT    30  0.25 Models\Units\DruHArc\DruHArcM.C2M Models\Units\DruHArc\DruHArcA_spell2.C2M
ADDHDIR #CASTDIRECT 0 128
BREAKANIMATION #CASTDIRECT
SETHOTFRAME2 #CASTDIRECT 25 20 200 0
SPEEDSCALE 110
GEOMETRY 1 40 60
//ROTATE 32
DAMAGE   0 9
LIFE     300
RECTANGLE 0 0 30 75
ATTACK_RADIUS 0 0 420
ATTACK_PAUSE 0 17
DET_RADIUS 0 0 8000
ADD_ATTACK_RADIUS 0 96
SEARCH_ENEMY_RADIUS 500
MATHERIAL 1 BODY
CANKILL 4 BODY FLY WOOD BUILDING
PRICE 1 FOOD 100
WEAPONKIND 0 piercing
BUILDSTAGES 100
VISION 0
STANDGROUND
WEAPON 0 3d_arrow_hero
VES 30
MOTIONSTYLE SINGLESTEP
SETHOTFRAME2 #ATTACK 5 80 200 0
MOVEBREAK #MOTION_L
BREAKANIMATION #REST
BREAKANIMATION #PSTAND
BREAKANIMATION #STAND
/BREAKANIMATION #PATTACK
/BREAKANIMATION #PATTACK1
/BREAKANIMATION #ATTACK
/BREAKAFTERFRAME #ATTACK 1
ADDSHOTRADIUS 24
PROTECTION 4 chopping 2 magical 0 piercing 3 crushing 3
UNITRADIUS 16
ZPOINTS 40 40
USAGE ARCHER
ARMRADIUS 		2000
ARCHER
RAZBROS 100
SHOWDELAY
FREESHOTDIST 500
CANSTORM
COLLISION 32
SELTYPE SelHero1 1 1
SELSHIFT 0
CANSTORM
VISITORMASK 1
PLACEINTRANSPORT 25
NOCOLLISION
DAMAGEONBUILDINGMULTIPLICATOR 10
COLUMN 6
/FASTCLICK_SOUND building_ready
/SOUND 5 #DEATH death
SOUND 9 #MOTION_L move_humanoids
SOUNDFRAME2 #MOTION_L 19 move_humanoids
EMOTICON Angry Interf3\Emotions_Elhant 0
EMOTICON Defiance Interf3\Emotions_Elhant 1
EMOTICON Despair Interf3\Emotions_Elhant 2
EMOTICON Gladness Interf3\Emotions_Elhant 3
EMOTICON Normal Interf3\Emotions_Elhant 4
EMOTICON Pride Interf3\Emotions_Elhant 5
EMOTICON Sadness Interf3\Emotions_Elhant 6

ABILITY DruidHeroMaxMANA
SOUND 5 #ATTACK arrow_shot
CYLINDER 20 50
EXPA 750
NO_HUNGRY
INCORPOREAL
ABILITY MC_aTreeOfLife
ABILITY MC_aAirSupport
ABILITY MagicCardMagicSemena1
ABILITY MC_aDesease
ABILITY MC_aFairyPowder
ABILITY MagicCardSwarmOfInsects
ABILITY MC_aWordofBanish
ABILITY MC_aCurse
ABILITY MagicCardFear
[END]