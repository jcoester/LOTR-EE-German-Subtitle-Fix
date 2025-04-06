# The Lord of the Rings: Extended Edition [German Subtitle Fix]

![2011 German Lord of the Rings Extended Edition Blu-ray](images/box-art.jpg)

Corrected **Elvish subtitle tracks** for the **2011 German Extended Edition Blu-ray** of **The Lord of the Rings: The Fellowship of the Ring** (***Der Herr der Ringe: Die Gefährten***). This fix addresses both **well-known** and lesser-known issues:

- *Disc 1*:
   - *1:19:13* → **"I bin Arwen"** was mistakenly used instead of **"Ich bin Arwen"**, disrupting the scene's serious tone. 
   - *1:19:57* → **Missing period** at the end of a sentence. 
- *Disc 2*:
   - *0:00:36* → **Comma sign** was used instead of a **period** at the end of a sentence. 
   - *0:00:41* → **"Rivendell"** was incorrectly used in place of the correct German term **"Bruchtal"**. 

!["I bin Arwen" to "Ich bin Arwen"](images/comparison.gif)  
!["Missing Period Fix"](images/comparison-2.gif)  
!["Comma Sign Fix"](images/comparison-3.gif)
!["Rivendell to Bruchtal"](images/comparison-4.gif)

## **How to Use the Updated Subtitles**

### **Step 1: Create MKV Files from Your Original Blu-ray Discs**

> **Note**: Permitted for personal, non-commercial use only.

1. Insert the **Fellowship of the Ring Extended Edition: Disc 1** into your Blu-ray drive.
2. Install **[MakeMKV](https://www.makemkv.com/download/)**, then open it and select the Blu-ray disc.
3. Create the **MKV file** using default settings.
4. Repeat for **Fellowship of the Ring Extended Edition: Disc 2**.

### **Step 2: Replace the Subtitle Track with the Fixed Version**

1. Download the **updated subtitles** for [Disc 1](https://github.com/jcoester/LOTR-EE-German-Subtitle-Fix/raw/main/lotr-ee-fotr1-german-subtitle-fix.sup) and [Disc 2](https://github.com/jcoester/LOTR-EE-German-Subtitle-Fix/raw/main/lotr-ee-fotr2-german-subtitle-fix.sup) from this repo.
2. Install **[MKVToolNix](https://mkvtoolnix.download/downloads.html)**, then open it and load:
   - a) the Disc 1 **MKV movie file**
   - b) the Disc 1 **updated subtitle file**.
3. **Deactivate** the original Elvish subtitle track.
4. **Start Multiplexing** to create the new MKV file.
5. Repeat for **Disc 2**.

## **Technical Details**

The Elvish subtitles come in **Blu-ray PGS (Presentation Graphic Stream) subtitle file (.sup)** format, which is **image-based** rather than text-based. The ".sup" files were extracted from the MKVs using **[gMKVExtractGUI](https://mkvtoolnix.download/links.html)**. The specific subtitle images were isolated using **[Subtitle Edit](https://www.nikse.dk/subtitleedit)** and then edited in **[Photoshop](https://www.adobe.com/products/photoshop.html)**. **"Ich bin"** was reused from the latter part of the sentence, and the proper German term **"Bruchtal"** was carefully assembled by reusing letters from other parts of the subtitles to preserve the original font, rendering style, and spacing. **X offsets** were adjusted to ensure the **updated subtitles are perfectly centered**.
