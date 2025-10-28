# StepMania AMX: Lua support

## Tier 1: PEngine

These Luas may replicate features from PEngine (ex. Red Swan), the expectation is that these Luas are trivial to support.

As an aside, double-check the NX20 files, as we may want to support those features natively.

```
02 - S.E.~EXTRA/(4) 405 - Mr. Larpus
04 - EXCEED~ZERO/(1) C02A - Moonlight (Original Ver.)
04 - EXCEED~ZERO/(1) C03 - Witch Doctor
05 - NX~NX2/(1) E13 - Pumptris Quattro
08 - FIESTA/1025 - Hello William
09 - FIESTA EX/1150 - Hot issue (Alternate Version)
12 - PRIME/1421 - Red Swan
12 - PRIME/1473 - Reminiscence
12 - PRIME/1490 - Prime
13 - PRIME 2/1536 - Twist of Fate (feat. Ruriling)
```

## Tier 2: Unity Engine

No research has been done for the Unity Engine, the expectation is that these Luas are also used to imitate features from the Unity Engine and should be trivial to support.

```
14 - XX/1603 - Obliteration
14 - XX/1635 - Tantanmen
14 - XX/1669 - Indestructible
14 - XX/1686 - Rising Star
14 - XX/16A4 - Forgotten Vampire
14 - XX/16D4 - [Remix] Prime Time
14 - XX/16D5 - [Remix] Fire Noodle Challenge
14 - XX/16E8 - [Full Song] GOOD BYE
14 - XX/16F7 - [Full Song] 8 6
16 - PHOENIX/1720 - Dancing
16 - PHOENIX/18015 - BOOOM!!
16 - PHOENIX/18042 - Simon Says, EURODANCE!! (feat. Sara M)
16 - PHOENIX/18048 - Appassionata
16 - PHOENIX/18048.5 - Super Akuma Emperor
16 - PHOENIX/18049 - Curiosity Overdrive
16 - PHOENIX/18049.5 - MEGAHEARTZ
16 - PHOENIX/18080 - Queencard
16 - PHOENIX/18215 - MilK
16 - PHOENIX/18236 - Alice in Misanthrope
16 - PHOENIX/18237 - R.I.P
16 - PHOENIX/18238.7.1 - this game does not exist
16 - PHOENIX/18242 - Destr0yer
16 - PHOENIX/18A40 - Hymn of Golden Glory
16 - PHOENIX/18F81 - [Short Cut] DUEL
```

## Tier 3: StepMania 4+

Some of these Luas (ex. Pink Fuzzy Bunnies) add simple eye candy. But some of these Luas (ex. Mawaru Infinity) may use too many APIs from StepMania 5, we're looking for the path of least resistance between:

- Reject the SSC files and do not display them in SSM
- Graceful Degradation (ex. disable the Lua scripts)
- Feature Parity (only if this is low effort)

```
07 - PRO~PRO2/(1) PE353 - Pink Fuzzy Bunnies
11 - INFINITY/INx02 - Black Maria
11 - INFINITY/INx20 - Extravaganza Reborn
11 - INFINITY/INx37 - Nervous
11 - INFINITY/INx52 - The Trident ov Power
11 - INFINITY/INx54 - Venetian Stacatto
11 - INFINITY/INx55 - VV
11 - INFINITY/INx61 - [Remix] Mawaru Infinity
11 - INFINITY/INxMT [Attack of the MiNi-MiXES]
```
