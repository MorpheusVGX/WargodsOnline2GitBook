# Damage Formula



* Physical = 7000 - ((200 - Strength) \* 10) - Random(0, 500 + (200 - Strength)) + (Round \* 100) + Class Modifier \* 1-(Resistance/100) \* 1.5 (Critical) + Damage Aid
* Mental = 8000 - ((200 - Wisdom) \* 10) - Random(0, 1000 + (200 - Wisdom)) + (Round \* 100) + Class Modifier \* 1-(Resistance/100) \* 1.5 (Critical) + Damage Aid
* Control = 7000 - ((200 - Wisdom) \* 10) - Random(0, 250+ (200 - Wisdom)) + (Round \* 100) + Class Modifier \* 1-(Resistance/100) \* 1.5 (Critical) + Damage Aid
* Range = 8000 - ((200 - Strength) \* 10) - Random(0, 750+ (200 - Strength)) + (Round \* 100) + Class Modifier \* 1-(Resistance/100) \* 1.5 ((Critical) + Damage Aid

Damage = baseDamge - ((200-Stat)\*10 Damage based on stats

\-Random(0,RandomBase+(200-Stat)) Damage based on chance

\+(Round\*100) Additive based on time

\+(B)\*1 Additive based on class

\-(Resistance/100)\*1.5(Random(0,100)>=( BaseCrit+(A)) ? 0:1) Additive based on slim chance

Where (A) = modified crit

Where (B) = Modified Damage
