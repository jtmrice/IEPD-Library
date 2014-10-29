---
title: IEPD Repository
layout: "default"
---
# IEPD Repository

NIEM is about the data and its structure as it moves between systems—i.e. "data in motion." The NIEM model is a data layer that provides building blocks, such as "person name," "birth date," or "activity" that define exchange message content often referred to as message payload. 

To use NIEM, you normally build an Information Exchange Package Documentation (IEPD). An IEPD defines a recurring message in XML and is built to satisfy information exchange business requirements. A developer builds an IEPD by incorporating the necessary NIEM core and domain model content. The developer may also extend that content as needed to account for information requirements that are not yet addressed in NIEM. The IEPD will ultimately define XML instance documents that will contain the information to be exchanged. Extended and new content developed in IEPD extension schema documents should be considered for future model updates. In turn, domain and core model updates will be harmonized and integrated into future NIEM releases. In this way, NIEM evolves with new and changing needs.

An IEPD is a combination of both business and technical information for an information exchange.

From a technical perspective, an IEPD is a set of XML schema documents that define instance XML documents which, in turn, will tag and carry the data and information to be exchanged. For example, when you want to exchange "person" data and its related attributes, you will leverage (essentially reuse from a NIEM release) XML schema components that define the “person” related tags and structures.

From the business perspective, an IEPD provides documentation such as business scenarios and other aspects of the business requirements for the exchange, including a catalog of its content, a change log, a conformance assertion, etc. In addition, reusing existing IEPDs that meet or can be easily adapted for similar business requirements is encouraged, and can save time and money! 

In an era when return on investment has never been more important to government services, NIEM enables organizations to exchange information across all levels of government in a manner that is both effective and efficient.

Be sure to check out the **[NIEM Cost Model] (https://niem.gov/aboutniem/roadmap/Pages/cost-model.aspx)**, which allows users to quantify the associated costs of adopting NIEM.

NOTE: Information exchange relies on many capabilities—NIEM provides a solid starting point. You rarely ever use NIEM by itself. Depending on business requirements, there are other aspects of information exchange implementations that are required, including access controls, policy automation, transmission protocol, and others. This is why the **[NIEM Implementation Cookbook] (https://github.com/NIEM/Implementation-Cookbook)** was created!


[the clickable text](http://github.com/)

<!-- icon menu -->
<div class="col-md-4">
  <div class="media">
    <div class="pull-left">
      <span class="fa-stack fa-2x">
        <i class="fa fa-square fa-stack-2x text-primary" style="color:#65c4cb; border-color:#3c8185"></i>
        <i class="fa fa-file-code-o fa-stack-1x" style="color:#005170"></i>
      </span>
    </div>
    <div class="media-body">
      <h4 class="media-heading" style="margin-top:15px"><a href="https://github.com/jtmrice/Template-IEPD/">Template IEPD</a></h4>
    </div>
  </div>
  <div class="media">
    <div class="pull-left">
      <span class="fa-stack fa-2x">
        <i class="fa fa-square fa-stack-2x text-primary" style="color:#65c4cb; border-color:#3c8185"></i>
        <i class="fa fa-gavel fa-stack-1x" style="color:#005170"></i>
      </span>
    </div>
    <div class="media-body">
      <h4 class="media-heading" style="margin-top:15px"><a href="#">Conformance Validation</a></h4>
    </div>
  </div>
</div>
<div class="col-md-4">
  <div class="media">
    <div class="pull-left">
      <span class="fa-stack fa-2x">
        <i class="fa fa-square fa-stack-2x text-primary" style="color:#65c4cb; border-color:#3c8185"></i>
        <i class="fa fa-file-text-o fa-stack-1x" style="color:#005170"></i>
      </span>
    </div>
    <div class="media-body">
      <h4 class="media-heading" style="margin-top:15px"><a href="#">Search for IEPDs</a></h4>
    </div>
  </div>
</div>
