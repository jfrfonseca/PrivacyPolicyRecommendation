===============================
# PrivacyPolicyRecommendation #
===============================

A recommender system that detects the fishy-er lines of a Privacy Policy statement, and presents those for yout deliberation.
Who has the time to read a 1000-line long unreadable legalese document? Gimme the important 20 or so lines!

The maintainers of most applications, services, web-pages, data or software packages, or actually anything nowadays, require users to agree and comply with a Privacy Policy Statement, a legal document full with a lot of complicated words that should inform you how the data collected from the user will be used or shared with third-parties.
The act of agreeing with a Privacy Policy attests the user’s compromise of compliance with the legal requirements as stated by the application maintainer, and concordance with the use given to the data collected.

The user may be prompted to read the legal document during the installation of a software package or creation of a web-service account, and by proceeding with the operation at hand the user is considered to have given consent for the collect and use of data.

It is estimated that a user would take 7 minutes to briefly skim through a medium-sized Privacy Policy Statement. They also estimated that the citizens of the United States of America collectively would
spend 53.8 billion hours to properly read all the Privacy Policies prompted to them, every year. Wow. We could be curing cancers, solving the economy, paying taxes or taking a vacation in Mars with all that time.

we propose a system capable of recommending sentences of interest from a document, to be carefully analyzed by the reader. The recommendation is based on the analysis of the document’s contents and a previously elaborated knowledge and probabilistic model.

We expect to minimize time cost of reading Privacy Policy Statements without compromising the user’s knowledge of its inner proceedings.

We used information retrieval techniques like fuzzy string matching to detect sentences from documents that are more closely related to a set of predetermined legal sentences known to be a threat to user privacy. Such sentences were elaborated after manual analysis of several Privacy Policies and consulting with a lawyer and different user privacy defender groups.
Potentially harmful sentences identified in documents are presented for the user to review, in decreasing order of similarity with known harmful sentences.

### This project is still in its early stages. A more scientific version of this text, a proper Research Project, can be found in the "academic" subdirectory

