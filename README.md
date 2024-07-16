# Sumerian script 𒆠𒂗𒄀 
As an example of using the GNU Image Manipulation Program (GIMP), we will tackle a fascinating problem: how to write in Sumerian.

The Sumerian cuneiform script was the first writing system invented by humankind. Therefore, all educated individuals should learn this 5,000-year-old script. In this tutorial, we will learn how to read and reproduce the writing on the Ur-Nammu 9 Brick.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/e941ce88-4aa3-46fb-95c4-921d63cff61c)

Below, you can see my first attempt at writing the contents of the Ur-Nammu No. 9 brick. You will undoubtedly notice that my script is quite different from the original. This ancient brick was inscribed before the Sumerian cuneiform script became more stylized, so I converted it to the stylized script.

![image](https://github.com/user-attachments/assets/958a6db2-2ffd-49f0-b57d-640f594fa099)

## Books
There are few grammar books for Sumerian. Unfortunately, Marie-Louise Thomsen's "**The Sumerian Language**" does not use cuneiform, so I cannot recommend it. This state of things leaves us with John Hayes's manual. Therefore, I advise you to buy "**A Manual of Sumerian: Grammar and Texts**" to learn this ancient language in depth.

## First Rectangle
The Ur-Nammu 9 document is divided into eight rectangles. In the first rectangle, the text 𒀭𒋀𒆠 is written, which is the Sumerogram for the name of Nanna, the god of the Moon. The 𒀭 symbol is read as DIG̃IR and is determinative for deity. We will learn in the next paragraph that this word is in the dative case; therefore, the translation of the rectangle is "**For Nanna.**"

## Second rectangle
The second rectangle contains three Sumerograms: 𒈗 (LUGAL), 𒀀 (syllable A), and 𒉌 (syllable NI). LUGAL (𒈗) means "King" or "Lord." ANI (𒀀𒉌) can be translated as "his." Then LUGAL ANI (𒈗𒀀𒉌) means "his Lord." The Sumerogram 𒈗 (LUGAL) is formed from 𒇽 (lu₂, "person") and 𒃲 (gal, "big").

In Sumerian, like in Latin and German, a nominal phrase has a case marker that indicates various grammatical functions. On the first and second rectangles, the case marker is the dative, which suggests the beneficiary of the action (**cui bono**). The dative marker is an "R," rarely expressed in writing. Therefore, the whole nominal phrase can be transliterated as [NANNA LUGAL.ANI]-(R), where the (R) is not expressed.

## Third Rectangle
The fourth rectangle contains the name of Ur-Nammu (𒌨𒀭𒇉), the king who rebuilt the temple of Nanna and is the document's author. The king's name is formed by 𒌨 (UR), which means man or dog, and 𒀭𒇉 (NAMMA), the Mother Earth of the Sumerians. Therefore, the king's name, 𒌨𒀭𒇉, means "The Man of Namma." Note that the determinative of deity (𒀭) precedes the goddess's name.

## Fourth Rectangle
On the fourth rectangle, 𒋀𒀕𒆠 (URIM2) is written, representing the city that was the cult center of Nanna. It is formed by the Sumerograms ŠEŠ (𒋀) and UNUG (𒀕). The Sumerogram 𒆠 is determinative for geographic names.

The genitive case denotes possession. Unlike the dative, English has a genitive case, formed by an apostrophe followed by "s." In English, one would say, "Urim's King." In Sumerian, the genitive follows the possessor and is marked with "AK" after consonants and "K" after vowels. In this case, the "A" of "AK" was assimilated with the previous consonant, becoming 𒈠 (MA). The Sumerogram 𒆤 (KE4) represents the "K" of the genitive and the "E4" of the ergative.

Sumerian is an ergative language, meaning the agent of transitive actions is marked. In Sumerian, the marker is "E." However, the subject of an intransitive verb, like "*to go*" or "*to sleep*," does not receive the "E" that marks the agent.

## Fifth Rectangle
The fifth rectangle introduces the temple (E2 - 𒂍) that Ur-Nammu built. The expression 𒂍𒀀𒉌 (E2 ANI) means "his temple."


## Sixth Rectangle
The verb 𒈬𒈾𒆕 (MUNADU3) can be translated as "built." The verb has three components:

1. 𒈬 — conjugation prefix
2. 𒈾 — cross-reference to the dative
3. 𒆕 — verbal root

## Seventh Rectangle
The noun phrase 𒂦𒋀𒀕𒆠𒈠 (BAD2.URIM2.MA) means "wall of URIM2." The sumerogram 𒂦 (BAD2) means "city wall." The /K/ of the genitive is omissible, meaning it is not expressed because it is not pronounced at the end of a nominal phrase.

## Eigth Rectangle
The last rectangle repeats the 𒈬𒈾𒆕 (MUNADU3) verb.


## The Method
I will use the method I employed in this first document to introduce a few other documents. In other words, each document's directory will contain a README.md with precise details: grammar, vocabulary, syllables, and Sumerograms essential for reading the document. This methodology ensures you will be able to handle a manageable amount of information initially.

Additionally, directories will include wedges, syllables, and necessary dictionary entries for the Sumerian document typesetting. Main directories store wedges of average size, while subdirectories like 'short' contain shorter wedges, 'long' hold longer ones, and others are designated for shallow, repeated, and angular wedges.

In the Gimp-Installation directory, you'll find a README.md with instructions for installing Gimp to facilitate Sumerogram typesetting.



## Installing Gimp
I will explain how to install GIMP on Ubuntu Linux. If you have Windows or Macintosh, I hope you will still find this installation process helpful. Linux has many package managers, such as Snap and Flatpak. I strongly recommend installing GIMP through the Advanced Package Tool (APT). First, open the terminal (press Ctrl+Alt+T) and run the command to add the GIMP PPA:

```console
~$ sudo add-apt-repository ppa:ubuntuhandbook1/gimp
```

When adding a PPA, Linux Mint users need to refresh the package cache, which is done automatically in Ubuntu. To ensure everything is up-to-date, run the following command:

```console
~$ sudo apt update
```

Finally, install Gimp and the libraries that it needs.

```console
~$ sudo apt install gimp gegl libgexiv2-2
```

## Preferences
Start GIMP and open the Edit menu, then select the Preferences submenu. Open the Folders tab by clicking on the + icon. Finally, open the Plug-ins tab to check where you will install your plugins. Generally, the plugins will be installed in the following directory:

```console
/home/your-home-directory/.config/GIMP/2.10/plug-ins
```

## SLOS
Since the Gimp brush set is not complete, you should download the SLOS brushes.

```console
~$ git clone https://github.com/SenlinOS/SLOS-GIMPainter
```

Then, go to Edit > Preferences > Folders > Brushes and add a directory for SLOS, as shown below. To activate the add directory field, click on the icon of a sheet of paper with a plus sign in the upper left corner.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/6b23d7e0-b26e-4097-bf02-8b4676b6225c)

Copy all the brushes you downloaded from https://github.com/SenlinOS/SLOS-GIMPainter into the brushes/SLOS directory, as shown below:

```console
~/SLOS-GIMPainter$ cp -rf brushes/SLOS/  ~/.config/GIMP/2.10/brushes/
```

The next step is to enter the Edit>Preferences>Folders>Dynamics menu and add a directory for dynamics.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/07970141-2c9f-4c2f-a8f3-2417ff1e74c5)

Copy the folder dynamics/SLOS from SLOS-GIMPainter to the above-defined directory.

```console
~/SLOS-GIMPainter$ cp -rf dynamics/SLOS/ ~/.config/GIMP/2.10/dynamics/
```

Finally, enter the Edit>Preferences>Folders>Tool Presets menu and inform the directory where you will install the Tool Presets.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/47b750f2-2ee5-448e-ace2-5e0886b3ad21)

Copy the tool presets to its final directory, and you will be done.

```console
~/SLOS-GIMPainter$ cp -rf tool-presets/SLOS/ ~/.config/GIMP/2.10/tool-presets/
```

## Creating a wedge-shaped blush

The Sumerian writing system is called cuneiform because its syllabary and ideograms are written with wedge-shaped strokes. The term "cuneiform" comes from the Latin word "cuneum," which means wedge. To create a brush with wedge dynamics, follow these steps:

1. Open the **Windows** menu.
2. Select the **Dockable Dialogs** submenu.
3. Choose the **Paint Dynamics** option.
4. Click on the icon in the shape of a paper sheet with a plus sign in the upper left corner.

Let’s name our new brush **Wedge Brush**. Check the **Size/Fade** box, as shown below.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/e23bf1cb-4ae8-4a0b-bfb1-417b86b9ff4b)

If you are curious about the dynamics of the new brush, choose the **Size** option in the menu below. While you can edit the **Size** curve, the default settings work well for our purposes.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/0389448e-98eb-4cf8-a1ab-bff32752d4f6)

Now, go to **Tools > Paint Tools > Paintbrush** menu to select the **Paintbrush** tool. Make sure that the **Wedge Brush** dynamics are selected, set the brush size to 30, and ensure that the **Reverse** box is checked.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/e73d6540-eb02-4212-aadf-3fe8afa26200)

## Creating our first cuneiform text

Let's try to copy the text below, which is a dedication that says: **"ᵈNanna lugal-a-ni Ur-Nammu..."** Translation: **"For Nanna, his Lord, Ur-Nammu..."** *built this temple*.

<img src="https://github.com/FemtoEmacs/Sumerian/assets/21132559/c6dafa3d-7964-4549-ad8c-74dc25192066" width="200" height="200">

The first step is to open a new document using the **File > New menu**. In the dialog that appears, let's choose a Width of 1024 and a Height of 1024 for the document.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/5a0dd1d2-d138-4236-bbcc-b08e14cecaa9)

Choose the menu item **Tools > Paint Tools > Paintbrush**. Select the brush **SLOS_flat-painted** with a size of 25, as shown below.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/e8e74002-7225-4905-aef1-0efa53259c3f)

In the Dynamics options, ensure the Wedge Brush is selected and the Reverse box is checked. For the Fade length, use 400 px for long wedges, 300 or 200 for medium-sized wedges, and 100 for short ones. Ensure you are using pixels (px) as the unit of measurement. Wedges will behave differently if you choose percentage or millimeters (mm), so sticking with pixels is essential.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/09757bf5-3f8a-4587-8c94-412f98840080)

Choose **Tools > Path** to start drawing or press the 'b' key. This action will allow you to indicate the path of the brush. Let's draw the star, an honorific determinative for a god or goddess. Mark the extremities of the wedge with the mouse. Finally, press the 'Stroke Path' button to draw the star.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/838b6d45-f312-4bdc-8eab-302231a84e8e)

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/5e435331-f896-4d38-8d38-859edfe294dc)

Press the 'Stroke' button in the dialog above to draw the wedge. Then, press the 'b' key to refresh the Tools/Path procedure. Repeat the operation by marking the ends of the remaining strokes, pressing 'Stroke Path,' clicking the Stroke button, and typing the 'b' key again. Here is the result:

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/6b6c7dea-bd49-4ec8-9755-0aa8f530d08f)

You must increase the wedge length to 400 pixels to draw the god's name, Nanna. Select **Tools > Paint Tools > Paintbrush** or press the 'p' key. Change the value to 400 px, press Enter, and ensure you did not change the unit from pixels to millimeters (mm). Select **Tools > Paths** to return to Tools/Paths. Remember, the Fade length will not change unless you press the 'Enter' key. Here is the first wedge of 'Nanna:'

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/7a9e3d5f-91f4-44be-b44f-26facb23fb50)

Change the **'Fade length'** to 300 to draw the following four wedges: 

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/08c2062a-6972-4a9e-ae44-253f1812b9c3)

Change the **'Fade length'** to 100 px to draw the four strokes inside the diamond shape. Press the 'Enter' key and verify that you didn't change the unit to millimeters (mm) or percentage (%).

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/eeed7535-63bb-4719-8585-7dc739731b28)

Change the **'Fade length'** to 300 for the next step.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/dba20b60-06cc-4632-8bca-a1fc45f4c8bb)

Change the **'Fade length'** to 100 for the final step.

![image](https://github.com/FemtoEmacs/Sumerian/assets/21132559/39ed7765-9da4-4e5b-b76f-f033bf07cfa5)


## Reading the brick
Let's read the whole brick inscription:

1. ᵈNanna -- For the god Nanna...
2. lugal-a-ni -- his Lord. The word 'lugal' means king or lord. It is formed from 'lu,' which means 'man,' and 'gal,' which can be translated as 'great.' The expression 'a-ni' is equivalent to the possessive pronoun 'his.'
3. Ur-Nammu
4. lugal-Urim5ki-ma-ke4 -- King of Ur,
5. e2-a-ni -- his temple. Remember that you already learned the meaning of 'a-ni.'
6. mu-na-du3 -- built.
7. bad3-Urim5ki-ma -- The wall of Ur,
8. mu-na-du3 -- he built for him.
