= List of first names, genders and country-specific frequencies

 This file is subject to the GNU Free Documentation License.
 Permission is granted to copy, distribute and/or modify
 this document under the terms of the GNU Free Documentation
 License, Version 1.2 or any later version published by the
 Free Software Foundation; with no Invariant Sections,
 no Front-Cover Texts, and no Back-Cover Texts.

 Copyright (c):
 2007-2008:  Jörg MICHAEL, Adalbert-Stifter-Str. 11,

             30655 Hannover, Germany

 Updated 2016:
             Matthias Winkelmann, <m@matthi.coffee>

             https://matthi.coffee

             https://twitter.com/whereismatthi

             Github: https://github.com/MatthiasWinkelmann/name-database

 Original work at http://www.heise.de/ct/ftp/07/17/182/


 This file is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty
 of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

 A copy of the license can be found in the file GNU_DOC.TXT.
 You should have received a copy of the GNU Free Documentation
 License along with this file;
 if not, write to the  Free Software Foundation, Inc.,
 675 Mass Ave, Cambridge, MA 02139, USA.

 Gender is encoded in column 2 as:

 - F  female
 - 1F female if first part of name, otherwise mostly male
 - ?F mostly female
 - M  male
 - 1M male if first part of name, otherwise mostly female
 - ?M mostly male
 - ?  unisex

 Frequencies are encoded in (2^x)% of the population,
 i. e. a "-2" in column 31 indicates a frequency between 2^-4 = 0.0625% and 2^-3 = 0.125% of the population of Great Britain

## A few words on quality of data

The dictionary of first names has been prepared with utmost care.

For example, the Turkish, Indian and Korean names in this dictionary
have all been independently lassified by several native speakers.
I also took special care to list only those names which can currently
be found.

The lesson from this?
Any modifications should be done very cautiously (and they must also
adhere to the sorting required by the search algorithm).

For example, knowing that "Sascha" is a boy's name in Germany, the author
never assumed the English "Sasha" to be a girl's name.
Knowing that "Jan" is a boy's name in Germany, I never assumed it to be
also a English short form of "Janet". Another case in point is the name
"Esra". This is a boy's name in Germany, but a girl's name in Turkey.

Or consider the following first names:

Mitja      male Russian name
Elizaveta  rare name; looks like misspelled "Elizabeta"
Roelf      rare name; looks like German "Rolf" with an erroneous 'e'

Borchert, Oltmann, Sievert, Hartmann    look like common German surnames

## Formats

A plus char ('+') "inside" a name symbolizes a '-', ' ' or an empty string
(this option applies to Chinese and Korean names only).
Thus, "Jun+Wei" represents the names "Jun-Wei", "Jun Wei" and "Junwei".


## Statistics of first names in dictionary


Number of first names   :   44568
   girl's names         :   16921
   boy's  names         :   17740
   unisex names         :    9907
Equivalent name pairs   :     734

Names from Great Britain  :  2232
Names from Ireland        :   876
Names from U.S.A.         :  3916
Names from Italy          :  2871
Names from Malta          :   526
Names from Portugal       :  1041
Names from Spain          :  1645
Names from France         :  1821
Names from Belgium        :  1518
Names from Luxembourg     :   564
Names from the Netherlands:  3302
Names from East Frisia    :  2589   ("Ostfriesland")
Names from Germany        :  2636
Names from Austria        :  1753
Names from Swiss          :  2464
Names from Iceland        :  1302
Names from Denmark        :  1139
Names from Norway         :  1064
Names from Sweden         :   974
Names from Finland        :   873
Names from Estonia        :  1121
Names from Latvia         :   710
Names from Lithuania      :   845
Names from Poland         :   359
Names from Czech Republic :   477
Names from Slovakia       :   477
Names from Hungary        :   371
Names from Romania        :  1971
Names from Bulgaria       :  1793
Names from Bosnia and Herzegovina:  1216
Names from Croatia        :   894
Names from Kosovo         :  1002
Names from Macedonia      :   851
Names from Montenegro     :   621
Names from Serbia         :   727
Names from Slovenia       :   636
Names from Albania        :  1748
Names from Greece         :   778
Names from Russia         :   489
Names from Belarus        :   508
Names from Moldova        :   405
Names from Ukraine        :   531
Names from Armenia        :   653
Names from Azerbaijan     :   764
Names from Georgia        :   293
Names from Kazakhstan/Uzbekistan,etc.:   862
Names from Turkey         :  1806
Names from Arabia/Persia  :  2025
Names from Israel         :  1067
Names from China          :  7334
Names from India/Sri Lanka:  1455
Names from Japan          :  1384
Names from Korea          :  1376
Names from Vietnam        :   307


## Statistics for Great Britain  (statistics are very good):
                rare            medium          common         total
first  names:  1485  201 143 100 100  80  80  30 10  3  0 0 0   2232
girl's names:   629   95  92  51  57  46  43  15  3  1  0 0 0   1032
boy's  names:   650   80  35  37  33  26  34  14  7  2  0 0 0    918
unisex names:   206   26  16  12  10   8   3   1  0  0  0 0 0    282

## Statistics for Ireland  (statistics are good):
                rare            medium          common         total
first  names:   311  134 124  78  80  65  53  25  6  0  0 0 0    876
girl's names:   175   73  60  43  46  44  27  16  2  0  0 0 0    486
boy's  names:   112   53  49  29  32  19  24   9  4  0  0 0 0    331
unisex names:    24    8  15   6   2   2   2   0  0  0  0 0 0     59

## Statistics for U.S.A.  (statistics are very good):
                rare            medium          common         total
first  names:  2646  401 292 202 190 103  56  18  8  0  0 0 0   3916
girl's names:  1468  206 155  93  92  48  27   8  1  0  0 0 0   2098
boy's  names:   953  152  99  71  69  37  22  10  7  0  0 0 0   1420
unisex names:   225   43  38  38  29  18   7   0  0  0  0 0 0    398

## Statistics for Italy  (statistics are very good):
                rare            medium          common         total
first  names:  1915  283 206 162 134  94  42  26  5  3  1 0 0   2871
girl's names:   910  142 118 101  75  45  21  12  1  1  1 0 0   1427
boy's  names:   999  141  88  61  59  49  21  14  4  2  0 0 0   1438
unisex names:     6    0   0   0   0   0   0   0  0  0  0 0 0      6

## Statistics for Malta  (statistics are medium quality):
                rare            medium          common         total
first  names:   137   93  74  79  47  43  30  11  7  3  2 0 0    526
girl's names:    41   42  17  35  23  23  18   2  2  1  1 0 0    205
boy's  names:    89   48  50  40  20  20  12   9  5  2  1 0 0    296
unisex names:     7    3   7   4   4   0   0   0  0  0  0 0 0     25

## Statistics for Portugal  (statistics are good):
                rare            medium          common         total
first  names:   509  181  84 120  70  36  14  13  7  3  3 1 0   1041
girl's names:   273   87  38  60  39  20   8   3  2  0  0 1 0    531
boy's  names:   235   92  46  58  29  16   6  10  5  3  3 0 0    503
unisex names:     1    2   0   2   2   0   0   0  0  0  0 0 0      7

## Statistics for Spain  (statistics are very good):
                rare            medium          common         total
first  names:   955  207 180 106  78  56  30  16  9  6  1 1 0   1645
girl's names:   530  110  91  46  45  34  10   9  3  1  0 1 0    880
boy's  names:   416   96  88  60  30  21  19   6  6  5  1 0 0    748
unisex names:     9    1   1   0   3   1   1   1  0  0  0 0 0     17

## Statistics for France  (statistics are very good):
                rare            medium          common         total
first  names:  1136  167 113 102  94  91  76  36  4  0  2 0 0   1821
girl's names:   686  111  72  56  60  58  43  13  0  0  1 0 0   1100
boy's  names:   313   42  35  42  33  29  33  21  3  0  1 0 0    552
unisex names:   137   14   6   4   1   4   0   2  1  0  0 0 0    169

## Statistics for Belgium  (statistics are very good):
                rare            medium          common         total
first  names:   489  253 204 181 186 120  55  26  1  3  0 0 0   1518
girl's names:   270  158 121  91 104  60  26   8  0  2  0 0 0    840
boy's  names:   169   76  70  82  73  51  26  17  1  1  0 0 0    566
unisex names:    50   19  13   8   9   9   3   1  0  0  0 0 0    112

## Statistics for Luxembourg  (statistics are very good):
                rare            medium          common         total
first  names:    77   59  86  77  83  76  56  35 11  2  2 0 0    564
girl's names:    40   25  40  51  52  52  30  13  1  1  1 0 0    306
boy's  names:    26   30  44  24  25  23  25  20  9  1  1 0 0    228
unisex names:    11    4   2   2   6   1   1   2  1  0  0 0 0     30

## Statistics for the Netherlands  (statistics are very good):
                rare            medium          common         total
first  names:  1976  426 329 233 147  99  66  22  3  1  0 0 0   3302
girl's names:  1006  226 186 119  74  58  28   9  0  0  0 0 0   1706
boy's  names:   781  150 105  91  53  28  34  13  3  1  0 0 0   1259
unisex names:   189   50  38  23  20  13   4   0  0  0  0 0 0    337

## Statistics for East Frisia  (statistics are good):
                rare            medium          common         total
first  names:  1411  529 210 147  91 106  62  31  2  0  0 0 0   2589
girl's names:   592  219 106  74  51  59  34   9  0  0  0 0 0   1144
boy's  names:   651  261  93  70  36  44  28  20  2  0  0 0 0   1205
unisex names:   168   49  11   3   4   3   0   2  0  0  0 0 0    240

## Statistics for Germany  (statistics are very good):
                rare            medium          common         total
first  names:  1872  189 145 132  90  86  73  41  8  0  0 0 0   2636
girl's names:   917   99  89  79  49  40  44  24  0  0  0 0 0   1341
boy's  names:   929   77  54  53  41  45  29  17  8  0  0 0 0   1253
unisex names:    26   13   2   0   0   1   0   0  0  0  0 0 0     42

## Statistics for Austria  (statistics are very good):
                rare            medium          common         total
first  names:  1090  175 126  99  84  69  59  40  7  4  0 0 0   1753
girl's names:   666  109  78  58  50  47  37  16  3  1  0 0 0   1065
boy's  names:   404   63  43  40  34  22  22  24  4  3  0 0 0    659
unisex names:    20    3   5   1   0   0   0   0  0  0  0 0 0     29

## Statistics for Swiss  (statistics are very good):
                rare            medium          common         total
first  names:  1252  359 289 204 169 101  53  32  5  0  0 0 0   2464
girl's names:   723  205 161 113  99  52  27  12  2  0  0 0 0   1394
boy's  names:   501  142 125  88  66  47  24  20  3  0  0 0 0   1016
unisex names:    28   12   3   3   4   2   2   0  0  0  0 0 0     54

## Statistics for Iceland  (statistics are very good):
                rare            medium          common         total
first  names:   329  199 188 148 142 122 100  50 19  5  0 0 0   1302
girl's names:   177   92  92  70  76  56  49  27  9  3  0 0 0    651
boy's  names:   152  107  96  78  66  66  51  23 10  2  0 0 0    651
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Denmark  (statistics are very good):
                rare            medium          common         total
first  names:   308  212 175 126  96  85  58  55 23  1  0 0 0   1139
girl's names:   180  118  97  71  48  54  31  31  9  0  0 0 0    639
boy's  names:   123   90  73  52  48  31  27  24 14  1  0 0 0    483
unisex names:     5    4   5   3   0   0   0   0  0  0  0 0 0     17

## Statistics for Norway  (statistics are good):
                rare            medium          common         total
first  names:   413  183 142  89  89  69  59  13  7  0  0 0 0   1064
girl's names:   234   92  73  46  46  32  31   3  1  0  0 0 0    558
boy's  names:   170   88  69  43  43  37  28  10  6  0  0 0 0    494
unisex names:     9    3   0   0   0   0   0   0  0  0  0 0 0     12

## Statistics for Sweden  (statistics are very good):
                rare            medium          common         total
first  names:   315  148 125 119  96  62  44  44 20  1  0 0 0    974
girl's names:   183   87  62  67  53  31  23  19 10  0  0 0 0    535
boy's  names:   125   58  62  50  42  31  21  25 10  1  0 0 0    425
unisex names:     7    3   1   2   1   0   0   0  0  0  0 0 0     14

## Statistics for Finland  (statistics are good):
                rare            medium          common         total
first  names:   244  101 129 113 107  72  60  33 13  1  0 0 0    873
girl's names:   142   57  65  61  58  30  35  13  8  0  0 0 0    469
boy's  names:   102   43  64  52  49  42  25  20  5  1  0 0 0    403
unisex names:     0    1   0   0   0   0   0   0  0  0  0 0 0      1

## Statistics for Estonia  (statistics are good):
                rare            medium          common         total
first  names:   449  183 103 122  93  93  56  22  0  0  0 0 0   1121
girl's names:   232  105  49  67  48  47  29  11  0  0  0 0 0    588
boy's  names:   214   78  54  55  45  46  27  11  0  0  0 0 0    530
unisex names:     3    0   0   0   0   0   0   0  0  0  0 0 0      3

## Statistics for Latvia  (statistics are good):
                rare            medium          common         total
first  names:   121  119  76 115 108  83  52  28  6  1  1 0 0    710
girl's names:    79   63  30  60  65  45  26  18  2  0  0 0 0    388
boy's  names:    42   56  46  55  43  38  26  10  4  1  1 0 0    322
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Lithuania  (statistics are good):
                rare            medium          common         total
first  names:   399  103  89  52  70  57  43  18  8  6  0 0 0    845
girl's names:   132   49  41  21  31  29  21   8  5  2  0 0 0    339
boy's  names:   267   54  48  31  39  28  22  10  3  4  0 0 0    506
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Poland  (statistics are good):
                rare            medium          common         total
first  names:    94   40  57  27  39  26  25  24 19  7  1 0 0    359
girl's names:    50   22  32  14  22  11   6  13  9  5  1 0 0    185
boy's  names:    44   18  25  13  17  15  19  11 10  2  0 0 0    174
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Czech Republic  (statistics are good):
                rare            medium          common         total
first  names:   149   64  48  49  48  39  30  27 10 12  1 0 0    477
girl's names:    97   40  27  32  26  23  16  20  4  3  0 0 0    288
boy's  names:    52   24  21  17  21  16  14   7  6  9  1 0 0    188
unisex names:     0    0   0   0   1   0   0   0  0  0  0 0 0      1

## Statistics for Slovakia  (statistics are good):
                rare            medium          common         total
first  names:    78   49  69  97  58  50  31  24 14  6  1 0 0    477
girl's names:    42   26  32  45  34  33  16  14  4  3  1 0 0    250
boy's  names:    36   23  37  52  24  17  15  10 10  3  0 0 0    227
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Hungary  (statistics are good):
                rare            medium          common         total
first  names:   117   49  20  34  37  36  29  21 21  7  0 0 0    371
girl's names:    65   28  11  17  18  26  20  15  9  2  0 0 0    211
boy's  names:    52   21   8  17  19  10   9   6 12  5  0 0 0    159
unisex names:     0    0   1   0   0   0   0   0  0  0  0 0 0      1

## Statistics for Romania  (statistics are very good):
                rare            medium          common         total
first  names:  1098  413 158  93  56  60  49  27 10  5  2 0 0   1971
girl's names:   724  234  99  53  36  38  25  14  4  0  1 0 0   1228
boy's  names:   374  179  59  40  20  22  24  13  6  5  1 0 0    743
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Bulgaria  (statistics are good):
                rare            medium          common         total
first  names:   748  241 244 142 162 126  66  42 16  6  0 0 0   1793
girl's names:   433  144 137  81  87  73  49  24  6  3  0 0 0   1037
boy's  names:   313   97 105  61  75  53  17  18 10  3  0 0 0    752
unisex names:     2    0   2   0   0   0   0   0  0  0  0 0 0      4

## Statistics for Bosnia and Herzegovina  (statistics are medium quality):
                rare            medium          common         total
first  names:   277  194 195 244 126 111  58  10  1  0  0 0 0   1216
girl's names:   113   96  85 104  40  49  28   7  1  0  0 0 0    523
boy's  names:   164   95 110 135  82  62  29   3  0  0  0 0 0    680
unisex names:     0    3   0   5   4   0   1   0  0  0  0 0 0     13

## Statistics for Croatia  (statistics are good):
                rare            medium          common         total
first  names:   256  217 103  97  63  67  51  31  6  2  1 0 0    894
girl's names:   127   95  44  48  36  34  26  17  1  1  0 0 0    429
boy's  names:   126  122  58  45  26  33  25  14  5  1  1 0 0    456
unisex names:     3    0   1   4   1   0   0   0  0  0  0 0 0      9

## Statistics for Kosovo  (statistics are medium quality):
                rare            medium          common         total
first  names:   257  188 184 174 117  52  27   3  0  0  0 0 0   1002
girl's names:   184   90  84  81  62  26  14   3  0  0  0 0 0    544
boy's  names:    73   96  99  93  55  26  13   0  0  0  0 0 0    455
unisex names:     0    2   1   0   0   0   0   0  0  0  0 0 0      3

## Statistics for Macedonia  (statistics are medium quality):
                rare            medium          common         total
first  names:   129  228 172 102  86  71  40  16  7  0  0 0 0    851
girl's names:    65   86  72  29  32  32  17  11  4  0  0 0 0    348
boy's  names:    64  140  98  72  53  39  23   5  3  0  0 0 0    497
unisex names:     0    2   2   1   1   0   0   0  0  0  0 0 0      6

## Statistics for Montenegro  (statistics are medium quality):
                rare            medium          common         total
first  names:   133  119  68  85  59  77  44  25 10  1  0 0 0    621
girl's names:    58   51  30  31  20  31  20  12  6  0  0 0 0    259
boy's  names:    73   67  37  53  39  46  23  13  4  1  0 0 0    356
unisex names:     2    1   1   1   0   0   1   0  0  0  0 0 0      6

## Statistics for Serbia  (statistics are medium quality):
                rare            medium          common         total
first  names:   150  139 103  61 121  68  45  27 11  2  0 0 0    727
girl's names:    79   70  49  19  52  32  22  13  5  1  0 0 0    342
boy's  names:    70   66  54  41  67  36  22  14  6  1  0 0 0    377
unisex names:     1    3   0   1   2   0   1   0  0  0  0 0 0      8

## Statistics for Slovenia  (statistics are medium quality):
                rare            medium          common         total
first  names:    62  144 106  85  90  62  48  31  7  1  0 0 0    636
girl's names:    34   66  44  33  36  36  25  13  2  1  0 0 0    290
boy's  names:    28   77  62  50  51  26  22  18  5  0  0 0 0    339
unisex names:     0    1   0   2   3   0   1   0  0  0  0 0 0      7

## Statistics for Albania  (statistics are good):
                rare            medium          common         total
first  names:   591  236 305 247 184 103  62  19  1  0  0 0 0   1748
girl's names:   315   97  87  75  60  49  34  12  1  0  0 0 0    730
boy's  names:   272  137 217 172 124  54  28   7  0  0  0 0 0   1011
unisex names:     4    2   1   0   0   0   0   0  0  0  0 0 0      7

## Statistics for Greece  (statistics are good):
                rare            medium          common         total
first  names:   359  123  49 107  45  32  27  18 11  5  2 0 0    778
girl's names:   242   74  30  58  25  20  16   9  7  1  1 0 0    483
boy's  names:   117   49  19  49  20  12  11   9  4  4  1 0 0    295
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Russia  (statistics are good):
                rare            medium          common         total
first  names:    73   51  69  73  46  55  34  33 28 23  4 0 0    489
girl's names:    44   28  38  44  28  29  14  14 11  8  2 0 0    260
boy's  names:    26   19  31  29  18  26  20  19 17 15  2 0 0    222
unisex names:     3    4   0   0   0   0   0   0  0  0  0 0 0      7

## Statistics for Belarus  (statistics are medium quality):
                rare            medium          common         total
first  names:    42   88  56  67  66  48  48  36 33 14 10 0 0    508
girl's names:    21   50  29  35  38  22  22  19  8  4  7 0 0    255
boy's  names:    21   35  27  32  26  26  26  17 25 10  3 0 0    248
unisex names:     0    3   0   0   2   0   0   0  0  0  0 0 0      5

## Statistics for Moldova  (statistics are medium quality):
                rare            medium          common         total
first  names:    44  104  72  37  42  31  31  21 14  9  0 0 0    405
girl's names:    31   60  38  18  20  12  19   8  6  4  0 0 0    216
boy's  names:    13   44  34  19  22  19  12  13  8  5  0 0 0    189
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Ukraine  (statistics are medium quality):
                rare            medium          common         total
first  names:    56   65  61  68  60  68  59  37 39 17  1 0 0    531
girl's names:    28   37  30  40  40  29  25  11 18  8  1 0 0    267
boy's  names:    28   28  26  28  20  39  34  26 21  9  0 0 0    259
unisex names:     0    0   5   0   0   0   0   0  0  0  0 0 0      5

## Statistics for Armenia  (statistics are medium quality):
                rare            medium          common         total
first  names:   101  101  81  66 156  68  46  24 10  0  0 0 0    653
girl's names:    51   64  18  24  68  28  20  11  6  0  0 0 0    290
boy's  names:    49   36  60  41  87  39  26  13  4  0  0 0 0    355
unisex names:     1    1   3   1   1   1   0   0  0  0  0 0 0      8

## Statistics for Azerbaijan  (statistics are medium quality):
                rare            medium          common         total
first  names:    91  211 157  85  93  76  31  18  2  0  0 0 0    764
girl's names:    30   93  86  42  52  37  14   7  2  0  0 0 0    363
boy's  names:    61  115  69  42  39  39  16  11  0  0  0 0 0    392
unisex names:     0    3   2   1   2   0   1   0  0  0  0 0 0      9

## Statistics for Georgia  (statistics are medium quality):
                rare            medium          common         total
first  names:    43   55  44  24  30  19  37  24 12  4  1 0 0    293
girl's names:    18   32  13   8  13   6  16   8  9  1  1 0 0    125
boy's  names:    25   23  31  16  17  13  21  16  3  3  0 0 0    168
unisex names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0

## Statistics for Kazakhstan/Uzbekistan,etc.  (statistics are medium quality):
                rare            medium          common         total
first  names:    93  152 134 196 159  61  45  19  3  0  0 0 0    862
girl's names:    46   79  83 101  82  30  20  14  2  0  0 0 0    457
boy's  names:    45   71  46  92  76  31  25   5  1  0  0 0 0    392
unisex names:     2    2   5   3   1   0   0   0  0  0  0 0 0     13

## Statistics for Turkey  (statistics are good):
                rare            medium          common         total
first  names:   455  408 280 272 212 115  45  12  6  1  0 0 0   1806
girl's names:   102  217 107 136 108  66  22   6  3  0  0 0 0    767
boy's  names:   331  170 150 120  98  48  22   5  3  1  0 0 0    948
unisex names:    22   21  23  16   6   1   1   1  0  0  0 0 0     91

## Statistics for Arabia/Persia  (statistics are good):
                rare            medium          common         total
first  names:   431  529 405 281 187 119  48  14  8  3  0 0 0   2025
girl's names:   191  189 158  97  73  50  21   7  3  0  0 0 0    789
boy's  names:   235  331 227 176 109  62  26   7  5  3  0 0 0   1181
unisex names:     5    9  20   8   5   7   1   0  0  0  0 0 0     55

## Statistics for Israel  (statistics are medium quality):
                rare            medium          common         total
first  names:   279  244 123 118  92 130  57  20  4  0  0 0 0   1067
girl's names:   138  111  62  43  36  66  21  11  2  0  0 0 0    490
boy's  names:   131  124  58  72  53  62  34   9  2  0  0 0 0    545
unisex names:    10    9   3   3   3   2   2   0  0  0  0 0 0     32

## Statistics for China  (statistics are very good):
                rare            medium          common         total
first  names:  5319 1126 507 194  82  46  26  23  8  3  0 0 0   7334
girl's names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0
boy's  names:     0    0   0   0   0   0   0   0  0  0  0 0 0      0
unisex names:  5319 1126 507 194  82  46  26  23  8  3  0 0 0   7334

## Statistics for India/Sri Lanka  (statistics are good):
                rare            medium          common         total
first  names:   225  463 371 219 116  45  15   1  0  0  0 0 0   1455
girl's names:   131  136 121  76  47  18   6   0  0  0  0 0 0    535
boy's  names:    71  289 197 102  39  11   4   1  0  0  0 0 0    714
unisex names:    23   38  53  41  30  16   5   0  0  0  0 0 0    206

## Statistics for Japan  (statistics are good):
                rare            medium          common         total
first  names:   429  266 204 142 153 110  56  22  2  0  0 0 0   1384
girl's names:   182   71  64  55  47  47  29  13  1  0  0 0 0    509
boy's  names:   215  180 130  77  98  56  21   5  1  0  0 0 0    783
unisex names:    32   15  10  10   8   7   6   4  0  0  0 0 0     92

## Statistics for Korea  (statistics are good):
                rare            medium          common         total
first  names:    65  579 341 136  91  50  36  33 20 22  2 1 0   1376
girl's names:     6  200 115  43  25   8   0   0  0  1  0 0 0    398
boy's  names:    24  274 125  40   6   0   0   0  0  0  0 0 0    469
unisex names:    35  105 101  53  60  42  36  33 20 21  2 1 0    509

## Statistics for Vietnam  (statistics are good):
                rare            medium          common         total
first  names:    32    0  36  41  39  39  34  31 26 19  7 1 2    307
girl's names:     0    0   0   0   0   0   0   0  3  0  0 0 1      4
boy's  names:     0    0   0   0   0   0   0   1  1  1  0 0 1      4
unisex names:    32    0  36  41  39  39  34  30 22 18  7 1 0    299
