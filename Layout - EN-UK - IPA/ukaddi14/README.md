# UK with IPA v14.0 (based on CuBE)
Download [version 14.0 from Releases page](https://github.com/fazzaan/keyboard-layouts/releases/tag/EngIPAv14).

## Images
### `AltGr` layer
![UK14 0 AltGr](https://github.com/user-attachments/assets/3a4ea0b5-4947-43ae-a111-2dd2a7f40c49)

### `AltGr`+`Shift` layer
![UK14 0 ShftAltGr](https://github.com/user-attachments/assets/3601438b-fbe6-4b78-a60c-36a30e73c61c)

# Changelog v14 from v13  

## Symbols  
* IPA syllable stress marker [ **ˈ** ] added to `AltGr+2` for keyboards without the `VK_OEM_5` key.  
	* Sub-stress marker [ **ˌ** ] still available on `AltGr+Shif+2`.
* Most deadkeys have been removed
	* I never used them for anything,
 	* and I personally prefer a composed glyph to exist as two unicode points (decomposed) rather than a single point (precomposed).
	* This is because I use a variety of diacritics on top of letters which are not supported by the standard Unicode encoding system, and thus muscle-memory habits like `Backspace` require _two_ keypresses for these keys, whereas composed glyphs require only one.
	* This is a problem because a precomposed glyph and a decomposed glyph are (supposed to be) visually indistinguishable.  

## Vowels  
IPA vowels for my own vowel model (based on CuBE) are more intuitive and easier to access than in v13.  
_Scroll to the end to see details for typing all vowels._
#### `AltGr` Layer
* ʉ on `AltGr+u`  
* ɪj on `AltGr+y`
#### `AltGr+Shift` layer
* aʉ on `AltGr+Shift+W`
* ɵʉ on `AltGr+Shift+U`
* ɜʉ on `AltGr+Shift+O`  
* ɑj on `AltGr+Shift+V` ( / ʌ + j = ɑj / )  
#### _Legacy symbols for old (standard) IPA and other accents_  
* ʊ on `AltGr+Shift+i`  
* æ on `AltGr+Shift+a`  

## Consonants
* added shortcuts to aspirated plosives:
	* pʰ on `AltGr+p`  
	* tʰ on `AltGr+t`  
	* kʰ on `AltGr+k`  
* moved θ from `y` to `f`, to make way for œ on `y`, and tʰ on `t`.  
* added implosives ɓ and ɗ because I also type Vietnamese IPA  
	* ɓ on `AltGr+Shift+b`  
	* ɗ on `AltGr+Shift+d`  
* moved Latin gamma ɣ to `AltGr+g`  

## Detailed typing info

### IPA Vowel Table  
| `Key` | `AltGr` | `AltGr+Shft` |
|-----|-------|------------|
| `a`   | ɛj    | æ          |
| `q`   | ɑ     | ɑː         |
| `w`   | ʉ     | aʉ         |
| `e`   | ə     |  ˞  (Rho colour) |
| `r`   | ɹ     |  ʴ (Rho colour) |
| `y`   | ɪj    | œ          |
| `u`   | ɵ     | ɵʉ         |
| `i`   | ɪ     | ʊ          |
| `o`   | ɔ     | ɜʉ         |
| `v`   | ʌ     | ɑj         |

### Typing IPA diphthongs  
| Diphthong | Sequence    |
|-----------|-------------|
| ɑj  | `AltGr+Shift+v`     | 
| ɛj  | `AltGr+a`     | 
| ɪj  | `AltGr+y` or `j`     | 
| oj  | `o` + `j`           | 
| aʉ  | `AltGr+Shift+w`     | 
| ɜʉ  | `AltGr+Shift+o`     | 
| ɔʉ  | `AltGr+o` + `AltGr+w` | 
| ɵʉ  | `AltGr+Shift+u`     | 
