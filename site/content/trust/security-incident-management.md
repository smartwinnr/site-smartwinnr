---
slug: "security-incident-management"
date: '2017-12-07T15:14:32+08:00'
type: ml_layout
layout: ml_layout
---

<section class="">
  <div class="padding50 ml-pure-white-background">
    <div class="row  ">
      <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12 div_sticky_privacy">
        <p><h4><b>Table of Contents</b></h4></p>
        <p><b><a href="#our-approach-to-handling-security-incidents"> Our Approach to Handling Security Incidents</a></b></p>  
        <p><b><a href="#more-on-our-philosophy-and-approach">  More on our philosophy and approach</a></b></p>
        <p><b><a href="#several-avenues-to-detect-potential-incidents-quickly">  Several avenues to detect potential incidents quickly</a></b></p>
        <p><b><a href="#an-established-framework-for-managing-security-incidents"> An established framework for managing security incidents</a></b></p>
        <p><b><a href="#in-summary">  In summary</a></b></p> 
      </div>
       <div class="col-lg-8 col-md-12 col-sm-12 col-xs-12 " id="our-approach-to-handling-security-incidents" class="privacy-content" >
        <h2><b>Our Approach to Managing Security Incidents</b></h2>
        <p><h4><b>Our Approach to Handling Security Incidents</b></h4>
          </p>
          <p>SmartWinnr has a comprehensive set of security measures in place to ensure we protect customer information and offer the most reliable and secure services we can. However, we also recognize that security incidents can (and do) still happen, and so it's just as important to have effective methods for handling them should they arise.
        </p>
        <p>
        As a result, we have a clearly defined approach for responding to security incidents affecting our services or infrastructure. Our incident response approach includes comprehensive logging and monitoring of our products and infrastructure to ensure we quickly detect potential incidents, supported by carefully defined processes that ensure there is clarity in what we need to do at all stages of an incident. This is supported by a team of highly-qualified on-call incident managers who have significant experience in coordinating an effective response. We have structured our incident management approach on guidance from <a href="https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final" target="_blank" class="ml_custom_link">NIST 800-61 Computer Security Incident Handling Guide,</a> and we catalog our incidents according to the <a href="http://veriscommunity.net/" target="_blank" class="ml_custom_link" id="more-on-our-philosophy-and-approach">Verizon VERIS framework.</a>
        </p>
        <br>
          <p>
            <h4>
              <b>More on our philosophy and approach </b>
            </h4>
          </p>
          <p>
          We consider a security incident to be any instance where there is an existing or impending negative impact to the confidentiality, integrity or availability of our customers' data, SmartWinnr's data, or SmartWinnr's services.
          </p>
          <p >
          We're focussed on putting the best processes in place so that we handle security incidents in a way that is always aligned with the best interests of our customers and ensures they continue to have an outstanding experience using our products. To that end, we've developed an incident response process that is robust and incorporates several features discussed below.<span id="several-avenues-to-detect-potential-incidents-quickly"></span>
          </p>
          <br>
          <p>
            <h4>
              <b>Several avenues to detect potential incidents quickly </b>
            </h4>
          </p>
          <p >
          We have several monitoring mechanisms in place to detect failures or anomalies in our products and infrastructure that may be an indicator of a potential security incident. These systems alert us immediately if an activity is detected that requires further investigation. We have an aggregated log capture and analytics platform which collates logs in a single location, so our analysts can investigate quickly and thoroughly, and our Site Reliability Engineers monitor the platform to make sure it’s always available. We also create alerts in our security information and event application that notify our teams proactively.<span id="an-established-framework-for-managing-security-incidents"></span>
          </p><br>
            <p>
            <h4>
              <b>An established framework for managing security incidents</b>
            </h4>
          </p>
          <p>
          To ensure our incident response process is consistent, repeatable and efficient, we have a clearly defined internal framework that covers the steps we need to take at each phase of the incident response process. We have documented playbooks that are continually updated which define in detail the steps we need to take to effectively respond to different incident types. At a high level, our response framework covers:
          </p>
          <p>
          Incident detection and analysis – the steps we take following initial notifications we receive about a potential incident, including how we confirm whether a security incident has occurred (so that we minimize false positives), through to understanding the attack vectors, scope of compromise, and the impact to SmartWinnr and its customers.
          </p>
          <p>
          Incident severity categorization – Once we understand what's happened through appropriate analysis, we use this information to determine the severity of the incident. We designate one of four severity levels to an incident:
          </p>
          <div class="ml_div_contents_in_center">
            <table class="table-bordered table-striped ml-margin-bottom10">
                <thead >
                  <tr class="text-center">
                    <th class="padding5" colspan="2" class="text-center">Incident Severity Description</th>                   
                  </tr>
                </thead >
                  <thead class="">
                  <tr>
                    <th class="padding5">Severity</th>        
                    <th class="padding5">Description</th>                 
                  </tr>
                </thead>
                  <tbody class="">
                  <tr>
                    <td class="padding5">0</td>
                    <td class="padding5"> Crisis incident with maximum impact</td>                       
                  </tr>
                    <tr>
                    <td class="padding5">1</td>
                    <td class="padding5"> Critical incident with very high impact</td>                       
                  </tr>
                    <tr>
                    <td class="padding5">2</td>
                    <td class="padding5"> Major incident with significant impact</td>                       
                  </tr>
                    <tr>
                    <td class="padding5">3</td>
                    <td class="padding5"> Minor incident with low impact</td>                       
                  </tr>
                  </tbody>
            </table>
            </div>
            <p>
            We use a variety of indicators to determine the severity of an incident – these vary depending on the product involved but will include consideration of whether there is a total service outage (and the number of customers affected), whether core functionality is broken, and whether there has been any data loss.
            </p>
            <p>
            Containment, eradication and recovery – Considering the incident severity, we then determine and implement the steps necessary to contain the incident, eradicate the underlying causes and start our recovery processes to ensure we return to business-as-usual as quickly as possible. Naturally, the steps we take in this phase will vary significantly depending on the nature of the incident. Whenever it will benefit our customers (or as required by our legal or contractual obligations), SmartWinnr will also communicate with its customers about the incident and its potential impacts for them during this phase of the incident response process.
            </p>
            <p>
            Notification - We aim to notify any customer without undue delay if their data is involved in a confirmed incident or a breach. This might be light on detail at first, but we’ll provide every detail available, when it is available.
            </p>
            <p id="in-summary">
            A robust post-incident review process – After every incident is resolved, we look at what lessons we can learn from what happened that can inform the development of technical solutions, process improvements and the introduction of additional best practices so that we can continue to provide the best experience for our customers and make the job of malicious actors even harder next time.
            </p>
            <br>
            <p><h4><b>In summary</b></h4></p>
            <p>SmartWinnr employs a robust and comprehensive approach to handling security incidents, centered around the use of the same tools we make available to our customers. This enables us to respond to incidents with a high degree of consistency, predictability and effectiveness and minimize the potential for damage to our customers, our partners, and SmartWinnr itself.
</p>
      </div>
   </div>
    </div>
  </div>
</section>
