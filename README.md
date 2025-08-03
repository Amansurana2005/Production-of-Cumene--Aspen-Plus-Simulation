# Production-of-Cumene--Aspen-Plus-Simulation
Steady-state simulation and optimization of cumene synthesis from benzene and propene using Aspen Plus. This project demonstrates advanced process modeling techniques, including reactor performance comparison, multi-unit separation design, and feed-rate optimization for enhanced product purity.


Project Title: Cumene Production Process Simulation and Optimization
Challenge: The objective was to design, simulate, and optimize a continuous process for producing cumene (isopropylbenzene) via the Friedel-Crafts alkylation of benzene and propene. The key challenges involved selecting the most effective reactor type (PFR vs. CSTR), designing a robust separation train, and optimizing the feed stream to maximize final product purity while minimizing waste.
Methodology:
1.	Process Flowsheet Design: The simulation was constructed in Aspen Plus, starting with two feed streams (benzene, and a propene-butane mixture in a 7:3 ratio) flowing at 400 kmol/hr each. These streams were heated to 367.8°C and fed into the reaction section. The simulation utilized the NRTL-RK property method for rigorous thermodynamic calculations.
2.	Reactor Performance Evaluation: Two reactor types were evaluated: a PFR (5m long, 8cm diameter, 350 tubes) and a CSTR. The PFR's performance was first simulated, and its residence time (16.67 seconds) was used to size the CSTR for a direct comparison. The PFR was found to be more efficient, producing 69.933 kmol/hr of cumene, a 13% increase over the CSTR's output.
3.	Separation and Recycle Loop Integration: A two-stage distillation process was designed to purify the PFR product. The first column (20 stages) separated lighter components (benzene, propene, butane) from the heavier products (cumene, p-diisopropylbenzene), while the second column (25 stages) further purified the cumene stream. A recycle loop with a membrane separator was then implemented to return unreacted benzene back to the feed mixer.
4.	Feed Rate Optimization: A sensitivity analysis was performed to investigate the impact of the fresh benzene feed rate on the final cumene purity. This analysis revealed a significant opportunity for optimization, as a high feed rate of 400 kmol/hr resulted in a purity of only 43% due to excess benzene carrying over into the product stream.
Results and Impact:
•	Maximized Production Rate: The PFR was conclusively identified as the superior reactor, with a production rate of 69.933 kmol/hr, making it the chosen reactor for the final design.
•	Achieved High Purity: By optimizing the fresh benzene feed rate and leveraging the recycle loop, the purity of the final cumene product was increased from 43% to nearly 100%, fulfilling the primary project objective.
•	Minimized Waste: The optimized design minimizes the amount of unreacted benzene discarded from the system, channeling it back into the process for reuse and improving overall resource efficiency.
•	Demonstrated Simulation Proficiency: The project successfully modeled a complete and complex chemical process, including competing reactions, multi-unit operations, and a converged recycle loop, showcasing proficiency in advanced process simulation and optimization techniques.

