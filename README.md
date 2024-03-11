<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Summary</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>
<h1>Bistability analysis of excitatory, inhibitory and somatostatin neuron network</h1>

<!-- Table of Contents -->
<h2>Table of Contents</h2>
<ul>
  <li><a href="#Introduction">Introduction</a></li>
  <li><a href="#Integrate-and-fire-model">Integrate and fire model</a></li>
  <li><a href="#QIF-model">QIF model</a></li>

</ul>


<!-- Sections -->
<!-- Introduction Section -->
<h2 id="#Introduction">Introduction</h2>
<p>Recently we have seen a lot of studies of E + I neuron networks, spiking models,
   γ oscillatory neurons, etc. Recent studies indicate the importance of the other populations 
   of inhibitory interneurons. The E + I network is specifically Pyramidal cells (E) and Parvalbumin(I) cells,
    notably, somatostatin neurons(I). They have different temporal properties and different connectivities. 
    The goal of this paper is to explore the dynamics when there are 3 populations of cells.
</p>

<!-- IF Section -->
<h2 id="#Integrate-and-fire-model">Integrate and fire model</h2>
<p>The Integrate-and-Fire neuron is a simplified computational model that simulates the membrane potential 
  of a neuron, integrating incoming electrical signals until a threshold is reached, at which point it "fires" 
  (generates an action potential) and then resets its membrane potential. This model captures the basic behavior
   of neuronal spiking in response to synaptic inputs.
   The right hand side RC circuit model 
  $$\tau \frac{dy}{dx}=-(u-u_{rest})+RI$$
<p>
  <p><img src="/images/I&F.png" alt="Integrate-and-fire-model w.r.t current inputs"></p>

</body>
</html>




   
    

