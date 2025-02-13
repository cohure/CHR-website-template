
<style>    
    h2 {
        margin-top: 0;
        margin-bottom: 1.5rem;
        line-height: 1.3;
    }
    
    h3 {
        margin-top: 2rem;
        margin-bottom: 1rem;
        font-size: 1.4rem;
        font-weight:bold;
    }
    
    .metadata {
        background-color: rgba(96,24,67,0.03);
        padding: 1rem;
        font-size:0.8rem;
        border-radius: 6px;
        margin-bottom: 2rem;
    }
    
    .metadata p {
        margin: 0.5rem 0;
    }
    
    .abstract {
        text-align: justify;
        font-size:0.8rem;
        padding: 1rem;
        background-color: rgba(96,24,67,0.03);
        border-left: 4px solid #2c5282;
        border-radius: 0 6px 6px 0;
    }
    
    strong {
        color: #2d3748;
        font-weight: 600;
    }
</style>
<main role="main">
<h2>Sub-optimal Recall in Visual Cluster Retrieval: When Clusters Look Like Bridges</h2>

<section class="metadata">
<p style='font-size:0.8rem'><i>(short paper)</i></p>
<p><strong>Authors:</strong> Mathieu Jacomy, Matilde Ficozzi and Anders K. Munk</p>
<p><strong>Presented in</strong> <a href="/programme/#postersession">Poster Session</a></p>
<p><strong>Paper:</strong> <a href="https://ceur-ws.org/Vol-3834/paper5.pdf">Download PDF</a></p>
</section>

<section>
<h3>Abstract</h3>
<div class="abstract">
<p>Force-directed node placement algorithms, a popular technique to visualise networks, are known to optimize ``cluster separability'': when sets of densely connected nodes get represented as well-separated groups of dots. Using these techniques leads us to conceive networks as sets of clusters connected by bridges. This is also how we tend to think of the ``community structure'' model embedded in clustering techniques like modularity maximization. Yet this mental model has flaws. We specifically address the notion that clusters (``communities'') necessarily look like groups of dots, through the mediation of a node placement algorithm. Although often true, we provide a reproducible counterexample: topological clusters that look like bridges. First, we present an empirical case that we encountered in a real world situation, while mapping the academic landscape of AI and algorithms. Second, we show how to generate a network of arbitrary size where a cluster looks like a bridge. In conclusion, we open a discussion about layout algorithms as a visual mediation of a network's community structure. We contend that when it comes to the accuracy of retrieving clusters visually, node placement algorithms have an imperfect recall despite an excellent precision.</p>
</div>
</section>
</main>