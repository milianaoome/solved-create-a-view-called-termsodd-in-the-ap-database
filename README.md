Download Link: https://assignmentchef.com/product/solved-create-a-view-called-terms_odd-in-the-ap-database
<br>
SQL questions.

use AP;/* Q1. (10 points)Create a view called Terms_odd in the AP database, which returns rows ofTerms table whose TermsID is an odd number and each row contains threecolumns: TID, Details, and DueDays, which are TermsID, TermsDescription,and TermsDueDays of Terms, respectively.Note that your Terms_odd must be able to include not only terms in thecurrent Terms table but also terms that are modified later.*//* Q2. (30 points)Write one DML statement to perform each of the following tasks:(a) Use Terms_odd to insert the following two new terms into Terms table:-The first new term Details is ‘Net due 100 days’ with DueDays of 100.-The second new term Details is ‘Net due 125 days’ with DueDays of 125.*//*(b) Use Terms_odd to change DueDays by increasing 15 days for terms whose current DueDays is larger than 90. If a term is changed, whose correspondingnumber in Details must also be changed together. For example, if DueDaysofa term is changed from 100 to 115, then, its Details ‘Net due 100 days’mustalso change to ‘Net due 115 days’. Hint: use REPLACE() of Chapter 8.*/