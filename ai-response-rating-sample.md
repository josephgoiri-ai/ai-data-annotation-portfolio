# AI Response Rating & Scoring Sample

## Overview

This portfolio sample demonstrates a structured approach to evaluating AI-generated responses using a defined quality rubric.

The examples are representative practice examples designed to demonstrate the type of reasoning used in AI response evaluation, rating, and quality assurance.

## Evaluation Criteria

Each response is evaluated independently using:

* **Accuracy** — Is the information factually correct?
* **Relevance** — Does the response directly address the user's request?
* **Helpfulness** — Does it provide useful information?
* **Completeness** — Does it cover the important parts of the request?
* **Clarity** — Is it easy to understand?
* **Instruction Following** — Does it follow the user's requirements?
* **Safety** — Does it avoid unsafe or inappropriate guidance?

---

## Example 1 — Factual Accuracy

### User Request

"Can you explain what a firewall does in a computer network?"

### AI Response

"A firewall is a security system that monitors and controls network traffic based on predefined rules. It can allow or block connections depending on factors such as source, destination, port, or protocol."

### Rating

| Criterion             | Score | Assessment                                                            |
| --------------------- | ----: | --------------------------------------------------------------------- |
| Accuracy              |   5/5 | The explanation correctly describes the basic function of a firewall. |
| Relevance             |   5/5 | It directly answers the question.                                     |
| Helpfulness           |   5/5 | It provides a useful explanation without unnecessary detail.          |
| Completeness          |   4/5 | The basic concept is covered, although examples could improve it.     |
| Clarity               |   5/5 | The wording is concise and understandable.                            |
| Instruction Following |   5/5 | The response explains the requested concept directly.                 |
| Safety                |   5/5 | No safety concerns are present.                                       |

**Overall Rating: 4.9/5 — High Quality**

### Evaluation Summary

The response is factually accurate and directly addresses the request. It gives enough technical detail to explain the concept while remaining accessible.

---

## Example 2 — Relevance and Instruction Following

### User Request

"Give me three short tips for writing a professional email."

### AI Response

"Professional emails should have a clear subject line and concise message. You should also include appropriate greetings and proofread the email before sending it. For example, business communication is important because companies communicate with customers, suppliers, employees, and other stakeholders."

### Rating

| Criterion             | Score | Assessment                                                                        |
| --------------------- | ----: | --------------------------------------------------------------------------------- |
| Accuracy              |   5/5 | The advice is generally correct.                                                  |
| Relevance             |   4/5 | Most information is relevant, but the final sentence is unnecessary.              |
| Helpfulness           |   4/5 | The first part provides useful advice.                                            |
| Completeness          |   4/5 | Three useful points are present.                                                  |
| Clarity               |   4/5 | The response is understandable but could be more concise.                         |
| Instruction Following |   3/5 | The user requested three short tips, but the response adds unrelated information. |
| Safety                |   5/5 | No safety concerns are present.                                                   |

**Overall Rating: 4.1/5 — Good Quality**

### Evaluation Summary

The response provides useful advice but does not fully follow the user's request for three short tips. The additional explanation about business communication reduces relevance and conciseness.

---

## Example 3 — Identifying an Incorrect AI Response

### User Request

"What is the capital city of Australia?"

### AI Response

"The capital city of Australia is Sydney."

### Rating

| Criterion             | Score | Assessment                                                               |
| --------------------- | ----: | ------------------------------------------------------------------------ |
| Accuracy              |   1/5 | The answer is factually incorrect. Canberra is the capital of Australia. |
| Relevance             |   5/5 | It directly attempts to answer the question.                             |
| Helpfulness           |   1/5 | The incorrect information makes the response unhelpful.                  |
| Completeness          |   5/5 | A direct answer was provided, but it is wrong.                           |
| Clarity               |   5/5 | The response is clear.                                                   |
| Instruction Following |   5/5 | It follows the requested format.                                         |
| Safety                |   5/5 | No safety concerns are present.                                          |

**Overall Rating: 3.9/5 — Poor Factual Quality**

### Evaluation Summary

The response is clear and relevant but contains a critical factual error. Accuracy must take priority because the user's question requires a factual answer.

---

## Example 4 — Completeness and Helpfulness

### User Request

"I'm preparing for a job interview. What should I do the day before?"

### AI Response

"Prepare your clothes and arrive on time."

### Rating

| Criterion             | Score | Assessment                                    |
| --------------------- | ----: | --------------------------------------------- |
| Accuracy              |   5/5 | The suggestions are reasonable.               |
| Relevance             |   5/5 | The response addresses interview preparation. |
| Helpfulness           |   3/5 | The suggestions are useful but very limited.  |
| Completeness          |   2/5 | Important preparation areas are missing.      |
| Clarity               |   5/5 | The response is simple and clear.             |
| Instruction Following |   5/5 | It answers the question.                      |
| Safety                |   5/5 | No safety concerns are present.               |

**Overall Rating: 4.3/5 — Acceptable but Incomplete**

### Evaluation Summary

The response provides correct advice but is too limited to fully answer the question. A stronger response could mention reviewing the job description, preparing questions, checking the interview location or connection, and getting necessary materials ready.

---

## Example 5 — Pairwise AI Response Ranking

### User Request

"Explain why data quality is important in AI training."

### Response A

"Data quality is important because AI models learn from the data they receive. Inaccurate, inconsistent, incomplete, or incorrectly labelled data can cause a model to learn incorrect patterns and produce unreliable results."

### Response B

"Data quality is important for AI because computers need data. Good data is usually better than bad data, and companies should make sure their data is useful."

### Evaluation

| Criterion    | Response A | Response B |
| ------------ | ---------: | ---------: |
| Accuracy     |        5/5 |        4/5 |
| Relevance    |        5/5 |        4/5 |
| Helpfulness  |        5/5 |        3/5 |
| Completeness |        5/5 |        2/5 |
| Clarity      |        5/5 |        4/5 |

### Preferred Response

**Response A**

### Justification

Response A is preferred because it provides a more precise explanation and identifies specific data-quality problems such as inaccurate, inconsistent, incomplete, and incorrectly labelled data. Response B is broadly correct but too general and does not explain the consequences of poor-quality training data.

---

## Quality-Control Process

When evaluating AI responses, I would:

1. Read the user's request carefully.
2. Review the evaluation rubric.
3. Identify the main requirements of the task.
4. Evaluate each response criterion independently.
5. Check factual claims where appropriate.
6. Look for missing information, irrelevant content, or instruction violations.
7. Assign scores based on evidence rather than personal preference.
8. Provide a concise justification explaining the rating.
9. Review the final rating for consistency with the rubric.

## Skills Demonstrated

* AI response evaluation
* Rating and scoring
* RLHF-style preference ranking
* Rubric-based assessment
* Factual accuracy assessment
* Relevance assessment
* Instruction-following evaluation
* Quality assurance
* Critical thinking
* Evidence-based justification
* Attention to detail
* Structured documentation

## Portfolio Note

These are **practice examples created for portfolio demonstration**. They are not presented as completed client or Sovrano production tasks.

The evaluation approach reflects common AI evaluation workflows such as response rating, scoring, and preference ranking described by Sovrano AI.
