# SAGA-Network-Aligner
Authors: Elham Mahdipour, Mohammad Ghasemzadeh

This is SA-GA network aligner program, and implemented by Elham Mahdipour that is Ph.D. Candidate of Artificial Intelligence at Yazd University, Yazd, Iran.  All copyright reserved by the authors.

You can run the program from first to end and see all the results, but since the population generation process can take a time depended on the node numbers of networks, you can use the populations stored in each program. We saved the populations as the pair of related species that you can see in the input folder and load them on program, such as "mm-ce-pop.pickle". Also you need another file such as "mm-ce-base_permute.pickle". Please upload data files on root of jupyter notebook or subfolder.

Therefore, you must run follow steps:
1) Run all cells in "Load Graphs", "Swap Graphs", "Define Target Graph",and "Compute Score for create similarity matrix" sections.
2) If you will use saved population, please upload related pickle on root of jupyter notebook, then go "load population" cell and run them; else, please run "multi tasking for initial population", "multi processing for speed up", and "Initialization such as MeAlign" cells. 
3) Run all remains cells to create results. 

Please feel free and contact to me (elham.mahdipour@gmail.com) if there are any problem.

You can change the data file name such as input and output subfolders and run program for other pairs of species. You can see the experimental results in output subfolders of data folder. 

we have limit in upload files. So we load MM-CE and MM-SC pairs of species. 
This data is available in Biogrid dataset. You can download data from https://downloads.thebiogrid.org/BioGRID/Release-Archive/BIOGRID-3.5.170/ and prepare them such as files in input folder. 

Best Regards,

Elham Mahdipour

Ph.D. candidate of Artificial Intelligence at Yazd University, Yazd, Iran. 
