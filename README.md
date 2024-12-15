java c
UFMF4X-15-M Robotic   Fundamentals 
Coursework: Serial and   Parallel Robot    Kinematics
This      document    explains       requirements    for    the      assessed      coursework      for      the       UFMF4X-15-M       Robotic   Fundamentals   module.
The module is assessed in one   report that is worth   50%   of your overall   mark. The assessment will   be   based   on a series of simulated experiments   using   a   series   and   a   parallel   manipulator.The   coursework   also   includes   suggestions   of topics   you   may   want   to   work   on   in   order   to   demonstrate   a   fuller    understanding    of    the    more      advanced      parts      and      attain      a      higher      mark.      This      additional      work      is   expressed   here   in an open-ended way, as appropriate   for   Masters   level    study.The   deadline for   submission   is 16th of January 2025,Thursday, 2pm on UWE Blackboard. Both members of each/every group needs to make a submission (same coppy). Dont forget to include UWE student number of each member. Robotics Toolbox of MATLAB is NOT allowed. 
PART   I: 
A.   From   material covered during   lectures,   lab exercises and   examples,   complete the   following   tasks:
1)       Derive a   DH   representation   of   forward   kinematics   for   the   Lynxmotion   arm.   Use   MATLAB,   lecture   material and further   reading.   Include all your   investigations and   report   this.
2)       Analyse the workspace of the centre   of   the   wrist   (5th   joint)   when   each   preceding joint   moves   through   its   range of   motion and   plot the   2D and 3D   views   of   the    workspace.
3)       Derive the   inverse   kinematics   model for the   manipulator   (analytical   solution).
B.    Complete   the following:
1)         Plan a task in   MATLAB with at least 5   positions. This   process should   give   you   at   least   5   sets   of   Cartesian coordinates specifying the end-effector   position and   orientation   in   3D    space.
2)       Solve the   Inverse   Kinematics for these   positions   in   3D   space   and   obtain   sets   of Joint Coordinates.   Create an appropriate   plot/animation   in   MATLAB for the   motion of the    robot.
3)         Implement 3 different trajectories   between the Cartesian   Points   identified   above   and   create   an   appropriate   plot to demonstrate them):
a.          Implement a free   motion   between the   points
b.         Implement a straight   line trajectory   between the   points
c.          Set an obstacle   between any two   points   (e.g.   a   cylinder   between   point   3   and 4)   and   implement an object   avoidance   trajectory.
PART   II: 
consider   a planar parallel robot used   in   a   surgical   procedure   to   position   a   needle   above   the   patient,   see Figure   1   .

Figure   1   .   Needle   positioning   parallel   Robot.
The   parallel   robot consists of a fixed   Base   plate,   a   Moving platform   ,   six pass代 写UFMF4X-15-M Robotic FundamentalsMatlab
代做程序编程语言ive   revolute joints   (Mi and   ppi   where   i=1:3)   and   three   active   revolute   joints   (PBi   where   i=1:3)   . The   ith   strut   of   the   robot   consists therefore   of   three joints that are subdivided   in the   upper section SA,   and the   lower section   L.   For further   information   to   the   robot   see   its   kinematic   model   in   Figure   2   .   Develop a   kinematic simulation   of   the   parallel   robot   in   MATLAB to: 
1)       solve   and   implement   parallel   robot   Inverse   kinematics.   calculate the joint coordinates i where   i=1:3   from   the   cartesian   parameters   of the   platform   '   S   Centre   {c}   (where   the   needle   is   based)   .   These   parameters   are   the   (xcs   Yc)   coordinates   and   the   orientation   of the   platform   (a)   .   plot   the   kinematic   model      in   two   different   positions.   changing   the   cartesian      input   parameters   should   adapt each   leg to the   new cartesian   position. An   example   plot   is shown   in   Figure 3   .
2)       plot   the    parallel   robots   workspace   for   a   given   orientation   a.   This   is   crucial   for   the   mechanism   synthesis   analysis.

Figure 2:   planar parallel   Robot   kinematic Model

Figure   3: simulated   robot   motion
PART   III: 
TO ATTAIN A   HIGHER   MARK CARRY OUT THE   FOLLOWING:choose   a   relevant   topic   that   is   not   mentioned   here,   but   relevant   to   the   coursework   subject   domain, and carry   out   theoretical   or   experimental   work   on   that   topic.   For   example,   this   work   could   be   analysing   alternative      methods      of   inverse      kinematics      calculation      such      as      motor      babbling,    optimisation,    screw theory,   etc.   ,   investigating   methods   and   algorithms   that   can   be   used   to   avoid   problems   when   operating close   to   a   singularity   in   the   robot's   workspace   etc.   or   something   else.   Discuss   your   chosen   topic with   the module tutors before you   start.
Reporting Details 
You   have   to   write   a   report,   using   not   more   than   3000 words   to   describe   your   investigations   and   results.   You   need   to:
1)       Demonstrate   that   you   understand   the   theory   behind   the   approaches   you   use   to   solve   a   problem.
2)       critical   assessment and   analysis of the   relative   merits of   the approaches you   have   used
3)       show      that    you    have    appreciation    of    issues    and      principles      used      to      establish      safe      operation      of   manipulators in the   human   environment
4)       present   your   conclusions.
5)       provide   any   references   using   the   Harvard   system
6)       provide   any   code   you   have   written   in   an   appendix   AND   the   actual   .   m   files   (Matlab)   as   attachments.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
