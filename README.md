<h2 style="color: blue;"><u>Frequently Asked Questions:</u> How to use MapmyIndia Developer Console</h2>
<br>

**Q1.  Difference b/w Projects Reports & Account Reports Section?**

**Ans:** Reports under Projects Section shows us the Report (commonly known as Timeline Report) of that Particular Project & Reports under Account Reports Section shows us the Report of the whole account as the account may have more than one project.

**Q2.  What is a Latency Report?**

**Ans:**  This is the report which shows the average response time for the various APIs you have used in the said duration. This is the part of the performance report.

**Q3.  What is a Status Code Report?**

**Ans:**  This is the report which shows the status codes of the APIs you have used corresponding to the Request count of the APIs. This is the part of the performance report.

**Q4.  What are the types of status code we have?**

**Ans:**

<p>

Status Code | Meaning
---- | ----
200 | success
204 | no matching result
400 | bad request
401 | unauthorised; access denied
403 | services for this key has been suspended due to hourly/daily transaction limit
500 | something went wrong; internal server error
503 | services unavailable; maintenance break
412 | precondition failed; expected combination not provided
499 | client redacted request in middle of processing
409 | conflict; unexpected state
417 | expectation failed
404 | resource not found
504 | gateway timeout
301 | moved permanently; redirection; mostly used in http calls
304 | not modified; similar in all terms & purposes to 200
408 | request timeout
502 | Bad gateway

</p>
<br>

**Q5.  What does API Groups Means?**

**Ans:**  We have distributed our APIs in Groups just like as mentioned below:

<p>

API Groups | API Name
---- | ----
Directions | Route Adv API w/o traffic, Route eta API w/ traffic, Route traffic API w/ traffic, Distance Matrix API w/o traffic, Distance Matrix ETA API w/ traffic, Distance Matrix Traffic API w/ traffic, Route Optimization API, Snap to road API, POI Along the route
Search | Autosuggest, Text Search, Reverse Geocode, Geocoding, Nearby, eLOC API, Address Standardization API
Maps | Raster SDK, Vector SDK
GeoAnalytics | State, District, SubDistrict, Pincode, Locality, SubLocality, SubSubLocaity, Road

<p>
<br>

**Q6.  Can I monitor project wise utilization?**

**Ans:**  Yes, you can monitor project wise utilization by using the project name filter.

**Q7.  What is the difference between Used Hits and Request Count in a downloaded report?**

**Ans:**  Used Hits are the hits which are based on the transaction strategy of the particular API whereas Request Count are the counts that how many times a particular API has been hit through the server. For example: The transaction strategy of our Directions APIs are basically based on how many coordinates you are passing through the request.

**Q8.  If I need multiple sets of keys for different Projects, how can I do so?**

**Ans:**  Currently, You can have a single set of keys against a project whereas you can have multiple projects in your account. For doing so you have to place the request to the MapmyIndia API support team at [apisupport@mapmyindia.com](mailto:apisupport@mapmyindia.com) and we are also constantly working on making our Dashboard more user friendly.

**Q9.  Where should I contact your team for any help?**

**Ans:**  You can always feel free to contact MapmyIndia API Support Team at [apisupport@mapmyindia.com](mailto:apisupport@mapmyindia.com), we are always available here to serve you better.

**Q10.  How can I add multiple Projects in my Dashboard?**

**Ans:**  Currently, You have to place the request to the MapmyIndia API support team at [apisupport@mapmyindia.com](mailto:apisupport@mapmyindia.com) and we are also constantly working on making our Dashboard fully user friendly.

**Q11.  Where do I go for APIs & SDKs Documentation?**

**Ans:**  All the documentation of our APIs & SDKs are available on our official website [www.mapmyindia.com/api](http://www.mapmyindia.com/api) & at our Github Repository available here at [www.github.com/mapmyindia](http://www.github.com/mapmyindia).

**Q12.  What is IP/Domain Whitelisting/Blacklisting?**

**Ans:**  This feature lets you whitelist or blacklist the particular IP/Domain in your project, so that the credentials of are binded to allowed IPs/Domains.

**Q13.  How to reset Password?**

**Ans:**  If you forget your password, you can reset it by visiting the following URL: [https://anchor.mapmyindia.com/app/#/forgotPassword](https://anchor.mapmyindia.com/app/#/forgotPassword)

**Q14.  What are the types of billing?**

**Ans:**  Following are the types of billing as mentioned below:
-  Free: This is for free & evaluation users who just signed up fresh on MapmyIndia API Portal.    
-  Custom: This is for paid users. It depends on the plan that the user/organization has opted for.

**Q15.  What is Project Type?**

**Ans:**  It shows that the project falls in which category like free, enterprise, projects, etc.

<style>
  p {
    font-family: Nunito;
    font-size: 14px;
  }
  h2 {
    font-family: Nunito;
    font-size: 20px;
  }
</style>
