## Noé Diette

Statistics and machine learning engineering student at ENSAI, Rennes.

---

### Projects

**[Recipe Parser](https://github.com/no0e/recipe-parser)** - fine-tuning a small LLM for structured extraction
Turns a messy recipe blog page (life story, ads, comments) into a clean structured recipe.
Qwen2.5-1.5B fine-tuned with QLoRA on synthetic noisy pages: 0.93 ingredient F1 on page layouts
never seen in training, against 0.61 for a rule-based parser and 0.18 for one-shot prompting.
Exported to GGUF and served on CPU with llama.cpp, with a live demo on Cloud Run.
`QLoRA` `Qwen2.5` `llama.cpp` `FastAPI`

**[Causal Uplift on the Criteo Trial](https://github.com/no0e/causal-uplift)** - who should see an ad
Not "who will visit" but "who will visit *because of* the ad". Five uplift models on a 14M-row
randomised trial, processed out of core with DuckDB and Polars: treating only the top 10% of
users keeps 85% of the campaign's incremental visits, against 11% for random targeting.
`causal inference` `EconML` `DoWhy` `DuckDB`

**[Two-Stage Hybrid Recommender](https://github.com/no0e/two-stage-recommender)** - sequential recommendation on Amazon products
LightGCN for candidate retrieval, BERT4Rec for reranking, content-based
embeddings for the cold-start items neither of them can see. First place out of
80 teams (2 to 4 students each) in an in-class Kaggle competition.
`LightGCN` `BERT4Rec` `cold start`

**[Hateful Memes: CA-AGFN](https://github.com/no0e/hateful-memes-ca-agfn)** - multimodal detection when text and image disagree
A meme is often hateful only through the combination of its text and its image.
The starting idea was to fuse the two explicitly: a clash feature between CLIP's text and image
embeddings, and a gate that decides how much to trust each side. A 27-run ablation then tested
that idea against simpler baselines, and plain concatenation turned out to do better.
`CLIP` `multimodal fusion` `ablation study`

**[UBJR Eats API](https://github.com/no0e/ubjr-eats-api)** - a delivery platform backend
FastAPI over a layered Model/DAO/Service architecture, JWT authentication for
three user roles, PostgreSQL, and test modules across the data and service
layers. Academic team project, 4 months.
`FastAPI` `PostgreSQL` `JWT` `pytest`

**[F1 Race Outcome Prediction](https://github.com/no0e/f1-race-prediction)** - win probability and pit strategy
Logistic regression over seventy years of Formula One results, with dashboards
that read the race back: pit stop timing against finishing position, and
constructor pace across eras. Academic team project, 4 months.
`scikit-learn` `pandas` `matplotlib`

---


### Currently

Finishing my studies at ENSAI and looking for a 6-month internship.
