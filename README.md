# **IMDB-sentiment-API**

Developping a IMDB ML model with API and Dockerisation

---

## **Context**

API for sentiment classification (IMDB). Served with FastAPI, containerized with Docker. First step of AI Engineer formation prod bases.

---

## **Set-up**

```
git clone https://github.com/AZimmermannPro/IMDB-sentiment-API.git
```

### **Generate and activate venv**

```
python -m venv .venv
```

**Mac/Linux**  
`source .venv/bin/activate`

**Windows**  
`.venv\Scripts\activate`

### **Install dependencies**

```
pip install scikit-learn==1.9.0 pandas==3.0.3 joblib==1.5.3
```

---

## **Usage**

TODO

---

## **Structure**

```
.
├── API                     # Scripts for API  
├── models                  # Generated aritfact (Not versioned)
├── train                   # ML tools and scripts            
├── tests                   # Automated tests 
├── README.md
└── .gitignore
```