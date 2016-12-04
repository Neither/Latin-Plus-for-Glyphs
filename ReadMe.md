# Latin Plus for Glyphs

Underware's [Latin Plus](http://www.underware.nl/latin_plus/) character set updated for the [Glyphs.app](https://glyphsapp.com/) font editor workflow.

## Background

### Character Sets

Briefly, a character set is just a list of symbols included in a font. In English, it could be as simple as `a, b, c ... z` in upper- and lower-case, plus a few basic punctuation marks. Because a font is used on a computer, what we're really talking about is a list of characters recognized by a computer, the software the font is used within, and the input devices used to enter the characters.

The world of [character sets](https://en.wikipedia.org/wiki/Category:Character_sets) (strictly, '[*character encodings*](https://en.wikipedia.org/wiki/Character_encoding)') is way more complex and fraught than you might think. Some common encodings for just Western languages include [ASCII](https://en.wikipedia.org/wiki/ASCII), [ISO 8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1), [ISO 8859-2](https://en.wikipedia.org/wiki/ISO/IEC_8859-2), [ISO 8859-9](https://en.wikipedia.org/wiki/ISO/IEC_8859-9), [Mac OS Roman](https://en.wikipedia.org/wiki/Mac_OS_Roman), [Windows-1252](https://en.wikipedia.org/wiki/Windows-1252) among dozens upon dozens more. Then between the [Adobe Latin sets 1 through 5](https://adobe-type-tools.github.io/adobe-latin-charsets/) and the *sixteen* parts of the [ISO/IEC 8859 Latin](https://en.wikipedia.org/wiki/ISO/IEC_8859) encoding and all the flaws and arguments it contains, the whole topic can quickly become overwhelming.


### Latin Plus

Latin Plus is a character set developed by Netherlands-based type studio [Underware](http://www.underware.nl/) since 2008. It is a [well-researched](http://www.underware.nl/case-studies/notes-on-latin-plus/) set useful for typeface designers who wish to target a wide a range of languages with as small a number of characters as possible.

As noted in their [introduction](http://www.underware.nl/latin_plus/info/):

> Underware Latin Plus is a character set developed by Underware, supporting over 200 Latin languages. This character set, which includes 446 characters in total, is created to offer decent language support for fonts.

Its development includes useful language references for each character as well as an online [validator](http://www.underware.nl/latin_plus/validate/) for fonts targeting the set.

### Glyphs Usage

As great as Latin Plus is, the current data has a few compatibility issues with the font editor Glyphs. Some are simple naming differences, others are more complex matters of internal structure and even ideology.

Much of this project is collecting and building on [this forum thread](https://forum.glyphsapp.com/t/underwares-latin-plus/1940) from 2015 where Glyphs developer Georg Seifert and the venerable [mekkablue](http://typedrawers.com/profile/97/Rainer%20Erich%20Scheichelbauer) (Rainer Erich Scheichelbauer) bring up a few initial concerns. User [contrafonts](https://forum.glyphsapp.com/users/contrafonts/) (Joaquin Contreras) contributed an updated list of glyph names. Thanks to all who pitched in there.

## The Changes

As noted, some are basic. But don't think that the mayhem of the world of character encoding can ever truly be avoided - some changes are more tricky, even contraversial.

Changes below are indicated as

```
original -> updated
```

### Basic - Nice Names

Some characters in the initial list are noted using their Unicode designation. These are friendlier and standard in Glyphs.

```
uni2113 -> literSign
uni1E9E -> Germandbls
uni0162 -> Tcedilla
uni0163 -> tcedilla
uni021A -> Tcommaaccent
uni021B -> tcommaaccent
uni2219 -> bulletoperator
uni2215 -> divisionslash
uni2116 -> numero
uniF8FF -> apple
uni00AD -> softhyphen
uni02C9 -> firsttonechinese
uni00A0 -> nbspace
```

### Basic - Glyphs 2-compatible Names

```
dotlessi -> idotless
dotlessj -> jdotless
```

### Tricky - Turkish Dotted & Dotless

https://www.glyphsapp.com/tutorials/localize-your-font-turkish  
http://typedrawers.com/discussion/932/what-is-i-latntrk  
http://www.i18nguy.com/unicode/turkish-i18n.html  

### Tricky - Accented Dutch ij

https://www.glyphsapp.com/tutorials/localize-your-font-accented-dutch-ij


## Other Resources
http://www.underware.nl/latin_plus/character_set/list  
https://www.glyphsapp.com/tutorials/diacritics  
https://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-3.html  
https://foundry.myfonts.com/guides/#incomplete-character  
https://foundry.myfonts.com/guides/#character-sets
