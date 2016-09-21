Dishonored Ultimate Difficulty Mod: Witches of Brigmore ver 0.04 JDV, Aug 2013
------------------------------------------------------------------------------

The aim of this mod is to stay true to the original game while forcing creativity. The goal is to make the game significantly more challenging while not modifying the health of any character, as the relative fragility of the characters is an important aspect of the Dishonored universe. My hope is that you will be pushed to your limit, combining your physical & magical attacks with stealth in suprising ways in order to survive this punishing world. There is no shame in hiding.

**Installation**

Overwrite the files found in

    %userdirectory%/My Documents/My Games/Dishonored/DishonoredGame/Config

with the files found in the download link below. Ensure the .ini files are read-only, or the game will overwrite these new settings with game defaults. I designed this on "very hard" difficulty, so you should perhaps make sure your game is set to "very hard" as well. Please be sure to backup your config folder before you make any changes!!!

**Stealth: Harder, but Required**

1. Enemies are more alert and persistant.
2. You make more noise and are easier to see.
3. You can no longer lean like a boss.
4. Sleep darts take 10 seconds to work without upgrades.

**Magic & Abilities: Encourage Specialization**

1. Abilities are now considerably more expensive.

**Combat: More Risky**

1. The world no longer stops for you during combat (except during assassinations. This causes problems if a target gets involved in a brawl.)
2. Enemies wait less time inbetween attacks & blocks.
3. Offscreen damage is now equal to onscreen damage.
4. You can be stunned for longer.
5. Enemies attack in greater numbers.
6. Guns no longer have any spread damage.
7. Windblast no longer causes any direct damage.

**Graphics: Cleaner**

1. Bodies pile up
2. No intro movies
3. Removed texture pop-in

**Thanks for your contributions: ZippyDSMlee, Phoenixedd, Mr.Bueno**

**Special thanks to Northon of TTLG, creator of the Thief 1/Gold Ultimate Difficulty Mod, which serves as a spiritual predecessor for this attempt.**



Changelog: My Documents Folder ("Dishonored")
---------------------------------------------

**AI.ini**

	[DishonoredGame.DishonoredGlobalAIManager]
	m_bCorpseCleanupInView=True --> False
	m_BullyCooldownPeriod=(m_fMinValue=3 --> 6, m_fMaxValue=8 --> 12)
	m_CorpseAbsoluteMaximumCount=10 --> 50
	m_CorpseIdealMaximumCount=5 --> 45
	m_fGroupDistance=1000 --> 2000
	m_fUpdateTime=1 --> 100
	m_ReactionDelay=(m_fMinValue=0.18 --> 0.12,m_fMaxValue=0.30 --> 0.20)
	m_TetherDelay=(m_fMinValue=6 --> 3, m_fMaxValue=8 --> 6)

	[DishonoredGame.DishonoredSearchCrumbsComponent]
	m_fChanceOfPsychicSearch=0.25 --> 0.75
	m_fCrumbLifetime=150 --> 150
	m_fDistanceBetweenCrumbs=800 --> 1200
	m_fMaxWanderStep=1000 --> 1500
	m_fMinWanderStep=500 --> 750
	m_fStickyProxyDuration=1 --> 2
	m_fWanderAngularRange=60 --> 75
	m_iNumSearchCrumbs=25 --> 50

	[DishonoredGame.DisAINoiseManager]
	m_LoudnessDistanceArray=0.000000
	m_LoudnessDistanceArray=200 --> 400
	m_LoudnessDistanceArray=300 --> 600
	m_LoudnessDistanceArray=400 --> 800
	m_LoudnessDistanceArray=500 --> 1000
	m_LoudnessDistanceArray=600 --> 1200
	m_LoudnessDistanceArray=800 --> 1600
	m_LoudnessDistanceArray=1000 --> 2000
	m_LoudnessDistanceArray=1200 --> 2400
	m_LoudnessDistanceArray=1500 --> 3000
	m_LoudnessDistanceArray=2000 --> 4000
	m_LoudnessDistanceArray=2500 --> 5000
	m_LoudnessDistanceArray=3000 --> 6000
	m_LoudnessDistanceArray=4000 --> 8000
	m_LoudnessDistanceArray=5000 --> 10000
	m_LoudnessDistanceArray=6000 --> 12000
	m_LoudnessDistanceArray=0.000000

	[DishonoredGame.DisGlobalCombatManager]
	m_fInhibitionTimeAttractSpell=15 --> 7.5
	m_fInhibitionTimeBackStep=8 --> 4
	m_fInhibitionTimeGrenades=10 --> 5
	m_fInhibitionTimeGrenadesWhenUnreachable=5 --> 2.5
	m_fInhibitionTimeJumpAttack=3.0 --> 1.5
	m_fInhibitionTimeLongAttack=0.8 --> 0.4
	m_fInhibitionTimeMediumAttack=1 --> 0.5
	m_fInhibitionTimeShortAttack=2 --> 1
	m_fInhibitionTimeSideStep=6 --> 3
	m_fInhibitionTimeStepBackAttack=1 --> 0.5
	m_fInhibitionTimeTeleportSpell=10 --> 5
	m_fInhibitionTimeThrowRocks=5 --> 2.5
	m_fInhibitionTimeWeeperArmGrab=20 --> 10
	m_fInhibitionTimeWHArmAttack=8 --> 4
	m_fInhibitionTimeWHJumpAttack=30 --> 15

	m_InnerSkirmishCaps[0]=1 --> 2
	m_InnerSkirmishCaps[1]=2 --> 3
	m_InnerSkirmishCaps[2]=3 --> 5
	m_InnerSkirmishCaps[3]=3 --> 6
	m_TotalSkirmishCaps[0]=2 --> 4
	m_TotalSkirmishCaps[1]=3 --> 6
	m_TotalSkirmishCaps[2]=4 --> 7
	m_TotalSkirmishCaps[3]=4 --> 8

**Camera.ini**

	[DishonoredGame.DishonoredCamera_Lean]
	m_fMaxLeanAngle=15 --> 4
	m_fMaxLeanAngle_Crouched=15 --> 4
	m_fMaxLeanSoftenAngle= 4 --> 2
	m_fMaxLeanSoftenSpeed= 4 --> 2

**Engine.ini**

	[FullScreenMovie]
	bForceNoStartupMovies=false --> true

**Player.ini**

	[DishonoredGame.DishonoredPlayerPawn]
	m_fVisRegionTopHeight_Crouched=40.000000 --> 100
	m_fOffscreenMeleeDamageReduction[0]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[1]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[2]=0.5 --> 0
	m_fOffscreenMeleeDamageReduction[3]=0.5 --> 0

	[DishonoredGame.DisThreatPerceptionComponent]
	m_fEngagedThreatRadius=700 --> 3000
	m_fThreatPredictionTime=1 --> 0.25
	m_fUnawareThreatRadius=400 --> 2000

	[DishonoredGame.DishonoredPowersComponent]
	m_Powers=(m_Name="Vitality",m_eUISelection=eDisUISelectionType_Vitality,        m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=1 --> 6,m_Modifiers=((m_AttributeName="Attribute_HealthMax",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20))),(m_RuneCost=3-->4,m_Modifiers=((m_AttributeName="Attribute_HealthMax",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20.000000),(m_AttributeName="Attribute_HealthRegenLimit",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=20.000000),(m_AttributeName="Attribute_HealthRegenInitialDelay",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=5.000000)))),m_CurrentLevel=-1)
	m_Powers=(m_Name="BloodThirsty",m_eUISelection=eDisUISelectionType_BloodThirsty,m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=),(m_RuneCost=3 --> 4,m_Modifiers=((m_AttributeName="Attribute_AdrenalineMax",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=-20.000000)))),m_CurrentLevel=-1)
	m_Powers=(m_Name="ShadowKill",m_eUISelection=eDisUISelectionType_ShadowKill,    m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=),(m_RuneCost=3 --> 4,m_Modifiers=)),m_CurrentLevel=-1)
	m_Powers=(m_Name="Celerity",m_eUISelection=eDisUISelectionType_Celerity,        m_Levels=((m_RuneCost=0,m_Modifiers=), (m_RuneCost=2 --> 6,m_Modifiers=((m_AttributeName="Attribute_JumpZ_PowerJump",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1300),(m_AttributeName="Attribute_PowerJumpFullStop_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=1000),(m_AttributeName="Attribute_FullStop_ExtraStopVel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=500.000000),(m_AttributeName="Attribute_HeldPowerJumpButtonTime_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_HeldPowerJumpAccel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=1800),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDamage",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=2550.000000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDeath",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3500.000000))),(m_RuneCost=3 --> 4,m_Modifiers=((m_AttributeName="Attribute_JumpZ_PowerJump",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1300.000000),(m_AttributeName="Attribute_PowerJumpFullStop_PROTOTYPE",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=1500.000000),(m_AttributeName="Attribute_FullStop_ExtraStopVel_PROTOTYPE",m_ModType=eDisAttributeModifierType_AddVal,m_fModValue=500.000000),(m_AttributeName="Attribute_HeldPowerJumpButtonTime_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_HeldPowerJumpAccel_PROTOTYPE",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3000.000000),(m_AttributeName="Attribute_WaterSpeed",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=10.000000),(m_AttributeName="Attribute_GroundSpeedSprint",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=30.000000),(m_AttributeName="Attribute_LandAnimRate",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=50.000000),(m_AttributeName="Attribute_MantleAnimRate",m_ModType=eDisAttributeModifierType_AddBasePercent,m_fModValue=50.000000),(m_AttributeName="Attribute_GroundStrafeMultiplierSprint",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.500000),(m_AttributeName="Attribute_GroundBackwardMultiplierSprint",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=0.400000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDamage",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=2550.000000),(m_AttributeName="Attribute_MaxSpeedBeforeFallingDeath",m_ModType=eDisAttributeModifierType_SetVal,m_fModValue=3500.000000)))),m_CurrentLevel=-1)

**PlayerState.ini**

	[DishonoredGame.StatePlayerMasterLeaning]
	m_fLeanReleaseTime=0.2 --> 0.4
	m_fLeanSpeed=1000 --> 750
	m_fMaxAllowedPitchDegrees=35 --> 45
	m_fMaxAllowedYawDegrees=60
	m_fMinAllowedPitchDegrees=-35 --> -45
	m_fMinAllowedYawDegrees=-60

	[DishonoredGame.StatePlayerMasterStunned]
	m_fStunDuration=0.1 --> 0.4
	m_bAllowIncomingAttacks=False --> True

	[DishonoredGame.StatePlayerMasterChoice_Base]
	m_bAllowIncomingAttacks=False --> True
	m_bAllowExplosionsFromPlayer=False --> True

	[DishonoredGame.StatePlayerMasterVersus]
	m_bAllowIncomingAttacks=False --> True

	[DishonoredGame.StatePlayerMasterMinigame]
	m_bAllowIncomingAttacks=False --> True

**Weapon.ini**

	[DishonoredGame.DishonoredDamageType_BulletBlast]
	m_bDisableHitReaction=True \\ added
	m_bCannotKillNPC=True \\ added
	m_bInstaDeath_NonPlayerToNPC=True --> False
	m_ExpectedHitReaction=eDisPawnHitReactionType_Strong --> None

	[DishonoredGame.DishonoredDamageType_Bullet]
	m_ExpectedHitReaction=eDisPawnHitReactionType_Knockdown --> None
	m_bInstaDeath_NonPlayerToNPC=True --> False

	[DishonoredGame.DishonoredDamageType_BulletMedium]
	m_bInstaDeath_NonPlayerToNPC=True --> False

	[DishonoredGame.DisDamageType_PostPossessSleep]
	m_fTimeBeforeSleep=0 --> 7.5

	[DishonoredGameContent.DisDamageType_Arrow_Sleep]
	m_bInstantSleepForUnawareNPCs=True --> False
	m_fTimeBeforeSleep=1.500000 --> 7.5

	[DishonoredGame.DisDamageType_SpringRazor]
	m_bApplyDamageReduction=False \\ added

	[DishonoredGame.DisDamageType_SpringRazorPlaced]
	m_bApplyDamageReduction=False \\ added

	[DishonoredGame.DisDamageType_WindBlast]
	m_bCannotKillNPC=True \\ added

**spell price overview: (total runes = 39, total cost = 58 --> 78):**

    blink1          = 0
    blink2          = 3
    posession1      = 3
    posession2      = 5
    bendTime1       = 2
    bendTime2       = 8
    devouringSwarm1 = 3
    devouringSwarm2 = 4
    windBlast1      = 3
    windBlast2      = 4
    darkVision1     = 1
    darkVision2     = 2
     -- total       = 38

    vitality1       = 1 --> 6
    vitality2       = 3 --> 4
    bloodThirsty1   = 2 --> 6
    bloodThirsty2   = 3 --> 4
    agility1        = 2 --> 6
    agility2        = 3 --> 4
    shadowKill1     = 2 --> 6
    shadowKill2     = 4 --> 4
    -- total        = 40

