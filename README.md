## Noé Diette

Statistics and machine learning engineering student at ENSAI, Rennes.

> **About the commit dates.** Most of the projects below were first built in private school and team
> repositories (ENSAI, Leiden). I forked them here, cleaned them up and translated them into English
> in autumn 2026, so the commit history shows when each one was republished, not when the work was done.

---

### Projects

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
three user roles, PostgreSQL.tests modules across the data and service
layers. Academic team project, 4 months.
`FastAPI` `PostgreSQL` `JWT` `pytest`

**[F1 Race Outcome Prediction](https://github.com/no0e/f1-race-prediction)** - win probability and pit strategy
Logistic regression over sixty years of Formula One results, with dashboards
that read the race back: pit stop timing against finishing position, and
constructor pace across eras. Academic team project, 4 months.
`scikit-learn` `pandas` `Tkinter`

---

### Currently

Finishing my studies at ENSAI and looking for a 6-month internship.
