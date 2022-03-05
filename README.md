Glossary
========

The EMREX glossary is meant as a non technical reference for readers of the documentation. Since many parts of EMREX is fairly technical, there is a need to explain the terminology in a non-technical fashion so that the documentation can be understood by others than technical staff. The plan is to have a completed glossary by the end of the project, covering all technical terminology that might be unclear to the reader.

External resources
------------------

 * [National Vocabulary of Education, OKSA (Finland)](https://confluence.csc.fi/download/attachments/8688189/Opetus_ja_koulutussanasto_20150803.pdf?version=1&modificationDate=1438756789198&api=v2)
 * [Nordic glossary (for information only - do not make any changes!)](https://drive.google.com/open?id=1cgGaihsj0S4l_F75Xu9qBQBmDlxHC5pva8Q3KUvRMDg&authuser=0)
 * [Spåkrådet nordisk termbase](http://nordterm.iterm.dk/portal/)
 
Defined terminology in EMREX
----------------------------

EMREX term | Type | Definition
-----------|------|-----------
EMREX Network | Technical | A network of countries and institutions that can share results
EMC | Technical | EMREX Client - A library of helpful methods to help countries joining the network; countries can use methods in this library to onnect to EMREG, validate ELMO and signatures, create requests to EMP and validate the student EMREX Client | Technical | A client in the network is an application that fetches results for a student. This application is typically part of an institutions student web sites.
EMP | Techncal | EMREX Contact Point - This is the clients access point to students results. This can either be a national application that has access to all of the country's data, or an institutinal contact point which provides data only for that institution.
EMREG | Technical | Registry of EMP's that participate in the EMREX network. Part of the EWP (Erasmus Without Paper) registry.
Public Key | Technical | The public part of the SSH key pair. See https://en.wikipedia.org/wiki/Key_(cryptography)
Private Key | Technical | The private part of the SSH key pair. See https://en.wikipedia.org/wiki/Key_(cryptography)
Certificate | Technical | An electronic document used to prove the ownership of a public key
ELMO | Format | The XML format EMREX uses to exchange results
Learner | Format | The student that the result is being fetched for
Issuer | Format | The institution that has issued the results
Schac | Format | Code that identifies the institution
Learning Opportunity | Format | A chance to participate in education or training.
Learning Opportunity Specification | Format | An abstract description of a learning opportunity, consisting of information that will be consistent across multiple instances of the learning opportunity (identifiers, credits, URLs, descriptions...)
Learning Opportunity Instance | Format | A single occurrence of a learning opportunity. Unlike a Learning Opportunity Specification, a Learning Opportunity Instance is not abstract, may be bound to particular dates or locations, and may be applied for or participated in by learners (time, result...)
Qualification | Format | A formal qualification from a study, such as degree
Credit | Format | A way of describing the work load of a study, see also ECTS
ECTS | Format | European Credit Transfer and Accumulation System ([ECTS explained](http://ec.europa.eu/education/resources/european-credit-transfer-accumulation-system_en))
Subject Area | Format | Area of study, see also ISCED
Isced | Format | The International Standard Classification of Education ([Wikipedia](https://en.wikipedia.org/wiki/International_Standard_Classification_of_Education))
Transcript of Records | Format | An official list of all the courses that you have completed, including information about the number of credits and the grades you have got
Grade distribution | Format | Distribution of grades for a given course, showing how many achieved what grade. Can be helpful to determine whether a certain grade was hard to achieve
Shortened grading table | Format | Shortened grading table contains threes numbers - number of grades lower, number of grades equal and number of grades higher than the grade obtained by a student. It is like grade distribution, but with only three values, making it easier to analyze as compared to a grade distribution with a fine grained grading scale.