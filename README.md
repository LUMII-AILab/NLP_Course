# Praktiskie darbi valodu tehnoloģijās

LU Eksakto zinātņu un tehnoloģiju fakultātes Datorikas nodaļas bakalaura un maģistra studiju programmas kursi:

* Bakalaura programma: Valodu tehnoloģiju pamati (DatZB022-LV, DatZB022-EN)
* Maģistra programma: Valodu tehnoloģiju lietojumi (DatZM037)

Kursā izmantotie [termini](VTI_termini.pdf); sk. arī [Termini.gov.lv](https://termini.gov.lv).

## Bakaulara programmas praktiskie darbi

### Rīkkopas valodas resursu priekšapstrādei

1. Teksta izgūšana: [TextExtraction.ipynb](notebooks/TextExtraction.ipynb)
2. Teksta priekšapstrāde: [TextPreprocessing.ipynb](notebooks/TextPreprocessing.ipynb)
3. Dinamiski ielādēta daudzvalodu satura apstrāde: [DW_scrape.ipynb](notebooks/DW_scrape.ipynb)

### Galīgie automāti un pārveidotāji

4. Morfoloģiskā analīze un sintēze: [HFST.ipynb](notebooks/HFST.ipynb), [HFST_en_and_more.ipynb](notebooks/HFST_en_and_more.ipynb)
5. Teksta izvēršana un savēršana: [Thrax.ipynb](notebooks/Thrax.ipynb), [Pynini.ipynb](notebooks/Pynini.ipynb)

### Gramatiskā analīze

6. Latviešu valodas morfoloģiskais analizators un sintezators: [TezaursAPI.ipynb](notebooks/TezaursAPI.ipynb)
7. Rīkkopas tekstvienību morfoloģiskajai marķēšanai: [POS_tagging.ipynb](notebooks/POS_tagging.ipynb)
8. Rīkkopas universālo atkarību parsēšanai: [ParsingUD.ipynb](notebooks/ParsingUD.ipynb)

### Statistiskie valodas modeļi

9. N-grammu modeļi: [NGram.ipynb](notebooks/NGram.ipynb)
10. TF-IDF : [tf-idf.ipynb](notebooks/tf_idf.ipynb) un Word2vec apmācība un lietojums: [Word2vec.ipynb](notebooks/Word2vec.ipynb)
11. Teksta klasificēšana: [LangID.ipynb](notebooks/LangID.ipynb), [NaiveBayes.ipynb](notebooks/NaiveBayes.ipynb)


### Neironu valodas modeļi

12. Teksta klasificēšana: [fastText.ipynb](notebooks/fastText.ipynb) (*1-layer*, *linear*) &rarr; [BERT.ipynb](notebooks/BERT.ipynb) (*deep*, *non-linear*)
13. Modeļi un demonstrācijas Hugging Face platformā:
- Skatīt [Tasks](https://huggingface.co/tasks), piemēram:
  - `Feature Extraction`: [AiLab-IMCS-UL/lvbert](https://huggingface.co/AiLab-IMCS-UL/lvbert)
  - `Fill-Mask`: [google-bert/bert-base-cased](https://huggingface.co/google-bert/bert-base-cased)
  - `Sentence Similarity`: [sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2](https://huggingface.co/sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2)
14. Vārdšķiru un morfoloģiskā marķēšana (Part of Speech (POS) Tagging): [POS_tagging.ipynb](notebooks/POS_tagging.ipynb)
15. Nosaukto entitāšu marķēšana (Named entity recognition): [NER.ipynb](notebooks/NER.ipynb)
16. LLM darbināšana mākonī: [LLM_as_a_service.ipynb](notebooks/LLM_as_a_service.ipynb)
17. LLM novērtēšana ar etalonuzdevumiem: [LLM_evaluation.ipynb](notebooks/LLM_evaluation.ipynb)


## Maģistra programmas praktiskie darbi

### Kodētāju un kodētāju-dekodētāju izmantošana, pielāgošana

1. Teksta klasificēšana ar BERT: [TextClassificationWithBERT.ipynb](notebooks/MSP/TextClassificationWithBERT.ipynb)
2. Tekstvienību klasificēšana ar BERT, T5 - interpunkcijas uzdevums: [bert_punctuation.ipynb](notebooks/MSP/bert_punctuation.ipynb), [seq2seq_punctuation.ipynb](notebooks/MSP/seq2seq_punctuation.ipynb)
3. Tekstvienību pozicionālā kodēšana: [positional_encoding.ipynb](notebooks/MSP/positional_encoding.ipynb)
4. BERT jēdzienvektoru dimensiju reducēšana, vizualizēšana: [PCA_of_BERT_embeddings.ipynb](notebooks/MSP/positional_encoding.ipynb)

### LLM izmantošana, pielāgošana, novērtēšana

5. LLM darbināšana mākonī: [LLM_as_a_service.ipynb](notebooks/MSP/LLM_as_a_service.ipynb)
6. LLM darbināšana, izmantojot Ollama: [ollama_LLMs_prompting.ipynb](notebooks/MSP/ollama_LLMs_prompting.ipynb)
7. LLM novērtēšana - etalonuzdevumi: [evaluation.ipynb](notebooks/MSP/Evaluation.ipynb)
8. LLM novērtēšana - perpleksitāte: [llm_perplexity.ipynb](notebooks/MSP/llm_perplexity.ipynb)
9. Multimodālu tiešraides komentāru ģenerēšana: [live_commentary_demo.ipynb](notebooks/MSP/live_commentary_demo.ipynb)
10. LLM aģenti - ārēju rīku izsaukšana: [LLM_ToolCalling.ipynb](notebooks/MSP/LLM_ToolCalling.ipynb)
11. LLM aģenti - "vibe coding": [LLM_VibeCode.ipynb](notebooks/MSP/LLM_VibeCode.ipynb)
12. RAG demonstrācija: [RAG_demo.ipynb](notebooks/MSP/RAG_demo.ipynb)

### ASR modeļu izmantošana, novērtēšana

13. Eksperimenti latviešu valodā: [speech_recognition.ipynb](notebooks/MSP/speech_recognition.ipynb)
14. Valodas atpazīšana (klasificēšana): [spoken_language_recognition.ipynb](notebooks/MSP/spoken_language_recognition.ipynb)


## Citas nodarbības

### [BSSDH 2024 Workshop 4](https://www.digitalhumanities.lv/bssdh/2024/lectures-and-workshops/)

1. Introduction: [slides](notebooks/resources/BSSDH2024/Intro.pdf)
2. Hands-on session: [notebook](notebooks/BSSDH2024.ipynb) (draft)
3. Initial results: [corpus](https://sandbox.nosketch.korpuss.lv/#dashboard?corpname=BSSDH2024) (draft)

### Ievads datorlingvistikā (SDSKM018)

LU HZF maģistra studiju programmas kurss:

1. Teksta korpusa izveide: [notebook](notebooks/CrawlingSimple.ipynb)
2. Teksta korpusa marķēšana: [notebook](notebooks/NLPPipeSimple.ipynb), [korpuss](notebooks/resources/velnini.txt)


## Autori

prof. Inguna Skadiņa\
prof. Normunds Grūzītis\
Viesturs Jūlijs Lasmanis\
Artūrs Znotiņš\
Roberts Darģis\
Paulis Filips Bārzdiņš


## Atbalsts

Kursa izstrādi finansē Eiropas Savienības Atveseļošanas un noturības mehānisma investīcija un valsts budžets projekta “Valodu tehnoloģiju iniciatīva” (2.3.1.1.i.0/1/22/I/CFLA/002) ietvaros.

## Citation

If you find this useful in your research, please consider citing: 

	@inproceedings{skadina-etal-2026-teaching-nlp,
    title = "Teaching {NLP} in the {AI} Era: Experiences from the {U}niversity of {L}atvia",
    author = "Skadina, Inguna  and
      Barzdins, Guntis  and
      Boj{\={a}}rs, Uldis  and
      Gruzitis, Normunds  and
      Paikens, P{\={e}}teris",
    editor = {A{\ss}enmacher, Matthias  and
      Biester, Laura  and
      Borg, Claudia  and
      Kov{\'a}cs, Gy{\"o}rgy  and
      Mieskes, Margot  and
      Serrano, Sofia},
    booktitle = "Proceedings of the Seventh Workshop on Teaching Natural Language Processing ({T}each{NLP} 2026)",
    month = mar,
    year = "2026",
    address = "Rabat, Morocco",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.teachingnlp-1.6/",
    doi = "10.18653/v1/2026.teachingnlp-1.6",
    pages = "34--36",
    ISBN = "979-8-89176-375-3"
}


