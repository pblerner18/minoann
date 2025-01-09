# minoann
Using c-GAN neural network to recognize language from transliterated fragment

I applied the c-GAN methodology I developed for the financial time series (A New Entropic Measure for the Causality of the Financial Time Series, https://www.mdpi.com/1911-8074/16/7/338) for recognition of the dependency of the natural languages. A potential goal of the method is to recognize the affinity of natural languages irrespectively of their decipherment as long as the signs can be transliterated into a uniform framework (for instance, UTF-8). Heretofore, the trade project is Minoann, which means Minoan and neural network in reference to the language, which has not been yet phonetically transliterated lest deciphered. 

My method uses making a 2-D array out of the text fragment. Using one fragment as a training sample and another-- as the test sample allows to determine correlations between the arrays simulated by c-GAN and an actual fragment array. The correlations between arrays allow to work out some distance properties between them. The thrust is to apply numerous computerized methods already developed for the analysis of the visual images to lingustic studies. 

Post-processing involves both visual and computerized analysis of the sample distances between arrays. The study is agnostic with respect to the potential meaning of the fragments and/or their decipherment and intended for a much more limited purpose -- namely, to distinguish between fragments of languages from different families. 
