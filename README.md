# Introduction

This repository includes a set of Forms Builder sequence and workflow templates for use with CampusNexus CRM and CampusNexus Student. These templates are helpful examples to get you started creating form sequences and workflows. 



## How to use this repository

* Download the export files (xml) and import them into your Forms Builder designer. 

* Download the README.docx for each template for prerequisites and detailed instructions on how to use the templates.



## CampusNexus Student



### Enrollment Agreement

This template provides a form sequence and supporting workflow for an enrollment agreement to be submitted by an applicant. The sequence requires the following:



* A complete Applicant Record must exist in the CampusNexus Student database (any missing field, e.g., Grade level, could cause a failure in the workflow). In our example, we are using the “Pending Applicant” status.

* The applicant must have a Portal login to log into this authenticated sequence.  



The template includes the steps required to collect DocuSign signatures/initials from the applicant and from a staff member. 
Upon completion of the sequence, the student’s Applicant Record is converted to an Enrollment and the signed enrollment agreement (PDF) is added to the student’s document list in CampusNexus Student.



### Financial Aid Verification

This template provides a form sequence and supporting workflow for a financial aid verification form. The template simplifies a significant portion of a complete student self-service financial aid verification process as detailed in the document **Build Your Own Financial Aid Verification Process** (see Financial Aid Verification Process README STEP 2.docx).



### Online Application

This sequence is intended to be used by students who enroll into a program at your institution. This is an authenticated sequence that requires the user to have a Portal user name and password. 



The application process involves collection of demographic information for the student, obtaining previous education information, collection of documents and necessary signatures using **DocuSign**, and managing other tasks and activities to enroll the student in a program. The information is used to create the applicant record for the student. 



### Request for Information

This sequence is intended to be used by prospective students who are interested in attending your institution. This is an anonymous sequence that does not require the user to be authenticated.  When the user successfully completes the sequence, a new prospect inquiry record and a systudent record are created in the CampusNexus Student database.  



The campus configuration determines whether duplicate checks are executed. Depending on the campus configuration, if a systudent record exists and a person with the same first and last name completes the RFI form, the status of the original systudent record may be updated to a new status (.e.g., New Lead > Active).



## CampusNexus CRM

-- coming soon --



