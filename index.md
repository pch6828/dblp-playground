[DBLP](https://dblp.uni-trier.de/) is an online database of academic publications in computer science and related fields. Handily, all of its data is available as an XML file, which can be converted into an SQL database and queried. Here, I share a few fun facts I discovered while exploring the data that DBLP holds about two of the main conferences on programming languages; namely, POPL and PLDI.

_Note: In what follows, I define a paper to be any entry in the proceedings that is at least four pages long. This slightly coarse rule means that some very short but legitimate papers may not get counted. There may also be a small number of entries that are not legitimate papers, such as extended tributes or announcements, but which get counted anyway._

Last update: 2-Jan-2021.

## Most papers

### POPL
<details>
  <summary>Click to expand.</summary>

rank  |  name | count 
------|--------------------|-------
1 | Benjamin C. Pierce |24
2 | Robert Harper 0001 |21
3 | Thomas W. Reps |18
3 | Derek Dreyer   |18
4 | Matthias Felleisen |16
5 | Shmuel Sagiv   |15

</details>

### PLDI

 rank |  name   | count 
------|---------------------|-------
1 | Alexander Aiken |30
2 | Martin T. Vechev|21
3 | Rastislav Bodík |18
3 | Martin C. Rinard|18
4 | Sumit Gulwani   |17
5 | Kathryn S. McKinley |16

### Both together

 rank |  name  | count 
------|--------------------|-------
1 | Alexander Aiken|43
2 | Martin C. Rinard   |30
3 | Shmuel Sagiv   |29
3 | Martin T. Vechev   |29
4 | Thomas W. Reps |28
4 | Sumit Gulwani  |28
5 | Rastislav Bodík|25
5 | Robert Harper 0001 |25

## Longest vacations

_That is, the longest gap between successive papers._

### POPL

 rank |  name   | from | to | gap 
------|---------------------|-----------|----------|-----
1 | Dennis E. Shasha|  1984 | 2018 |  34
2 | Alan Mycroft|  1986 | 2017 |  31
3 | Uday S. Reddy   |  1985 | 2012 |  27
4 | Kedar S. Namjoshi   |  1995 | 2020 |  25
4 | Guy L. Steele Jr.   |  1994 | 2019 |  25
4 | Luc Maranget|  1991 | 2016 |  25
4 | Bengt Jonsson   |  1989 | 2014 |  25
5 | Maurice Herlihy |  1987 | 2010 |  23
5 | Mark P. Jones   |  1997 | 2020 |  23
5 | Pierre-Louis Curien |  1993 | 2016 |  23

### PLDI

 rank | name  | from | to | gap 
------|-------------------|-----------|----------|-----
1 | Barbara Liskov|  1988 | 2015 |  27
2 | Roland H. C. Yap  |  1992 | 2018 |  26
3 | Joxan Jaffar  |  1992 | 2015 |  23
4 | M. Frans Kaashoek |  1997 | 2019 |  22
5 | Edith Schonberg   |  1989 | 2010 |  21

## Longest careers

_That is, the longest period between first paper and most recent paper._

### POPL

 rank | name  | from  | to  | span 
------|-------------------|------|------|------
1 | Patrick Cousot| 1977 | 2019 |   42
2 | Philip Wadler | 1980 | 2018 |   38
2 | Thomas W. Reps| 1981 | 2019 |   38
3 | Gordon D. Plotkin | 1984 | 2020 |   36
3 | Dexter Kozen  | 1984 | 2020 |   36
4 | Radhia Cousot | 1977 | 2012 |   35
5 | Dennis E. Shasha  | 1984 | 2018 |   34
5 | John C. Reynolds  | 1978 | 2012 |   34

### PLDI

 rank |  name  | from  | to  | span 
------|--------------------|------|------|------
1 | Suresh Jagannathan | 1987 | 2019 |   32
1 | John H. Reppy  | 1988 | 2020 |   32
1 | Thomas W. Reps | 1988 | 2020 |   32
1 | Alexander Aiken| 1988 | 2020 |   32
2 | Monica S. Lam  | 1988 | 2019 |   31
3 | R. Kent Dybvig | 1990 | 2020 |   30
4 | J. Eliot B. Moss   | 1987 | 2016 |   29
4 | Keshav Pingali | 1989 | 2018 |   29
4 | Guy E. Blelloch| 1991 | 2020 |   29
5 | Barbara Liskov | 1988 | 2016 |   28

## Longest streaks

### POPL

 rank |  name  | from | to | streak length 
------|--------------------|-------|------|--------------
1 | Derek Dreyer   |  2009 | 2018 |   10
2 | John C. Mitchell   |  1984 | 1992 |9
3 | Nikhil Swamy   |  2012 | 2019 |8
3 | Amir Pnueli|  1980 | 1987 |8
3 | Benjamin C. Pierce |  1991 | 1998 |8

### PLDI

 rank |name | from | to | streak length 
------|-----------------|-------|------|--------------
1 | Alexander Aiken |  2011 | 2020 |   10
2 | Sumit Gulwani   |  2008 | 2015 |8
2 | Alexander Aiken |  2001 | 2008 |8
3 | Isil Dillig |  2014 | 2020 |7

## Most papers in a single conference

### POPL

 rank |   name| year | papers 
------|-----------------------|----------|-------
1 | Derek Dreyer  | 2020 | 4
2 | Adam Chlipala | 2015 | 3
2 | Deian Stefan  | 2019 | 3
2 | Derek C. Oppen| 1978 | 3
2 | Gilles Barthe | 2020 | 3
2 | Justin Hsu| 2020 | 3
2 | Karl Crary| 2003 | 3
2 | Krishnendu Chatterjee | 2018 | 3
2 | Nobuko Yoshida| 2019 | 3
2 | Robert Harper 0001| 2003 | 3
2 | Simon L. Peyton Jones | 2014 | 3
2 | Swarat Chaudhuri  | 2014 | 3
2 | Viktor Vafeiadis  | 2019 | 3
2 | Zachary Kincaid   | 2014 | 3

### PLDI

 rank |   name   | year | papers 
------|----------------------|----------|-------
1 | Martin T. Vechev | 2018 | 4
1 | Sumit Gulwani| 2011 | 4
2 | Andrew C. Myers  | 2015 | 3
2 | Armando Solar-Lezama | 2016 | 3
2 | David I. August  | 2011 | 3
2 | Hongseok Yang| 2014 | 3
2 | James R. Larus   | 1999 | 3
2 | Kathryn S. McKinley  | 2010 | 3
2 | Loris D'Antoni   | 2020 | 3
2 | Martin T. Vechev | 2012 | 3
2 | Martin T. Vechev | 2020 | 3
2 | Milind Kulkarni 0001 | 2019 | 3
2 | Peter Lee 0001   | 1998 | 3
2 | Rahul Sharma 0001| 2016 | 3
2 | Rastislav Bodík  | 2007 | 3
2 | Rastislav Bodík  | 2005 | 3
2 | Thomas W. Reps   | 2020 | 3