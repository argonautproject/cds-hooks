{% include publish-box.html %}

{:.no_toc}

<!-- TOC  the css styling for this is \pages\assets\css\project.css under 'markdown-toc'-->

* Do not remove this line (it will not be displayed)
{:toc}

<!-- end TOC -->

source pages/\_include/{{page.md_filename}}.md  file

## {{ site.data.fhir.igName }} Implementation Guide

The Argonaut CDS Hooks implementation guide is a supplement to the [CDS Hooks] initiative and documents:

 - patient-view hook
 - Security and Authorization
 - ..

#### Use Case

This specification is focused primarly on the patient-view hook.

**Purpose** Inform an external CDS service that a user just opened a new patient record and is viewing on the summary screen of "face sheet", and solicit feedback about this patient. 

[CDS Hooks]: http://cds-hooks.org/

### Jekyll Site Variables

igName : Title of the implementation Guide -  {% raw %} {{ site.data.fhir.igName }} {% endraw %}= {{site.data.fhir.igName}}

path : path to the main FHIR specification -  {% raw %} {{ site.data.fhir.path }} {% endraw %}= {{site.data.fhir.path}}

canonical : canonical path to this specification -  {% raw %} {{ site.data.fhir.canonical }} {% endraw %} = {{ site.data.fhir.canonical }}

errorCount : number of errors in the build file (not including HTML validation errors) -  {% raw %} {{ site.data.fhir.errorCount }} {% endraw %} = {{ site.data.fhir.errorCount }}

version : version of FHIR -  {% raw %} {{ site.data.fhir.version }} {% endraw %} = {{ site.data.fhir.version }}

revision : revision of FHIR -  {% raw %} {{ site.data.fhir.revision }} {% endraw %} = {{ site.data.fhir.revision }}

versionFull : version-revision -  {% raw %} {{ site.data.fhir.versionFull }} {% endraw %} = {{ site.data.fhir.versionFull }}

totalFiles : total number of files found by the build -  {% raw %} {{ site.data.fhir.totalFiles }} {% endraw %} = {{ site.data.fhir.totalFiles }}

processedFiles : number of files genrated by the build -  {% raw %} {{ site.data.fhir.processedFiles }} {% endraw %} = {{ site.data.fhir.processedFiles }}

genDate : date of generation (so date stamps in the pages can match those in the conformance resources) -  {% raw %} {{ site.data.fhir.genDate }} {% endraw %} = {{ site.data.fhir.genDate }}


### Introduction

blah blah blah

### More Stuff

#### And More Stuff
