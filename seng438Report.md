<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.518 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Mon Jan 24 2022 19:42:08 GMT-0800 (PST)
* Source doc: SENG 438 Assignment 1 Report
* Tables are currently converted to HTML tables.
----->


**SENG 438 Assignment 1 Report	**

**Group: (number)**


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

**Introduction**

In this lab, we explored different techniques used to test software. Exploratory testing is an approach to software testing that is often described as simultaneous learning, test design, and execution. It focuses on the discovery and relies on the guidance of the individual tester to uncover defects that are not easily covered in the scope of other tests. On the other hand, manual scripting testing mainly depends on developing a test script and then testing it which is pretty similar to unit testing. We revisited all the bugs in regression testing. We reported resolved and in-progress bugs with this. 

 

**High-level description of the exploratory testing plan**

The initial step was to explore balance inquiry and withdrawal functionalities. Check money markets and other available accounts. Reading the functionality, we thought withdrawal will give errors for the money market as we will extensively test the money market to be buggy with the balance inquiry. Proposed path: log in with card no: 2 and pin: 1234. Then go to balance inquiry and extensively test it. Then test buttons available on the screen to see if they work according to their functionality. Then move forward with testing withdrawal. We will also later the functionalities with card no 1. 

For testing, we decided that one pair of groups should do exploratory testing.

 

**Comparison of exploratory and manual functional testing**

Exploratory testing is more natural and the way most testing is usually performed while writing code in general. Manual testing is a more thorough type of testing performed a bit later to make and it also made it easier to catch small bugs that would be harder to find through exploratory testing. Exploratory testing was very quick to do since there was no particular structure to it, however, due to the lack of structure we accidentally ended up finding the same bugs multiple times. Also, exploratory testing was a bit harder to log and write down as compared to manual testing. When it comes to a more reliable form of testing, manual testing is much better in general since it maximizes the time spent performing actual code and has an initial overhead at the start. However, exploratory testing allows for random unknown bugs to be found that could have been glanced over or not realized in the manual test cases.

**Notes and discussion of the peer reviews of defect reports**

We followed the suggested format in the lab manual which was pair testing. We always had at least 2 people review one bug. This peer-reviewing process helped us as it removed many false-positive bugs. Also, that other person added feedback when they checked on our internal document for consistency. We pretty much stuck to the suggested format to report and then reproduce the bug later with version 1.1.

As soon as a bug report was submitted we had our partner recheck the format of the report. This was to ensure that the reports submitted had enough information to properly deduce what was causing the defect and why it was occurring. We tried to stick to the suggested format for bug reports that the lab manual proposed, each one containing the function being tested, the initial state of the program, what steps are necessary to reproduce the bug, and the expected outcome (or oracle) as well as the actual outcome of the test being performed.

 

**How the pair testing was managed and teamwork/effort was divided**

For pair testing, one partner was sharing their screen and the other was logging the bugs in the software. For exploratory and manual testing one benefit of the partner was discussing bugs and talking about them and ensuring no mistakes were made. Working with a partner provided a different perspective on testing and gave different ideas. 

 

**Difficulties encountered, challenges overcome, and lessons learned**

Since there was no explicit format about exploratory testing it was a little difficult to report and keep track of the bugs due to a lack of specific format. We fixed the problem by reporting the bug when we encountered it, without even trying to reproduce it, since that's not the nature of exploratory testing. Also we learned that manual testing is a more organized form of testing and allows for everything to be performed more effectively.

 **Comments/feedback on the lab and lab document itself**

The lab was interesting and we learned a lot about different testing techniques. We would prefer a pdf submission instead as that is what we are more accustomed to.
