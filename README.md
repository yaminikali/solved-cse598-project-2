Download Link: https://assignmentchef.com/product/solved-cse598-project-2
<br>
The aim of this assignment is to make sure that you have read the text and the slides, and you have understood the software integration and workflow concepts in Workflow Foundation and in BPEL covered in the lectures and in the text. By the end of the project, you should have a good understanding of the concepts and have applied these concepts in developing operational software in Workflow Foundation. Both parts of the project are individual work. No collaboration is allowed. All students must submit independently developed applications. You cannot repeat the examples given in the book or lecture slides. You can follow the examples, but significant changes must be made.

<h1>Part 0     Practice Exercises (No submission required)</h1>

<ol>

 <li>Reading: Textbook chapters 7 and 8.</li>

 <li>Practice exercises: Questions at the end of Chapters 7 and 8.</li>

 <li>Follow the lectures 2-2 and 2-3 and the text chapter 7 to implement the Image Verifier service using workflow.</li>

 <li>Write a Web site application to consume the Image Verifier service.</li>

 <li>Implement a new workflow service based on the Image Verifier service.</li>

 <li>Download the Mortgage example and test the mortgage example.</li>

 <li>Explore the ASU Repository at: neptune.fulton.ad.asu.edu/WSRepository/repository.html</li>

 <li>Follow the lectures 2-4 through 2-6, the text chapter 8, and the BPEL tutorials in the assignment folder to implement a BPEL process.</li>

 <li>Write a client to consume the BPEL service.</li>

</ol>




Note: Workflow Foundation module may not be included in your Visual Studio 2017. In this case, you cannot create a new Workflow Foundation project. However, you can use your Visual Studio to open a Workflow Foundation. Then, Visual Studio will add Workflow Foundation module automatically.

<strong> </strong>




<h1>Assignment 3 Workflow Composition Project (Submission Required)</h1>

Due: February 22, 2020 by 11:59pm, plus a one-day grace period

In this part of the project, you will develop a Web service and a sensible application based on your own ideas. You <strong>cannot</strong> use the number guessing game (application and it services) that you used in assignment 1 in this assignment. You cannot use the same example found in the lecture slides. For the application, you can use any type of human interface: console, Windows Forms, ASP .Net website, HTML5, or MVC1/2. In the application, you must access the service that you develop in this project, and a service in the ASU Service Repository or one that you discovered from public repository, as shown in Figure 1.

<strong>Figure 1.</strong> Workflow-based application

You must use the <strong>Workflow Foundation</strong> to develop <strong>both</strong> the application and the Web service. You must also use at least one <strong>CodeActivity </strong>in one of the workflows (in the application workflow or in the Web service workflow). The application must combine at least the two services to deliver the integrated functionality. If needed, you can use more services and other components. For all services, you can choose to use either SOAP or RESTful services. The assignment is broken down into the following tasks.

<ol>

 <li>Use Workflow Foundation and flowcharts to develop a service that provides a sensible function to be used in your application. [10]</li>

 <li>Use Workflow Foundation to develop a sensible application using at least two services (or service operations). One service is developed in question 1 of this assignment. The other service is a remote service from a service repository, such as those in the ASU Service Repository. For the human user interface, you can use any type of interface. Your service will be hosted on the localhost / IIS Express.</li>

</ol>

[20]

<ol start="3">

 <li>Develop a sensible CodeActivity within the workflow application (from question 2). [10]</li>

 <li>User Manual: You must write a mini user manual in an html web page. The main components include: (1) Introduction to the application and the Web service that you have developed. (2) A description of the interface. (3) A diagram illustrating the application logic, workflow, and the code activity that you have implemented. (4) Testing instruction (How the TA can test your application and services) and at least two test cases (inputs and outputs) and screenshots you used to test your software. [10] <strong>Assignment 3 Canvas Submission: </strong></li>

</ol>

Zip all the following items into a single file folder for submission.

<ol>

 <li>The Visual Studio Solution folders with all the files, developed in questions 1, 2 and 3.</li>

 <li>The user manual in question 4.</li>

</ol>







<h1>Assignment 4 BPEL Composition and Integration (Submission Required)</h1>

Due: February 29, 2020 by 11:59pm, plus a one-day grace period

In this part of the project, you will develop a BPEL process and its WSDL interface for a similar project that you developed in assignment 3 of the project. The architecture is shown in Figure 2.

<strong>Figure 2.</strong> BPEL application

In this assignment, you can take one of the two options:

<ul>

 <li>You can also directly use an XML editor to write the BPEL process and the part of the WSDL required in this assignment. You do not need to create the operational executable software.</li>

 <li>You can use Oracle SOA Suite and JDeveloper (or Eclipse BPEL Designer) to create the process in XML and to generate the WSDL file.</li>

</ul>

Note: Oracle SOA Suite and JDeveloper are large enterprise software packages. It may take significant effort to install and to learn using it. It may take significantly longer time to take option (2). You take this option if you have intrinsic motivation for learning BPEL and Oracle SOA Suite programming.

The project is broken down into the following tasks.

<ol>

 <li>Use BPEL process (in XML language) to model the application that you developed in Part 1. You will consider the application in assignment 3 as the BPEL process that offers a WSDL service. You will write a simple client to call this BPEL-based service. In this question, you will define the complete BPEL process in XML, including partnerLink to all the Web services that you use, variables, receivereply for input and output, and the workflow that performs the application’s function. [30]</li>

 <li>Provide the WSDL file for your BPEL process. You do not have to provide the complete WSDL file. You just need to provide the roles and the port types to the <strong>client</strong> and to the <strong>two services</strong> that the process uses. [15]</li>

 <li>Your BPEL process must access at least two Web services, one in synchronous mode and one in asynchronous mode.        [5]</li>

</ol>

Note, you do not need to provide the operational software in this assignment. However, the process, the WSDL interfaces must be complete and correct, as we discussed in the lecture and in the test. The main purpose is to exercise the BPEL-based workflow concepts and the partners’ definitions.




<strong>Assignment 4 Canvas submission: </strong>

Zip all the following items into a single file folder for submission.

<ol>

 <li>The BPEL process in XML file.</li>

</ol>




<ol start="2">

 <li>The WSDL file for your BPEL process.</li>

 <li>WSDL files of the two Web services.</li>

</ol>