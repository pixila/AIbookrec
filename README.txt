AI Book Recommender – Final Prototype Submission
Student: Priscilla Barbin
Course: CSIT-191 – Artificial Intelligence
Date: 04/18/2025

-----------------------------------------------------------
OVERVIEW
-----------------------------------------------------------
This prototype is a book recommendation system that uses a trained neural network (MultilayerPerceptron) in Weka to predict whether a book would be recommended based on its genre and author. The Java Swing interface allows users to select options and get real-time recommendations.

-----------------------------------------------------------
FOLDER CONTENTS
-----------------------------------------------------------
/LibraryBookRecommender/
├── src/aiprototype/LibraryAIPrototype.java   – main GUI code
├── weka.jar                                 – Weka library (add to build path)
├── BestBookModel.model                      – trained model file
├── BestBooksRecommendation_SAFE.arff        – ARFF structure file
├── .classpath and .project                  – Eclipse project files
├── bin/ (optional)                          – compiled classes (if needed)

AI_Book_Recommender_Report.pdf            – final report


/Screenshots/                             – GUI and Weka output screenshots

-----------------------------------------------------------
HOW TO RUN THE PROTOTYPE
-----------------------------------------------------------
1. Open Eclipse
2. Go to File > Import > Existing Projects into Workspace
3. Select the `LibraryBookRecommender` folder
4. Right-click the project > Build Path > Configure Build Path > Add External JARs
   → Add `weka.jar`
5. Run the file `LibraryAIPrototype.java` (in `aiprototype` package)
6. Use the dropdowns to select a genre and author, then click "Get Recommendation"

-----------------------------------------------------------
Questions or Issues
-----------------------------------------------------------
If anything is unclear or does not work, please let me know during feedback.
