# LPnetlib/lp_e226

 UF Sparse Matrix Collection, Tim Davis

 http://www.cise.ufl.edu/research/sparse/matrices/LPnetlib/lp_e226

 [Netlib LP problem e226: minimize c'*x, where Ax=b, lo<=x<=hi]

 id: 620

 date: 

 author: M. Saunders

 ed: D. Gay

 fields: title name A b id aux kind date author ed notes

 aux: c lo hi z0

 kind: linear programming problem

 notes:

 A Netlib LP problem, in lp/data.  For more information                        

 send email to netlib@ornl.gov with the message:                               

                                                                               

 	 send index from lp                                                          

 	 send readme from lp/data                                                    

 	 send minos from lp/data                                                     

                                                                               

 The following are relevant excerpts from lp/data/readme (by David M. Gay):    

                                                                               

 The column and nonzero counts in the PROBLEM SUMMARY TABLE below exclude      

 slack and surplus columns and the right-hand side vector, but include         

 the cost row.  We have omitted other free rows and all but the first          

 right-hand side vector, as noted below.  The byte count is for the            

 MPS compressed file; it includes a newline character at the end of each       

 line.  These files start with a blank initial line intended to prevent        

 mail programs from discarding any of the data.  The BR column indicates       

 whether a problem has bounds or ranges:  B stands for "has bounds", R         

 for "has ranges".                                                             

                                                                               

 The optimal value is from MINOS version 5.3 (of Sept. 1988)                   

 running on a VAX with default options.                                        

                                                                               

                        PROBLEM SUMMARY TABLE                                  

                                                                               

 Name       Rows   Cols   Nonzeros    Bytes  BR      Optimal Value             

 E226        224    282     2767      17749       -1.8751929066E+01            

                                                                               

 From Michael Saunders, Systems Optimization Laboratory at Stanford University.

 When included in Netlib: Extra free rows omitted.                             

                                                                               

 The following are relevant excerts from lp/data/minos (by Michael Saunders),  

 regarding experience with MINOS 5.0 on the problems he provided:              

                                                                               

                                                      (unscaled)   (scaled)    

 File   Name    Rows  Cols  Elems  Optimal Objective  Itns  Time  Itns  Time   

 ---- --------  ----  ----  -----  -----------------  ----  ----  ----  ----   

   8. E226       226   282   3038 -1.8751929E+01       570   9.4   471   7.5   

                                                                               

 * Objective  is the first row of type N.  It is minimized except as shown.    

                                                                               

 * Itns       is the number of iterations required to solve the problem        

              by the primal simplex method, as implemented in the Fortran      

              code MINOS 5.0 (May 1985), using default values for all          

              parameters.  (The initial basis is triangular.)                  

                                                                               

 * Time       is the processor time required on an IBM 3081K.  The MINOS       

              source code was compiled with the IBM Fortran 77 compiler        

              VS FORTRAN, using the options NOSDUMP, NOSYM and OPT(3).         

                                                                               

![LPnetlib/lp_e226](http://yifanhu.net/GALLERY/GRAPHS/GIF_SMALL/LPnetlib@lp_e226.gif)
