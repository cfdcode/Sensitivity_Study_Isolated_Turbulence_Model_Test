# Sensitivity_Study_Isolated_Turbulence_Model_Test
This code is for a sensitivity study of three turbulence models: realizableKE, kOmegaSST and RNGkEpsilon - the comparative analysis between CFD results and wind tunnel testing outcomes. The experiment example of the Architectural Institute of Japan (AIJ) was chosen [1], [2], [3], [4], [5]. The code for kOmegaSST and RNGkEpsilon is same as that of realizableKE with the exception of "momentumTransport" file. Hence, only momentumTransport file has been posted for the kOmegaSST and RNGkEpsilon. Refer to the code of realizableKE for the full script. The code was created with C++ based on OpenFOAM source (v.9) [6].

References

[1] Mochida, A., Y. Tominaga, S. Murakami, R. Yshie, T. Ishihara, and R. Ooka. “Comparison of various k-ε models and DSM applied to flow around a high-rise building – report on AIJ cooperative project for CFD prediction of wind environment –.” Wind and Structures 5, no. 2-4 (April 2002): 227-44.
https://doi.org/10.12989/was.2002.5.2_3_4.227.

[2] Tominaga, Y., A. Mochida, T. Shirasawa, R. Yoshie, H. Kataoka, K. Harimoto, and T. Nozu, “Cross Comparisons of CFD Results of Wind Environment at Pedestrian Level around a High-rise Building and within a Building Complex.” J. Asian Archit. Build. Eng. 3, no. 1 (April 2004): 63-70.
https://doi.org/10.3130/jaabe.3.63.

[3] Tominaga, Yoshihide, Akashi Mochida, Ryuichiro Yoshie, Hiroto Kataoka, Tsuyoshi Nozu, Masaru Yoshikawa, and Taichi Shirasawa. “AIJ Guidelines for Practical Applications of CFD to Pedestrian Wind Environment around Buildings.” Journal of Wind Engineering and Industrial Aerodynamics 96, no. 10–11 (October 2008): 1749–61. https://doi.org/10.1016/j.jweia.2008.02.058.

[4] Yoshie, R., A. Mochida, Y. Tominaga, H. Kataoka, K. Harimoto, T. Nozu, and T. Shirasawa. “Cooperative Project for CFD Prediction of Pedestrian Wind Environment in the Architectural Institute of Japan.” Journal of Wind Engineering and Industrial Aerodynamics 95, no. 9 (1 October 2007): 1551–78.
https://doi.org/10.1016/j.jweia.2007.02.023.

[5] Architectural Institute of Japan. “Guidebook for CFD Predictions of Urban Wind Environment.” Accessed October 6, 2021.
https://www.aij.or.jp/jpn/publish/cfdguide/index_e.htm.

[6] The OpenFOAM Foundation. “C++ Source Code Guide.” OpenFOAM v9. Accessed October 6, 2021.
https://cpp.openfoam.org/v9/index.html.
