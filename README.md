# GermEval 2019 Task 3: Shared task on the lemmatization of German web and social media texts (EmpiriST-lemmatization 2019) #

## Goal ##

The goal of the shared task is to encourage the developers of NLP
applications to adapt their tools and resources to the lemmatization
of German Web pages and written German discourse in genres of
computer-mediated communication (CMC). Examples for CMC genres are
chats, forums, wiki talk pages, tweets, blog comments, social
networks, SMS and WhatsApp dialogues.

The shared task is a follow-up to the [EmpiriST 2015 shared
task](https://sites.google.com/site/empirist2015/), which focused on
tokenization and POS-tagging. The current task focuses on the next
fundamental step in the NLP pipeline. Lemmatization is crucial for
general corpus indexing purposes as well as for many applications in
lexicography, text classification, discourse analysis, etc.

## Tasks ##

Participants will receive pre-tokenized and pre-tagged text files
and will have to provide surface-oriented lemmata and/or
normalized lemmata. Surface-oriented lemmata are mainly based on
the inflectional suffixes of the token and retain, as far as
possible, any non-standard orthographical features of the
token. For normalized lemmata, on the other hand, obvious
spelling errors are corrected and non-standard forms are treated
as standard forms.

### Subtask 1: Surface-oriented lemmatization ###

    XD	EMOASC	XD
    du	PPER	du
    killst	VVFIN	killen
    mich	PPER	mich
    !	$.	!
    Soooo	PTKIFG	soooo
    herrlich	ADJD	herrlich
    xDD	EMOASC	xDD


### Subtask 2: Normalized lemmatization ###

    XD	EMOASC	XD
    du	PPER	du
    killst	VVFIN	killen
    mich	PPER	mich
    !	$.	!
    Soooo	PTKIFG	so
    herrlich	ADJD	herrlich
    xDD	EMOASC	xDD


## Schedule ##

  * 2019-04-26: Release of training data
  * 2019-07-15 to 2019-07-25: Evaluation period
  * 2019-07-31: Publication of results
  * 2019-08-15: Submission of system description papers
  * 2019-08-31: Notification of acceptance
  * 2019-10-01: Camera-ready papers due
  * 2019-10-08: Workshop in Erlangen, Germany

The shared task will be a pre-conference workshop of the Conference on
Natural Language Processing (“Konferenz zur Verarbeitung natürlicher
Sprache”, KONVENS) hosted on October 8, 2019 at FAU
Erlangen-Nuremberg, see <http://2019.konvens.org/>.

## Mailing list ##

All participants and further interested parties are invited to
register to our [mailing
list](https://lists.fau.de/cgi-bin/listinfo/workshop-lemmatisierung).

## Lemmatization guidelines ##

The training and test data of the shared task have been manually
lemmatized according to our [lemmatization
guidelines](doc/lemmatisierungsrichtlinien.pdf) (in German) that are
an extension of the [TIGER annotation
scheme](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/TIGERCorpus/annotation/tiger_scheme-morph.pdf).

## Data sets ##

The training data were individually lemmatized by four student
annotators according to our [lemmatization
guidelines](doc/lemmatisierungsrichtlinien.pdf). Unclear cases were
decided in group meetings with the task organizers.

  * [training data](data/empirist-lemmatization_training_data_2019-04-26.zip) (2019-04-26)

## Organizers ##

The shared task is organized by:

  * [Natalie Dykes](https://www.germanistik.phil.fau.de/person/natalie-dykes/)
  * [Stefan Evert](http://www.stefan-evert.de/)
  * [Philipp Heinrich](https://philipp-heinrich.eu/)
  * [Besim Kabashi](http://besim-kabashi.net/)
  * [Thomas Proisl](https://thomas-proisl.de/)
