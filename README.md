# Supplementary Materials for the article ‘Genre and the Distribution of Dialogue: Direct Speech and Genre in 500 Contemporary Novels in Swedish’

**May 25, 2025.**

## Data about the books included in the corpus

The corpus data files consist of tables in the form of five comma-separated values (CSV) files:

(1) [`gddcorpus.csv`](gddcorpus.csv): A csv listing the 501 works in the corpus subjected to the full quantitative analysis. See note below (and the main article) on the selection.
The metadata fields are as follows:

`id`: Project-specific book identifier.

`title`: Title.

`all_authors`: Listing of the author(s).

`author_gender`:	F, M, or 2. (2 for two gender teams.)

`publisher`: Publisher.

`publication_date`: Publication date.

`subset`: Reason for selection: bestseller, beststreamer, original (Storytel Original), or august (August prize nominee, including winner).

`award`: Award for which the work was a nominee, including winner, if any. Empty in most cases. August obviously the most common non-blank value.

`category`: Crime, prestige, romance, or other.

`orthography`: Orthography for direct speech dialogue: quot(ation mark) or dash.

(2) [`gddcorpex.csv`](gddcorpex.csv): A csv listing the 32 works which had non-standard orthographies for direct speech dialogue and in one case (Minnestrådar) a very deviant use of this device. These were only analysed qualitatively, and thus excluded from the quantitative part of the study. Fields as above, adding `dialogue_style`, describing the (non-standard) orthography, and thus motivating the works exclusion from the main study.

(3) [`gddvals.csv`](gddvals.csv): A csv listing of the following measurements for the works in the mdcorp.csv: 1) the relative amount of direct speech dialogue (`rfdsd`, in parts per million), 2) the mean length of the direct speech dialogue insets (`mninsl`, in words), and 3) the length of the works, as word count (`wc`).

(4) [`dial_time10.csv`](dial_time10.csv): A csv collecting, for each work in `gddcorp.csv`, the relative amount of direct speech dialogue for each part when the text is divided into ten equally long parts (based on word count) (`b0` to `b9`, in parts per million).

(5) [`dial_time20.csv`](dial_time20.csv): A csv collecting, for each work in `gddcorp.csv`, the relative amount of direct speech dialogue for each part when the text is divided into twenty equally long parts (based on word count) (`b0` to `b19`, in parts per million).

## Note: The Subset of the Corpus behind the Full Quantitative Analysis

As mentioned in the article, the corpus behind the study comprises 533 books, but 32 books were excluded from the full quantitative analysis. In 31 of these cases the books do not contain substantial amounts of DSD marked in a clear or conventional way. Carola Hansson’s *Minnestrådar* (2019) represents another kind of exception. Here, the DSD form is used as an overarching narrative technique, where one character (Madame Vidal) is retelling the main story as it appeared from her memory to two listeners, who are only minor characters in the narrative as a whole. Since the narration is more or less completely embedded in the DSD in Hansson’s book, it becomes an extreme outlier for all measures concerning direct speech, which makes it less productive to analyse quantitatively (although the monologue form of Madame Vidal’s retellings of course ontologically has the status of a dialogue). For this reason – its extreme outlier position and its use of DSD differently than all other novels in the corpus – it was been excluded from the quantitative calculations, leaving 501 books. Notably, the 32 titles excluded from the quantitative analysis all belong either to the category of prestige fiction (24) or to other fiction (8). A listing of the reasons for excluding these 32 books from the computational analysis is found in the file `gddcorpex.csv`.
