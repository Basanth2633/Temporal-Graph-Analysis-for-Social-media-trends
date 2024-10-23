This project focuses on identifying trends in misinformation about monkeypox on social media, particularly Twitter, by leveraging network analysis techniques. The core methodology revolves around constructing a directed graph where nodes represent users and tweets, and edges capture interactions such as retweets, replies, and likes. The dataset includes user information, tweet content, and timestamps, allowing for temporal pattern analysis. After extensive data preprocessing—removal of noise, tokenization, lemmatization, and handling missing values—the graph was built, using interaction metrics like retweets as edge weights.

Two centrality measures, degree centrality and PageRank, were implemented to assess the influence of users within the misinformation network. Degree centrality identifies users with the most direct interactions, while PageRank highlights users whose content receives engagement from influential nodes. Preliminary results reveal high-degree centrality users initiating misinformation cascades, while PageRank identifies key nodes involved in propagating fake news.

The project aims to refine the algorithms for improved accuracy, conduct temporal analysis to capture shifts in influencer dynamics, and enhance graph visualizations. Challenges faced include handling missing or inconsistent data and mitigating the computational complexity of PageRank for large graphs. Future work will incorporate advanced centrality measures such as closeness centrality and betweenness centrality to further analyze misinformation flow. The progress made thus far demonstrates the utility of graph-based approaches in studying misinformation, with ongoing work focusing on enhancing trend detection and visualization capabilities.






