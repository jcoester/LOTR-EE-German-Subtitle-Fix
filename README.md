# LOTR-EE-German-Subtitle-Fix

A corrected **Elvish subtitle track** for the **2011 German Extended Edition Blu-ray** of **The Lord of the Rings: The Fellowship of the Ring** (**Der Herr der Ringe: Die Gefährten**). The fix addresses a typographical error where **"I bin Arwen"** was shown instead of the correct **"Ich bin Arwen"**. This error unintentionally evokes a humorous association with the German youth slang "[I bims](https://www.dw.com/en/i-bims-german-youth-word-of-the-year-2017/a-41422471)" which contradicts the serious tone of the scene. Additionally, two other issues were resolved: the absence of a period at the end of a sentence, and the use of the English term **"Rivendell"** instead of the correct German **"Bruchtal"**. 

![Subtitle Comparison](images/comparison.gif)

![Subtitle Comparison](images/comparison-2.gif)

![Subtitle Comparison](images/comparison-3.gif)

## **How to Use the Updated Subtitles**

> **Note**: Permitted for personal, non-commercial use only.

### **Step 1: Create MKV Files from Your Original Blu-ray Discs**

1. Insert the **Fellowship of the Ring Extended Edition: Part 1** into your Blu-ray drive.
2. Install **[MakeMKV](https://www.makemkv.com/download/)**, then open it and select the Blu-ray disc.
3. Create the MKV file. Default settings work well for this.
4. Repeat for **Fellowship of the Ring Extended Edition: Part 3**

### **Step 2: Replace the Subtitle Track with the Fixed Version**

1. Download the updated subtitle file for [Part 1](https://github.com/jcoester/LOTR-EE-German-Subtitle-Fix/raw/main/lotr-ee-fotr1-german-subtitle-fix.sup) and [Part 2](https://github.com/jcoester/LOTR-EE-German-Subtitle-Fix/raw/main/lotr-ee-fotr2-german-subtitle-fix.sup) from this repo.
2. Install **[MKVToolNix](https://mkvtoolnix.download/downloads.html)**, then open it and load a) the **MKV movie file** and b) the **updated subtitle file**.
3. **Deactivate** the Original Elvish Subtitle Track.
4. **Start Multiplexing** to create the new MKV file.

## **Technical Details**

The Elvish subtitles come in **Blu-ray PGS (Presentation Graphic Stream) subtitle file (.sup)** format, which is image-based rather than text-based. The ".sup" file was extracted from the MKV using **[gMKVExtractGUI](https://mkvtoolnix.download/links.html)**. Using **[Subtitle Edit](https://www.nikse.dk/subtitleedit)**, the specific subtitle images were isolated and edited in **Adobe Photoshop**. The incorrect **"I bin"** was replaced with **"Ich bin"**, taken from the latter part of the sentence. The **X offset** was adjusted to center the updated subtitles precisely. The term **"Rivendell"** was replaced with the proper German equivalent **"Bruchtal"**, carefully assembled by cutting and reusing existing letters from other subtitles to preserve the original font and rendering style as seen below.

![Behind-the-scenes](images/behind-the-scenes.png)