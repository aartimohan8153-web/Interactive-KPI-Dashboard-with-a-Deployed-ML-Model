# Interactive-KPI-Dashboard-with-a-Deployed-ML-Model
# Tech Stack

- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn, XGBoost, SHAP
- **Web App & Dashboard:** Streamlit, Plotly
- **API Framework:** FastAPI, Uvicorn
- **Deployment & DevOps:** Docker, Streamlit Cloud

## Project Architecture
[ Raw Data ] ➔ [ Data Processing Pipeline ] ➔ [ Trained Model Artifact ]
                                                    │
                                                    ▼
                                            [ FastAPI Backend ]
                                                    │
                                                    ▼
                                          [ Streamlit Dashboard ]
