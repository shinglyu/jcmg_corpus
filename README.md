JCMG Corpus for Computer Expressive Music Performance
======================================================
By Shing Lyu
Last modified: 2014/09/05

# Introduction

  This corpus is a collection of monophonic piano performances with their corresponding scores. They were intended to be used for computer expressive music performance research, but you may adapt to your own research needs. This corpus is a part of my master thesis at Prof. Shyh-Kang Jeng's lab, JCMG (Jeng's Computer Music Group). 

# License

  This corpus is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
  Please use this corpus freely, but remember to cite (see Citing This Work section).

# Content
  The corpus consists of 6 set of recordings of Muzio Clementi's Sonatinas Op.36 (See Appendix A), recorded by 6 graduate students (not majored in music).
One of the performer (涂智展) didn't finish all the pieces in Op.36. The name of the performers are listed below:

|Codename       |Real name|
|-------|-------------------|
|wei  	|	魏振宇|
|jen  	|	任俞仲|
|jung 	|	鍾  愛|
|lin  	|	林宗緯|
|lian 	|	林廉喬|
|tu   	|	涂智展|

  The recordings, along with their corresponding scores, come in two formats: a whole piece and a piece split into phrases. The phrasing is given by the author. The phrasing information is also provided, so you can split a piece into phrases manually.

  The scores are downloaded from IMSLP (http://imslp.org/wiki/6_Sonatinas,_Op.36_%28Clementi,_Muzio%29), published by Paris: Durand & Cie., n.d.(1915). Plate D. & F. 9318 (reissue 1968). The scores are manually reduced to monophonic melodies. 

# Equipments:
  * Yamaha P-80 88-key graded hammer effect digital piano
  * M-Audio MIDISPORT 2x2 MIDI-to-USB converter
  * Lenovo x220i Laptop
  * Rosegarden DAW (on Linux)





# Format

  All the complete, pre-split files are in the ./corpus/whole folder.
  Each sample comes in the following filename:

    [performer name]_clementi_sonatina-36-[no]-[movement no].perf.mid         //performance
    [performer name]_clementi_sonatina-36-[no]-[movement no].score.xml        //score
    [performer name]_clementi_sonatina-36-[no]-[movement no].score.xml.phrase //phrasing file

  Here [performer name] is a codename given to each performer recording that piece. [no] is the piece number. [movement no] indicates the movement number.
  The phrasing file is a plain text file, each line in the file marks the starting point of a phrase (unit: beats). If the phrase starts on a non-integer beat, the number may be rounded to an integer between the end of the previous phrase and the start of the current phrase.


  All the split phrase files are in the ./corpus/split folder.
  Each sample comes in the following filename:

    [performer name]_clementi_sonatina-36-[no]-[movement no]-[phrase no].perf.mid  //performance
    [performer name]_clementi_sonatina-36-[no]-[movement no]-[phrase no].score.xml //score
  

# Citing This Work

  This corpus is a part of my master thesis, so please cite the thesis:

    Shing Lyu, “A Semi-automatic Computer Expressive Music Performance System Using Structural Support Vector Machine,” M.S. thesis, Department of Electrical Engineering, National Taiwan University, Taipei, Taiwan (R.O.C), 2014. 

# Special Thanks

  Thanks Prof. Shyh-Kang Jeng for providing guidance through out my graduate years,and supplying the lab space and equipments. And thank all the performers for participating the wonderful performances.

# Appendix A: List of works
Muzio Clementi: 6 sonatinas, Op.36

    1. Sonatina in C major 

    I. Allegro 
    II. Andante 
    III. Vivace 

    2. Sonatina in G major 

    I. Allegretto 
    II. Allegretto 
    III. Allegro 

    3. Sonatina in C major 

    I. Spiritoso 
    II. Un poco adagio 
    III. Allegro 

    4. Sonatina in F major 

    I. Con spirito 
    II. Andante con espressione 
    III. Rondó: Allegro vivace 

    5. Sonatina in G major 

    I. Presto 
    II. Allegretto moderato 
    III. Rondó: Allegro molto 

    6. Sonatina in D major 

    I. Allegro con spirito 
    II. Allegretto 

# Change Log
2014/9/5	Initial version.
