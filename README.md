# Classical-CG-Normalized-CG-Normalized-with-Restart-CG-Methods
Optimizing the likelihood function and determining the parameters of parametric operational equations using optimization methods, such as Classical Conjugate Gradient (Classical CG),
Normalized Conjugate Gradient (N.CG), and Normalized Conjugate Gradient with Restart (NR.CG), within the PIGP technique."

1) Implement the parametric operator equation, represented as K covariance matrix blocks, within the 'likelihood.m' file for all three optimization methods mentioned above."

2) In all three optimization methods, you can configure settings related to the number of training data points and data noise within the 'mainClassicalCG.m', 'mainNormalizedCG.m,
 ' and 'mainNRCG.m' files, specifically in the 'Setup' section. Additionally, the training data can be accessed or generated within the same files in the Generate section.
  For the 'Normalized with Restart CG' method, you need to manually determine different values for the initial step length in the 'mainNRCG' file within the Optimize model section.
 This requirement does not apply to the other two optimization methods."
3) In the 'Normalized CG' and 'NRCG' optimization methods, you can adjust the variable for η to normalize the initial step length within the 'NormalizedCG.m' and 'NRCG.m' files,
  respectively, specifically in the 'Computation of Wolf LineSearch and 'Initial step length normalization' sections.

After making the above settings, you can run any of the optimization methods from the main file. 
work in progress by Esmaeilbeigi, Kamandi, Ezati. 
A portion of these codes has been derived from the GPr sections of the implementations provided by Raissi, and we have made some modifications to them.
