# How-to: Add icons to texts using RegEx

Open Notepad++ 
Use Search and Replace with this code and replace it with [nothing]:
**Click the "Details" text to see the code**

<Details>
(\s+<Entry>\s+<ID>.*?<\/ID>((?!((\b(Constitution|Fit|Hardy|Robust)\b)|((Sicken)(\b|ed|ing))|((Weaken)(\b|s|ed|ing))|((Enfeebl)(\b|ed))|(\b(Resolve|Steadfast|Resolute|Courageous)\b)|((Shaken)(\b|s|ed|ing))|((Frighten)(\b|s|ed|ing))|((Terrif)(\b|ies|ied|ying|y))|(\b(Dexterity|Quick|Nimble|Swift)\b)|((Hobbl)(|ed|es|e|ing)\b)|((Immobiliz)(|ed|e|ing)\b)|((Paralyz)(|ed|es|e|ing|ation))|(\b(Might|Strong|Tenacious|Energized)\b)|((Stagger)(\b|ed|ing))|((Daz)(\b|ed|es|e|ing))|((Stun)(\b|s|ned|ning))|(\b(Intellect|Smart|Acute|Brilliant)\b)|((Confus)(\b|ed|es|e|ing))|((Charm)(\b|ed|ing))|((Dominat)(\b|ed|es|e|ing))|(\b(Perception|Insightful|Aware|Intuitive)\b)|((Distract)(\b|ed|s|ing))|((Disorient)(\b|ed|s|ing))|((Blind)(\b|s|ed|ing|ness))|(\b(Deflection|Reflex|Reflexes|Fortitude|Willpower|Will)\b)|(\b((Shock)(\b|ed|ing))|((Burn)(\b|s|ed|ing))|((Freez)(|es|ed|ing|e))|(Corrode)|(Corrosive)\b)|(\b((Slash)(\b|ing))|((Pierc)(|ing|es))|((Crush)(\b|ing|es))|(Raw)\b)))[0-9a-zA-Z,.&;'"#!-_+ <>\/\s])+?<\/Entry>)
</Details>


You now have all Entries with the keywords above isolated in your abilities.stringtable file.

Use this macro in Notepad++ to add colors and icons to Inspiration keywords:
**Click the "Details" text to see the code**

<Details>
<Macro name="RegEx-Inspirations" Ctrl="no" Alt="no" Shift="no" Key="0">
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Fit" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://2370256c-67fe-4481-bfae-9081b2dc10d3&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Fit&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Hardy" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://fd4d0c5c-f525-4010-99dc-f30a59b2f729&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Hardy&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Robust" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://86f9c246-c37c-46a6-8838-7dc36c18e08d&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Robust&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Quick" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://a0b4a490-2c99-456e-b6fb-131353133fba&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Quick&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Nimble" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://0451672b-af45-4b44-96b4-ff2c1b6aa1d3&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Nimble&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Swift" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://1418c0ae-790d-4aef-9ca6-00238012c84e&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Swift&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Smart" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://0435c12c-8049-4f50-b234-ed3cca340696&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Smart&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Acute" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://c4ada862-ee17-4c10-8967-734e08daa4aa&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Acute&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Brilliant" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://dee61b5a-6313-4406-ab83-4fb72b37cea2&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Brilliant&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Strong" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://79b41b80-d3c4-4176-a44b-69490efa41a8&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Strong&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Tenacious" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://93eb382a-dc8e-469b-a116-4686c73e1eb5&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Tenacious&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Energized" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://c56f70b5-b611-4dee-b80f-335033b98e2f&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Energized&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Insightful" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://412f8f5e-d257-4c52-ac66-0e49fd603ef2&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Insightful&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Aware" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://a64e1484-5867-4112-843c-06da3be5399b&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Aware&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Intuitive" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://c2fb23c5-9907-4654-b62e-77adbc37c9bc&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Intuitive&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Steadfast" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://92d1a280-2f8e-4a6d-87a9-6599d41d65e4&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Steadfast&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Resolute" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://51e1cbfc-506b-4e7c-880e-b89312a4b4c3&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolute&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="Courageous" />
            <Action type="3" message="1625" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://dc62af47-239f-4ee4-8d91-a5e8b3b97564&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Courageous&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="771" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
</Macro>
</Details>

---

Use this macro in Notepad++ to add colors and icons to Affliction keywords:
**Click the "Details" text to see the code**

<Details>
<Macro name="RegEx-Afflictions" Ctrl="no" Alt="no" Shift="no" Key="0">
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Sicken)(\b|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://1e99c141-5288-4bf0-abc2-65cc78638745&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Weaken)(\b|s|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://a6368675-47ed-460d-be4f-2593f24ad126&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Enfeebl)(\b|ed)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://fe0997e7-422f-4d1d-b9f6-241946fbd1f1&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Hobbl)(\b|ed|es|e|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://c1d82f88-4f54-4279-8e72-43104bf754a2&quot;&amp;gt;&amp;lt;#72da26&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Immobiliz)(\b|ed|e|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://a31fdd6c-5f4f-404d-92f5-5d7d8c166f2c&quot;&amp;gt;&amp;lt;#72da26&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Paralyz)(\b|ed|es|e|ing|ation)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://72de641d-d2f1-47ca-85f2-6ec3e41140bd&quot;&amp;gt;&amp;lt;#72da26&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Confus)(\b|ed|es|e|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://917ea7e5-133c-4163-93c6-55c7d55420a4&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Charm)(\b|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://f4a09726-a62d-49a2-8cc6-c3713676c833&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Dominat)(\b|ed|es|e|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://9e773415-4d95-4be6-ab87-325d9815e0d7&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Stagger)(\b|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://67f6a58b-658e-4c97-b0a2-5d53067dcbd8&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Daz)(\b|ed|es|e|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://3a790bc4-40a9-4d9f-8da8-a76f3cb6c5e1&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Stun)(\b|s|ned|ning)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://fc2d1039-c512-484a-81e8-a843ba03df4e&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Distract)(\b|ed|s|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://919bddc8-1e05-412b-bb5c-8272545b28f0&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Disorient)(\b|ed|s|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://1021cac0-2d10-4f0d-93e3-e1b0ce24f9fd&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Blind)(\b|ed|s|ing|ness)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://76a5e15a-e75c-4853-889b-2e9229d46444&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Shaken)(\b|s|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://8f4832b6-49ef-4f40-9d64-20eb50fd9bb6&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Shaken&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#185;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Frighten)(\b|s|ed|ing)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://d9e00789-14d3-46f1-be3e-4c1379148d24&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#178;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Terrif)(\b|ies|ied|ying|y)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;gamedata://0d89a32d-c883-4a18-9fbd-4ff58f1fd0de&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam='(Confounding &amp;lt;link=&quot;gamedata://76a5e15a-e75c-4853-889b-2e9229d46444&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Blind&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;#179;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;)' />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="(Confounding Blind)" />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
</Macro>
</Details>

---

Use this macro in Notepad++ to add colors and icons to Attribute keywords:
**Click the "Details" text to see the code**

<Details>
<Macro name="RegEx-Grouped-Afflictions-and-Inspirations" Ctrl="no" Alt="no" Shift="no" Key="0">
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect and Perception Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Inspration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect, Might, and Perception Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, and &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Inspration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might and Perception Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Inspration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might and Intellect Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might, Constitution, or Dexterity Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Inspration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, or &amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect and Perception Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect, Perception, and Constitution Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, and &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve and Constitution Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve, Might, and Dexterity Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;, and &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Perception and Intellect Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt; and &amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Constitution Insprations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Insprations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Constitution Inspration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Inspration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Constitution Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Constitution Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Constitution&quot;&amp;gt;&amp;lt;#f7b733&amp;gt;Constitution&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_constitution&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Dexterity Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Dexterity Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Dexterity Inspirations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Dexterity Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Dexterity&quot;&amp;gt;&amp;lt;#72da26&amp;gt;Dexterity&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_dexterity&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect Inspirations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Intellect Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Intellect&quot;&amp;gt;&amp;lt;#00a4ff&amp;gt;Intellect&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_intellect&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might Inspirations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Might Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Might&quot;&amp;gt;&amp;lt;#ff4800&amp;gt;Might&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_might&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Perception Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Perception Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Perception Inspirations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Perception Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Perception&quot;&amp;gt;&amp;lt;#ca58ff&amp;gt;Perception&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_perception&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve Afflictions)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Afflictions&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve Affliction)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Afflictions_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Affliction&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve Inspirations)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Inspirations&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="(Resolve Inspiration)" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Inspirations_Resolve&quot;&amp;gt;&amp;lt;#30d3d5&amp;gt;Resolve&amp;#160;Inspiration&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;attribute_resolve&quot; tint=1&amp;gt;&amp;lt;/color&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="770" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
        </Macro>
        <Macro name="OneLine" Ctrl="no" Alt="no" Shift="no" Key="0">
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="^\s*" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1702" wParam="0" lParam="1792" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\R&lt;ID&gt;" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="&lt;ID&gt;" />
            <Action type="3" message="1702" wParam="0" lParam="1792" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\R&lt;DefaultText&gt;" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="&lt;DefaultText&gt;" />
            <Action type="3" message="1702" wParam="0" lParam="768" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\R&lt;FemaleText /&gt;" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="&lt;FemaleText /&gt;" />
            <Action type="3" message="1702" wParam="0" lParam="768" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\R&lt;/Entry&gt;" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam="&lt;/Entry&gt;" />
            <Action type="3" message="1702" wParam="0" lParam="768" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="2" message="0" wParam="44022" lParam="0" sParam="" />
            <Action type="0" message="2025" wParam="0" lParam="0" sParam="" />
            <Action type="0" message="2422" wParam="0" lParam="0" sParam="" />
            <Action type="0" message="2325" wParam="0" lParam="0" sParam="" />
            <Action type="0" message="2025" wParam="0" lParam="0" sParam="" />
            <Action type="0" message="2422" wParam="0" lParam="0" sParam="" />
            <Action type="0" message="2325" wParam="0" lParam="0" sParam="" />
</Macro>
</Details>

---

Use this macro in Notepad++ to add colors and icons to defense and damage keywords:
**Click the "Details" text to see the code**

<Details>
<Macro name="RegEx-DefenseAndDamage" Ctrl="no" Alt="no" Shift="no" Key="0">
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Fortitude)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Fortitude&quot;&amp;gt;Fortitude&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_fortitude&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Deflection)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Deflection&quot;&amp;gt;Deflection&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_deflection&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Reflexes)\b|\b(Reflex)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Reflexes&quot;&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_reflex&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Will)\b|\b(Willpower)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Will&quot;&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_will&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Slash)\b|\b(Slashing)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Slashing&quot;&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_slash&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Crushing)\b|\b(Crushes)\b|(Crush)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Crushing&quot;&amp;gt;$1$2$3&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_blunt&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Piercing)\b|\b(Pierces)\b|\b(Pierce)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Piercing&quot;&amp;gt;$1$2$3&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_pierce&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Raw)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Raw&quot;&amp;gt;Raw&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_raw&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Burns)\b|\b(Burned)\b|\b(Burning)\b|\b(Burn)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Burning&quot;&amp;gt;$1$2$3$4&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_burn&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Corrode)\b|\b(Corrosive)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Corrode&quot;&amp;gt;$1$2&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_corrosive&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Freeze)\b|\b(Freezes)\b|\b(Freezed)\b|\b(Freezing)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Freezing&quot;&amp;gt;$1$2$3$4&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_freeze&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
            <Action type="3" message="1700" wParam="0" lParam="0" sParam="" />
            <Action type="3" message="1601" wParam="0" lParam="0" sParam="\b(Shock)\b|\b(Shocked)\b|\b(Shocking)\b" />
            <Action type="3" message="1625" wParam="0" lParam="2" sParam="" />
            <Action type="3" message="1602" wParam="0" lParam="0" sParam='&amp;lt;link=&quot;glossary://GlossaryEntry_Shock&quot;&amp;gt;$1$2$3&amp;#160;&amp;lt;sprite=&quot;Inline&quot; name=&quot;cs_shock&quot; tint=1&amp;gt;&amp;lt;/link&amp;gt;' />
            <Action type="3" message="1702" wParam="0" lParam="1794" sParam="" />
            <Action type="3" message="1701" wParam="0" lParam="1609" sParam="" />
</Macro>
</Details>

And that's it! You're now done!
