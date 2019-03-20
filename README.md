# RISM IT department

## Table of Contents

## I. Data management
1. [Import](#import)  
    1.1. [ICCU](#iccu)  
    1.2. [BNF](#bnf)  
    1.3. [Sistina](#sistina)  
    1.4. [Spain](#spain)  
    1.5. [ÖNB](#oebn)  
    1.6. [Cambridge University Library](#cul)  
    1.7. [Fitzwilliam Museum](#fitzwilliam)  
2. [Maintenance](#maintenance)  
    2.1. [Migration](#migration)  
    2.2. [Data](#data)  
3. [Interfaces](#interfaces)  
    3.1. [Muscat API](#api)  
    3.2. [PDF catalogue outprint](#pdf)  
    3.3. [Sigla catalogue](#sigla)  
    3.4. [BSB export](#bsb)  
    3.5. [OPAC development](#opac)  
    3.6. [OPAC translations](#translation)  

## II. Muscat development
1. [Development](#muscat)  
    1.1. [Work model](#work)  
    1.2. [Validations](#validations)      
    1.4. [Thesaurus](#thesaurus)  
    1.5. [Issues](#issues)  
    1.6. [Prints](#prints)  
2. Quality assurance  
    2.1. [Rspec](#rspec)  
    2.2. Checklists  

## III. Internet services and infrastructure
1. Internet services  
    1.1. [Mailserver](#mailserver)  
    1.2. [Webserver](#webserver)  
2. [Sysadmin](#sysadmin)  
    4.3. [PC clients and infrastructure](#clients)  
    4.4. [Monitoring](#clients)  

## IV. Other
1. [Other](#other)    
    1.1. [Hackathon](#hack)  
    1.2. [RISM data service booklet](#booklet)  
    1.3. [Early motet](#motet)  
    1.4. [Canto: Gesangsschulen](#canto)
    1.5. [Workflow](#workflow)
&nbsp;  

## 1. Muscat Development <a name="muscat"></a>
### 1. Work model (2018)  <a name="work"></a>
Status: 30%  
Should contain linkage to catalogue, standard_term; also including musical incipit, uri

### 2. Validations  <a name="validations"></a>
### 3. Rspec  <a name="rspec"></a>
### 4. Thesausus (2019)  <a name="thesaurus"></a>
Status: 0%
### 5. Issues   <a name="issues"></a>
### 6. Prints   <a name="prints"></a>
- [ ] There should be an improved search for holdings  
&nbsp;  

## 2. Import  <a name="import"></a>
https://github.com/rism-international/import

### 1. ICCU (2018) <a name="iccu"></a>  
https://github.com/rism-international/iccu  

Status | Size |  Testenv 
--- | --- | --- |
80% | 217.699 | iccu.rism.info | 

<sub>[2018-07-18]</sub>   

### 2. BNF (2018) <a name="bnf"></a>
Status: 60%  

### 3. Sistina <a name="sistina"></a>
Status: 80%
https://github.com/rism-international/sistina

https://sistina.rism.info

<sub>[2018-07-18]</sub>  

### 4. Spain <a name="spain"></a>
ca. 3.000 records, Status: 10%
https://github.com/rism-international/import/tree/master/Spain/input


### 5. ÖNB <a name="oebn"></a>
Status: 5%  
Excel sheet with about 15.000 names, 60% linkage to GND  
- [ ] create repository with data  
- [ ] data analysis  
<sub>[2018-07-18]</sub>  
### 6. Cambridge University Library <a name="cul"></a>

### 7. Fitzwilliam Museum <a name="fitzwilliam"></a>
&nbsp;  

## 3. Maintenance   <a name="maintenance"></a>

### 1. Migration <a name="migration"></a>
Fix some A/I issues from old migration, see https://github.com/rism-international/a1  
<sub>[2018-07-18]</sub>   

### 2. Data <a name="data"></a>
&nbsp;  

## 4. Sysadmin   <a name="sysadmin"></a>
### 1. Mailserver <a name="mailserver"></a>
Issue concerning long running mails: all plugins should be deactivated, also there should be a test concerning DNS.  

<sub>[2018-07-18]</sub>   

### 2. Webserver <a name="webserver"></a>
- [ ] Write to Digitale Akademie concerning running old instances

### 3. PC clients and infrastructure <a name="clients"></a>
Rollout of Ubuntu 18.04 ca. **2018-09-01**  
&nbsp;  

### 4. Monitoring  <a name="clients"></a>  
https://github.com/rism-international/monitor  

Running monitors at zeus.rism.info monitor and mail.rism.info monitor.  
<sub>[2018-07-19]</sub> 

https://github.com/rism-international/monitoring

## 5. Interfaces  <a name="interfaces"></a>
### 1. Muscat API <a name="api"></a>
There should be a Restful API from Muscat with Rails 5.1, using serializers, with marc_source as json.

### 2. PDF catalogue outprint <a name="pdf"></a>
-  [ ] Catalogue of A-Sm about 2018-08-01  
Make all-included dockerfile

### 3. Sigla catalogue <a name="sigla"></a>
Updated at 20180710  

### 4. BSB export <a name="bsb"></a>
Last update 2018-06-18
- [ ] next on **2018-07-20**

### 5. OPAC development <a name="opac"></a>
Latest release on 2018-07-16

### 6. OPAC translations <a name="translation"></a>
- [ ] data update on 2018-07-19  
&nbsp;  

## 6. Other  <a name="other"></a>
### 1. Hackathon on **2018-10-10**  <a name="hack"></a>
http://www.rism.info/en/home/newsdetails/article/2/rism-at-the-coding-da-vinci-2018-hackathon.html
### 2. RISM data service booklet <a name="booklet"></a>
- [ ] There should be an 2018/2019 update   
https://github.com/rism-international/data-service-booklet  
<sub>[2018-07-18]</sub>   
### 3. Early motet <a name="motet"></a>
### 4. Cantus project: Gesangschulen <a name="canto"></a>  

see https://canto.rism.info

https://github.com/rism-international/canto

### 5. Workflow 

- this file
- https://github.com/rism-international/tasks
- https://github.com/rism-international/tasks/projects
- https://github.com/rism-international
- sessions of the zentralredaktion and the protokols on x/Office\ Dokumente/Protokolle/
