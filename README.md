# Using GIMP to Write Sumerian Script 𒆠𒂗𒄀 

In a world filled with various image manipulation tools, why choose the GNU Image Manipulation Program (GIMP)? Despite having access to Maxon One, which includes the Adobe toolkit for image manipulation, I find the Adobe toolkit significantly inferior to GIMP. However, there's another compelling reason: GIMP is open-source and integrates seamlessly with major image processing libraries such as G'MIC and GEGL. Over time, the collaborative power of open-source development will likely make GIMP unbeatable.

But why use GIMP today when expensive paid tools are the industry standard? 
- **The Power of Open Source**: GIMP can leverage image processing research from around the world, including contributions from notable projects like the French G'MIC and the GEGL library, developed by the Oscar-winning Rhythm & Hues Studios, which also wrote GIMP’s core.
- **Advanced Scripting and Compatibility**: GIMP is programmed in Scheme, a dialect of Lisp, making it easier to write scripts. Additionally, GIMP uses SVG for paths, a user-friendly format.
With these advantages, GIMP stands out as a powerful, flexible, and continually evolving tool for image manipulation, making it a compelling choice for both current use and future developments.

As an example of using GIMP, let's tackle a fascinating problem: how to write in Sumerian.

## Order of reading
1. The present README contains the first lesson with the document ```Ur-Nammu 9```.
2. In the ```Emacs``` directory, the second lesson briefly introduces the Emacs editor and annotates the document ```Ur-Nammu 7```.
3. Directory ```ur-nammu-31``` contains the third lesson.
4. The fourth lesson is in the directory ```Ur-Nammu-23```.
5. The fifth lesson is in the directory ```lesson-five-Ur-Nammu-5```.

## Sumerian script

The Sumerian cuneiform script was the first writing system invented by humankind. Therefore, all educated individuals should learn this 5,000-year-old script. In this tutorial, we will learn how to read and reproduce the writing on the Ur-Nammu 9 Brick.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/e941ce88-4aa3-46fb-95c4-921d63cff61c)

Below, you can see my first attempt at writing the contents of the Ur-Nammu No. 9 brick. You will undoubtedly notice that my script is quite different from the original. This ancient brick was inscribed before the Sumerian cuneiform script became more stylized, so I converted it to the stylized script.

![image](https://github.com/user-attachments/assets/958a6db2-2ffd-49f0-b57d-640f594fa099)

## Books
There are few grammar books for Sumerian. Unfortunately, Marie-Louise Thomsen's "**The Sumerian Language**" does not use cuneiform, so I cannot recommend it. This leaves us with John Hayes's manual. Therefore, I advise you to buy "**A Manual of Sumerian: Grammar and Texts**" to learn this ancient language in depth.

## Sentence structure
1- [NANNA \
2-  LUGAL.ANI].{(R) #benefactive}  -- For his king\
3- [UR.NAMMU\
4- LUGAL.URIM5.{AK #genitive}].{E #ergative} --  the king of UR\
5- [E2.ANI].{#object}      --  his temple\
6- MU.NA.DU3 #verb     -- he built\
7- [[BAD3.URIM5].{A(K) #genitive}].{#object} -- the city wall of Ur\
8- MU.NA.DU3  #verb      -- he built

1,2- The benefactive has an unwritten R, which is represented by {(R)}\
3,4- The genitive ends in {AK} after consonant; the ergative ends in {E}\
5- The object of the action has no ending, which is represented by {}\
7- The genitive has an unwritten K, which is represented by {A(K)}

<p>Braces represent endings. In the representation of an ending,
I may add a hash-prefixed comment on the grammatical function. For instance,
  the ergative ending {E} may be written as {E #ergative}. The
  empty ending of the object is commented as {#object}.
  Unwritten endings are placed between parentheses, such as {(R)}.
</p>

## First Rectangle
The Ur-Nammu 9 document is divided into eight rectangles. In the first rectangle, the text 𒀭𒋀𒆠 is written, which is the Sumerogram for the name of Nanna, the god of the Moon. The 𒀭 symbol is read as DIG̃IR and is determinative for deity. We will learn in the next paragraph that this word is in the dative case; therefore, the translation of the rectangle is "**For Nanna.**"

<table>
 <tr>
  <th><h3>𒀭</h3></th>
   <th><h3>𒋀𒆠</h3></th>
 </tr>
 <tr>
  <td>an</td>
  <td>nanna</td>
 </tr>
 <tr>
  <td colspan="2">
     ===============================================</br>
    (cn an nanna)</br>
    [Nanna
  </td>
 </tr>
  <tr>
  <td colspan="2">
   <i>For nanna,</i> 
  </td>
 </tr>
  <tr>
  <td colspan="2">
    <h4>𒀭𒋀𒆠 • (d-nanna) Nanna, the moon god, patron of Ur</h4>
  </td>
  </tr>
</table>


## Second rectangle
The second rectangle contains three Sumerograms: 𒈗 (LUGAL), 𒀀 (syllable A), and 𒉌 (syllable NI). LUGAL (𒈗) means "King" or "Lord." ANI (𒀀𒉌) can be translated as "his." Then LUGAL ANI (𒈗𒀀𒉌) means "his Lord." The Sumerogram 𒈗 (LUGAL) is formed from 𒇽 (lu₂, "person") and 𒃲 (gal, "big").

In Sumerian, like in Latin and German, a nominal phrase has a case marker that indicates various grammatical functions. On the first and second rectangles, the case marker is the dative, which suggests the beneficiary of the action (**cui bono**). The dative marker is an "R," rarely expressed in writing. Therefore, the whole nominal phrase can be transliterated as [NANNA LUGAL.ANI]-(R), where the (R) is not expressed.

<table>
 <tr>
  <th><h3>𒈗</h3></th>
   <th><h3>𒀀𒉌</h3></th>
 </tr>
 <tr>
  <td>lugal</td>
  <td>a-ni</td>
 </tr>
 <tr>
  <td colspan="2">
    ===============================================</br>
    (cn lugal a ni)</br>
  lugal.ani].(r)
  </td>
 </tr>
  <tr>
  <td colspan="2">
   <i>his master,</i> 
  </td>
 </tr>
  <tr>
  <td colspan="2">
   <h4>𒈗 • (lugal) king, lord, master, owner</h4>
    <h4>𒀀𒉌 • (a-ni, a-ne2) his/her (3d-person human possessive pronoun)</h4>
  </td>
 </tr>
</table>

## Third Rectangle
The third rectangle contains the name of Ur-Nammu (𒌨𒀭𒇉), the king who rebuilt the temple of Nanna and is the document's author. The king's name is formed by 𒌨 (UR), which means man or dog, and 𒀭𒇉 (NAMMA), the Mother Earth of the Sumerians. Therefore, the king's name, 𒌨𒀭𒇉, means "The Man of Namma." Note that the determinative of deity (𒀭) precedes the goddess's name.

<table>
 <tr>
  <th><h3>𒌨𒀭𒇉</h3></th>
 </tr>
 <tr>
  <td>ur-nammu</td>
 </tr>
 <tr>
  <td colspan="1">
     ===============================================</br>
    (cn ur-nammu)</br>
  [Ur.Nammu
  </td>
 </tr>
  <tr>
  <td colspan="1">
   <i>Ur-Nammu,</i> 
  </td>
 </tr>
  <tr>
  <td colspan="1">
   <h4>𒌨𒀭𒇉 • (ur-d-namma) Ur-Nammu (a king famous for his law-code)</h4> 
  </td>
 </tr>
</table>

## Fourth Rectangle
On the fourth rectangle, 𒋀𒀕𒆠 (URIM2) is written, representing the city that was the cult center of Nanna. It is formed by the Sumerograms ŠEŠ (𒋀) and UNUG (𒀕). The Sumerogram 𒆠 is determinative for geographic names.

The genitive case denotes possession. Unlike the dative, English has a genitive case, formed by an apostrophe followed by "s." In English, one would say, "Urim's King." In Sumerian, the genitive follows the possessor and is marked with "AK" after consonants and "K" after vowels. In this case, the "A" of "AK" was assimilated with the previous consonant, becoming 𒈠 (MA). The Sumerogram 𒆤 (KE4) represents the "K" of the genitive and the "E4" of the ergative.

Sumerian is an ergative language, meaning the agent of transitive actions is marked. In Sumerian, the marker is "E." However, the subject of an intransitive verb, like "*to go*" or "*to sleep*," does not receive the "E" that marks the agent.

<table>
 <tr>
  <th><h3>𒈗</h3></th>
   <th><h3>𒋀𒀊𒆠</h3></th>
   <th><h3>𒈠</h3></th>
   <th><h3>𒆤</h3></th>
 </tr>
 <tr>
  <td>lugal</td>
   <td>urim5</td>
   <td>ma</td>
   <td>ke4</td>
 </tr>
 <tr>
  <td colspan="4">
    ===============================================</br>
    (cn lugal urim ma ke4)</br>
    lugal.urim5.ak].e
  </td>
 </tr>
  <tr>
  <td colspan="4">
   <i>the king of Ur,</i> 
  </td>
 </tr>
  <tr>
  <td colspan="4">
   <h4>𒋀𒀕𒆠 • (urim2ki) Ur (city in southern Mesopotamia</h4>
   <h4>𒈠𒆤 • (m.ak.e) genitive contracted with ergative</h4>
  </td>
 </tr>
</table>

## Fifth Rectangle
The fifth rectangle introduces the temple (E2 - 𒂍) that Ur-Nammu built. The expression 𒂍𒀀𒉌 (E2 ANI) means "his temple."

<table>
 <tr>
  <th><h3>𒂍</h3></th>
   <th><h3>𒀀</h3></th>
   <th><h3>𒉌</h3></th>
 </tr>
 <tr>
  <td>e2</td>
   <td>a</td>
   <td>ni</td>
 </tr>
 <tr>
  <td colspan="3">
     ===============================================</br>
    (cn e2 a ni)</br>
    e2.ani
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <i>his temple</i> 
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <h4>𒂍 • (e2) (pl. 𒂍𒈨𒌍 (È.MEŠ)) house, temple</h4> 
  </td>
 </tr>
</table>


## Sixth Rectangle
The verb 𒈬𒈾𒆕 (MUNADU3) can be translated as "built." The verb has three components:

1. 𒈬 — Ventive Conjugation Prefix (CP). The Ventive CP indicates that the action occurs here, close to the speaker.
3. 𒈾 — Dimensional Prefix (DP) cross-referencing the dative.
   Sumerian has a DP for each sentence component, except the ergative and the patient.
5. 𒆕 — verbal root

<table>
 <tr>
  <th><h3>𒈬</h3></th>
   <th><h3>𒈾</h3></th>
   <th><h3>𒆕</h3></th>
 </tr>
 <tr>
  <td>mu</td>
   <td>na</td>
   <td>du3</td>
 </tr>
 <tr>
  <td colspan="3">
     ===============================================</br>
    (cn mu na du3)</br>
    mu.na.du3
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <i>he built for him</i> 
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <h4>𒆕 • (du3) to build, to make, to plant</h4>
   <h4>𒈬 • (mu) conjugation prefix (CP), ventive prefix</h4>
   <h4>𒉌 • (i3), 𒀀 • (a), 𒀠 • (al) CP: finite marker prefixes  </h4>
   <h4>𒉌 𒌈 • (ib2), 𒉎 • (im), 𒅔 • (in) CP: finite marker prefixes  </h4>
  <h4> 𒈾 or 𒀀 • (na) DP that cross-references the dative</h4>
 </td>
 </tr>
</table>

## Seventh Rectangle
The noun phrase 𒂦𒋀𒀕𒆠𒈠 (BAD2.URIM2.MA) means "wall of URIM2." The sumerogram 𒂦 (BAD2) means "city wall." The /K/ of the genitive is omissible, meaning it is not expressed because it is not pronounced at the end of a nominal phrase.

<table>
 <tr>
  <th><h3>𒂦</h3></th>
   <th><h3>𒋀𒀕𒆠</h3></th>
   <th><h3>𒈠</h3></th>
 </tr>
 <tr>
  <td>bad2</td>
   <td>urim5</td>
   <td>ma</td>
 </tr>
 <tr>
  <td colspan="3">
     ===============================================</br>
    (cn bad3 urim ma)</br>
    bad3.urim5.a
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <i>The city wall of Ur,</i> 
  </td>
 </tr>
  <tr>
  <td colspan="3">
   <h4>𒂦 • (bad3) wall, fortification</h4>
   <h4>𒈠 • (m.a(k)) genitive, of Ur</h4> 
  </td>
 </tr>
</table>

## Eigth Rectangle
The last rectangle repeats the 𒈬𒈾𒆕 (MUNADU3) verb.

<table>
 <tr>
  <th><h3>𒈬</h3></th>
   <th><h3>𒈾</h3></th>
   <th><h3>𒆕</h3></th>
 </tr>
 <tr>
  <td>mu</td>
   <td>na</td>
   <td>du3</td>
 </tr>
 <tr>
  <td colspan="3">
     ===============================================</br>
    (cn mu na du3)</br>
    mu.na.du3
  </td>
 </tr>𒈬𒌦𒉈𒆪𒂊 (mu-nne.dab.e) he seizes them
  <tr>
  <td colspan="3">
   <i>he built for him</i> 
  </td>
 </tr>
<tr>
  <td colspan="3">
  Below, there is a complete list of Dimensional Prefixes (DP).</br>
  The concept of DP does not exist in English. 
   <h4> 𒈾 or 𒀀 • (na) DP that cross-references the dative</h4>
   <h4> 𒁕 • (da) DP comitative, indicates group action, as in ‘with’</h4>
   <h4> 𒋫 • (ta) DP ablative, indicates separation</h4>
   <h4> 𒋫 • (ta) DP ablative, indicates separation</h4>
   <h4>𒂠 • (še) DP terminative, indicates goal </h4>
  <h4>𒉌 • (ni) DP locative, indicates where something is happening</h4>
  <h4> 𒂊 • (ni) DP, indicates motion toward something </h4>
</td>
 </tr>
</table>


## The Method
I will use the method I employed in this first document to introduce a few other documents. In other words, each document's directory will contain a README.md with precise details: grammar, vocabulary, syllables, and Sumerograms essential for reading the document. This methodology ensures you will be able to handle a manageable amount of information initially.

Additionally, directories will include wedges, syllables, and necessary dictionary entries for the Sumerian document typesetting. Main directories store wedges of average size, while subdirectories like 'short' contain shorter wedges, 'long' hold longer ones, and others are designated for shallow, repeated, and angular wedges.

In the Gimp-Installation directory, you'll find a README.md with instructions for installing Gimp to facilitate Sumerogram typesetting.


## Reading the brick
Let's read the whole brick inscription:

1. ᵈNANNA (𒀭𒋀𒆠) -- For the god Nanna...
2. LUGAL ANI (𒈗𒀀𒉌) -- his Lord. The word 'LUGAL' meanse  king or lord. It is formed from 'lu,' which means 'man,' and 'gal,' which can be translated as 'great.' The expression 'a-ni' is equivalent to the possessive pronoun 'his.'
3. UR-NAMMU (𒌨𒀭𒇉)
4. LUGAL-URIM2ki-MA-KE4 (𒈗 𒋀𒀕𒆠 𒈠 𒆤)-- King of Ur,
5. E2-ANI (𒂍𒀀𒉌) -- his temple. Remember that you already learned the meaning of 'ANI.'
6. MU-NA-DU3 (𒈬𒈾𒆕) -- built.
7. BAD3.URIM2.MA (𒂦𒋀𒀕𒆠𒈠) -- The wall of Ur,
8. MU-NA-DU3 (𒈬𒈾𒆕) -- he built for NANNA.

The meaning of the whole document is something like this: **"For the god Nanna, his Lord, Ur-Nammu, the King of Urim, built his temple. The king also built the city walls of Urim."**

# Sentence structure
The subject of a sentence is the topic of
the conversation. Besides the subject, the sentence may have
other components, such as a dative and a locative.
Many actions have a benefactive, which is called dative by linguists.
In Sumerian, the dative is marked with 𒊏 (ra, r). The place where
the action occurs is called locative and is marked by 𒀀(a).

## Transitive verbs
A transitive verb describes an action that transitions
from a subject to a direct object. In a transitive verb, the subject is the
doer of the action and is called ergative, which is the Greek
term for the person who performs a task.
In Sumerian, the ergative is marked with 𒂊 (e).

The direct object can be the person accused of a deed.
In this case, the direct object is called accusative.
The direct object can also be a target of a shooting. Or it can be the
object of health care, in which case it is called patient by the doctors.
Some linguists call **patient**  all kinds of direct objects, while others
prefer the term **accusative**. In Sumerian, the
direct object does not receive any mark.

The transitive verb itself comes last in a Sumerian sentence,
and is described by a chain of affixes
surrounding the stem.

The verbal chain may contain a Modal Prefix (MP, such as 𒉡 • nu • not),
a Conjugation Prefix (CP, such as 𒈬 • mu • *ventive*, here),
initial pronominal prefix (IPP, such as N in 𒈬𒌦𒆪𒂊 •  mu-n.dab.e •  he seizes him)
and suffix pronouns (𒂗𒉈𒂗 • en-de3-en • **us**, 𒌦𒍢𒂗 • un-ze2-en • **you people**).
Below, there are examples of all initial pronominal prefixes.

<h3>𒈬𒆪𒂊 (mu'dab.e) he seizes me</h3>
<h3>𒈬𒂊𒆪𒂊 (mu-e.dab.e) he seizes you</h3>
<h3>𒈬𒌦𒆪𒂊 (mu-n.dab.e) he seizes her</h3>
<h3>𒈬𒈨𒆪𒂊 (mu-me.dab.e) he seizes us</h3>
<h3>𒈬𒌦𒉈𒆪𒂊 (mu-nne.dab.e) he seizes them</h3>

Below, I have for you a complete example of a transitive sentence.
I provided you with a pronunciation key and vocabulary, so I hope
you can scan the sentence.


<h2>𒊩𒊏𒇽𒂊𒊺𒌷𒀀</br>𒈬𒈾𒀊𒋧𒂊</h2>
<table>
 <tr>
  <td><h3>𒊩𒊏</h3></td>
  <td><h3>𒇽𒂊</h3></td>
  <td><h3>𒊺</h3></td>
  <td><h3>𒌷𒀀</h3></td>
  <td><h3>𒈬𒈾𒀊𒋧𒂊</h3></td>
 </tr>
 <tr>
  <td><h3>munus.ra</h3></td>
  <td><h3>lu2.e</h3></td>
  <td><h3>ŝe.∅</h3></td>
   <td><h3>uru.a</h3></td>
   <td><h3>mu•na•ab•shum2.e</h3></td>
 </tr>
  <tr>
  <td><h3>for the woman</h3></td>
  <td><h3>the man</h3></td>
  <td><h3>barley</h3></td>
    <td><h3>in the city</h3></td>
   <td><h3>here•to her•it</br>•he gave</h3></td>
 </tr>
 <tr>
  <td colspan="5">
   <i>The man gave the woman barley in the city.</i>
  </td>
 </tr>
 <tr>
  <td colspan="5">
   <h4>𒊩 • (munus) woman, female</h4>
   <h4>𒊏 • (ra) *dative marker* </h4>
   <h4>𒇽 • (lu2) man, male</h4>
   <h4>𒂊 • (e) *ergative marker* </h4>
   <h4>𒊺 • (še) barley, grain</h4>
   <h4>𒌷 • (uru) city</h4>
  <h4>𒀀 • (a) *locative marker* </h4>
  <h4>𒈬 • (mu) *venitive conjugation prefix,* **here** </h4>
     <h4>𒈾 • (na) *cross-reference to the dative,* **to her** </h4>
    <h4>𒀊  • (na) *Initial Prefix Pronoun,* **it**  </h4>
    <h4>𒋧 • (shum2) to give</h4>
  </td>
 </tr>
</table>

## Intransitive verb
An intransitive verb does not have a direct object.
In Sumerian, the subject of an intransitive verb is
not marked.

<h2>𒈗𒉌𒅎𒁺</h2>
<table>
 <tr>
  <td><h3>𒈗</h3></td>
  <td><h3>𒌷𒂠</h3></td>
  <td><h3>𒉌</h3></td>
  <td><h3>𒅎</h3></td>
  <td><h3>𒁺</h3></td>
 </tr>
 <tr>
  <td><h3>lugal..∅</h3></td>
  <td><h3>uru she</h3></td>
  <td><h3>i3</h3></td>
  <td><h3>im</h3></td>
   <td><h3>g̃en</h3></td>
 </tr>
  <tr>
  <td><h3>the king</h3></td>
  <td colspan="2"><h3>finite verb marker</h3></td>
   <td><h3>came</h3></td>
 </tr>
 <tr>
  <td colspan="5">
   <i>The king came.</i>
  </td>
 </tr>
 <tr>
  <td colspan="5">
   <h4>𒈗 • (lugal) king</h4>
   <h4>𒉌𒅎 • (im) *finite verb marker* </h4>
   <h4>𒁺 • (g̃en) to come</h4>
    <h4>𒂠 • (še3)  to, towards</h4>
    <h4>𒌷 • (uru) city</h4>
  </td>
 </tr>
</table>

