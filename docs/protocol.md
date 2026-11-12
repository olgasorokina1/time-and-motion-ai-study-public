# Test protocol

This document describes how I measure time and quality in this study.

## Tasks

10 tasks: 5 general office tasks (T01-T05) and 5 accounting tasks (T06-T10).
Each task has two input files of the same difficulty: version A and version B.
Version A is for the manual run. Version B is for the AI run.
All input data is synthetic.
Input data and results are in Spanish. Documentation is in English.

## Rules

1. Manual run: I do the task without any AI tool.
2. AI run: I use one AI tool for all tasks: Claude.
3. Time in the AI run includes writing the prompt and editing the result.
4. The timer starts when I open the input file.
5. The timer stops when the result is ready to send without more edits.
6. I write the time in minutes with one decimal (example: 12.5).
7. I do 2 tasks per day. I change the order: one task starts with the
   manual run, the next task starts with the AI run.
8. I count manual edits after the AI answer (manual_edits).

## Quality checklist

Each result gets a score from 1 to 5 for every point:

1. Accuracy: facts and numbers are correct.
2. Completeness: nothing important is missing.
3. Clarity: the text is easy to understand.
4. Tone: the tone fits the situation.
5. Ready to send: no more edits are needed.

The final quality score is the average of the five points.

## Blind review

A reviewer scores the results without knowing which one is manual
and which one is made with AI. Files have neutral names (X and Y).
