---
layout: default
---
<body>
    
<h1>SLIME Cloud: A Free Massive World Class High Performance SAT Solver.</h1>    
    <h3>Winner of Crypto Track and 3rd place on Cloud Track at the <a href="https://satcompetition.github.io/2021/">SAT Competition 2021</a></h3>
    <p><a href="https://github.com/maxtuno/SLIME">https://github.com/maxtuno/SLIME</a></p>
    
<h1>SLIME CLI & SLIME CLOUD</h1>
    <h2>Currently the best SAT Solver, several light years around.</h2>
    <p><a href="https://github.com/maxtuno/slime-sat-solver/tree/master/SLIME_CLI">SLIME CLI</a></p>
    <img src="SLIME_CLI/media/plot.png" alt="">
    <img src="SLIME_CLI/media/summary.png" alt=""> 
    
<h1>Kissat-sc2020 vs SLIME 5 at 10.000 seconds</h1>

    <a href="https://www.starexec.org/starexec/secure/details/job.jsp?anonId=e73ac153-4ffc-4e94-b271-8c36f45427dd">Anonymous Link to Report</a></li>

    <p><a href="https://github.com/maxtuno/slime-sat-solver/tree/master/SLIME5-binary">SLIME 5</a></p>
    <p>PAR-2 Score 1499518.553</p>
    <p>Solved 192 = SAT 131 + UNSAT 61</p>

    <p>Kissat-sc2020: http://fmv.jku.at/kissat/</p>
    <p>PAR-2 Score 1564281.3671</p>
    <p>Solved 185 = SAT 115 + UNSAT 71</p>
        
    <img src="SLIME5-binary/log.png" alt="">
    <img src="SLIME5-binary/plot.png" alt="">
    <img src="SLIME5-binary/summary.png" alt="">  
    
    
<h1>SLIME 5 Cloud: A Free Massive World Class High Performance SAT Solver.</h1>
   
    
<ul>
    <li>SLIME 5, binary distribution, single node compilation.</li>
    <li>https://github.com/maxtuno/slime-sat-solver/tree/master/SLIME5-binary</li>
    <li>SLIME 4 win 3rd place on Cloud Track from SAT Competition 2020 https://satcompetition.github.io/2020/index.html.</li>
</ul>

<h1>SLIME 5: The Unofficial State of The Art</h1>
<ul>
    <li>SLIME vs The Winner of the SAT Competition 2020 Main Track.</li>
</ul>    
    
<img src="media/v5/log5.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v5/normal5.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v5/summarry.png" alt="SAT Race 2019 (Secondhalf)">    
    
<h1>SLIME 3.1.1: The Unofficial State of The Art</h1>
<ul>
    <li>SLIME vs The Winners of the SAT Race 2019.</li>
</ul>

<img src="media/v3.1.1/5000s.png" alt="CaDiCaL vs MapleLCMDiscChronoBT-DL-v3 vs SLIME 3.1.1">

<img src="media/v3.1.1/vs.png" alt="CaDiCaL vs MapleLCMDiscChronoBT-DL-v3 vs SLIME 3.1.1">
<img src="media/v3.1.1/result.png" alt="CaDiCaL vs MapleLCMDiscChronoBT-DL-v3 vs SLIME 3.1.1">

<h1>SLIME 3.1: The Unofficial State of The Art</h1>
<ul>
    <li>Support long term executions without overflow on counters and variables.</li>
    <li>The State of The Art Performance.</li>
</ul>

<img src="media/v3/satrace2019_alone.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v3/satrace2019_alone_log.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v3/satrace2019_alone_rep.png" alt="SAT Race 2019 (Secondhalf)">

<h1>SLIME 3.0: The Unofficial State of The Art</h1>
<ul>
    <li>Implementation of Alternating Dual BOOST Heuristic.</li>
    <li>The State of The Art Performance.</li>
</ul>

<img src="media/v3/satrace2019.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v3/satrace2019_log.png" alt="SAT Race 2019 (Secondhalf)">
<img src="media/v3/satrace2019_rep.png" alt="SAT Race 2019 (Secondhalf)">

<img src="media/v3/satrace2006.png" alt="SAT Race 2006">

<h1>SLIME 2.2: A Free World Class Multiplatform High Performance SAT Solver</h1>
<ul>
    <li>Windows support - include a precompiled executable</li>
    <li>usage: slime_cli cnf-file [sat-model-file] [unsat-proof-file]</li>
    <li>2.0 performance</li>
</ul>

<h1>SLIME 2.1: A Free World Class High Performance SAT Solver</h1>
<ul>
    <li>Full ANSI C++
    <li>Remove ZLib dependency
    <li>Extreme simplification of unused components
    <li>2.0 performance
    <li>More compatibility with all OS. (Full Raspbian Compatibility)</li>
</ul>

<h1>SLIME 2.0: A Free World Class High Performance SAT Solver</h1>
<h3>SAT Race 2015</h3>
<ul>
    <li>v1.0 PAR-2 605079.2646</li>
    <li>v2.0 PAR-2 591812.0663</li>
</ul>

(The solvers will ranked using the PAR-2 scheme: The score of a solver is defined as the sum of all runtimes for solved instances + 2*timeout for unsolved instances, lowest score wins.)

<img src="media/v2/results.png" alt="SAT Race 2006">
<img src="media/v2/default.png" alt="SAT Race 2015">
<img src="media/v2/log.png" alt="SAT Race 2006">

<h1>SLIME: A Minimal Heuristic to Boost SAT Solving</h1>
<br>

On CDCL Based SAT Solvers the trail size is strictly related to progress or to the total conflicts on the current assignment,
such that if the trail size is the same that the number of variables, then current assignment is valid.

On the other hand, in the selection of the current variable it is necessary to assign a predetermined polarity to the resulting literal, which in most implementations is a predefined value.

SLIME implement a simple heuristic with minimal complexity, that correlated the trail size and the polarity of the current variable to assign.

The selection of variable is not related to trail size, this decouple the both concepts.

<br>
<br>

<embed src="slime/doc/slime.pdf" type="application/pdf" width="100%" height="600px"/>

</body>
