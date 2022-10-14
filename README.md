# Chicago_Crimes
Data Science Project Predicting Crimes (from an alternate perspective)

Chicago Crime Recommendation System
(From an Alternate Perspective)

Jarrod Johnson
University of Houston

Data Science II (COSC4337)
March 5, 2021


Incremental project background work is viewable within git by accessing the .ipynb files in order. 

Incremental project presentation work is viewable within git by accessing the .pdf files in order (click "more pages" at bottom to see full doc), with project3 .pdf being a final summary presentation to AI Alphabet Inc. 




Project Novel Idea

AI Alphabet Inc. is planning to become the world's first industrial supervillain. After recently accessing the power of data science and statistical predictions, they plan to use the Chicago crimes dataset to realize their vision of supervillainy. Within this dataset they’ve identified a very special feature column; One that can hopefully empower their evil AI hench-bot (powered by Jupyter Notebook) to reveal the best course of action for them to commit crimes in Chicago and avoid immediate capture. The feature column is titled “Arrest” and is conveniently binary. This column reflects true or false for whether an arrest has been made sometime (1 or more week) after a crime occurred. Data/business understanding This information will hopefully allow them to predict different combinations of which, where, and possibly when different crimes happen that do not have arrests related to them. They would like to arrange the data so they can have the ability to: Choose a crime type given a place (and time), or Choose a place (and time) given a crime type, that will give them the best opportunity to escape arrest, (at least immediately (Arrest = 0/F)).



Data description 

Source Overview Column description Data Types Source Data Provided by: Chicago Police Department Contact Dataset Owner https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2 Licensing and Attribution License See Terms of Use Source Link https://portal.chicagopolice.org/portal/page/portal/ClearPath

Overview 

Date Created September 30, 2011 Data Provided by Chicago Police Department Dataset Owner Cocadmin Rows 7.28M Columns 22 Each row is a Reported Crime

This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. Should you have questions about this dataset, you may contact the Research & Development Division of the Chicago Police Department at PSITAdministration@ChicagoPolice.org. 

Disclaimer: 

These crimes may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the Chicago Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The Chicago Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The Chicago Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of Chicago or Chicago Police Department web page. The user specifically acknowledges that the Chicago Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. The unauthorized use of the words "Chicago Police Department," "Chicago Police," or any colorable imitation of these words or the unauthorized use of the Chicago Police Department logo is unlawful. This web page does not, in any way, authorize such use. Data are updated daily. 

To access a list of Chicago Police Department - Illinois Uniform Crime Reporting (IUCR) codes, go to http://data.cityofchicago.org/Public-Safety/Chicago-Police-Department-Illinois-Uniform-Crime-R/c7ck-438e





