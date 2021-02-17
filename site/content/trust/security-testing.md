---
slug: "security-testing"
date: '2017-12-07T15:14:32+08:00'
type: ml_layout
layout: ml_layout
---

<section class="">
  <div class="padding50 ml-pure-white-background">
    <div class="row  ">
      <div class="col-lg-3 col-md-12 col-sm-12 col-xs-12 div_sticky_privacy">
       <p> <h4><b>Table of Contents</b></h4></p>
        <p><b><a href="#ongoing-security-assurance">Ongoing security assurance</a></b></p>  
        <p><b><a href="#measuring-the-right-things">Measuring the right things</a></b></p>
      </div>
      <div class="col-lg-9 col-md-12 col-sm-12 col-xs-12 " id="policy-covers" class="privacy-content">
        <h2><b>Our Approach to Security Testing</b></h2>
        <p>
        Our security testing approach is built around the concept of 'continuous assurance' – that complements a point-in-time penetration test approach.
        </p>
        <p>
        Bugs are an unavoidable part of the development process - the question is not whether we have bugs, the question is how effectively and quickly we find them and address them. This doesn’t mean we like bugs or aren’t constantly innovating ways to reduce their frequency and severity, but when it comes to software bugs, denial is not an effective approach.
        </p>
        <p>
          We aim to increase the cost of finding and exploiting vulnerabilities in our products and services - through rapidly identifying and resolving issues we aim to increase the economic cost of finding security bugs. By increasing the cost of exploiting a vulnerability – by making it take longer, require more knowledge and more resources from the bad guys – we reduce their return on investment. If we can reduce it far enough, it becomes prohibitive or not attractive to them.
      </p>
      <p>
        We support and use industry standards - standardisation in our terminology and approach helps us ensure we’re covering everything, and helps customers understand how to understand what we do. For example, common ratings of vulnerabilities using the <a href="https://nvd.nist.gov/vuln-metrics/cvss" target="_blank" class="ml_custom_link" id="ongoing-security-assurance">Common Vulnerability Scoring System (CVSS)</a> ensures clarity for severity of a particular vulnerability between us and our customers.
        </p>
      <div><br>
      <h3><b>Ongoing security assurance</b></h3>
      <p><h5><b>Penetration testing</b></h5></p>
      <p>We do use specialist security consulting firms to complete penetration tests on high risk products and infrastructure on a regular basis.
      </p>
      <p>
      Testing will focus on a particular threat scenario, such as assuming a compromised instance exists, and testing lateral movement from that starting point.
      </p>
      <p>
      Vulnerabilities we seek to be identified include common types captured in the<a href="https://www.owasp.org/index.php/Main_Page" target="_blank" class="ml_custom_link"> Open Web Application Security Project (OWASP)</a> and <a href="http://www.webappsec.org/" target="_blank" class="ml_custom_link">Web Application Security Consortium (WASC)</a> threat lists. They include:
      </p><p>
          <ul>
              <li>Cross Instance Data Leakage/Access</li>
              <li>Remote Code Execution (RCE)</li>
              <li>Server-Side Request Forgery (SSRF) </li>
              <li>Cross-site Scripting (XSS)</li>
              <li>Cross-site Request Forgery (CSRF)</li>
              <li>SQL Injection (SQLi)</li>
              <li>XML External Entity Attacks (XXE)</li>
              <li>Access Control Vulnerabilities (Insecure Direct Object Reference issues, etc) </li>
              <li>Path/Directory Traversal Issues </li>
          </ul>
          </p>
      </div>
       <div>
          <p><h5><b>Vulnerability reporting</b></h5></p>
          <p>
             When a vulnerability is identified by one of our users during the course of their standard use of the product (as opposed to being identified through a specific attempt to test the system, which we require to occur via our bug bounty program), we welcome notification via our Support Team. We respond promptly to any vulnerabilities submitted and will keep inquiring parties up to date as we investigate and respond to the issue.
          </p><span id="measuring-the-right-things"></span>
          <p>
              Before disclosing an issue publicly we ask that researchers first request permission from us. SmartWinnr will process requests for public disclosure on a per report basis. Public disclosure requests will only be considered once the reported vulnerability is fixed.
          </p> 
      </div>
      <br>
      <div>
          <h3><b>Measuring the right things</b></h3>
          <p>
            When categorizing bugs, we use the <a href="https://www.first.org/cvss/specification-document" target="_blank" class="ml_custom_link">Common Vulnerability Scoring System (CVSS version 3),</a> which helps communicate the severity of vulnerabilities to our customers. We attempt to meet the following timeframes for fixing security issues:
          </p>
          <ul>
          <li>Critical severity bugs (CVSS v2 score >= 8, CVSS v3 score >= 9) should be fixed in product within 4 weeks of being reported.</li>
           <li>High severity bugs (CVSS v2 score >= 6, CVSS v3 score >= 7) should be fixed in product within 6 weeks of being reported.</li>
            <li>Medium severity bugs (CVSS v2 score >= 3, CVSS v3 score >= 4) should be fixed in product within 8 weeks of being reported.
          </li>
          </ul>
          <p>
          These timeframes are re-evaluated on an annual basis and adjusted as needed based on the changing threat environment.
          </p>
      </div>
   </div>
    </div>
  </div>
</section>
