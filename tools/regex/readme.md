# How-to: Add icons to texts using RegEx

**Step 1.** Open Notepad++

**Step 2.** Use the "Find and Replace"-tool with this code and leave the "Replace with:" area blank. The RegEx will then look for entries that doesn't contain the pre-defined keywords (i.e "Fit", "Hardy" or "Robust") and removes them leaving only the entries you need behind.

### A. Affliction, Inspiration, Defense and Damage keywords

```
(\s+<Entry>\s+<ID>.*?<\/ID>((?!((\b(Constitution|Fit|Hardy|Robust)\b)|((Sicken)(\b|ed|ing))|((Weaken)(\b|s|ed|ing))|((Enfeebl)(\b|ed))|(\b(Resolve|Steadfast|Resolute|Courageous)\b)|((Shaken)(\b|s|ed|ing))|((Frighten)(\b|s|ed|ing))|((Terrif)(\b|ies|ied|ying|y))|(\b(Dexterity|Quick|Nimble|Swift)\b)|((Hobbl)(|ed|es|e|ing)\b)|((Immobiliz)(|ed|e|ing)\b)|((Paralyz)(|ed|es|e|ing|ation))|(\b(Might|Strong|Tenacious|Energized)\b)|((Stagger)(\b|ed|ing))|((Daz)(\b|ed|es|e|ing))|((Stun)(\b|s|ned|ning))|(\b(Intellect|Smart|Acute|Brilliant)\b)|((Confus)(\b|ed|es|e|ing))|((Charm)(\b|ed|ing))|((Dominat)(\b|ed|es|e|ing))|(\b(Perception|Insightful|Aware|Intuitive)\b)|((Distract)(\b|ed|s|ing))|((Disorient)(\b|ed|s|ing))|((Blind)(\b|s|ed|ing|ness))|(\b(Deflection|Reflex|Reflexes|Fortitude|Willpower|Will)\b)|(\b((Shock)(\b|ed|ing))|((Burn)(\b|s|ed|ing))|((Freez)(|es|ed|ing|e))|(Corrode)|(Corrosive)\b)|(\b((Slash)(\b|ing))|((Pierc)(|ing|es))|((Crush)(\b|ing|es))|(Raw)\b)))[0-9a-zA-Z,.&;'"#!-_+ <>\/\s])+?<\/Entry>)
```

### B. Only Afflictions and Inspirations keywords

```
(\s+<Entry>\s+<ID>.*?<\/ID>((?!((\b(Constitution|Fit|Hardy|Robust)\b)|((Sicken)(\b|ed|ing))|((Weaken)(\b|s|ed|ing))|((Enfeebl)(\b|ed))|(\b(Resolve|Steadfast|Resolute|Courageous)\b)|((Shaken)(\b|s|ed|ing))|((Frighten)(\b|s|ed|ing))|((Terrif)(\b|ies|ied|ying|y))|(\b(Dexterity|Quick|Nimble|Swift)\b)|((Hobbl)(|ed|es|e|ing)\b)|((Immobiliz)(|ed|e|ing)\b)|((Paralyz)(|ed|es|e|ing|ation))|(\b(Might|Strong|Tenacious|Energized)\b)|((Stagger)(\b|ed|ing))|((Daz)(\b|ed|es|e|ing))|((Stun)(\b|s|ned|ning))|(\b(Intellect|Smart|Acute|Brilliant)\b)|((Confus)(\b|ed|es|e|ing))|((Charm)(\b|ed|ing))|((Dominat)(\b|ed|es|e|ing))|(\b(Perception|Insightful|Aware|Intuitive)\b)|((Distract)(\b|ed|s|ing))|((Disorient)(\b|ed|s|ing))|((Blind)(\b|s|ed|ing|ness))))[0-9a-zA-Z,.&;'"#!-_+ <>\/\s])+?<\/Entry>)
```


**Step 3.** Use this macro to stylize Inspiration keywords: [RegEx-Inspirations](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/master/tools/regex/RegEx-Inspirations.xml)

**Step 4.** Use this macro to stylize Affliction keywords: [RexEx-Afflictions](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/master/tools/regex/RegEx-Afflictions.xml)

**Step 5.** Use this macro to stylize Attribute keywords: [RegEx-Attributes](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/master/tools/regex/RegEx-Attributes.xml)

**Step 6.** Use this macro to stylize defense and damage keywords: [RegEx-DefenseAndDamage](https://github.com/Xaratas/pillarsofeternity-2-Enhanced-UI/blob/master/tools/regex/RegEx-DefenseAndDamage.xml)
###### (skip this step if you used RegEx B)

And that's it! You've now successfully deleted all unused entry ID's while also applying colors and icons to the specified keywords.
