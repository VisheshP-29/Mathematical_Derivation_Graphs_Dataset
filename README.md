# Mathematical Derivation Graphs Dataset
File: derivation_graphs.json stores the manually parsed derivation graphs for 107 articles. The formatting for each derivation graph entry is as follows:
```json
{
   "Article ID": "",
   "Equation ID": [],
   "Adjacency List": {},
   "Equation Number": {},
   "Most Important Equation": "" 
}
```
- "Article ID" is the identifying ID for each article.
- "Equation ID" is the list of unique IDs for each equation in the article.
- "Adjacency List" is the dictionary that stores the adjacency list for each equation.
- "Equation Number" is the identifying reference number assigned in the article for each equation.
- "Most Important Equation" is the most important equation that was identified for each article and part of follow up work.