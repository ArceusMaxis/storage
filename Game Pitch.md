# Character sheet
| CODE NAME              | CHARACTER NAME | REFERENCE |
| ---------------------- | -------------- | --------- |
| tech genius            | Meijuan        |     Beat Game      |
| yes-man                | Uzoma          |     Unlock      |
| Supersoldier           | Balaji         |     Unlock      |
| PR officer             | Avarez         |  On 1st run         |
| Biochemist             | Skzzrit        |      Unlock     |
| Moleman                | Sarg. Lance    |   On 1st run        |
| Boomarang Boi/Tomahawk | "Cooper"       |     Hidden      |
| Incurvator             | K.Z.           |      Hidden     |

# Game Loop
Proc-gen world that changes every playthrough. (EtG room-based style)

Game Cycle: 

| No. | Level name     |
| --- | -------------- |
| 1.1 | Dreams         |
| 1.2 | Past           |
| 1.3 | Now            |
| 1.4 | Future         |
| 1.5 | The Repressed  |
| 1.6 | Fear           |
| 1.7 | The Dark Place | 

# Premise
You are a official belonging to a shadow government corp named The Agency. The CEO of this corp is one of your besties, recently due to an attack and some personal issues before that, your friend now lies in a coma. all of modern medicine and shadow medicine have been tried and it appears that she is locked into a battle with herself and her fears. Enter her mind and try to save her, If you lose, we can try again! (loop reasoning)

# Sergeant Lance

## CWO : Chief Weapons Officer
He is a mole person from the under-earth.He is very big.

Sounds: Grunts,Mousy sounds,etc.

## Attributes
| attr  | value |
| ----- | ----- |
| HP    | ++    |
| Speed | -     |
| Weapon Slots      |    2   |
| Ammo Count | 1 |

### Passive Ability
###### Burrow
Temp Invicibility.
No DMG taken.
Time : 3 secs

Goes into the ground by digging fastly, uses the drainage cover on his back to shield himself from foes.

### Epiphany
Burrows into the ground for cover and travels 0-60 meters in given direction.

# Avarez
## PRO : Public Relations Officer 
Brazilian , very chatty , speaks during battle.
Social manipulator and Mastermind.

Sounds: Grunts,Mousy sounds,etc.

## Attributes
| attr        | value   |
| ----------- | ------- |
| HP          | Default |
| Speed       | Default |
| Weapon Slots |2         |
| Ammo Count | 1 |

### Passive Ability
###### Cache Clear/Brainwash
Throws a phone that explodes on contact. Makes enemy into minion. 
Radius of explosion is 1.25 tiles: 20px
Radius of range is 5 tiles: 80px
Cooldown Time : 10 secs

### Epiphany
Throws 3 phones that do the same. (n,e,w three cardinals)
Radius of explosion is 2 tiles: 32px
Cooldown Time : 5 secs

# Balaji
## CUO : Clean-Up & Cover-Up Officer
Indian , quiet , average build , stealth expert.
Wears a Z-CAT suit with Kytrai augments. Red-eye goggle for left eye.

## Attributes
| attr        | value |
| ----------- | ----- |
| HP          | +     |
| Speed       | 0.95 |
| Weapon Slot | 1      |
| Ammo Count | 1 |

### Passive Ability
###### Kytrail Shotgun/rifle
Second weapon for balaji, only one other weapon is allowed.
**Forms:**
- Railgun : Shoots a beam for 2.6 seconds, cant move or stop inbetween
- Shotgun : 3 seconds of shotty, Fire rate is 0.75, charges up to release 3 shots 

Railgun/shotgun **one-shots** non-boss enemies.

### Epiphany
Damage is same, slight pushback whenever you shoot.
- railgun beam : 32px / 2 tiles wide
- Shotgun : 5 shots

# Uzoma
## Assistant CEO
Doesnt know about his atent power :  Obatala's inheritor.
He is an Ugadan dude, very cool, charismatic, but worries about Meijuan very much.
Taller than usual. (About 18-19 pixels)
## Attributes
| attr        | value |
| ----------- | ----- |
| HP          | +     |
| Speed       | Default |
| Weapon Slot | 2     |
| Ammo Count | 1 |

### Passive Ability
###### Kwenda
Phase through enemies. If enemy detected, they take some damage.
Phase range : 1.75 tiles : 28px
Cooldown : 5 secs

### Epiphany
Changes into Obatala's golden armour form for 8 secs. Touch enemies to make em take damage.
Transformation takes 1.5 secs (not immune to damage)
Cant use weaponry in meantime.
Move speed: ++/ 2

# Skzzrit
## MBWO : Medical & Bio-Weaponry Officer
It is a reptilian from hollow earth. More reptile -less human.
little legs, thick tail, green skin, yellow eyes

Sounds: hisses often

## Attributes
| attr        | value   |
| ----------- | ------- |
| HP          | Default |
| Speed       | 1.15    |
| Weapon Slot | 2       |
| Ammo Count | 1 |
| Decoy HP    | 2       | 

### Passive Ability
###### Shedding
Sheds a decoy for once per level ability in exchange for 1 hp
Decoy gets targeted over Skzzrit until death.
Decoy runs in random direction(new direction every 2 secs) for infinite time.
Decoy is a grayish version of Skzzrit.

### Epiphany
**Reptile Brain** , Decoy takes current holding gun, decoy is a fixed turret that shoots one whole mag of ammo. Decoy HP is 3. 
# Meijuan
## CEO : Chief Executive Officer

## Attributes
| attr        | value   |
| ----------- | ------- |
| HP          | -- |
| Speed       | Default |
| Weapon Slots |2         |
| Ammo Count | 1 |

### Passive Ability
###### Confidence
- Unique confidence bar that fills on successful hits on enemies and elims.
- Reduces when no enemy is hit or missed shot.
When confidence bar is filled:
 - heal 1 HP

### Epiphany
- No projectile damage for 1 minute (doesn't carry over to next level)
- Shooting damage increased by 2
- Analog wave fire rate : 
| 0.25 | 2   |
| ---- | --- |
- heal 2 HP
- Timed shots (ROR2 railgunner): instant kill non-boss
- Timed shots (ROR2 railgunner): Do damage for 12.5% of boss HP

# K.Z.
##  ??? : ??????
Japanese, white hair, black glasses,tuxedo, gauntlets

Sounds: Laughs... a lot

## Attributes
| attr        | value   |
| ----------- | ------- |
| HP          | -3 |
| Speed       | Default |
| Weapon Slots |1         |
| Ammo Count | 0.5 |

### Passive Ability
###### Deflection
Deflect projectiles 180 degrees, same speed, same damage
All damage is applied as explosion
Radius of explosion is 2 tiles: 32px
Radius of deflection is 2.5 tiles: 40px
Cooldown Time : 0.75 secs

### Epiphany
Deflection range increased to 4 tiles: 64px
Radius of explosion is 3.5 tiles: 56px
Damage of explosion is 2x

# "Cooper"
##  ??? : ??????
A cave-man diseased by Jovite Crystal Growth on his back.
A possible experiment victim? (i know lore but dont wanna share it lol)

## Attributes
| attr        | value   |
| ----------- | ------- |
| HP          | -5 |
| Speed       | Default |
| Weapon Slots |1         |
| Ammo Count | 0.5 |

### Passive Ability
###### Gaakroteii
Pulls a shard from back and strikes enemy at distance
Stuns enemy for 5 secs
Range of shard : Infinity
Cooldown Time : 1.1 secs
Wind-up time : 0.3 secs

### Epiphany
3 Shards are pulled out, and smashed together to make a boomerang
Throws it to fly in a spiralish path for about 5.5 tiles : 88px
Duration : 8 secs
Cooldown Time: 40 secs
Can still do passive ability at will

##### Comments
Cooper is a mix of both stunner + tomahawk...
idk what to say, needs improvement/refinement a lot?
