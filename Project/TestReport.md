# Test Report

This assignment marks the end of your project, so further changes to the system should not be made after this assignment is submitted (there is a project presentation due a week later, but changes to your system made between this assignment and your project presentation will not be graded, so spend time on the presentation, not the system, after this point).

There are two things to submit.  One is the final version of your system, in exactly the configuration that you tested.  Submit this in the same way as in the prior assignment (i.e., either as a URL or as the files that we need to install and run your system).

The other thing is your project test report.  This should include four parts:

* A brief description of any changes to your system since you submitted your project prototype.  
* Complete instructions on how to run (and, if necessary, how to install, your system).  These can be copied from your prior assignment, but with any necessary changes included.
* Your project test plan.  This should be based on the initial draft test plan that you submitted with your project detailed design (which was not graded at that time, but which we will have commented on), with any changes that resulted from design changes or differences between your plan and your actual implementation, and with any improvements based on what you have learned from our comments, from the experience of building the system, and from actually trying to run the test yourself. 
* Your test results.

There are some timing issues to consider in planning your work on this.  The system you submit must be the system as tested, so if you discover a problem with your system during testing and you choose to fix your system, you would then need to rerun the test.  The other thing you may find a problem with is your test plan (your system might be fine, but you might find that you designed a poor test), and of course if you change your test plan then you also need to rerun your final test plan.  So don't be doing your first test on the day all this is due!  The best approach would be to actually run your test on your prototype as soon as you turn that in, and then you will have time to make any final changes to your system and your test plan and to plan some time to run the final test and complete your test report.

Your report should be about 10 pages, single spaced.

The grade for this assignment will be divided as 5 points for your project, and 5 points for your test planning and the report of your test results.

### Score: 10/10

## Feedback
- tabulated results
- evaluation measures + variation by annotator
- were 3 tags enough to draw conclusions
- comparison of TFID and BERT
- report was below expected length

Grade for the project: 5 
This was an ambitious project in which the team integrated automatic processing of content from Twitter with automatic processing of downloaded news stories and automatic text classification. The projects scope was well managed in order to complete the core functionality that was the teams principal focus, and the resulting functionality matched the revised scope well. The investigation of BERT classification was an excellent choice as an additional stretch goal, although results are not provided in the report for BERT classification. I ran the BERT code (after manually specifying a GLP runtime, since it fails with a CPU runtime) and I see that evaluation results are reported on a dataset called validation, but I was not able to see how it would be (or was) run on the same data as the original system. 

Grade for testing: 5 The focus of the test plan on evaluating the degree to which the system decision matched human decisions on the same document was well chosen. The choice to use of two human annotators, operating independently of each other and neither of whom knew the system’s decision, was excellent. The selection of three sets of five results each (a total of 15 results, with two human decisions for each) was sufficient to illustrate the evaluation process, although it was not sufficient to perform a statistically reliable evaluation. The narrative description of the evaluation results is sufficient to explain what was done and how the results were interpreted, but the test report lacks details on the actual results (bother by the system and by each annotator), despite being less than half of the expected length as specified in the assignment. The description of two evaluation measures that could be computed (precision, recall, and balanced accuracy) was useful, but no evaluation measure values are included in the report. Moreover, it seems that no evaluation measures were computed, since results are described only with reference to individual cases and not with reference to any particular evaluation measure. The descriptive analysis did produce useful insights, although the lack of detailed data and the lack of evaluation measures limited the clarity with which those results were communicated (e.g., we are told that in one case the “ratings varied between each checker” but we are not told the nature of the variation).
