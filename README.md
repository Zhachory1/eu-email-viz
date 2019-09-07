# eu-email-viz
a graph visualization of the eu-Email-core dataset (https://snap.stanford.edu/data/email-Eu-core.html) where the colors are different departments and the edges have the lowest betweeness centrality score of the original edges. This allows us to visualize department heads and inter-departmental communications.

## To see visualizations
You can run a simple python2 HTTP server with this command:

```
python3 -m http.server
```

Then you can navigate to any of the following files to see some visualizations:

```
localhost:8000/low.html
localhost:8000/low-node.html
localhost:8000/high.html
localhost:8000/high-node.html
```

The "low" files are the ones that kept the lowest centrality objects while "high" kept the highest. The "node" files kept the nodes with the highest/lowest centrality while the files without visualized the edges.
