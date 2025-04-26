# csc3150-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSC3150 Assignment 1 Solved](https://www.ankitcodinghub.com/product/csc3150-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;104974&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC3150 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Homework Requirements

Please note all bold fonts!!!!!!!!!

Environment

If you follow the tutorials guidance, your VM setting should be fine. However, we also highly recommend you to verify your environment again.

Linux Distribution: Ubuntu 20.04 (others are ok)

Linux Kernel Version: 5.10.x (Test Environment) (use uname -r to get it)

GCC Version: 4.9 above (use gcc -v to get it)

Makefile: Please write makefile to compile and install your program in this course. So please learn how to write makefile. We only use makefile to test your program when we grade (If not used, this program will have a score of 0, and it is not acceptable to use your own computer to run). Code Style: Please use clang-format to format your code before submitting. (-10 points if not)

Submission

Violation against the format requirements will lead to grade deduction.

Please compress all files in the file structure root folder into a single zip file and name it using your student id as the code showing below, for example, Assignment_1_118010001.zip. The report should be submitted in the format of pdf, together with your source code. Format mismatch would cause grade deduction(5 points deducted). Here is the sample step to compress your code.

Task 1 (30 points)

In this task, you should write a program ( program1.c ) that implement the functions below:

In user mode, fork a child process to execute the test program. (10 points)

When child process finish execution, the parent process will receive the SIGCHLD signal by wait() function. (5 points)

There are 15 test programs provided. 1 is for normal termination, and the rest are exception cases.

Please use these test programs as your executing programs.

The termination information of child process should be print out. If normal termination, print normal termination and exit status. If not, print out how did the child process terminates and what signal was raised in child process. (15 points) The main flow chart for Task 1 is:

Task 2 (60 points)

In this task, a template (“program2.c”) is provided. Within the template, please implement the functions below:

When program2.ko being initialized, create a kernel thread and run my_fork function. (10 points)

Within my_fork, fork a process to execute the test program. (10 points)

The parent process will wait until child process terminates. (10 points)

Print out the process id for both parent and child process. (5 points)

Within this test program, it will raise signal. The signal could be caught and related message should be printed out in kernel log. (10 points)

Follow the hints below to implement your function. If the function is non-static, you should firstly export this symbol so that it could be used in your own kernel module. After that, you should compile the kernel source code and install it. (Kernel compile: 15 points) Hints:

Use “kernel_thread” or “kernel_clone” to fork a new process.

Use “do_execve” to execute the test program.

Use “getname_kernel” to get filename.

Use “do_wait” to wait for child process’ termination status.

The main flow chart for Task 2 is:

Demo output(Please output your name and student id when module init):

[ 3769.385776] [program2] : module_init {name} {student id}

[ 3769.385777] [program2] : module_init create kthread start

[ 3769.385777] [program2] : module_init kthread start

[ 3769.389787] [program2] : The child process has pid = 2914

[ 3769.389793] [program2] : This is the parent process, pid = 2912

[ 3769.391602] [program2] : child process

[ 3769.391604] [program2] : get SIGTERM signal

[ 3769.391605] [program2] : child process terminated

[ 3769.391605] [program2] : The return signal is 15

[ 3773.346070] [program2] : module_exit./my

Note: the variable path in my_exec() in program2.c should be /tmp/test before submitting your homework, otherwise your grade would be influenced seriously.

Bonus Task (10 pionts)

In this task, we need to create a file to implement this function and the file name is pstree.c . There are many options of pstree . You can use man pstree to discover it. Before implementing this program, I suggest that use this command by yourself to see how it works.

The grading criteria:

The program can output a process tree as above. (5 points)

You will receive one point for each option implemented. So if you want to get 10 points in bonus, you need to implement another 5 options of pstree .

You cannot call the pstree command directly in your program.

Hints: This reference(https://en.wikipedia.org/wiki/Procfs) might help you to finish the bonus task.

Report (10 points)

Write a report for your assignment, which should include main information as below:

Your name and student id.

How did you design your program? (4 points)

How to set up your development environment, including how to compile kernel? (2 points) Screenshot of your program output. (2 points)

What did you learn from the tasks? (2 points)

Please note that the report will only be graded if your total score for Task 1 and Task 2 exceeds 54 points.

Grading rules

Completion Marks

Bonus 10 Points

Report 10 Points

Completed with good quality 80 ~ 90

Completed accurately 80 +

Fully Submitted (compile successfully) 60 +

Partial submitted 0 ~ 60

No submission 0

Late submission Not Allowed

References

https://www.gnu.org/software/libc/manual/html_node/Process-Identification.html

https://elixir.bootlin.com/linux/v5.10/source (This one can help you to search symbols in the kernel.) https://seisman.github.io/how-to-write-makefile/ (Chinese) https://makefiletutorial.com/
