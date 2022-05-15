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
