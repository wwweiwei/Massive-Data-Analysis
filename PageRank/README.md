# HW2 - PageRank
- Question: PageRank
  - Given a big matrix M. Specifically the column-normalized adjacency matrix where each column represents a webpage (vertex) and where it links to the non-zero entries. 
  - Write a program that calculates Google Matrix A: A = $\beta$M + (1-$\beta$)[1/N]NxN
  - With PageRank equation [Brin-Page, ‘98], forming recursive problem: r = A∙r
  - If M contains dead-ends, we have to renormalize.
  - NOTE: Please set β =0.8, and initial PageRank value = 1/N in this homework. 
- Data format
  - Input: A file that contains one line for each link, and each line contains a pair of numbers that represent the vertices that are connected by the link.
  - Output: There should be one line for each vertex, and each line should contain the vertex identifier and the PageRank values.
