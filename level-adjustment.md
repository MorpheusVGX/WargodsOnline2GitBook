# Level Adjustment

After damage/heal is calculated it is then adjusted by the attacker’s effective level. Restrict the result to go no lower than 1.

* (Damage or Heal) / (100 - (level - 1))
