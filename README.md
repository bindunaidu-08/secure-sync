🌐 Web Page Similarity via SVD + Eigenvalue — F5

«B.Tech 1st Year Mathematics Mini Project»

An interactive mathematical web application that analyzes and ranks web pages using Cosine Similarity, Eigenvalue Centrality, and Singular Value Decomposition (SVD).

The project demonstrates how mathematical concepts can be applied to real-world applications such as SEO, search engines, and content recommendation systems.

---

🚀 Project Overview

The system takes 5 web pages represented as keyword/word vectors and performs two different mathematical analyses:

1. Eigenvalue Centrality — ranks pages based on their similarity connections with other pages.
2. SVD-based Analysis — identifies the strongest latent pattern/topic and ranks pages according to their contribution to that pattern.

Finally, both rankings are compared to understand how the two mathematical approaches differ.

---

🧮 Mathematical Concepts

1. Cosine Similarity

For two page vectors (P_i) and (P_j):

[
S_{ij} =
\frac{P_i \cdot P_j}
{|P_i||P_j|}
]

This produces a 5 × 5 similarity matrix.

---

2. Eigenvalue Centrality

The similarity matrix (S) is analyzed using:

[
Sv = \lambda v
]

The eigenvector corresponding to the largest eigenvalue provides the page centrality scores.

Higher centrality means the page has stronger similarity connections with other pages.

---

3. Singular Value Decomposition

The page-keyword matrix is decomposed as:

[
A = U\Sigma V^T
]

Where:

- U → page relationships with latent components
- Σ → strength of the components
- Vᵀ → keyword relationships with the components

The first singular component represents the strongest latent pattern in the dataset.

---

🔄 Project Workflow

5 Web Pages
     ↓
Keyword / Word Vectors
     ↓
Word-Frequency Matrix A
     ↓
Cosine Similarity
     ↓
Similarity Matrix S
     ↓
 ┌─────────────────────┐
 │                     │
 ▼                     ▼
Eigenvalue Centrality   SVD
 │                     │
 ▼                     ▼
Page Ranking            Topic Ranking
 │                     │
 └──────────┬──────────┘
            ▼
     Ranking Comparison

---

💡 Real-World Applications

🔎 Search Engines

Pages with strong relationships to other relevant pages can be identified and ranked.

📈 SEO

The system demonstrates how page similarity and keyword relationships can help analyze content.

🤖 Content Recommendation

Similar pages can be identified and used to recommend related content to users.

📰 Content Analysis

Latent patterns in collections of documents can be explored using SVD.

---

✨ Features

- 📊 Cosine similarity matrix
- 🧮 Eigenvalue centrality
- 📐 SVD decomposition
- 🏆 Two different page rankings
- 📈 Ranking comparison charts
- 🔥 Similarity heatmap
- 🎯 Keyword/topic analysis
- 📉 Sensitivity analysis
- 🖥️ Interactive frontend
- 🎨 Modern lavender-themed UI
- 📱 Responsive design

---

🧪 Benchmark Dataset

The demonstration uses five pages:

Page| Main Focus
AI SEO Guide| AI, SEO, data
Cybersecurity Guide| Security, network
Web Development Guide| Web, Python
Machine Learning Guide| AI, learning, Python
Cloud Computing Guide| Cloud, data

The dataset is designed for demonstration and can be replaced with real page/keyword data.

---

🛠️ Technologies Used

Mathematical / Backend

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab

Frontend

- HTML
- CSS
- JavaScript
- Interactive visualization components
- Cloud Artifacts

Mathematics

- Vector Spaces
- Cosine Similarity
- Eigenvalues & Eigenvectors
- Matrix Decomposition
- Singular Value Decomposition (SVD)

---

📊 Output

The application produces:

- Cosine similarity matrix
- Similarity heatmap
- Eigenvalues
- Eigenvalue centrality scores
- Eigenvalue ranking
- Singular values
- Dominant SVD component
- SVD page ranking
- Ranking comparison
- Sensitivity analysis

---

🎯 Project Objective

The main objective is to demonstrate that linear algebra can be applied to real-world information retrieval and content analysis problems.

The project compares two mathematical perspectives:

«Eigenvalue Centrality → “How important is a page based on its connections?”»

«SVD → “How strongly does a page contribute to the dominant latent pattern?”»

---

👥 Team

Team F5

Project: Web Page Similarity via SVD + Eigenvalue

Application Areas:
SEO • Search Engines • Content Recommendation

---

📌 Future Enhancements

- Extract keywords automatically from real web pages
- Use TF-IDF weighting
- Add more than 5 pages
- Add real-time web-page analysis
- Add interactive topic exploration
- Add advanced ranking algorithms
- Deploy the application online

---

📜 Academic Note

This project is developed as a B.Tech Mathematics Mini Project to demonstrate the practical application of linear algebra concepts in modern computing and information retrieval.

---

⭐ Conclusion

Web Page Similarity via SVD + Eigenvalue connects mathematical theory with real-world applications.

By combining Cosine Similarity, Eigenvalue Centrality, and SVD, the project provides two different ways to understand and rank web pages based on their relationships and latent content patterns.

«Mathematics + AI + Web Technology = F5 🚀»