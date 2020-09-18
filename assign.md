---
layout: page
title: Assignments
permalink: /assignments/
---

<h2> Programming Assignments </h2>
<hr>

<p>
We will do <font color="#FF0000">five</font> programming
assignments. The first four programming assignments take up 10% of
your total grade. The fifth assignment takes up 15% of your total
grade. Some assignments provide extra credit beyond your total grade.
</p>

<ul>
<li> Assignment 1: <a href="../assignment/assignment1/wordcounting.html"> A Word Counting Program</a> (due: 11:59 PM on 9/18 (Friday)) </li>
<li> Assignment 2: <a href="../assignment/assignment2/stringfile.html"> String Manipulation</a>  (due: 11:59 PM on 10/08 (Thursday)) </li>
<li> Assignment 3: TBA (due: 11:59 PM on 11/06 (Friday)) </li>
<li> Assignment 4: TBA (due: 11:59 PM on 11/27 (Friday)) </li>
<li> Assignment 5: TBA (due: 11:59 PM on 12/22 (Tuesday)) </li>
</ul>


<h2> Tips on Downloading Files and Making a File Executable </h2>
<hr>

<!--font color="##FF0000"-->
<p>
To download any files linked in assignment pages from your linux terminal, you can use <code>wget</code> and specify the URL of the file. For example,
</p><pre style="margin-left:2em; color:blue">wget https://ee209-2020-fall.github.io/assignment/assignment1/samplewc209
</pre>
this command will download the sample binary (samplewc209) to your current directory. You can get the URL of the file by right-clicking the hyperlink and then selecting "copy link address".
<p>
If you downloaded a binary file and want to execute it, you need to set its execution bits. If you want to allow a file named <code>samplewc209</code> to be executable in current directory, type:
</p><pre style="margin-left:2em; color:blue">chmod u+x samplewc209
</pre>
then <code>samplewc209</code> will become
executable. The <code>u</code> option in <code>chmod</code> indicates
that the operation applies to access of the user who owns this file
and <code>x</code> means that the command updates the execution bit of
the file. For more information about <code>chmod</code>
or <code>wget</code>, try <code>man</code>.

<!--/font-->

<h2> Assignment Submission (Important) </h2>
<hr>

<p>
Use <a href="http://klms.kaist.ac.kr/">KAIST KLMS</a> to submit your
assignments. Your submission should be one gzipped tar file
whose name is

</p><p>
YourStudentID_assign#.tar.gz

</p><p>
For example, if your student ID is 20195399, and it is for assignment #1,
please name the file as

</p><p>
20195399_assign1.tar.gz

</p><p>
To create the .tar.gz, first move all your files to the directory (20195399_assign1).

</p><p>
mkdir 20195399_assign1 <br>
mv all_your_files 20195399_assign1<br>

</p><p>
Then, create a .tar.gz file by the 'tar' command like

</p><p>
tar zcf 20195399_assign1.tar.gz 20195399_assign1

</p><p>
Then, you'll see  20195399_assign1.tar.gz. If you want to decompress and release the files in it (in a different directory),

</p><p>
tar zxf 20195399_assign1.tar.gz

</p><h2> Ethics Document (Important) </h2>
<hr>

<p>
For every assignment submission, please fill out and submit
the <b>pdf</b> version of <a href="../assignment/EthicsOath.docx">this
document</a> that pledges your honor that you did not violate any
ethics rules required by <a href="../policy">this course</a> and
KAIST.  You can either scan a printed version into a pdf file or make
the Word document into a pdf file after filling it out.

</p><p>
Please sign on the document and submit it along with your other
assignment files, or we won't grade your assignment.


</p><h2> Late Submission Penalty </h2>
<hr>

<p>
Students can use late submission (late pass) which can be late up
to <i>three days</i> without penalty for the first four programming
assignments. That is, you can apply your late submission days (within
3 days in total) spread over the first four programming
assignments. The minimum granulaity is one day: if you are 1 hour
late, that's still counted as one day late. If you're going to spend
your free late days, please say so in your readme file.

Beyond the free late days, we will enforce this penalty rule for each
assignment. One will get
</p><ul>
<li> 95% of the full credit up to 3 hours late,
</li><li> 90% of the full credit up to 6 hours late,
</li><li> 85% of the full credit up to 12 hours late,
</li><li> 75% of the full credit up to 24 hours late,
</li><li> 50% of the full credit up to 48 hours late,
</li><li>  0% of the full credit beyond 48 hours late
</li></ul>

<p> <b>Important</b>: Note that we do not accept late submission for the
last assignment (assignment 5). Any late submission (e.g., submitted after 11:59 PM on
12/22, regardless of whether you have free days or not) will result in
zero credit for the last assignment.

</p><p>We will grant extensions only in case of illness(with doctor's note)
or extraordinary cicrumstances. In case you are submitting your work
late due to illness or extraordinary circumstances, please consult
with the instructor as soon as possible. Please plan ahead (travel,
religious holidays, etc.) to meet the deadlines. Note that heavy
workload is not counted as extraordinary cicrumstances.


</p><h2> Collaboration Policy </h2>
<hr>

<p>
Please refer to <a href="../policy">the course policy page</a>.


</p><h2> Coding Style </h2>
<hr>

<p>
Good coding style will be one criterion for grading each
assignment. Please make sure your code has proper indentation and
descriptive comments. At the start of each file, please add your name,
lab account ID and the description of the file. Make sure not to leak
any memory and check/handle every return value of function calls.
</p>

<h2> Assignment Grading </h2>
<hr>

<p>
Your submission will be graded on one of the Lab machines for the
course.  You are free to use other machines for coding and debugging,
but please make sure to compile and test your final version on the Lab
machines. In a rare case, library mismatch or O/S stack difference
(Solaris vs. Linux) can bypass some of your bugs, but they can
actually show up on the Lab machines while grading. In order to avoid
this last-minute surprise, please test on Lab machines before
submitting your work.
</p>

<h2> Manual grading policy </h2>
<hr>

<p>
Trivial mistake in your submission may cause huge amount of deduction in your assignment score. For such exceptional circumstances, you can request and get manual grading at the TA's discretion. For each modification and manual grading, you will get <font color="#FF0000">15% amount of deduction</font> from your total score.
</p>
