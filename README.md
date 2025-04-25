# cs2102-project-1-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs2102-your-company-apasaja-pte-ltd-has-been-commissioned-to-design-and-implement-a-database-application-to-record-information-about-car-rental-operation-for-the-pinjamobil-pte-ltd-the-applicatio/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128030&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2102 Project 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (4 votes)    </div>
    </div>
Your company, Apasaja Pte Ltd, has been commissioned to design and implement a database application to record information about car rental operation for the PinjaMobil Pte Ltd. The application stores and manages historical information about the customers and cars.

The application also stores and manages information about the cars. A specific car is identified by their license plate with the color of the car recorded. The current scheme for license plate starts with letter S followed by two letters, four digits, and the final checksum letter (see: Wikipedia). The brand and the model of each car are also recorded, which we call as the make of the car.

The application also tracks all passenger information of a car that are being rented. If a car is not currently being rented, there should be no passenger. For simplicity, the passenger will ride for the entire duration of the rented car. So if a car is being rented in the interval [s, e], then any passenger of this car will ride in the car for the entire interval [s, e].

References

Page 2

1. (3 points) Creating and Populating Tables with Constraints

(a) (3 points) DDL

Write the SQL Data Definition Language (DDL) code, CREATE TABLE with integrity constraints, to create the necessary table(s) for storing the data required by the application. Ensure all necessary data can be accommodated, and avoid catering for unnecessary, inconsistent, or unnecessarily redundant data. Propagate updates to maintain referential integrity. Only propagate deletions where it make sense.

(b) (0 points) DML

Other random data can be found from Mockaroo. There is a car make in Mockaroo but it is closer to brand in our terminology. Although technically the model year matters for capacity, we will simplify the problem by ignoring this information.

Use this data to write SQL Data Manipulation Language (DML) code to populate the database.

Submission

• Canvas Submission: “Assignments &gt; Questions 1” (one file per project group)

• Files

– SQL DDL: schema.sql

Ensure that schema.sql can be executed on a fresh database.

– SQL DML: data.sql

Page 3
