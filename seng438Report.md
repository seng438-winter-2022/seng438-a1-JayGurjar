<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.518 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0Î²33
* Mon Jan 24 2022 19:42:08 GMT-0800 (PST)
* Source doc: SENG 438 Assignment 1 Report
* Tables are currently converted to HTML tables.
----->

# Lab Report - Assignment 1 - Group 18

<table>
  <tr>
   <td>
    Sr.
   </td>
   <td>
    Name
   </td>
   <td>
    UCID
   </td>
  </tr>
  <tr>
   <td>
    1.
   </td>
   <td>
    Ali Siddiqi
   </td>
   <td>
    30092156
   </td>
  </tr>
  <tr>
   <td>
    2.
   </td>
   <td>
    Jay Gurjar
   </td>
   <td>
    30096042
   </td>
  </tr>
  <tr>
   <td>
    3.
   </td>
   <td>
    Kai Wang
   </td>
   <td>
    30002810
   </td>
  </tr>
  <tr>
   <td>
    4.
   </td>
   <td>
    Mohamed Numan
   </td>
   <td>
    30086940
   </td>
  </tr>
</table>


**<span style="text-decoration:underline;">SENG 438 GROUP</span>**

## Introduction

Before this lab we had very little knowledge about testing itself, having only one scenario in a previous course where testing of a java program was carried out. With respect to exploratory testing we knew that it required random investigation of the product to find bugs, adding to this we also knew that our imagination of scenarios was key in this type of testing. Regarding manual scripted testing the name of the testing was self explanatory. The script had to be followed scrictly to discover bugs, and the tests had to determined before the actual testing phase began.
In this lab, we learnt more about the testing techniques. Exploratory testing is an approach to software testing that is often described as simultaneous learning, test design, and execution. It focuses on the discovery and relies on the guidance of the individual tester to uncover defects that are not easily covered in the scope of other tests. On the other hand, manual scripting testing mainly depends on developing a test script and then testing it which is pretty similar to unit testing. We revisited all the bugs in regression testing, after which we reported them. This part of testing required changing the status of the bugs that were reported from the first two testing mechanism. The bugs were noted to be either resolved or in-progress. 

## High-level description of the exploratory testing plan

Exploratory testing required investigation and innovation of testcases during execution. The initial step was to explore balance inquiry and withdrawal functionalities. We also checked various testcases using the money market and other available accounts. After a thorough understanding of the softwares functionality. The plan consisted of just our imagination and how we would use our imagination to come up with scenarios that could have a bug in them.
Our Proposed and followed path for one functionality: 
- Log in with Card number: 2 and Pin: 1234. 
- Choose Balance Inquiry and perform random testcases to find bugs
- Test all buttons visible on the screen to find bugs

We follow the same path for Withdrawal as well as the other functionalities to find bugs.
After complete testing and reporting of bugs using Card number 2, we then followed the same path for Card number 1 to ensure that all the functionalities worked without errors.

## Comparison of exploratory and manual functional testing

Exploratory testing is more natural and the way most testing is usually performed while writing code in general. Manual testing is a more thorough type of testing mechanism performed after Exploratory testing is complete to ensure all the bugs have been found. Moreover Manual Scripted testing also made it easier to catch small bugs that would be harder to find through exploratory testing thus making Manual scripted testing more effective in aiding bug tracking. Exploratory testing was very quick since there was no particular structure on how the tests should be performed, and due to this we unintentionally ended up finding the same bugs multiple times. Therefore with respect to efficiency we conclude that Manual scripted testing was a better approach. Also, exploratory testing was difficult to log and write down as compared to manual testing. Though either of the options have their benefits, we conclude that when it comes to a more reliable form of testing, manual testing is much preferable in general since it maximizes the time spent performing actual code and has an initial overhead at the beginning. However, exploratory testing opens up chance for random unknown bugs to be found that could have been glanced over or not realized in the manual scripted test cases.


## Notes and discussion of the peer reviews of defect reports

We followed the suggested format in the lab manual which was pair testing. We always had at least 2 people review one bug. This peer-reviewing process helped us as it removed many false-positive bugs. Adding to this, the other teammate added feedback when they checked on our internal document for consistency. We followed the suggested format to report and reproduce the bug later with version 1.1.
As soon as a bug report was submitted we had our partner recheck the format of the report. This was to ensure that the reports submitted had enough information to properly deduce what was causing the defect and why it was occurring. We tried to stick to the suggested format for bug reports that the lab manual proposed, each one containing the function being tested, the initial state of the program, what steps are necessary to reproduce the bug, and the expected outcome (or oracle) as well as the actual outcome of the test being performed.


## How the pair testing was managed and teamwork/effort was divided

For pair testing, we had one partner who was sharing their screen and attempting to run the scripted testcases or an exploratory testcase while the other overlooked the execution of the testcase. After execution one of them logged the bugs in the software. The roles were switched for every testcase to provide both partners hands-on learning experience with testing. For exploratory and manual testing one benefit of the partner was discussing bugs and talking about them and ensuring no errors were made. Working with a partner provided a different perspective on testing and gave different ideas. 


## Difficulties encountered, challenges overcome, and lessons learned

Since there was no explicit format or steps for exploratory testing it was a bit difficult to think of testcases, report and keep track of the bugs. lack of a definite number of testcases adding to the difficulties while we were performing exploratory testing. We fixed the problem by reporting the bug when we encountered it, without even trying to reproduce it, since that's not the nature of exploratory testing. We learned that manual testing is a more organized form of testing and allows for everything to be performed more effectively in a systematic manner, adding to this we learnt that manual scripted testing allows us to replicate the test very easily since the script is documented beforehand.

## Comments/feedback on the lab and lab document itself

The lab was interesting and informative, we learnt a lot about different testing techniques and the importance of testing itself, we became aware of the fact that testing is a major component in the success of a work product. We would prefer a pdf submission instead as that is what we are more accustomed to.
