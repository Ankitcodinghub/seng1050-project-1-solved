# seng1050-project-1-solved
**TO GET THIS SOLUTION VISIT:** [SENG1050 Project 1 Solved](https://www.ankitcodinghub.com/product/seng1050-data-structures-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124649&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SENG1050 Project 1&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
<h1>OVERVIEW</h1>
<ul>
<li>For this project, you will calculate the different statistics about the items to be delivered through courier company. First you will start with raw data and use combine knowledge of Hash Table and Tree structure to arrange large chunk of data in Hash Table array. Each array element holds the pointer to the root element of the Tree structure.</li>
</ul>
<h1>OBJECTIVES</h1>
<ul>
<li>Create and use Hash tables.</li>
<li>Create and use Tree Data Structures.</li>
<li>Use the search and traversal mechanism in Tree data structure.</li>
<li>Use common algorithms to enhance software development.</li>
<li>Use best practices to effectively produce quality software.</li>
</ul>
<h1>EVALUATION</h1>
<ul>
<li>The evaluation of this assignment will be done as detailed in the Marking lecture in Week 2 of the C course.</li>
</ul>
<h1>PREPARATION</h1>
<ul>
<li>Understand how to implement hash tables.</li>
<li>Understand how to implement tree structure.</li>
</ul>
<h1>BACKGROUND</h1>
Consider you work for a large courier company, and they wanted to develop inventory management system. Every item that arrived to the courier company for distribution are entered into their system and it generates huge text file. We will review what data are stored and how data are stored in text files. You must read items data from file and offer user to display various output based on their search.

<h1>REQUIREMENTS</h1>
&nbsp;

<ul>
<li>Your data should contain many things but for simplicity you will have destination, weight and valuation ($$) for the parcels to be dispatched. So, each parcel can have three pieces of information linked to it, destination, weight, valuation. Destination is name of the country where parcel will be dispatched.</li>
<li>As a starting point for this application, you will load large amount of data in application memory to perform further action.</li>
<li>You will read the couriers.txt file and load the three pieces of information from the file.</li>
<li>txt would have destination, weight and valuation. The format of data stored in file would be <strong>destination, weight, value</strong>. Destination would be country name max 20 character and weight is the gross weight of parcel in numbers and valuation in float.</li>
</ul>
Gross weight is typically in the range of 100 gms to 50000 gms. All weights are in grams.&nbsp; And valuation should be in the range of $10 to $2000.

<ul>
<li>You can create a file (couriers.txt) with destination, weight, value min 2000 records are OK.</li>
<li>You can assume that for given destination there shouldn’t be other parcels with same weight. In real world those parcels can be combined to make one larger parcel, but we will not do that. e. Canada, 500 and Japan, 500 is correct but there is no duplicate weight for same destination.</li>
<li>Allocate memory for destination dynamically.</li>
<li>After reading data from files, you will load them in HashTable.</li>
<li>You will create a Hash table of size 127. This will make sure that good distributions will happened across buckets. Few buckets will be empty, for now that is fine.</li>
<li>Each index of the HashTable will hold the root node of the Tree structure.</li>
<li>You will use the Country name as a key to generate the Hash Value to store the data to specific Hash Index. <strong>I have also provided the list of the Country, please use countries from them only, these countries name generate the unique Hash Value so that you can avoid more than one country data to be part of same bucket</strong>. <strong>Please select at least 50 or more countries. </strong></li>
<li>You must use the “djb2 function” to generate the unique Hash Value of each record using the associated country name and then store those data into Balance AVL tree at specific bucket index.</li>
<li>Each node in AVL tree represents a parcel.</li>
<li>Each node in the AVL tree is placed using parcel’s weight.</li>
<li>It’s OK to use more than 2000 names but don’t have more than 5000.</li>
<li>After loading the data into application’s memory, you will present the following user menu to the user.</li>
<li>Please see the below user menu:
<ul>
<li>Enter country name and display all the parcels details: when user enters 1, application allow user to enter County name. Then display each parcel’s details.</li>
<li>Enter country and weight pair: This menu offers user to display all the parcel for given country whose weight is higher/lower than weight entered.</li>
<li>Display the total parcel load and valuation for the country: When user enters country name, display the cumulative parcel load and total valuation of all the parcels. &nbsp;o 4.&nbsp; Enter the country name and display cheapest and most expensive parcel’s details. &nbsp;o 5. Enter the country name and display lightest and heaviest parcel for the country.</li>
<li>Exit the application.</li>
</ul>
</li>
<li>Make the hash table 127 buckets in size.</li>
<li>Design your code so that you do not have to duplicate code unnecessarily.</li>
</ul>
This is very important.

<ul>
<li>Clean up all allocated memory before exiting.</li>
</ul>
&nbsp;

&nbsp;

<h1>OTHER REQUIREMENTS</h1>
<ul>
<li>The field containing the names must be dynamically allocated to an appropriate size.</li>
<li>Do not get any other user input except as indicated in these requirements.</li>
<li>Do not display output except as indicated in these requirements.</li>
<li>Do not clear the screen at any time in this program.</li>
<li>You must do error checking where necessary.
<ul>
<li>If you detect an error, you should display an appropriate error message and take appropriate action.</li>
<li>You can assume that all statements above that have the phrase “will be” in them will be true when testing is done.</li>
</ul>
</li>
<li>It must not use global variables.</li>
<li>It must not use goto.</li>
<li>Be aware that you still cannot use C++ strings in this assignment because malloc() does not support them.</li>
<li>You can assume that the country names will not be longer than 20 characters in length.</li>
<li>If you are working in group or solo, you must be able to explain the code. Also, code should work on your machine and your partner’s machine as well. This may require demoing your code in group.</li>
<li>The SET Coding Standards must be adhered to.</li>
</ul>
<h2>GIT REQUIREMENTS</h2>
<ul>
<li>For the group project, you can create your own repository and work in group with other members. So that both members should have access to repository and you can manage issues locally.</li>
<li>It is expected that both members would have a reasonable number of commits with meaningfully descriptive commit comments.</li>
</ul>
<h2>CHECKLIST REQUIREMENTS</h2>
<ul>
<li>Create a requirements checklist. This should contain the specific requirements from this assignment as well as any relevant requirements that have been covered in lecture or that are found in the SET Coding Standards or SET Submission Standards. Do it in whatever form you wish. Hand in your completed checklist in PDF form as checklist.pdf. Not having this checklist will result in a cap of 80 on your mark.</li>
</ul>
<h2>FILE NAMING REQUIREMENTS</h2>
<ul>
<li>You must call your source file project.cpp.</li>
<li>You must call your checklist checklist.pdf.</li>
<li>Sample data file name should be couries.txt file</li>
</ul>
&nbsp;

<h2>SUBMISSION REQUIREMENTS</h2>
<ul>
<li>Submit the files mentioned in the File Naming Requirements. Do not hand in any other files. Yes, please submit the sample data that you have used for this project.</li>
<li>Submit your files to the <em>Project</em> Submission Folder. Only one member needs to submit the file.</li>
<li>Once you have submitted your file, make sure that you’ve received the eConestoga email confirming your submission. Do not submit that e-mail (simply keep it for your own records until you get your mark).</li>
</ul>
