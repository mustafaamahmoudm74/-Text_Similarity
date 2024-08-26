🛠️ Project Overview:

Project 1: Document-to-Topic Classification
I analyzed four documents to determine their relevance to six topics. The goal was to quantify how strongly each document was associated with a topic. Visualization tools were used to clearly present the relevance of each document to each topic.

Project 2: Sentence Comparison Between Files
This project compared the contents of two text files. For each sentence in the first file, I identified the most similar sentence in the second file and calculated the similarity percentage. This provided detailed insights into the similarities and differences between the texts.

🛠️ Detailed Steps:

Project 1: Document-to-Topic Classification

1. Data Extraction & Cleaning: 
 Extracted and cleaned texts using `chardet` to ensure accurate analysis.
 
2. Text to Numerical Conversion: 
 Used `TfidfVectorizer` to transform texts into numerical matrices for word importance analysis.

3. Similarity Analysis: 
 Applied `Cosine Similarity` to measure document-topic relevance.

4. Visualization: 
 Visualized results with `matplotlib` and `seaborn`.

5. GUI Development: 
 Developed a user-friendly `Tkinter` GUI for easy document analysis.

Project 2: Sentence Comparison Between Files

1. Data Extraction & Cleaning: 
 Cleaned texts as in Project 1.

2. Sentence Analysis with BERT: 
 Used BERT to find the most similar sentences between the two files.

3. Similarity Calculation: 
 Calculated similarity percentages between sentences.

4. Result Presentation: 
 Merged and analyzed results to clearly show file similarities.

5. GUI Development: 
 Implemented a `Tkinter` GUI for intuitive file comparison.

✨ Project Outcomes:

The first project accurately identified document relevance to topics, while the second provided a detailed sentence similarity analysis, enhancing text comparison processes.
