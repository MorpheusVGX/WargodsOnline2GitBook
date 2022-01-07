# Aid

### Base Damage Aid <a href="#_s75bskom47h7" id="_s75bskom47h7"></a>

* Physical - 15000
* Mental - 12000
* Range - 12000

### Base Aid Critical <a href="#_wxbxg3c4i7o0" id="_wxbxg3c4i7o0"></a>

* All - 0%

### Aid Formula <a href="#_dyl82a890hqk" id="_dyl82a890hqk"></a>

Aid damage is added to the attack damage before level adjustment calculation

* Physical = 15000 - ((200 - Wisdom) \* 10) - Random(0, 250+ (200 - Wisdom)) + (Round \* 100) \* 1.5 (Critical)
* Mental = 12000 - ((200 - Wisdom) \* 10) - Random(0, 250+ (200 - Wisdom)) + (Round \* 100) \* 1.5 (Critical)
* Range = 12000 - ((200 - Wisdom) \* 10) - Random(0, 250+ (200 - Wisdom)) + (Round \* 100) \* 1.5 (Critical)
