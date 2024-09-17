# Evaluation-model-inspiration
I want to know how to evaluate un machine learning model

Before start, let's know some indicators :

$$ 
True\ Positive\ Rate\ (TPR)\ =\ \frac{True\ Possitive}{All\ Possitive\ \(TP+FN\)} 
$$

$$ 
False\ Positive\ Rate\ (FPR)\ =\ \frac{False\ Negative}{All\ Negative\ \(FP+TN\)} 
$$

## KS Indicator
It is often used in finance, with model of risk. We talk about it when the prediction has been done and we have some data reel to check
### Formula
$$
KS\ = \ \max{ ( False\ Positive\ Rate\ - False\ Positive\ Rate )  }
$$

In financial case, 
* KS < 0,2 means that a model can't be able to well distinct good guy and bad guy. 
* KS between 0,2 and 0,4 is the most case, means the model has some capacity to distinct the case and it means something but not enough. Il needs to continue to study with other indice
* KS between 0,4 and 0,7, that's good, it's good to used in comocial environement.
* KS > 0,7, it's too great to use, we need to check in the model


here is an example :
