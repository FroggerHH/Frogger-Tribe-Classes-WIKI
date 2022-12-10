# Class Settings

###  [🏠To the main page](https://github.com/FroggerHH/Frogger-Tribe-Classes-WIKI#readme)

## ```com.FroggerTribeClasses.LevelTree.json``` 
➡[The default configuration being created](config/com.FroggerTribeClasses.LevelTree.json)


blocks List of ClassInfo elements with class information
  * className - The name of the class, it is not recommended to change. If you want to change the display name of the class, you can create your own localization file and rename its mentions there to your own version.
  * levelTree-  A list of Level Info elements with information about a specific level.
    * level - The level for which bonuses are indicated below.
    * bonuses - A list of characteristics added by this level to the existing ones.
      * enable - Allows you to enable/disable the application of these bonuses to the player without the need to delete from the file. It will soon be removed as unnecessary.
      * Health - The amount of health added.
      * HealthRegeneration - Additional health regeneration.
      * Stamina Количество - Additional stamina.
      * StaminaRegeneration - Additional stamina regeneration.
      * Armor - The number of added armor.
      * Defense - How many percent of the armor will be increased. The armor added to you by the class is taken into account in the calculation.
      * MoveSpeed - By how many percent will the character's movement speed be increased.
      * Vampirism - How much health (number) the player will receive when dealing damage.
      * ChanceToNotTakeDmg - Chance (in %, of course) not to take damage when you are attacked.
      * ChanceToReturnDmg - The chance (in %, of course) to inflict the offender in return Return Dmg damage when he attacks you.
      * ReturnDmg - The amount of damage that will be dealt in response.
      * ChanceToX2Dmg - The chance (in %, of course) that you will deal double damage when attacking.
      * AttackSpeed - Attack speed increases by X% (if -X%, then decreases).
      * MaxCarryWeight - Additional maximum portable weight.
      * DamageMod - *ALL* damage increases by X% (if -X%, then decreases).
      * m_ModifySkill - A list of ModifySkill elements with information about the increased skill. Note, it only works with vanilla skills.
        * skillName - The name of the skill to increase. Just like on [wiki](https://valheim.fandom.com/wiki/Skills), but without spaces.
        * add - How many points will be added.
      * unlockSuper - Will the class aura be unlocked for the player at this level.
  * levelExpModifier - The experience required to obtain each subsequent level will be calculated by multiplying the experience required to obtain the previous level by this number. This is where the First Level Exp from the [main config file](https://github.com/FroggerHH/Frogger-Tribe-Classes-WIKI/blob/main/MainConfig.md) affects.
  * everyLevelBonuses - A list of characteristics added by each level to the existing ones.
  * dualWieldExcludedTypesOfWeapons - A list of weapon types that this class cannot use. Just like on [wiki](https://valheim.fandom.com/wiki/Weapons).
  * dualWieldExclusionCertainItems - A list of weapon types that this class cannot use. Indicators, for example: AxeFlint, KnifeCopper, SwordIron, KnifeBlackMetal, etc..
  * super - Characteristics added to the player when the aura is activated and taken away when it ceases to act.
    * name - The name of the aura, it is not recommended to change. If you want to change the aura's display name, you can create your own localization file and rename its mentions there to your own version.
    * range - The radius in which the members of the group will also receive an aura when it is activated.
    * cooldown - The time between using the aura.
    * time - The duration of the aura.
    * bonuses - Characteristics added by the aura.

* [📒Main config file](https://github.com/FroggerHH/Frogger-Tribe-Classes-WIKI/blob/main/MainConfig.md#main-config-file) 
* [⚙️Mob Settings](https://github.com/FroggerHH/Frogger-Tribe-Classes-WIKI/blob/main/MonstersSettings.md#mob-settings) 
