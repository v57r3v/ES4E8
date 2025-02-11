java c
Design of Power Semiconductor Devices, ES4E8 assignment, 2023/24 

Module Code 
ES4E8 
Module Title 
Advanced Power Electronic Converters and Devices 
Assignment Title 
Design of Power Semiconductor Devices 
Assignment 
Weighting / Credits 
30% coursework / 4.5 CATS 
Submission Deadline 
Noon Thursday Week 21 (22nd February 2024) 
Intended Learning Outcomes (ILOs) Assessed 
Intended Learning Outcome(s) (ILOs) 
Task / Criterion / Section 
LO1: Apply advanced concepts through the use of device physics in the context of device design. [M1, M2, M3, M4, M6] 
In this assignment, there are three questions. Please answer all questions. 
Question A [M1, M2, M3, M4, M6] 
Question B [M1, M3, M4] 
Question C [M1, M2, M4, M6] 
Notes: 
•         A   total   mark   below   40%   indicates   that   the   ILOs   have   not   all   been   met   at   threshold   level;
•         A total   mark   in the   range   40 - 48%   indicates   that   the   ILOs   have   all   been   partially   met   to at   least threshold   level;
• A total   mark of at   least 50%   indicates that the   ILOs   have   all   been   met.
Submission Details 
The submission details for this   assignment   are:
• Deadline: 12 noon  Thu 13 th February 2025. 
• Method: Online submission via Tabula. 
• Format of submission: A single .pdf file with a meaningful filename that would contain the student number, the module code, and assignment name, for example: 
“1234567_ES4E8_Lab Report.pdf” 
• Submission length: Maximum 2000 words. You will lose 5 marks per extra page over the limit. 
• Formatting instructions: Use a   minimum   11-point Arial   (or equivalent) font for the text,   with   1.5   line spacing   and   25   mm   margins all   round.Note: Submissions   should    be    of   an    appropriate   file   size    and    students   are    responsible   for   ensuring that   work   is   uploaded   successfully   before the   deadline.   If there   are technical   issues   when                submitting                online,                   please                contact                the                   Engineering                Student                Office (eng.eso@warwick.ac.uk).
Guidance and Referencing Style It   is serious Academic   Misconduct to   pass   off the work   of   others   (including   peersor AI-based   chatbots   such   as   ChatGPT)   as   your   own   and   you   should   not   permit   colleagues   to   copy   from   you.   Sources must be appropriately and properly acknowledged everytime reference   is   made   to    another’s    work,    using      the      Harvard      Referencing      system.      Failure      to      do      so      amounts      to   plagiarism   which    breaches    university    regulations   and   falls   short   of   the   Academic    Integrity   expected   in the department and   university.
Find out   more about the School of   Engineering   Referencing   System   here:
https://warwick.ac.uk/fac/sci/eng/eso/undergraduate_students/guidance/handbook/skills/s hb-2-04 There   are   also   other   types   of   academic   offences   including   duplication   or   ‘self-plagiarism’   .   Refer      to https://warwick.ac.uk/fac/arts/history/students/undergraduate/assess-plagiarism/ for further details.
Style. and Formatting Guide 
Submissions   are   expected to   conform. to   professional   standards   on   style   and formatting,   and   guidance can   be found   here:
https://warwick.ac.uk/fac/sci/eng/eso/undergraduate_students/guidance/handbook/skills/s h-1-06/ 
Assignment Feedback 
•         Your submitted   report will   be   marked electronically. The   marks of the various
sections will   be   provided as well as an   outline   of   the   answers   of   the   various   sections   in order to   identify where/how to   improve.
Question A 
A= (last two digits of your university ID number+450) 
B= (last two digits of your university ID number×7+1000) 
1.          Figure   1.1 shows the   basic cell   structure   of   a   power   MOSFET.
Describe   the   internal   resistance   components   in   the   power   MOSFET   on-state   operation   as   shown   in
figure   1.2(a) and   (b) and comment on their   effect   as   the   device   voltage   rating   increases.   [5%]

Figure   1.1.   Lateral channel   power   MOSFET - device   parameters.

Figure   1.2   (a)   Planar   power   MOSFET and   (b) Trench   power   MOSFET.

Table   1:   Device   parameters
2.          Calculate the on-state   resistance % contribution at   room   temperature   of   each   internal   resistance   component over the total on-state   resistance for a “A”V   breakdown   rated   MOSFET @ Vgate=15V,      Vthreshold=   6.4V and Vdrain=0.6V   (where the value of “A”   is defined above).   Identify   the   most important   resistance contributions.
Use the   device   parameters as given   in table   1   (you   may find   reference   [1], section   6.4    6.5   useful for   this analysis).         [10%]
3.          Calculate the on-state   resistance % contribution at   room   temperature   of   each   internal   resistance   component over the total on-state   resistance for a “B”V   breakdown   rated   MOSFET @ Vgate=15V,         Vthreshold=   6.4V and Vdrain=0.6V   (where the value of “B”   is defined above).   Identify   the   most important   resistance contributions   and discuss   how these compare to your finding   in   part   (3).
Use the   device   parameters as given   in table   1   (you   may find   reference   [1],   section   6.4    6.5   useful for   this analysis).            [5%]
4.          Using    MATLAB    (or    analogous    software)    discuss  代 写ES4E8 Advanced Power Electronic Converters and DevicesMatlab
代做程序编程语言  how    the    variation    of    JFET    region    LJFET          (i.e    the   distance   between the two   p-base   regions   LJFET= 2*LA) affects the   performance of the device in   part
(2)   with   specific   reference   to   internal   resistance   components.   Keep   the   cell   width   and   channel   length constant.   Illustrate your answers   by   means of corresponding   plots.   [5%]
5.          Discuss   how a   1.2kV   breakdown-rated Silicon   MOSFET device   would   alter the   on-state   resistance   contributions as the temperature   increases from   room temperature to   125C°   .      [5%]
6.          Discuss   how the   on-state   and   off-state   performance   differs   between the Trench   MOSFET   and the
Planar   MOSFET.   Refer to   Figures   1.2   (a) and   (b) for comparison.   [5%]
References 
[1]   Book “Fundamental of   Power semiconductor   Devices”   B.J.   Baliga, Springer   International   Publishing 2008.
Question B The   unipolar   limit   is the theoretical   maximum current-carrying capability of a   unipolar   semiconductor   device, such as a MOSFET, where only one type of charge carrier (either electrons or holes) contributes   to   conduction. This   is   usually   represented   as the   relationship   between the   breakdown voltage   vs   the   specific on-state   resistance. The   unipolar   limit for Silicon   is   plotted   in   Fig.2.An    abrupt    one-dimensional    P+N    diode    is    described    by    the    following    equations    for    the    maximum   electric field (EM   ) V/cm at the   junction and the thickness of the depletion region (WD   ) cm, as functions   of the doping concentration   (N) cm-3      and the applied   reverse   bias   voltage   (VR   ):

Critical electric field   (Ec) for Si, SiC and   GaN   materials   is   shown   below:

Electron   (μe) and   hole   (μℎ)   mobility   models for Si, SiC and   GaN   are   shown   below:




References
[1]   Book “Fundamental of   Power semiconductor   Devices”   B.J.   Baliga, Springer   International   Publishing   2008.[2] T. Hatakeyama, K. Fukuda   and H. Okumura, "Physical   Models for SiC and Their Application to Device   Simulations of SiC Insulated-Gate Bipolar Transistors," in IEEE Transactions on Electron Devices, vol. 60,   no.   2,   pp.   613-621,   Feb. 2013, doi:   10.1109/TED.2012.2226590.[3]   T.   T.   Mnatsakanov,   M.   E.   Levinshtein,   L.   I.   Pomortseva,   S.   N.   Yurkov,   G.   S.   Simin,   and   M.   A.   Khan,   "Carrier    mobility    model    for    GaN," Solid-State    Electronics,    vol.    47,    no.    1,      pp.      111–115,      2003,      doi:   10.1016/S0038-1101(02)00256-3.[4]   J.   A.   Cooper   and   D.   T.   Morisette,   "Performance   Limits   of   Vertical   Unipolar   Power   Devices   in   GaN   and       4H-SiC,"       in IEEE       Electron       Device Letters,       vol.       41,         no.         6,         pp.         892-895,       June         2020,         doi:   10.1109/LED.2020.2987282.
Given the theory above:
1.          Derive   and    plot   the   unipolar   limit   (breakdown   voltage   vs   specific   on-state   resistance)   for   all   three materials: Si, SiC and GaN, where the   majority carrier is electrons. Clearly state equations   used    to    plot    the      unipolar      limit      and      discuss    the      fundamental      differences      between      those   materials. Note, that the breakdown voltage range should be within 100-10 000 V range.   [10%]
2.          Using   the   mobility   equations    provided   above,   plot   the   mobility   vs   doping   for       p-type   and   n-   type   Si,   SiC   and   GaN   materials   and   discuss   the   differences   between   p-type   and   n-type   Si,   SiC   and GaN   materials   in the context of their   impact on   power   device   performance   [10%].
3.         Three   semiconductor   manufacturers,   A,    B,   and   C,   fabricate   650   V   Si    MOSFET   devices.   The   performance    of    these    devices      is      reported      in      Fig.      2.       Explain    the    difference      between    the   performance of the device C compared   to   A   and   B.   [10%]

Figure   2   Performance comparison of   MOSFET devices from   manufacturers A,   B,   and   C.
Question C 
Figure   3.1   shows   the   on-state   characteristics   of   a   3.3kV   Si   and   SiC   PIN   diodes   at   25°C.   Parameters   of   which are summarized   in Table   2.

Table   2.   Parameters for 3.3   kV Si and   SiC   PiN   Diodes.
The   3.3   kV SiC Schottky diode   has the following   I-V equation:

Where A∗ is the   Richardson’s constant equal to   146 A.cm-2K-2      and ΦBN      (eV)   is the   barrier   height.
1.          Discuss which type of diode   you   would   use for   applications   of   100   A/mm2.      (10%)
2.         Justify   the    differences    of   the    two    curves    given   the    material    properties    (i.e.    Vo       value    and   differential   resistance   (line curvature))?   (15%)
3.          Identify      the      SiC      Schottky       diode      forward      voltage      drop      at      100      A/cm2          and       plot      the       I-V   characteristics   for   the   Schottky   contact   metals   with ΦBN    equal   to   0.6   eV,   1.0   eV   and   1.5   eV.   Discuss      how      the      selection      of    the       contact      metal    will       affect      the       on-state      and      off-state   performance.   (15%)

Figure   3.1: The on-state characteristics of a   3.3kV Silicon   and   Silicon   Carbide   PIN   diodes   at   25°C



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
