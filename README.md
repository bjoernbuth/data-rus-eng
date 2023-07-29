[![License](https://img.shields.io/badge/license-%20CC--BY-blue.svg)](LICENSE)


## General information

Title of the dataset: "Data used by SMARTool for English-speaking learners of Russian"

DOI: (to be filled out later)

Contact information:
- Name: Janda, Laura A.
- Institution: UiT The Arctic University of Norway
- Email: laura.janda@uit.no
- ORCID: https://orcid.org/0000-0001-5047-1909

Contributors:
- Bast, Radovan (UiT The Arctic University of Norway) - ORCID: 0000-0002-7658-1847
- Janda, Laura A. (UiT The Arctic University of Norway) - ORCID: 0000-0001-5047-1909
- Kopotev, Mikhail (University of Helsinki): ORCID: 0000-0002-4998-2952
- Lyashevskaya, Olga (National Research University Higher School of Economics) - ORCID: 0000-0001-8374-423X
- McDonald, James D.
- Nesset, Tore (UiT The Arctic University of Norway): - ORCID: 0000-0003-1308-3506
- Rakhilina, Ekaterina (National Research University Higher School of Economics) - ORCID: 0000-0002-7126-0905
- Sokolova, Svetlana (UiT The Arctic University of Norway) - ORCID: 0000-0002-1353-0452
- Sudarikova, Evgeniia (Higher School of Economics in Moscow)
- Tyers, Francis M. (Indiana University) - ORCID: 0000-0001-6108-2220
- Zhukova, Valentina (UiT The Arctic University of Norway) - ORCID: 0000-0002-8058-6480
- Elizaveta Kibisova (Higher School of Economics in Moscow) - ORCID: 0000-0001-8922-9239

Data type: textual linguistic data

Date of data collection/generation: 2016-2022

Geographic location: Russia

Funding sources:
- The Norwegian Agency for International Cooperation and Quality Enhancement in Higher Education (Diku): CPRU-2017/10027


## Description of the dataset

Data used by: SMARTool for English-speaking learners of Russian (website:
https://smartool.github.io/smartool-rus-eng/, source code:
https://github.com/smartool/smartool-rus-eng)

The SMARTool is a free web resource for L2 learners of Russian that
implements findings of a learning simulation experiment and corpus
research to optimize the acquisition of Russian vocabulary and
morphology. Corpus data (Janda & Tyers 2018) reveals that for any given
Russian lexeme, only a few (usually 1-3) wordforms account for nearly
all attestations, while remaining wordforms are rare or unattested. Our
computational learning experiment shows that learning of Russian
inflection is best when training is restricted to high frequency
wordforms. The SMARTool builds on these findings for a basic vocabulary
of 3000 nouns, adjectives, and verbs culled from major textbooks and
other sources to represent levels A1, A2, B1, and B2 (CEFR scale). We
have identified both a) the three most frequent wordforms for each
lexeme (reducing the target number of wordforms to learn from 150,000 to
9,000) and b) the most typical grammatical constructions and
collocations that motivate each wordform. We have also created c)
corpus-based example sentences instantiating typical use.

Audio for all sentences (in both female and male voices) and English
translations are available at the click of a button. The SMARTool has
filters that facilitate searching by: a) CEFR Level, b) Topic (such as
время/time, еда/food, здоровье/health etc.), c) Analysis (such as
Ins.Sing, facilitating grammatical exercises), and d) Dictionary form.


## Data sources

Lexemes were selected from a merged list of vocabulary from five Russian
language textbooks (Hertz et al. 2001, Chernyshov 2004, Robin, Shatalina, and
Evans-Romaine 2012, deBenedette et al. 2013, Bondar’ and Lutin 2013) plus the
Лексический минимум по русскому языку как иностранному (Andriushchina et al.
2014–2015) for the corresponding levels. A panel of experienced teachers of
Russian from three universities in Russia and Europe collaborated on the
selection of lexemes (see SMARTool Authors):
- Hertz, Birgitte, Hanne Leervad, Henrik Lærkes, Henrik Møller, and Peter
  Schousboe. 2001. Свидание в Петербурге. Møde i Petersborg. Copenhagen:
  Gyldendal.
- Chernyshov, Stanislav. 2004. Poexali! St. Petersburg: Zlatoust.
- Robin, Richard, Galina Shatalina, and Karen Evans-Romaine. 2012. Golosa. Vols
  1–2. 5th ed. New York: Pearson.
- deBenedette, Lynne, William J. Comer, Alla Smyslova, and Jonathan Perkins.
  2013. Между нами (Between You and Me): An Interactive Introduction to
  Russian. Accessed April 1, 2018. http://www. mezhdunami.org/.
- Andriushchina, N. P., G. A. Bitekhtina, L. P. Klobukova, L. N. Noreiko, I. V.
  Odintsova, eds. 2014–2015. Leksicheskii mimimum po russkomu iazyku kak
  inostrannomu. Levels A1–B2. St. Petersburg: Zlatoust.


## Data and file overview

- README.md: contains metadata about the dataset
- SMARTool_data_A1.csv: example sentences for the A1 level
- SMARTool_data_A2.csv: example sentences for the A2 level
- SMARTool_data_Abbreviations.csv: mapping abbreviations to their full names
- SMARTool_data_B1.csv: example sentences for the B1 level
- SMARTool_data_B2.csv: example sentences for the B2 level
- SMARTool_data_Terms.csv: mapping grammatical terms to their full names
- SMARTool_data_Topics.csv: mapping topics to their translations


## Sharing/access information

The dataset is provided under the [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/)


## Related publications

1.  Janda, Laura A. and Francis M. Tyers. 2021. Less is more: why all paradigms
    are defective, and why that is a good thing.  *Corpus Linguistics and
    Linguistic Theory* 14(2), 33pp.  <doi.org/10.1515/cllt-2018-0031>.

2.  Janda, Laura A. 2019. Businessmen and Ballerinas Take Different
    Forms: A Strategic Resource for Acquiring Russian Vocabulary and
    Morphology. *Russian Language Journal* 69, 175--193.

3.  Janda, Laura A. 2021. Getting more out of limited input: strategic
    mastery of foreign languages. In: papers of the Kazan International
    Linguistic Summit "Challenges and Trends in World Linguistics"
    **Вызовы и тренды мировой лингвистики: **Казанский международный
    лингвистический саммит (Казань, 16--20 ноября 2020 г.): тр. и
    матер.: в 2 т. / под общ. ред. Р.Р. Замалетдинова, Ф.Х. Тарасовой,
    Е.А. Горобец. -- Казань: Издательство Казанского университета. --
    Т. 1. -- 450 с., <https://cloud.mail.ru/public/xeKT/vGMAQBUMa> , pp.
    280--284.
