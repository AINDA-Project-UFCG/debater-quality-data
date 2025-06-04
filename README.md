# **DEBISS-eval Corpus**

## **Overview**

DEBISS-eval is a subcorpus derived from [DEBISS (Individual, Spoken, and Semi-Structured Debates)](http://docs.google.com/link-to-main-DEBISS-repository-if-it-exists-or-paper), focused on providing rich data for research in debate quality assessment and debater performance analysis. This corpus contains detailed evaluations of academic debates in Brazilian Portuguese, conducted by expert judges.

The evaluations were carried out on 16 debates, involving 67 first-semester computer science students, who discussed the theme "Generative Artificial Intelligence and its impacts on society." Five judges with backgrounds in Linguistics (Brazilian Portuguese) and prior experience in the debate genre evaluated each debate and the debaters' performance.

## **Repository Content**

This repository contains the following materials:

1. **Transcripts with Judges' Annotations (transcripts\_judges\_annotations/):**  
   * .csv files containing the debate transcripts.  
   * These files include additional columns with annotations and comments made by the judges directly on the debaters' utterances during the analysis (e.g., judges\_notes).  
   * Each file generally corresponds to a specific debate.  
2. **Judges' Responses to the Evaluation Form (judges\_evaluation\_form\_responses/):**  
   * .csv files containing the detailed responses from the judges to the evaluation forms.  
   * These forms include:  
     * Quantitative Likert scale (1-5) evaluations for multiple criteria (e.g., "Argumentation," "Clarity," "Engagement," "Subject Mastery").  
     * "Hard Voting" results (categorical vote for the best debater).  
     * "Soft Voting" results (cumulative scores based on criteria).  
     * Qualitative justifications for the choice of the best debater.  
   * A total of 80 evaluation responses are provided (5 judges x 16 debates).  
3. **Evaluation Protocol (protocol/):**  
   * A .docx file (Evaluation\_Protocol\_DEBISS-eval.docx) detailing the methodology and criteria used by the judges to evaluate the debates and debaters.  
   * This document describes the guidelines provided to the judges, the definitions of the evaluation criteria, and the experimental process.

## **File Formats**

* **Transcription and Evaluation Data:** .csv (Comma-Separated Values)  
  * The CSV files are UTF-8 encoded.  
  * The column separator is a comma (,).  
* **Evaluation Protocol:** .docx (Microsoft Word Document)

## **Data Structure (Simplified Example)**

**Example structure in transcripts\_judges\_annotations/debate\_XX.csv:**

| utterance\_id | debater | utterance\_transcription | judges\_notes\_judge1 | judges\_notes\_judge2 | ... |