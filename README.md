# Fairness

#####################
###############Provided 4 different algos##########################

LPC  (minimize DP)
LPCA (accuracy)(beta as input)
LPCA_gerry (accuracy+gerry)
LPCA_generative (accuracy+generative(LPCA with (alpha>0) variations for configuration generation )(* LPCA only with beta as variables)

LPCNA (accuracy) (beta as input) (without confidence values)

####################################################################
#####################
#########################Important methods####################

1> min_sum_lpc()/min_sum_lpca()/min_sum_lpca_gerry()/min_sum_lpca_g()
use: to solve Demographic disparity

2> main()
use: to get groupwise precision and recall 

3> svm()
use: to split train test sets

4> main(sensitive, Y_test, Y_test_pred,e)
use: to call and run the methods to get output
################################################################
#####################

Instructions:

Please run the cells in top down fashion

--->The main callable function(4) will finally call all other functions inherently to generate out put for the given inputs.   

#####################
