# Valodu tehnoloģiju pamati (DatZB022)

LU Eksakto zinātņu un tehnoloģiju fakultātes Datorikas nodaļas Bakalaura studiju programmas kurss.

Kursā izmantotie [termini](VTI_termini.pdf); sk. arī [Termini.gov.lv](https://termini.gov.lv).

## Praktiskie darbi

### Rīkkopas valodas resursu priekšapstrādei

1. Teksta izgūšana: [TextExtraction.ipynb](notebooks/TextExtraction.ipynb)
2. Teksta priekšapstrāde: [TextPreprocessing.ipynb](notebooks/TextPreprocessing.ipynb)
3. Dinamiski ielādēta daudzvalodu satura apstrāde: [DW_scrape.ipynb](notebooks/DW_scrape.ipynb)

### Galīgie automāti un pārveidotāji

4. Morfoloģiskā analīze un sintēze: [HFST.ipynb](notebooks/HFST.ipynb), [HFST_en_and_more.ipynb](notebooks/HFST_en_and_more.ipynb)
5. Teksta izvēršana un savēršana: [Thrax.ipynb](notebooks/Thrax.ipynb), [Pynini.ipynb](notebooks/Pynini.ipynb)

### Gramatiskā analīze

6. Latviešu valodas morfoloģiskais analizators un sintezators: [TezaursAPI.ipynb](notebooks/TezaursAPI.ipynb)
7. Rīkkopas universālo atkarību parsēšanai: [ParsingUD.ipynb](notebooks/ParsingUD.ipynb)

### Statistiskie valodas modeļi

8. N-grammu modeļi: [NGram.ipynb](notebooks/NGram.ipynb)
9. TF-IDF : [tf-idf.ipynb](notebooks/tf_idf.ipynb) un Word2vec apmācība un lietojums: [Word2vec.ipynb](notebooks/Word2vec.ipynb)
10. Teksta klasificēšana: [LangID.ipynb](notebooks/LangID.ipynb), [NaiveBayes.ipynb](notebooks/NaiveBayes.ipynb)

Linkolnas Universitātes vieslekcijas [(https://github.com/cfrantzidis/sleepCare)]

### Neironu valodas modeļi

11. Teksta klasificēšana: [fastText.ipynb](notebooks/fastText.ipynb) (*1-layer*, *linear*) &rarr; [BERT.ipynb](notebooks/BERT.ipynb) (*deep*, *non-linear*)
12. Modeļi un demonstrācijas Hugging Face platformā:
- Skatīt [Tasks](https://huggingface.co/tasks), piemēram:
  - `Feature Extraction`: [AiLab-IMCS-UL/lvbert](https://huggingface.co/AiLab-IMCS-UL/lvbert)
  - `Fill-Mask`: [google-bert/bert-base-cased](https://huggingface.co/google-bert/bert-base-cased)
  - `Sentence Similarity`: [sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2](https://huggingface.co/sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2)
13. Vārdšķiru un morfoloģiskā marķēšana (Part of Speech (POS) Tagging): [POS_tagging.ipynb](notebooks/POS_tagging.ipynb)
14. Nosaukto entitāšu marķēšana (Named entity recognition): [NER.ipynb](notebooks/NER.ipynb)

## [BSSDH 2024 Workshop 4](https://www.digitalhumanities.lv/bssdh/2024/lectures-and-workshops/)

1. Introduction: [slides](notebooks/resources/BSSDH2024/Intro.pdf)
2. Hands-on session: [notebook](notebooks/BSSDH2024.ipynb) (draft)
3. Initial results: [corpus](https://sandbox.nosketch.korpuss.lv/#dashboard?corpname=BSSDH2024) (draft)

## Ievads datorlingvistikā (SDSKM018)

LU HZF maģistra studiju programmas kurss:

1. Teksta korpusa izveide: [notebook](notebooks/CrawlingSimple.ipynb)
2. Teksta korpusa marķēšana: [notebook](notebooks/NLPPipeSimple.ipynb), [korpuss](notebooks/resources/velnini.txt)

## Autori

prof. Inguna Skadiņa\
asoc. prof. Normunds Grūzītis\
asistents Viesturs Jūlijs Lasmanis

## Atbalsts

Kursa izstrādi finansē Eiropas Savienības Atveseļošanas un noturības mehānisma investīcija un valsts budžets projekta “Valodu tehnoloģiju iniciatīva” (2.3.1.1.i.0/1/22/I/CFLA/002) ietvaros.
