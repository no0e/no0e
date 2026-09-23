## Noé Diette

Statistics and machine learning engineering student at ENSAI, Rennes.

I work on sequence models and on the part most projects skip: not just what a
model predicts, but how sure it is allowed to say it is. My internship work
turned that into a method that ships a search area a human can act on, not a
point estimate with no error bars.

---

### Projects

**[Residual Trajectory Prediction](https://github.com/no0e/residual-trajectory-prediction)** - where a ship will be after it stops broadcasting
A 317k-parameter mixture density network that predicts the *residual* of a
parameter-free kinematic prior, so predicting zero reproduces the baseline
exactly. 29% below that prior on New York Harbor traffic, and 90% confidence
regions that hold 87.8 to 90.6% on vessels never seen in training. Beats a
published transformer three times its size inside that paper's own protocol.
`PyTorch` `mixture density networks` `conformal prediction`

**[Two-Stage Hybrid Recommender](https://github.com/no0e/two-stage-hybrid-recommender)** - sequential recommendation on Amazon products
LightGCN for candidate retrieval, BERT4Rec for reranking, content-based
embeddings for the cold-start items neither of them can see. First place out of
80 in an in-class Kaggle competition.
`LightGCN` `BERT4Rec` `cold start`

**[Hateful Memes: CA-AGFN](https://github.com/no0e/hateful-memes-ca-agfn)** - multimodal detection when text and image disagree
A meme is hateful in the gap between what it says and what it shows. This model
builds that gap explicitly as a clash feature, then gates the two modalities
with a language-conditioned entropy gate: the less the text commits to
anything, the more the image decides.
`XLM-RoBERTa` `CLIP` `cross-modal attention`

**[UBJR Eats API](https://github.com/no0e/ubjr-eats-api)** - a delivery platform backend
FastAPI over a layered Model/DAO/Service architecture, JWT authentication for
three user roles, PostgreSQL. 17 test modules across the data and service
layers. Team project, four developers, fifteen months.
`FastAPI` `PostgreSQL` `JWT` `pytest`

**[F1 Race Outcome Prediction](https://github.com/no0e/f1-race-prediction)** - win probability and pit strategy
Logistic regression over sixty years of Formula One results, with dashboards
that read the race back: pit stop timing against finishing position, and
constructor pace across eras.
`scikit-learn` `pandas` `Tkinter`

---

### Currently

Finishing at ENSAI, and looking for machine learning engineering work where
calibration and evaluation are treated as part of the model, not as an
afterthought.
