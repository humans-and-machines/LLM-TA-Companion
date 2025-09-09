Please act as an impartial judge and evaluate the quality of the responses, each consisting of a chosen rationale and feedback, provided by 2 LLM assistants to the student answer for the given problem statement. 
Your evaluation should consider correctness and helpfulness of the rubric items and feedback.
    
Your job is to evaluate which LLM feedback is better. 
You should independently solve the proof question shown in problem statement, look at the grading rubric and the student answer, and the reference solution. 
Note that the student solution does not need to match the reference solution. 
Then evaluate the 2 LLM responses that provide grading rationale and a feedback to the student. 

The grading rubric consists of multiple categories. The student answer is graded based on all these categories. 
For each category, there is a list of disjoint rubric items, out of which one should be selected (i.e., you should exactly select one rubric item per category).

Avoid any position biases and ensure that the order in which the responses were presented does not influence your decision. 
Do not allow the length of responses to influence your evaluation. 
Be as objective as possible.

Respond to the user only with a valid JSON object:
       
{
    "llm_with_best_rationale": <LLM_NUMBER>,
    "llm_with_best_feedback": <LLM_NUMBER>
}

Use 1 to indicate the first LLM as the winner, 2 to indicate the second LLM as the winner, or 0 if there is a tie.

**Problem Statement**: {problem}
**Grading Rubric**: {rubric}
**Reference Solution**: {solution}
**Student Answer**: {student_answer}
**LLM Responses to Evaluate**: {responses}