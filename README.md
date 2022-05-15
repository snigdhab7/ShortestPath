# ShortestPath
Bellman-Ford and Dijkastras' algorithm for shortest path finding 
<br>
<b><u>Bellman-Ford Algorithm for shortest path finding:</b></u><br>
-------------------SAMPLE INPUT--------------------<br>
   Edges = 8,Vertices = 5<br>
   g->edge[1].source = 0;<br>
   g->edge[1].destination = 2;<br>
   g->edge[1].weight = 4;<br>
   g->edge[0].source = 0;<br>
   g->edge[0].destination = 1;<br>
   g->edge[0].weight = -1;<br>
   g->edge[4].source = 1;<br>
   g->edge[4].destination = 4;<br>
   g->edge[4].weight = 2;<br>
   g->edge[3].source = 1;<br>
   g->edge[3].destination = 3;<br>
   g->edge[3].weight = 2;<br>
   g->edge[2].source = 1;<br>
   g->edge[2].destination = 2;<br>
   g->edge[2].weight = 3;<br>
   g->edge[6].source = 3;<br>
   g->edge[6].destination = 1;<br>
   g->edge[6].weight = 1;<br>
   g->edge[5].source = 3;<br>
   g->edge[5].destination = 2;<br>
   g->edge[5].weight = 5;<br>
   g->edge[7].source = 4;<br>
   g->edge[7].destination = 3;<br>
   g->edge[7].weight = -3;<br>
 <br>
-------------------SAMPLE OUTPUT--------------------<br>
<br>
Vertex :			 0 	1 	2 	3 	4 	<br>
The distance From Source : 0 	-1 	2 	-2 	1 	<br>
<br>
 <br>
 Steps to run-<br>
[clone git ptoject -> import project->build->Run BellmanFord.cpp]<br>

<br>
<b><u>Dijkstra's Algorithm for shortest path finding:</b></u><br>
-------------------SAMPLE INPUT--------------------<br>
    vertex = 9;  <br>
    graph.edge_add(0, 7, 8); <br>
    graph.edge_add(0, 1, 4); <br>
    graph.edge_add(1, 7, 11);  <br>
    graph.edge_add(1, 2, 8);<br>
    graph.edge_add(2, 5, 4);<br>
    graph.edge_add(2, 8, 2);  <br>
    graph.edge_add(2, 3, 7);  <br>
    graph.edge_add(3, 5, 14);<br>
    graph.edge_add(3, 4, 9);  <br>
    graph.edge_add(4, 5, 10);  <br>
    graph.edge_add(5, 6, 2); <br>
    graph.edge_add(6, 8, 6);  <br>
    graph.edge_add(6, 7, 1);  <br>
    graph.edge_add(7, 8, 7);  <br>
    Tp find: shortest Path from source 0 
 <br>
-------------------SAMPLE OUTPUT--------------------<br>
<br>
vertex: 	Distance from Source<br>   
   0 		:                0 <br>
   1 	   :            	 4<br>
   2 		 :               12<br>
   3 	     :          	 19<br>
   4 	      :         	 21<br>
   5 	       :        	 11<br>
   6 		     :           9<br>
   7 		      :          8<br>
   8 		       :         14<br>
<br>
<br>
 <br>
 Steps to run-<br>
[clone git ptoject -> import project->build->Run Dijkstra.cpp]<br>
