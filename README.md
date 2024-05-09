# CMSC516_NERProject
NER Model to parse CoNLL-2003 data and identify named entities.

**To Run:**
1. Download `NER_Conll2003_Final.ipynb`.
2. Pull your Hugging Face access token (needs to have write permissions).
3. Upload `NER_Conll2003_Final.ipynb` to Google Colab. (File > Upload Notebook)

![image](https://github.com/BrandonM001/CMSC516_NERProject/assets/43420985/dd1f2109-e323-4f43-a3ce-09596100ac01)

4. Under the second code snippet in the "Inspect the Dataset" section, the code will attempt to log in to Hugging Face. It will likely error out on the first run. Once you provide your Hugging Face access token:
   - Click into the code box.
    ![image](https://github.com/BrandonM001/CMSC516_NERProject/assets/43420985/07f2b2b6-ddfa-4bda-a343-691a9290b7d2)

   - Select `Runtime > Run After`.

    ![image](https://github.com/BrandonM001/CMSC516_NERProject/assets/43420985/b3ba073b-e473-4c4e-be7b-7d032a7131de)

5. **Note:** If you plan to re-run the code, comment out the `create_repo` call within this code block or change the `reposito` and `output_dir` strings.
Line to comment out (if needed): ![image](https://github.com/BrandonM001/CMSC516_NERProject/assets/43420985/d5886173-0e5c-466e-8bb9-32c7bf32855c) 




6. The code will take about 30 minutes to run from start to finish. It uses 3 epochs for training and 3 for testing (diminishing results with additional epochs).

**Notable Output Includes:**
- CoNLL-2003 Dataset Metrics
- Training Output
- Testing Output
