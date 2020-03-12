# Spam-Classifier-using-SVMs
Many email services today provide spam filters that are able to classify emails into spam and non-spam email with high accuracy.
In this project, I used SVMs to build my own spam filter. I trained a classifier to classify whether a given email, x, is spam 
(y = 1) or non-spam (y = 0). In particular, I converted each email into a feature vector x 2 Rn.  The dataset included for this
project is based on a subset of the SpamAssassin Public Corpus.3 For the purpose of this project, I only used the body of the 
email (excluding the email headers).


Working Output:
________________________________________________________________________________________________
Preprocessing sample email (emailSample1.txt)

==== Processed Email ====

anyon know how much it cost to host a web portal well it depend on how mani
visitor you re expect thi can be anywher from less than number buck a month
to a coupl of dollarnumb you should checkout httpaddr or perhap amazon ecnumb
if your run someth big to unsubscrib yourself from thi mail list send an
email to emailaddr

=========================
Word Indices:
 86 916 794 1077 883 370 1699 790 1822 1831 883 431 1171 794 1002 1893 1364 592 1676 238 162 89 6
88 945 1663 1120 1062 1699 375 1162 479 1893 1510 799 1182 1237 810 1895 1440 1547 181 1699 1758
1896 688 1676 992 961 1477 71 530 1699 531

Program paused. Press enter to continue.

Extracting features from sample email (emailSample1.txt)

==== Processed Email ====

anyon know how much it cost to host a web portal well it depend on how mani
visitor you re expect thi can be anywher from less than number buck a month
to a coupl of dollarnumb you should checkout httpaddr or perhap amazon ecnumb
if your run someth big to unsubscrib yourself from thi mail list send an
email to emailaddr

=========================
Length of feature vector: 1899
Number of non-zero entries: 45
Program paused. Press enter to continue.

Training Linear SVM (Spam Classification)
(this may take 1 to 2 minutes) ...
Training ......................................................................
...............................................................................
...............................................................................
....................................................... Done!

Training Accuracy: 99.825000

Evaluating the trained Linear SVM on a test set ...
Test Accuracy: 98.700000

Top predictors of spam:
 our             (0.501456)
 click           (0.467989)
 remov           (0.419438)
 guarante        (0.382354)
 visit           (0.365856)
 basenumb        (0.342807)
 dollar          (0.328581)
 price           (0.271460)
 will            (0.270347)
 nbsp            (0.260170)
 pleas           (0.257697)
 most            (0.252503)
 lo              (0.248815)
 hour            (0.241071)
 da              (0.239341)



Program paused. Press enter to continue.

==== Processed Email ====

do you want to make dollarnumb or more per week if you ar a motiv and qualifi
individu i will person demonstr to you a system that will make you dollarnumb
number per week or more thi is not mlm call our number hour pre record number
to get the detail number number number i need peopl who want to make seriou
monei make the call and get the fact invest number minut in yourself now
number number number look forward to your call and i will introduc you to
peopl like yourself who ar current make dollarnumb number plu per week number
number number numberljgvnumb numberleannumberlrmsnumb
numberwxhonumberqiytnumb numberrjuvnumberhqcfnumb numbereidbnumberdmtvlnumb

=========================

Processed spamSample1.txt

Spam Classification: 1
(1 indicates spam, 0 indicates not spam)
_______________________________________________________________________________________
