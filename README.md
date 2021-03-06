# JavaScript-Interview-Questions

> Click :star:if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
|---- | ---------
| <span id="Q1">1</span> | [What is Javascript?](#What-is-Javascript)|
| <span id="Q2">2</span> | [What are features of Javascript?](#What-are-features-of-Javascript)|
| <span id="Q3">3</span> | [What are advantages of Javascript?](#What-are-advantages-of-Javascript)|
| <span id="Q4">4</span> | [What are disadvantages of Javascript?](#What-are-disadvantages-of-Javascript)|
| <span id="Q5">5</span> | [What is difference between Javascript and ECMAScript?](#What-is-difference-between-Javascript-and-ECMAScript)|
| <span id="Q6">6</span> | [Who developed Javascript?](#Who-developed-Javascript)|
| <span id="Q7">7</span> | [How to insert Javascript in Web page?](#How-to-insert-Javascript-in-Web-page)|
| <span id="Q8">8</span> | [What are advantages of using external javascript?](#What-are-advantages-of-using-external-javascript)|
| <span id="Q9">9</span> | [Javascript is case sensitive language?](#Javascript-is-case-sensitive-language)|
| <span id="Q10">10</span> | [Is Semicolon compulsory in Javascript at end of the statement?](#Is-Semicolon-compulsory-in-Javascript-at-end-of-the-statement)|
| <span id="Q11">11</span> | [What are different data types in Javascript?](#What-are-different-data-types-in-Javascript)|
| <span id="Q12">12</span> | [How to add comment?](#How-to-add-comment)|
| <span id="Q13">13</span> | [What is Javascript engine?](#What-is-Javascript-engine)|
| <span id="Q14">14</span> | [What are different Javascript frameworks that you know?](#What-are-different-Javascript-frameworks-that-you-know)|
| <span id="Q15">15</span> | [Explain variable in Javascript.](#Explain-variable-in-Javascript)|
| <span id="Q16">16</span> | [What is var?](#What-is-var)|
| <span id="Q17">17</span> | [What is let?](#What-is-let)|
| <span id="Q18">18</span> | [What is const?](#What-is-const)|
| <span id="Q19">19</span> | [What is difference between let and var?](#What-is-difference-between-let-and-var)|
| <span id="Q20">20</span> | [What is difference between let and const?](#What-is-difference-between-let-and-const)|
| <span id="Q21">21</span> | [What is automatic type conversion?](#What-is-automatic-type-conversion)|
| <span id="Q22">22</span> | [What are operators in Javascript?](#What-are-operators-in-Javascript)|
| <span id="Q23">23</span> | [Explain different types of operators in Javascript.](#Explain-different-types-of-operators-in-Javascript)|
| <span id="Q24">24</span> | [What are control flow statements?](#What-are-control-flow-statements)|
| <span id="Q25">25</span> | [What is break statement?](#What-is-break-statement)|
| <span id="Q26">26</span> | [What is continue statement?](#What-is-continue-statement)|
| <span id="Q27">27</span> | <a href="#N27">What is the difference between comparing variables using "==" and "===" operator?</a>||
| <span id="Q28">28</span> | [What is typeof operator?](#What-is-typeof-operator)|
| <span id="Q29">29</span> | [What is variable hoisting?](#What-is-variable-hoisting)|
| <span id="Q30">30</span> | [What is difference between undefined and null?](#What-is-difference-between-undefined-and-null)|
| <span id="Q31">31</span> | <a href="#N31">What is output of null == undefined?</a>|
| <span id="Q32">32</span> | [What are escape characters?](#What-are-escape-characters)|
| <span id="Q33">33</span> | [How to create array in javascript?](#How-to-create-array-in-javascript)|
| <span id="Q34">34</span> | [How to create three dimensional array?](#How-to-create-three-dimensional-array)|
| <span id="Q35">35</span> | [What are the variable naming conventions in JavaScript?](#What-are-the-variable-naming-conventions-in-JavaScript)|
| <span id="Q36">36</span> | [Why you should not prefer to use global variables?](#Why-you-should-not-prefer-to-use-global-variables)|
| <span id="Q37">37</span> | [What are functions?](#What-are-functions)|
| <span id="Q38">38</span> | [What are types of functions in Javascript?](#What-are-types-of-functions-in-Javascript)|
| <span id="Q39">39</span> | [What are frequently used built-in global functions?](#What-are-frequently-used-built-in-global-functions)|
| <span id="Q40">40</span> | [What is isNaN?](#What-is-isNaN)|
| <span id="Q41">41</span> | [What is parseInt?](#What-is-parseInt)|
| <span id="Q42">42</span> | [What is alert?](#What-is-alert)|
| <span id="Q43">43</span> | [What is confirm?](#What-is-confirm)|
| <span id="Q44">44</span> | [What is charAt?](#What-is-charAt)|
| <span id="Q45">45</span> | [What is indexOf?](#What-is-indexOf)|
| <span id="Q46">46</span> | [What are function scopes?](#What-are-function-scopes)|
| <span id="Q47">47</span> | [What is strict mode?](#What-is-strict-mode)|
| <span id="Q48">48</span> | [What is function closure?](#What-is-function-closure)|
| <span id="Q49">49</span> | [What is callback function?](#What-is-callback-function)|
| <span id="Q50">50</span> | [What is setTimeout function?](#What-is-setTimeout-function)|
| <span id="Q51">51</span> | [What is setInterval function?](#What-is-setInterval-function)|
| <span id="Q52">52</span> | [What is difference between setInterval and setTimeout functions?](#What-is-difference-between-setInterval-and-setTimeout-functions)|
| <span id="Q53">53</span> | [What is encodeURI() method?](#What-is-encodeURI-method)|
| <span id="Q54">54</span> | [What is decodeURI() method?](#What-is-decodeURI-method)|
| <span id="Q55">55</span> | [What are Events?](#What-are-Events)|
| <span id="Q56">56</span> | [What are different events in Javascript?](#What-are-different-events-in-Javascript)|
| <span id="Q57">57</span> | [What are event handlers?](#What-are-event-handlers)|
| <span id="Q58">58</span> | [What is addEventListener() method?](#What-is-addEventListener-method)|
| <span id="Q59">59</span> | [How to remove event listener from any element?](#How-to-remove-event-listener-from-any-element)|
| <span id="Q60">60</span> | [What are different key codes?](#What-are-different-key-codes)|
| <span id="Q61">61</span> | [What is event bubbling?](#What-is-event-bubbling)|
| <span id="Q62">62</span> | [Is it possible to stop event bubbling?](#Is-it-possible-to-stop-event-bubbling)|
| <span id="Q63">63</span> | [What is event capturing?](#What-is-event-capturing)|
| <span id="Q64">64</span> | [What is event delegation?](#What-is-event-delegation)|
| <span id="Q65">65</span> | [What is Object?](#What-is-Object)|
| <span id="Q66">66</span> | [What are ways to create objects?](#What-are-ways-to-create-objects)|
| <span id="Q67">67</span> | [Which are built-in or native objects?](#Which-are-built-in-or-native-objects)|
| <span id="Q68">68</span> | [What is ‘this’ keyword?](#What-is-this-keyword)|
| <span id="Q69">69</span> | [What is String object?](#What-is-String-object)|
| <span id="Q70">70</span> | [What is Number object?](#What-is-Number-object)|
| <span id="Q71">71</span> | [What is Boolean object?](#What-is-Boolean-object)|
| <span id="Q72">72</span> | [Explain about Array object.](#Explain-about-Array-object)|
| <span id="Q73">73</span> | [Explain about Date object.](#Explain-about-Date-object)|
| <span id="Q74">74</span> | [Explain about Math object.](#Explain-about-Math-object)|
| <span id="Q75">75</span> | [Explain about RegExp object.](#Explain-about-RegExp-object)|
| <span id="Q76">76</span> | [What is namespace?](#What-is-namespace)|
| <span id="Q77">77</span> | [How to create namespace?](#How-to-create-namespace)|
| <span id="Q78">78</span> | [What is prototype in javascript?](#What-is-prototype-in-javascript)|
| <span id="Q79">79</span> | [What is prototypal inheritance?](#What-is-prototypal-inheritance)|
| <span id="Q80">80</span> | [What is difference between call() and apply()?](#What-is-difference-between-call-and-apply)|
| <span id="Q81">81</span> | [What is Promise?](#What-is-Promise)|
| <span id="Q82">82</span> | [What is Browser Object Model?](#What-is-Browser-Object-Model)|
| <span id="Q83">83</span> | [What is Window Object?](#What-is-Window-Object)|
| <span id="Q84">84</span> | [What alert method in window object?](#What-alert-method-in-window-object)|
| <span id="Q85">85</span> | [Explain confirm method of window object.](#Explain-confirm-method-of-window-object)|
| <span id="Q86">86</span> | [Explain prompt method of window object.](#Explain-prompt-method-of-window-object)|
| <span id="Q87">87</span> | [How to redirect other webpage?](#How-to-redirect-other-webpage)|
| <span id="Q88">88</span> | [What is Navigator Object?](#What-is-Navigator-Object)|
| <span id="Q89">89</span> | [How to identify operating system of client device?](#How-to-identify-operating-system-of-client-device)|
| <span id="Q90">90</span> | [What is History Object?](#What-is-History-Object)|
| <span id="Q91">91</span> | [How to load previous page in browser programmatically?](#How-to-load-previous-page-in-browser-programmatically)|
| <span id="Q92">92</span> | [How to load next page in browser programmatically?](#How-to-load-next-page-in-browser-programmatically)|
| <span id="Q93">93</span> | [What is go method of history object?](#What-is-go-method-of-history-object)|
| <span id="Q94">94</span> | [What is Screen Object?](#What-is-Screen-Object)|
| <span id="Q95">95</span> | [What is Location Object?](#What-is-Location-Object)|
| <span id="Q96">96</span> | [How to print a web page?](#How-to-print-a-web-page)|
| <span id="Q97">97</span> | [What is Document Object?](#What-is-Document-Object)|
| <span id="Q98">98</span> | [What is DOM?](#What-is-DOM)|
| <span id="Q99">99</span> | [What are DOM nodes?](#What-are-DOM-nodes)|
| <span id="Q100">100</span> | [How to get element with id in DOM?](#How-to-get-element-with-id-in-DOM)|
| <span id="Q101">101</span> | [How to get element using class in DOM?](#How-to-get-element-using-class-in-DOM)|
| <span id="Q102">102</span> | [How to get content of any element?](#How-to-get-content-of-any-element)|
| <span id="Q103">103</span> | [What are DOM levels?](#What-are-DOM-levels)|
| <span id="Q104">104</span> | [What are deferred scripts?](#What-are-deferred-scripts)|
| <span id="Q105">105</span> | [What are asynchronous scripts?](#What-are-asynchronous-scripts)|
| <span id="Q106">106</span> | [What is difference between attribute and property?](#What-is-difference-between-attribute-and-property)|
| <span id="Q107">107</span> | [What is the difference between innerHTML &innerText?](#What-is-the-difference-between-innerHTML-&-innerText)|
| <span id="Q108">108</span> | [What is the difference between textContent & innerText?](#What-is-the-difference-between-textContent-&-innerText)|
| <span id="Q109">109</span> | [What is HTMLCollection?](#What-is-HTMLCollection)|
| <span id="Q110">110</span> | [What is NodeList?](#What-is-NodeList)|
| <span id="Q111">111</span> | [What are frames?](#What-are-frames)|
| <span id="Q112">112</span> | [What is cookie?](#What-is-cookie)|
| <span id="Q113">113</span> | [How cookie helps client server HTTP communication?](#How-cookie-helps-client-server-HTTP-communication)|
| <span id="Q114">114</span> | [Where are cookies stored?](#Where-are-cookies-stored)|
| <span id="Q115">115</span> | [Where are parameters of cookie?](#Where-are-parameters-of-cookie)|
| <span id="Q116">116</span> | [Can user disable cookies?](#Can-user-disable-cookies)|
| <span id="Q117">117</span> | [How to create cookie?](#How-to-create-cookie)|
| <span id="Q118">118</span> | [How to read cookie?](#How-to-read-cookie)|
| <span id="Q119">119</span> | [How to delete cookie?](#How-to-delete-cookie)|
| <span id="Q120">120</span> | [What is difference between local storage and session storage?](#What-is-difference-between-local-storage-and-session-storage)|
| <span id="Q121">121</span> | [What is form validation?](#What-is-form-validation)|
| <span id="Q122">122</span> | [What is required attribute?](#What-is-required-attribute)|
| <span id="Q123">123</span> | [What is pattern attribute?](#What-is-pattern-attribute)|
| <span id="Q124">124</span> | [How to validate form using Javascript function?](#How-to-validate-form-using-Javascript-function)|
| <span id="Q125">125</span> | [How to validate email in the form?](#How-to-validate-email-in-the-form)|
| <span id="Q126">126</span> | [How to validate field without submitting form?](#How-to-validate-field-without-submitting-form)|
| <span id="Q127">127</span> | [What is .test method?](#What-is-.test-method)|
| <span id="Q128">128</span> | [What is .match method?](#What-is-.match-method)|
| <span id="Q129">129</span> | [How to validate Date?](#How-to-validate-Date)|
| <span id="Q130">130</span> | [How to allow number only in input field?](#How-to-allow-number-only-in-input-field)|
| <span id="Q131">131</span> | [What is error object?](#What-is-error-object)|
| <span id="Q132">132</span> | [What are different error types in Javascript?](#What-are-different-error-types-in-Javascript)|
| <span id="Q133">133</span> | [How to handle exceptions in JavaScript?](#How-to-handle-exceptions-in-JavaScript)|
| <span id="Q134">134</span> | [Explain try…catch…finally.](#Explain-try…catch…finally)|
| <span id="Q135">135</span> | [How to throw exceptions programmatically?](#How-to-throw-exceptions-programmatically)|
| <span id="Q136">136</span> | [What is debugging?](#What-is-debugging)|
| <span id="Q137">137</span> | [What is debugger keyword?](#What-is-debugger-keyword)|
| <span id="Q138">138</span> | [What is console object?](#What-is-console-object)|
| <span id="Q139">139</span> | [How to activate debugging in browser?](#How-to-activate-debugging-in-browser)|
| <span id="Q140">140</span> | [How to get mobile devices view of webpage in desktop browser?](#How-to-get-mobile-devices-view-of-webpage-in-desktop-browser)|
| <span id="Q141">141</span> | [How to deactivate breakpoint in browser?](#How-to-deactivate-breakpoint-in-browser)|
| <span id="Q142">142</span> | [How to pause script execution?](#How-to-pause-script-execution)|
| <span id="Q143">143</span> | [How to execute function line by line while debugging?](#How-to-execute-function-line-by-line-while-debugging)|
| <span id="Q144">144</span> | [How to execute function without stepping into it while debugging?](#How-to-execute-function-without-stepping-into-it-while-debugging)|
| <span id="Q145">145</span> | [What is code smell?](#What-is-code-smell)|
| <span id="Q146">146</span> | [What is AJAX?](#What-is-AJAX)|
| <span id="Q147">147</span> | [What is difference between GET and POST?](#What-is-difference-between-GET-and-POST)|
| <span id="Q148">148</span> | [What is XMLHttpRequest object?](#What-is-XMLHttpRequest-object)|
| <span id="Q149">149</span> | [How to make HTTP GET call using AJAX?](#How-to-make-HTTP-GET-call-using-AJAX)|
| <span id="Q150">150</span> | [How to make HTTP POST call using AJAX?](#How-to-make-HTTP-POST-call-using-AJAX)|
| <span id="Q151">151</span> | [What are HTTP status codes?](#What-are-HTTP-status-codes)|

## 1. Fundamentals

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

1. ### What is Javascript?

* Javascript is basically *scripting language* used to make web pages more _interactive_ as it can be inserted into HTML.
* Javascript is understood by all modern web browsers.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q1">**⬆ Back to Question 1**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

2. ### What are features of Javascript?

* **Input validation** : Javascript allows you to validate user input before sending it to server for backend operations.
* **Control over browser** : Javascript gives more control over browser due to which you can change the background colour of this page as well as the text on the browser's status bar.
* **Detect browser and OS** : Javascript enables you to detect user’s browser and OS due to which you can perform platform dependant operations.
* **Handling date and time** : Javascript enables you to write code based users date and time, it also enables you to capture users date and time as user and server may be in different time zone.
* **Generating HTML on fly** : Javascript enables you to dynamically generate HTML.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q2">**⬆ Back to Question 2**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

3. ### What are advantages of Javascript?

* **Faster speed** : JavaScript is fast because it run immediately within the client-side browser. Javascript is not dependant on network unless backend data is required to be processed. Need to compile Javascript on the client–side as it is interpreted directly by web
browsers.
* **Interoperability** : Javascript can be inserted into web page regardless of extension. Within other languages such as Perl and PHP it can be used inside the script.
* **Rich interfaces** :  Javascript has vast libraries like (charts, drag and
drop, sliders etc.) which enables you to provide attractive look to your website.
* **Reduction in server load** : Since Javascript is client-side scripting
language it reduces load on website servers as many operations can be performed at client-side which reduces load on server and enables it serve to more users.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q3">**⬆ Back to Question 3**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

4. ### What are disadvantages of Javascript?

* **Client-side security** : JavaScript code executes in users computer hence in some cases it can be manipulated for malicious purpose.
* **Browser support** : JavaScript is sometimes interpreted differently by different browsers.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q4">**⬆ Back to Question 4**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

5. ### What is difference between Javascript and ECMAScript?

* JavaScript is a scripting language that has been formed by keeping ECMAScript specification at its core.
* ECMAScript is nothing but a standard or specification defined in order to create different scripting languages and one of them is JavaScript.
* Javascript, Jscript and ActionScript are few scripting languages that follow ECMAScript specifications.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q5">**⬆ Back to Question 5**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

6. ### Who developed Javascript?

* JavaScript was created in 1995 by Brendan Eich during his time at Netscape Communications. 
* It was inspired by Java, Scheme and
Self.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q6">**⬆ Back to Question 6**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

7. ### How to insert Javascript in Web page? 

* You can use `<script>` tag in html.
* `<script>` tag has type attribute
which defined which code is there inside the script tag.
* You can use `<script>` element in web pages in following ways:

    * In head element
    * In body element
    * As an external script file

* To use Javascript as a scripting language for web pages in `<head>`
or `<body>` you can define type as **“text/javascript”**.

e.g.
```html
<script type=”text/javascript”>
</script>
```
* Sometime you may need to use same Javascript code in several web pages, in such cases you can store Javascript code in external file and save file as `<filename>.js` file.
* Then this script can be made available to web page using src attribute of `<script>` tag

e.g.
```html
<script src=”external file URL”>
</script>
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q7">**⬆ Back to Question 7**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

8. ### What are advantages of using external javascript?

* Placing JavaScript code in external js files has few advantages over inline scripts:
* Segregating HTML and JavaScript code helps to manage the code base better.
* To improve development output designers can work along with coders in parallel without code conflicts.
* This approach also works well with modern source code version control systems like GIT and SVN.
* Each of these files can maintain history.
* Segregating HTML and JavaScript makes code as well as HTML is easily readable.
* Segregated external JavaScript files are cached by browsers and can speed up page load times.
* These small js files can be minified to reduce the size and make it not readable by humans, using Google closure or YUI Compressor or other.
* Many popular JavaScript libraries are available as hosted on content delivery networks (cdn) and you can simply point to them using the URL in the src, this avoids copying the js file to local folder.
* Using external Js you can take benifits of advanced tools such as RequireJS or CommonJS to load these scripts logically and modularly.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q8">**⬆ Back to Question 8**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

9. ### Javascript is case sensitive language?

* Yes, Javascript is case sensitive scripting language. 
* Variables, functions, keywords must have consistent casing otherwise it will not be recognized by Javascript and will generate error.

e.g.
```javascript
var sandeep;
var sanDeep;
```
* In above case sandeep and sanDeep will be considered as different variables.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q9">**⬆ Back to Question 9**</a>

----
  _Questions_ <a href="#Q1">**1**</a> | <a href="#Q2">**2**</a> | <a href="#Q3">**3**</a> | <a href="#Q4">**4**</a> | <a href="#Q5">**5**</a> | <a href="#Q6">**6**</a> | <a href="#Q7">**7**</a> | <a href="#Q8">**8**</a> | <a href="#Q9">**9**</a> | <a href="#Q10">**10**</a>
  ----

10. ### Is Semicolon compulsory in Javascript at end of the statement?

* No, it is not necessary to use semicolon at end of the statement still it will be considered as valid statement.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q10">**⬆ Back to Question 10**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

11. ### What are different data types in Javascript?

Below are basic data types in Javascript:
* **Primitive Data Types** :

    * Number: Represent numeric values, both integer and float.
    * String: Sequence of characters are represented using String.
    * Boolean: Represent Boolean value, true or false.
    * Undefined: Represent undefined value.
    * Null: Represent null.

* **Non-Primitive Data Types** :
    * Object: Represent more complex data structure.
    * Array: Represent group of elements.
    * RegExp: Represent regular expression.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q11">**⬆ Back to Question 11**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

12. ### How to add comment?

* JavaScript provides two kinds of comments:

    * Single-line comments and multiline comments.

        * Single-line comments start with // and are terminated by the end of the line:

        e.g.
        ```javascript
        x++; // single-line comment
        ```
        * Multiline comments are delimited by /* and */:

        e.g.
        ```javascript
        /* This is
        a multiline
        comment.
        */
        ```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q12">**⬆ Back to Question 12**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

13. ### What is Javascript engine?

* JavaScript engine is a computer program used to execute Javascript code.
* JS engines were developed by web browser vendors and every major browser has one.
* Chrome V8 from google is most used engine, Google chrome use it.
* SpiderMonkey is developed by Mozilla for use in firefox.
* JavaScriptCore is Apples engine for its Safari browser.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q13">**⬆ Back to Question 13**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

14. ### What are different Javascript frameworks that you know?

Many frameworks are based on Javascript now, below are few of them:
* Angular
* React
* Vue
* Node
* Ember
* Meteor
* Backbone
* Aurelia
* Polymer
* Mithril

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q14">**⬆ Back to Question 14**</a>

----
## 2. Variables, Operators and Statements

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

15. ### Explain variable in Javascript.

* Basically, variable is used for temporary storage of data. 
* It has name, value and memory address. 
* You have to declare variable before using it for storing data. 
* Below is syntax to declare variable:
```javascript
var variablename;
```
* **_Note :_** Here var is keyword and variablename is name of the variable.
* You can also define multiple variables using single statement as:
```javascript
var variable1, variable2, variable3;
```
* Value can be assigned to variable as:
```javascript
var variablename = value;
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q15">**⬆ Back to Question 15**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

16. ### What is var?

* The var statement declares a variable and can also optionally initialize its value.
* Variables are declared using var as below,
```javascript
var varname1 [= value1] [, varname2 [= value2] ... [, varnameN [= valueN]]];
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q16">**⬆ Back to Question 16**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

17. ### What is let?

* The **‘let’** allows you to declare variables that are limited in scope to
the particular block, expression on which it is used or statement.
* Variables are declared using let as below,
```javascript
let var1 [= value1] [, var2 [= value2]] [, ..., varN [= valueN];
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q17">**⬆ Back to Question 17**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

18. ### What is const?

* Constants are block-scoped, much like variables defined using the let statement.
* The value of a constant cannot change through reassignment, and it can't be re-declared.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q18">**⬆ Back to Question 18**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

19. ### What is difference between let and var?

* The variable defined with var is available anywhere within the function hence 'var' keyword has function scope.
* The let has a Block Scope. A variable declared with ‘let’ keyword has a scope only with in that block.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q19">**⬆ Back to Question 19**</a>

----
  _Questions_ <a href="#Q11">**11**</a> | <a href="#Q12">**12**</a> | <a href="#Q13">**13**</a> | <a href="#Q14">**14**</a> | <a href="#Q15">**15**</a> | <a href="#Q16">**16**</a> | <a href="#Q17">**17**</a> | <a href="#Q18">**18**</a> | <a href="#Q19">**19**</a> | <a href="#Q20">**20**</a>
  ----

20. ### What is difference between let and const?

* ‘let’ allows you change the value of variable any number of times.
* Using ‘const’, after the first assignment of the value we cannot redefine the value again.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q20">**⬆ Back to Question 20**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

21. ### What is automatic type conversion?

* When Javascript tries to operate on a wrong date type it will try to convert the value to a “right” type.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q21">**⬆ Back to Question 21**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

22. ### What are operators in Javascript?

* An operator is a symbol or word which is used to perform particular operation.
* Arithmetic, Assignment, Comparison, Logical and Conditional Operators are types of operators.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q22">**⬆ Back to Question 22**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

23. ### Explain different types of operators in Javascript.

Below are types of operators:
* **Arithmetic operators** : Arithmetic operators are used to perform arithmetic between variables and values. 

    * Addition (+),
    * Subtraction (-), 
    * Multiplication (*), 
    * Division (/), 
    * Modulus (%),
    * Increment (++) and 
    * Decrement (--) 
    
    are arithmetic operators.

* **Assignment operators** : Assignment operators are used to assign values to variables. 

    * =, 
    * +=, 
    * -=, 
    * *=, 
    * /=, 
    * %= 
    
    are Assignment operators.

* **Comparison operators** : Comparison operators are used to compare variables or values. 

    * Equal to (==),
    * equal value and type (===), 
    * not equal (!=), 
    * not equal value or type (!==),
    * less than (<), 
    * greater than (>), 
    * less than or equal to (<=) and
    * greater than or equal to (>=) 
    
    are comparison operators.
* **Logical operators** : Logical operators allow program to make decision based on multiple conditions logic. Logical operators used for decision making are 
    * And (&&), 
    * or (||), 
    * not (!).

* **Conditional operator** : Conditional operators are used to assign values to variable conditionally. 

    * (condition) ? value1: value2 

is conditional operator.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q23">**⬆ Back to Question 23**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

24. ### What are control flow statements?

* You can change the sequence in which Javascript statements are executed by using control flow statements.
* Below are types of control flow statements:

    * **Selection statements** : Selection statements use condition to determine which group of statements should be executed, if….else,if and switch are selection statements.
    * **Loops** : Loops allow you to execute group of statements repeatedly till condition is satisfied, while, do…while and for are loops.
    * **Jump statements**: Jump statements are used to break or exit loop, break and continue are jump statements.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q24">**⬆ Back to Question 24**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

25. ### What is break statement?

* Break statement stops execution of loop entirely.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q25">**⬆ Back to Question 25**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

26. ### What is continue statement?

* Continue statement stops execution of current iteration in a loop and continues with next iteration of loop.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q26">**⬆ Back to Question 26**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

27. ### <span id="N27"></span> What is the difference between comparing variables using "==" and "===" operator?

* The ‘==’ operator tests for abstract equality i.e. it does the required type conversions before doing the equality comparison.
* But the ‘===’ operator tests for strict equality i.e. it will not do the type conversion thus if the two values are not of the same type, when compared, it will return false.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q27">**⬆ Back to Question 27**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

28. ### What is typeof operator?

* The **typeof** operator is used to get the data type of its operand. 
* The operand can be either a literal or a data structure such as variable, function or an object.

e.g.
```javascript
console.log(typeof somevar);
```
* The typeof operator returns below values as string: object, Boolean, function, number, string and undefined.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q28">**⬆ Back to Question 28**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

29. ### What is variable hoisting?

* In Javascript regardless of where the actual declaration has been made, all variable declarations that are using var, are hoisted/lifted to the top of their functional/local scope (if declared inside a function) or to the top of their global scope (if declared outside of a
function).
* This lifting of scopes is called hoisting.
Hence,
```javascript
bla = 2;
var bla;
// ...is implicitly understood as:
var bla;
bla = 2;
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q29">**⬆ Back to Question 29**</a>

----
  _Questions_ <a href="#Q21">**21**</a> | <a href="#Q22">**22**</a> | <a href="#Q23">**23**</a> | <a href="#Q24">**24**</a> | <a href="#Q25">**25**</a> | <a href="#Q26">**26**</a> | <a href="#Q27">**27**</a> | <a href="#Q28">**28**</a> | <a href="#Q29">**29**</a> | <a href="#Q30">**30**</a>
  ----

30. ### What is difference between undefined and null?

* The undefined means a variable has been declared but has no value has yet been assigned.
* On the other hand, null is basically a value which has been assigned.
* Also, undefined is a type itself (undefined) while null is an object.
* Unassigned variables are initialized with a default value of undefined by JavaScript or undefined can be assigned to variable through code.
* Whereas JavaScript never sets a value to null.That must be done programmatically.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q30">**⬆ Back to Question 30**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

31. ### <span id="N31"></span> What is output of null == undefined?

* **null == undefined** will return true.
* However, **null === undefined** will return false.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q31">**⬆ Back to Question 31**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

32. ### What are escape characters?

* Escape characters (backslash) is used before special characters like ampersand, single quotes, double quotes and apostrophes to display them.

e.g.
```javascript
console.log(‘I\’m Sandeep Dalal’);
// Correct syntax
console.log(‘I’m Sandeep Dalal’);
// Syntax error
```
* In above example, if backslash is not used before single quotes this line will give syntax error.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q32">**⬆ Back to Question 32**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

34. ### How to create three dimensional array?

* You can define three dimentionalarray arrays using the array follows:
```javascript
var threedimentionalarray = [[[]]];
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q34">**⬆ Back to Question 34**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

35. ### What are the variable naming conventions in JavaScript?

* The following rules are to be followed while naming variables in JavaScript:
  
  * You are not allowed to use* any of the reserved keyword as variable name.
  * JavaScript variable names should not begin with a numbers (0-9).
  * They must start with a letter or the underscore character.
  * JavaScript variable names are case sensitive.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q35">**⬆ Back to Question 35**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

36. ### Why you should not prefer to use global variables?

* Global variable can be created by many developers resulting in duplicate global variables.
* Duplicate variable can overwrite the value of your variable.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q36">**⬆ Back to Question 36**</a>
----
## 3. Functions
----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

37. ### What are functions?

* Function is a collection of statements which can be used anywhere in program, it is used to perform specific task.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q37">**⬆ Back to Question 37**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

38. ### What are types of functions in Javascript?

* Below are the types of functions:

  * Named: Functions which have name at the time of definition are named functions.

  e.g.
  ```javascript
  function print() {
  console.log(“This is named function!!!”);
  }
  ```
  * Anonymous: Functions which do not have names are anonymous functions.
  
  e.g
  ```javascript
  var print=function() {
  console.log(“This is anonymous function!!!”);
  }
  ```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q38">**⬆ Back to Question 38**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

39. ### What are frequently used built-in global functions?

* Alert(), 
* prompt(),
* isNan(), 
* eval(), 
* isFinite(),
* confirm(), 
* parseInt(),
* parseFloat(), 
* escape(), 
* unescape() 

are most frequently used built-in
global functions.

----
### Usage and Syntax :
* Alert() Function - 

  * Syntax
  ```javascript
  window.alert(message);
  ```
  * Parameters
    1. **message | Optional** : A string you want to display in the alert dialog, or, alternatively, an object that is converted into a string and displayed.
  * Example
  ```javascript
  window.alert("Hello world!");
  alert("Your error message!!!");
  ```
  * Output

    <img src="images/alert.png" width="150px" height="130px">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q39">**⬆ Back to Question 39**</a>

----
  _Questions_ <a href="#Q31">**31**</a> | <a href="#Q32">**32**</a> | <a href="#Q33">**33**</a> | <a href="#Q34">**34**</a> | <a href="#Q35">**35**</a> | <a href="#Q36">**36**</a> | <a href="#Q37">**37**</a> | <a href="#Q38">**38**</a> | <a href="#Q39">**39**</a> | <a href="#Q40">**40**</a>
  ----

40. ### What is isNaN?

* It is a function which determine whether or not value is an illegal number. 
* The isNan() method returns true if the passed value is NaN(Not a number) and is of type number, else it returns false.

e.g.
```javascript
Input: '213'
Output: false
Input:'hello'
Output: true
```
* Syntax
  
  > isNaN(value)
  
  * Parameters
    1. **value** : The value to be tested.
  * Return Value
    **_true_** if the given value is NaN; otherwise, **_false_**.
  * Example
  ```javascript
  console.log(isNaN(213));
  console.log(isNaN("hello"));
  ```
  * Output
  
    * false
    * true

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q40">**⬆ Back to Question 40**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

41. ### What is parseInt?

* The parseInt is a function which parses the string and returns the integer value found in string.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q41">**⬆ Back to Question 41**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

42. ### What is alert?

* The alert() function is used to display information in message box.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q42">**⬆ Back to Question 42**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

43. ### What is confirm?

* The confirm() function displays a message box with two buttons, Ok
and cancel.
  
  * When you click the Ok button, the function returns true.
  * When you click cancel button function returns false.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q43">**⬆ Back to Question 43**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

44. ### What is charAt?

* The charAt() function returns character from specified index.

e.g.
```javascript
var str="Sandeep";
console.log(str.charAt(0));
```
* Output : S

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q44">**⬆ Back to Question 44**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

45. ### What is indexOf?

* This function returns the index within the calling string object of first occurrence of the specified value and returns index of found occurrence or -1 if not found.

e.g.
```javascript
var str="This is javascript book";
console.log(str.indexOf(“javascript”));
```
* Output: 8

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q45">**⬆ Back to Question 45**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

46. ### What are function scopes?

* Scope defines accessibility of function and its variables. 
In Javascript scope is divided into two categories:

  * Global: Function with global scope can be accessed anywhere in the program.
  * Local: Function with local scope can be accessed only within its parent function.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q46">**⬆ Back to Question 46**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

47. ### What is strict mode?

* Strict mode prevents certain actions and throws more exceptions.
* The statement **“use strict”** orders browser to use the Strict mode, which is a reduced and safer feature set of JavaScript.
* Strict mode eliminates some silent errors in JavaScript by changing them to throw errors.
* Strict mode resolves mistakes that make it difficult for JavaScript engines to perform optimizations hence strict mode code can sometimes run faster than identical code that’s not strict mode.
* Strict mode forbids some syntax likely to be defined in future versions of ECMAScript.
* It prevents, or throws errors, when unsafe actions are taken (such as gaining access to the global object).
* It disables features that are confusing or poorly thought out.
* Due to Strict mode it becomes easier to write secure JavaScript.
* Strict mode applies to individual functions or to entire scripts. It doesn't apply to block statements enclosed in {} braces; attempting to apply it to such contexts does nothing.
* To invoke strict mode for an entire script, put statement "use strict" before any other statements.
* To invoke strict mode for a function, put statement "use strict" in the function's body before any other statements.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q47">**⬆ Back to Question 47**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

48. ### What is function closure?

* A closure is a feature in JavaScript where an inner function has access to the outer (enclosing) function’s variables.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q48">**⬆ Back to Question 48**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

49. ### What is callback function?

* A function passed into another function as an argument, which is then invoked inside the outer function to complete some kind action is called as callback function.

e.g.
```javascript
function showName(name) {
alert('User name is:' + name);
}
function displayName(callback) {
var name = prompt('Please enter name to be displayed');
callback(name);
}
displayName(showName);
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q49">**⬆ Back to Question 49**</a>

----
  _Questions_ <a href="#Q41">**41**</a> | <a href="#Q42">**42**</a> | <a href="#Q43">**43**</a> | <a href="#Q44">**44**</a> | <a href="#Q45">**45**</a> | <a href="#Q46">**46**</a> | <a href="#Q47">**47**</a> | <a href="#Q48">**48**</a> | <a href="#Q49">**49**</a> | <a href="#Q50">**50**</a>
  ----

50. ### What is setTimeout function?

* The setTimeout() function executes function at specified interval.
```javascript
setTimeout(expression, timeout);
```
* Here, expression is the function/code that is called only once and timeout is number of milliseconds to wait before calling the function.
* **Note :** The clearTimeout() function is used to deactivate or cancel timer set by setTimeout() fuction.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q50">**⬆ Back to Question 50**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

51. ### What is setInterval function?

* The setInterval() function executes a function after a specified time interval.
```javascript
setInterval(expression, timeout);
```
* Here, expression specifies function/code to be called after particular time interval and timeout specifies the time interval between function calls.
* The clearInterval() function is used to cancel or deactivate the timer set by setInterval() function.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q51">**⬆ Back to Question 51**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

52. ### What is difference between setInterval and setTimeout functions?

* The setTimeout(expression, timeout) runs the function once after timeout
* The setInterval(expression, timeout) runs the function in intervals repeatedly, with length of timeout between them.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q52">**⬆ Back to Question 52**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

53. ### What is encodeURI() method?

* The encodeURI() method encodes a Uniform Resource Identifier by replacing each instance of particular characters by one, two, three or four escape sequences representing UTF-8 encoding of
character.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q53">**⬆ Back to Question 53**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

54. ### What is decodeURI() method?

* The decodeURI() method decodes a Uniform Resource Identifier previously created by encodeURI().

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q54">**⬆ Back to Question 54**</a>
----
## 4. Events
----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

55. ### What are Events?

* Events are actions or occurrences that happen in the system you are programming to which you can respond in some way.
* Events are handled by function know as event handler.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q55">**⬆ Back to Question 55**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

56. ### What are different events in Javascript?

Few of the important events are listed below:
* **Input Events**

  * onsubmit - triggers on submitting a form.
  * onselect - triggers on selecting an element.
  * onchange - triggers when changes happen to an element.
  * onfocus - triggers when windows gets focus.
  * onreset - triggers when user clicks reset button.
  * onblur - triggers when window loses focus.
  * onkeyup - triggers on releasing a key.
  * onkeydown - triggers on pressing a key.

* **Click Events**
  
  * onclick - trigger on clicking a mouse button.
  * ondblclick - triggers on double clicking mouse button.

* **Mouse Events**
  
  * ondrag - triggers when element is dragged.
  * ondragend - triggers when drag ends.
  * ondragstart - triggers when drag starts.
  * ondragenter - triggers when dragged element is dropped.
  * ondragleave - triggers on leaving target while dragging element.
  * onmouseover - triggers when mouse pointer moves over element.
  * onmousedown - triggers on pressing mouse button.
  * onmouseup - triggers on releasing mouse button.
  * onscroll - triggers on scrolling a scroll bar of an element.

* **Load Events**
  
  * onload- triggers when page has been loaded.
  * onerror- triggers when an error occurs when loading an image.
  * onunload- triggers when browser closes document.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q56">**⬆ Back to Question 56**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

57. ### What are event handlers?

* Event handler is a routine that is used to deal with event, allowing programmer to write code that will be executed when event occurs.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q57">**⬆ Back to Question 57**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

58. ### What is addEventListener() method?

* The addEventListener() method attaches an event handler to specified element.
* You can add multiple event handlers to one element.
* It is possible to add event listener to any DOM object.

e.g.
```javascript
document.getElementById(“someUniqueDivId”).addEventListener(“click”, respondtoclick);

function respondtoclick() {
  console.log(“Do some stuff!!!”);
}
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q58">**⬆ Back to Question 58**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

59. ### How to remove event listener from any element?

* The **removeEventListener()** is an inbuilt function in JavaScript which removes an event handler from an element for attached event.
* Below example show how to remove event listener which was added in previous example.

e.g.
```javascript
document.getElementById(“someUniqueDivId”).removeEventListener("click", respondtoclick);
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q59">**⬆ Back to Question 59**</a>

----
  _Questions_ <a href="#Q51">**51**</a> | <a href="#Q52">**52**</a> | <a href="#Q53">**53**</a> | <a href="#Q54">**54**</a> | <a href="#Q55">**55**</a> | <a href="#Q56">**56**</a> | <a href="#Q57">**57**</a> | <a href="#Q58">**58**</a> | <a href="#Q59">**59**</a> | <a href="#Q60">**60**</a>
  ----

60. ### What are different key codes?

It is necessary to know the codes associated with keys to identify
which key is pressed in the code.
Below table gives key codes:

| Key | Code | Key | Code | Key | Code | Key | Code |
|----|----|----|----|----|----|----|----|
| backspace | 8 | A | 65 | numpad0 | 96 |  semicolon | 186 |
| Tab | 9 | B | 66 | numpad1 | 97 | equal sign | 187 |
| Enter | 13 | C | 67 | numpad 2 | 98 | comma | 188 |
| Shift | 16 | D | 68 | numpad 3 | 99 | dash | 189 |
| Ctrl | 17 | E | 69 | numpad 4 | 100 | period | 190 |
| Alt | 18 | F | 70 | numpad 5 | 101| forward slash | 191 |
| pause/break | 19 | G | 71 | numpad 6 | 102 | grave accent | 192 |
| caps lock | 20 | H | 72 | numpad 7 | 103 | open bracket | 219 |
| escape | 27 | I | 73 | numpad 8 | 104 | back slash | 220 |
| page up | 33 | J | 74 | numpad 9 | 105 | close braket | 221 |
| page down | 34 | K | 75 | multiply | 106 | single quote | 222 |
| End | 35 | L | 76 | add | 107 | | |
| home | 36 | M | 77 | subtract | 109 | | |
| left arrow | 37 | N | 78 | decimal point | 110 | | |
| up arrow | 38 | O | 79 | divide | 111 | | |
| right arrow | 39 | P | 80 | f1 | 112 | | |
| down arrow | 40 | Q | 81 | f2 | 113 | | |
| insert | 45 | R | 82 | f3 | 114 | | |
| delete | 46 | S | 83 | f4 | 115 | | |
| 0 | 48 | T  |84 | f5 | 116 | | |
| 1 | 49 | U | 85 | f6 | 117 | | |
| 2 | 50 | V | 86 | f7 | 118 | | |
| 3 | 51 | W | 87 | f8 | 119 | | |
| 4 | 52 | X | 88 | f9 | 120 | | |
| 5 | 53 | Y | 89 | f10 | 121 | | |
| 6 | 54 | Z | 90 | f11 | 122 | | |
| 7 | 55 | left window key | 91 | f12 |123 | | |
| 8 | 56 | right window key | 92 | num lock | 144 | | |
| 9 | 57 | select key | 93 | scroll lock | 145 | | |

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q60">**⬆ Back to Question 60**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

61. ### What is event bubbling?

* When an event happens on an element, it first runs the handlers on that particular element, after that handlers on its parent runs, this happens all the way up on all other ancestors. This bubbling of events from child to parent is called event bubbling.
* A click on inner `<p>` first runs onclick on that `<p>`, then on outer `<div>`, then on outer `<form>` and so on till document object. 

<img src="images/event-bubbling.png">

* This process is called **“bubbling”**, because events **“bubble”** from the inner element up through parent like a bubble in the water.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q61">**⬆ Back to Question 61**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

62. ### Is it possible to stop event bubbling?

* Yes, by using method **event.stopPropagation()**.
* If you want to stop the event flow from event target to top element in DOM, **event.stopPropagation()** method stops the event to travel to the bottom to top.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q62">**⬆ Back to Question 62**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

63. ### What is event capturing?

In the capturing phase:
* The browser checks to see if the element's outer-most ancestor `(<html>)` has an onclick event handler registered on it during the capturing phase, and runs it if so.
* Then it moves on to the next element inside `<html>` and does the same thing, then the next one, and so on until it reaches the element that was actually clicked on.
* The capturing phase is not often used. Usually it is invisible to us.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q63">**⬆ Back to Question 63**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

64. ### What is event delegation?

* Event delegation concept relies on the fact that if you want some code to run when you click on any one of a large number of grouped child elements, you can set the event listener on their
parent and have events that happen on them bubble up to their parent, instead of having to set the event listener on every child individually.
* A good example is a series of list items `<li>` — You can set the click event listener on the parent `<ul>`, if you want each one of them`<li>` to pop up a message when clicked and it will bubble to the list items.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q64">**⬆ Back to Question 64**</a>
----
## 5. Objects
----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

65. ### What is Object?

* The object is collection of properties and methods.
* Object in Javascript are variables as well. Object can have properties any data types (String, Number, Boolean etc.).
* Object properties can be primitive values, other objects and functions.

e.g.
```javascript
var notes = {
name : "Javascript Notes",
auther: "Sandeep Dalal",
pages: 100
}
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q65">**⬆ Back to Question 65**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

66. ### What are ways to create objects?

* In Javascript you can create objects through following ways:
* **Using literals :**
  * Using object literal you can basically create object by using name
  value pairs inside curly {} braces.
  
  e.g.
  ```javascript
  var notes = {
  name : "Javascript Notes",
  auther: "Sandeep Dalal",
  pages: 100
  }
  ```
* **Using new keyword with built-in object constructor function :**
  
  * Using new keyword you can create object and then set its properties as below,
  
  e.g.
  ```javascript
  var person= new Object();
  person.name= "John";
  person.auther= "Doe";
  person.pages= 50;
  ```
* **Using new keyword with built-in user defined constructor function :**
  
  * We first create a constructor function and then get objects using
  ‘new’ keyword. .
  
  e.g.
  ```javascript
  function Book(name, author, pages) {
  this.name = name;
  this.author = author;
  this.pages = pages;
  }
  ```
  * And then we create Book object as below,
  ```javascript
  var book = new Book("Notes", "Sandeep Dalal", 100);
  ```
* **Using Object.create() :**
  
  * The Object.create() method creates a new object, using an existing object as the prototype of the newly created object.
  
  e.g.
  ```javascript
  const person = {
  isHuman: false,
  printIntroduction: function () {
  console.log(`Am I human? ${this.isHuman}`);
  }
  };
  const me = Object.create(person);
  ```
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q66">**⬆ Back to Question 66**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

67. ### Which are built-in or native objects?

* JavaScript provides Number, Boolean, String, Array, Date, Math, RegExp which are built in objects.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q67">**⬆ Back to Question 67**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

68. ### What is ‘this’ keyword?

* The this keyword refers to the object it belongs to.
* In an object method, this refers to the object to which method belongs.
* When used alone, the owner is the Global object, so this refers to the Global object (Windows object).
* In a function, this refers to the Global object (Windows object).
* In strict mode, when used in a function, this is undefined.
* In HTML event handlers, this refers to the element in html that received the event.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q68">**⬆ Back to Question 68**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

69. ### What is String object?

* String object is basically sequence of characters. String object provides number of methods to perform required operations on String object.
* It provides methods like charAt(), charCodeAt(), concat(), indexOf(),
match(), slice(), split(), substr(), toLowerCase(), toUpperCase(), valueOf(), toString() which provides important functionalities that can be performed on string.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q69">**⬆ Back to Question 69**</a>

----
  _Questions_ <a href="#Q61">**61**</a> | <a href="#Q62">**62**</a> | <a href="#Q63">**63**</a> | <a href="#Q64">**64**</a> | <a href="#Q65">**65**</a> | <a href="#Q66">**66**</a> | <a href="#Q67">**67**</a> | <a href="#Q68">**68**</a> | <a href="#Q69">**69**</a> | <a href="#Q70">**70**</a>
  ----

70. ### What is Number object?

* The number is Javascript wrapper object which allows you to work with numerical values.
* Number object is created as,
```javascript
var numberVar = new Number([value]);
```
* It provides methods like isNaN(), isFinite(), isInteger(),
isSafeInteger(), parseInt(), parseFloat() to work with numbers.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q70">**⬆ Back to Question 70**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

71. ### What is Boolean object?

* The Boolean object wraps a boolean value.
* Boolean object is created as,
```javascript
var booleanVar = new Boolean([value]);
```
* If the value is omitted or is 0, -0, null, false, NaN, undefined, or the
empty string (""), the object has an initial value of false. 
* All other values, including any object or the string "false", create an object
with an initial value of true.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q71">**⬆ Back to Question 71**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

72. ### Explain about Array object.

* The Array is a global object that is used to store different elements for the construction of arrays.
* Array object is created as,
```javascript
new Array(ele0, ele1[, ...[, eleN]])
new Array(arrayLength)
``` 
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q72">**⬆ Back to Question 72**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

73. ### Explain about Date object.

* The JavaScript Date object represents a single moment in time.
* Date objects use a unix timestamp which is a integer value that is number of milliseconds since 1 January 1970.
* Date object is created as,
```javascript
new Date();
new Date(value);
new Date(dateString);
new Date(year, monthIndex [, day [, hours [, minutes [, seconds [, milliseconds]]]]]);
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q73">**⬆ Back to Question 73**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

74. ### Explain about Math object.

* Math is a built-in object that has methods and properties for mathematical constants and functions.
* Unlike the other global objects, Math does not have a constructor.
* All methods and properties of Math are static.
* It provides methods like sin(x), cos(x), tan(x), exp(x), floor(x), max([x[, y[, …]]]), min([x[, y[, …]]]), pow(x, y), random(), round(x), trunc(x) for mathematical operations.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q74">**⬆ Back to Question 74**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

75. ### Explain about RegExp object.

* The RegExp constructor is used to create a regular expression object for matching text with a pattern.
* Date object is created as,
```javascript
new RegExp(pattern[, flags])
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q75">**⬆ Back to Question 75**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

76. ### What is namespace?

* In JavaScript, namespace is a single global object which will contain all our functions, methods, variables.
* Javascript don’t provide default namespace you have to create it, so all functions, variables and object in Javascript are by default global.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q76">**⬆ Back to Question 76**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

77. ### How to create namespace?

* Below is example to create namespace and access function within it:
```javascript
var myProjectNameSpace = {
  projectfunctionone: function() {
},
projectfunctiontwo: function() {
}
}
.
.
.
myProjectNameSpace. Projectfunctionone();
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q77">**⬆ Back to Question 77**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

78. ### What is prototype in javascript?

* All objects in Javascript have property called as prototype, the prototype is an object which has a constructor properties by default.
* The prototype object is associated with every functions and objects by default in JavaScript, where function's prototype property is accessible and modifiable and object's prototype property is not visible.
* The prototype property allows you to add properties and methods to any object.

e.g.
```javascript
somecustomcreationobject.prototype.age=29;
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q78">**⬆ Back to Question 78**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

79. ### What is prototypal inheritance?

* Object have property called as prototype which can refer to other
object.
* When you want to read a property from object, and it’s missing, JavaScript automatically takes it from the prototype. This is called “prototypal inheritance”.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q79">**⬆ Back to Question 79**</a>

----
  _Questions_ <a href="#Q71">**71**</a> | <a href="#Q72">**72**</a> | <a href="#Q73">**73**</a> | <a href="#Q74">**74**</a> | <a href="#Q75">**75**</a> | <a href="#Q76">**76**</a> | <a href="#Q77">**77**</a> | <a href="#Q78">**78**</a> | <a href="#Q79">**79**</a> | <a href="#Q80">**80**</a>
  ----

80. ### What is difference between call() and apply()?
* `call()` Method

  * The Function.prototype.call() method calls a function with a provided **_this_** value and arguments provided **_individually_**.
  * It is necessary to know arguments of function when using call() method.
* `apply()` Method

  * The Function.prototype.apply() method calls a function with a provided **_this_** value, and arguments provided as an **_array_** (or an array-like object).
  * It is necessary to know arguments of function when using apply() method.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q80">**⬆ Back to Question 80**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

81. ### What is Promise?

* The Promise object represents the eventual completion (or failure) of an asynchronous operation along with its resulting value.
* A Promise is a proxy for a value which may or may not be known when the promise is created.
* It allows you to associate handlers with an asynchronous action's eventual success value or failure reason.
* This enables asynchronous methods return values like synchronous methods: instead of immediately returning final value, the asynchronous method returns a promise to provide the value at some point in the future.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q81">**⬆ Back to Question 81**</a>
----
## 6. Browser Object Model
----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

82. ### What is Browser Object Model?

* The browser object model (BOM) is a hierarchy of browser objects that are used to manipulate methods and properties associated with the Web browser itself.
* The default object of browser is window means you can invoke all the functions of window by specifying window or directly
* Objects that make up the BOM include the window object, navigator object, screen object, location object, history, and the document object.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q82">**⬆ Back to Question 82**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

83. ### What is Window Object?

* In a tabbed browser, each tab is represented as Window object.
* Every object, variable, and function defined in a web page uses of the window as its Global object.
* Window object provides methods like alert(), blur(), close(), confirm(), print(), prompt(), open().

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q83">**⬆ Back to Question 83**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

84. ### What alert method in window object?

* Alert dialogs are typically used when users has to be made aware of something that they have no control over, such as errors.
* Often alert dialogs pops up when the user enters invalid data into a
form.
* When alert() is called,the browser creates a system message box that displays the given text with an OK button.
* For example, the following line of code causes the message box in to be displayed:
```javascript
alert(“Your error message!!!”);
```
<img src="images/alert.png" width=250px height="200px">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q84">**⬆ Back to Question 84**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

85. ### Explain confirm method of window object.

A confirm dialog appears similar to an alert dialog.
The main difference between them is the presence of a Cancel
button along with the OK button in the confirm dialog, which allows
the user to confirm if a given action should be taken.
For example, the following line of code displays the confirm dialog
shown in Figure
confirm(“Do you wish to proceed?”);

<img src="images/confirm.png" width=250px height="200px">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q85">**⬆ Back to Question 85**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

86. ### Explain prompt method of window object.

* The prompt method is used to display dialog with input from user.
* Along with OK and Cancel buttons, prompt dialog also has a text box where the user is asked to enter some data.
* The `prompt()` method accepts two arguments: the text to display to
the user and the default value for the text box (which can be an empty string if you so desire).
* The following line results in the
window displayed:
```javascript
prompt("Enter the country","USA");
```
<img src="images/promote.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q86">**⬆ Back to Question 86**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

87. ### How to redirect other webpage?

* It is possible to redirect to other webpage in javascript by directly
assigning value to `window.location` or by using `location.assign()`,`location.replace()` and `location.reload()` methods.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q87">**⬆ Back to Question 87**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

88. ### What is Navigator Object?

* The navigator object is used to get browser information like name, version, type, language. 
* It has methods like `javaEnabled()` and
`taintEnabled()`.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q88">**⬆ Back to Question 88**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

89. ### How to identify operating system of client device?

* **“Navigator.appVersion”** is used to find operating system of client
device.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q89">**⬆ Back to Question 89**</a>

----
  _Questions_ <a href="#Q81">**81**</a> | <a href="#Q82">**82**</a> | <a href="#Q83">**83**</a> | <a href="#Q84">**84**</a> | <a href="#Q85">**85**</a> | <a href="#Q86">**86**</a> | <a href="#Q87">**87**</a> | <a href="#Q88">**88**</a> | <a href="#Q89">**89**</a> | <a href="#Q90">**90**</a>
  ----

90. ### What is History Object?

* The History object consist of array of URLs which are visited by a user in browser.
* History object provides method like back(), forward() and go().

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q90">**⬆ Back to Question 90**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

91. ### How to load previous page in browser programmatically?

* `history.back()` can be used to load previous page in browser through
code.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q91">**⬆ Back to Question 91**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

92. ### How to load next page in browser programmatically?

* `history.forward()` can be used to load next page in browser through
code.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q92">**⬆ Back to Question 92**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

93. ### What is go method of history object?

* The `go()` method loads a specific URL from the history list.

`history.go(number|URL)`

**number|URL** parameter can either be a number which goes to the URL within the specific position (1 goes forward one page, -1 goes back one page), or a string. 
* The string has to be a partial or full URL, and the function will go to the first URL that matches the string.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q93">**⬆ Back to Question 93**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

94. ### What is Screen Object?

* The Screen object consist of information about display screen like height, width and colour bits of screen.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q94">**⬆ Back to Question 94**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

95. ### What is Location Object?

* The Location object consist of information about current URL of
window object.
* Location object provides methods like assign(), reload and replace().

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q95">**⬆ Back to Question 95**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

96. ### How to print a web page?

* The **window.print()** will print the current web page when invoked.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q96">**⬆ Back to Question 96**</a>
----
## 7. Document Object Model
----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

97. ### What is Document Object?

* The Document object represents HTML document that is displayed in window.
* Document object has properties which allows access and modification of document content.
* The way document is accessed and modified is called Document Object Model or DOM.
* Document object provides methods like open(), close(), write(), getElementById(), getElementByName(), getElementByTagName().

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q97">**⬆ Back to Question 97**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

98. ### What is DOM?

* The Document Object Model (DOM) represents HTML or XML page in such a way that programs can change document structure, content and style.
* The DOM represents the document as nodes as well as objects.
* The DOM is object oriented representation of web page, which can
be modified by scripting language like Javascript.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q98">**⬆ Back to Question 98**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

99. ### What are DOM nodes?

* According to the W3C HTML DOM standards, everything in HTML can be represented as nodes.
* Document node represents whole document.
* Element node represents every HTML element such as HTML, HEAD, BODY, A, H1 etc.
* Text node represents text content inside the element.
* Attribute node represents every HTML attribute.
* Node has node properties that contain information about the node

  * The nodeName property specifies name of the node.
  * The nodeValue property specifies value of the node.
  * The nodeType property specifies type of the node.

<img src="images/dom-nodes.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q99">**⬆ Back to Question 99**</a>

----
  _Questions_ <a href="#Q91">**91**</a> | <a href="#Q92">**92**</a> | <a href="#Q93">**93**</a> | <a href="#Q94">**94**</a> | <a href="#Q95">**95**</a> | <a href="#Q96">**96**</a> | <a href="#Q97">**97**</a> | <a href="#Q98">**98**</a> | <a href="#Q99">**99**</a> | <a href="#Q100">**100**</a>
  ----

100. ### How to get element with id in DOM?

* The `getElementById()` method of document object can be used to get element using id.
e.g.
```javascript
document.getElementById(“myUniqueId”);
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q100">**⬆ Back to Question 100**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

101. ### How to get element using class in DOM?

* The `getElementByClassName ()` method of document object can be used to get element using class.

e.g.
```javascript
document.getElementByClassName(“myClass”);
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q101">**⬆ Back to Question 101**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

102. ### How to get content of any element?

* The **innerHTML** property is useful for getting or replacing the content of HTML elements.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q102">**⬆ Back to Question 102**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

103. ### What are DOM levels?

The W3C DOM specifications are divided into different levels where each level contain some required and optional modules.
* Level 0: Provide low-level set of interfaces.
* Level1: DOM level 1 can be described in two parts: CORE and HTML.

  * CORE provides a low level interfaces that can be used to represent any structured document.
  * HTML provides high-level interfaces that can be used to represent HTML document.

* Level2: Consist of six specifications:
CORE2, VIEWS, EVENTS, STYLE, TRAVERSAL and RANGE.

  * CORE2: extends functionality of CORE specified by DOM level 1.
  * VIEWS: views allow programs to dynamically access and manipulate content of document.
  * EVENTS: events are scripts that are executed when user reacts to web page.
  * STYLES: allow programs to dynamically access and manipulate content of style sheets.
  * TRAVERSAL: allows programs to dynamically traverse the document.
  * RANGE: allows programs to dynamically identify range of content in document.

* Level3: consists of five different specifications: CORE3, LOAD,
SAVE, VALIDATIONS, EVENTS and XPATH.

  * CORE3: extents functionality of CORE specified by DOM level 2.
  * LOAD and SAVE: allows program to dynamically load the content of XML document into DOM document and save DOM document into XML document by serialization.
  * VALIDATION: allows program to dynamically update the content and structure of document while ensuring the document is valid.
  * EVENTS: extents functionality of Events specified by DOM level 2.
  * XPATH: XPATH is a path language that can be used to access DOM tree.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q103">**⬆ Back to Question 103**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

104. ### What are deferred scripts?

* By default, Javascript files will interrupt parsing of HTML document
in order for them to be fetched and executed.
* The defer attribute tells browser to only execute the script file once
the HTML document has been fully parsed.
```javascript
<script defer src="myscript.js">
```
* This reduces loading time of web page and web page is displayed faster.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q104">**⬆ Back to Question 104**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

105. ### What are asynchronous scripts?

* By default, Javascript files will interrupt parsing of HTML document
in order for them to be fetched and executed.
* The async attribute is used to indicate browser that script file can be
executed asynchronously.
```javascript
<script async src="somescript.js">
```
* The HTML parser does not have pause at the point it reaches the script tag to fetch and execute, the execution can occur whenever the script becomes ready after being fetched in parallel with
document parsing.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q105">**⬆ Back to Question 105**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

106. ### What is difference between attribute and property?

* Attributes: Provide more details on an element like id, type, value etc.
* Property: Value assigned to the property like type=”text”, value=’Name’ etc.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q106">**⬆ Back to Question 106**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

107. ### What is the difference between innerHTML & innerText?

* innerHTML: It will process an HTML tag if found in a string
* innerText: It will not process an HTML tag if found in a string

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q107">**⬆ Back to Question 107**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

108. ### What is the difference between textContent & innerText?

* The textContent returns every element in the node.
* The innerText is aware of styling and won't return the text of “hidden” elements.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q108">**⬆ Back to Question 108**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

109. ### What is HTMLCollection?

* The HTMLCollection interface represents a generic collection of elements (in document order) and offers methods & properties for selecting from the list.
* HTMLCollection has length property which returns the number of items in the collection.
* It is not possible to iterate over HTMLCollection list using forEach
by default.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q109">**⬆ Back to Question 109**</a>

----
  _Questions_ <a href="#Q101">**101**</a> | <a href="#Q102">**102**</a> | <a href="#Q103">**103**</a> | <a href="#Q104">**104**</a> | <a href="#Q105">**105**</a> | <a href="#Q106">**106**</a> | <a href="#Q107">**107**</a> | <a href="#Q108">**108**</a> | <a href="#Q109">**109**</a> | <a href="#Q110">**1100**</a>
  ----

110. ### What is NodeList?

* NodeList objects are collections of nodes which are usually returned by properties such as Node.childNodes and functions such as `document.querySelectorAll()`.
* NodeList has length property which returns the number of nodes in
nodelist.
* for...of loops will loop over NodeList objects accurately.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q110">**⬆ Back to Question 110**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

111. ### What are frames?

* Frame divides page into section and in each section different page
can be displayed.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q111">**⬆ Back to Question 111**</a>
----
## 8. Cookies
----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

112. ### What is cookie?

* The Cookies are small items of data that consists of name and value pair. * Cookies are stored on your computer so that it can be accessed by your web browser.
* A web browser and server communicate through HTTP which is stateless protocol. * Stateless protocol treats each request
independently, so server does not keep data after sending it to browser. With cookies such data can be fetched directly from stored cookie file instead of communicating with server.
* For example when user visits web page, user name can be stored in cookie. 
* Now when next time user visits the page cookie belonging to the page is added to the request. 
* This way server gets necessary data “remembered” by cookie.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q112">**⬆ Back to Question 112**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

113. ### How cookie helps client server HTTP communication?

* When a user sends a request to the server, then each of that request is treated as a new request sent by the different user.
* When receiving an HTTP request, a server can possibly send a Set-Cookie header with the response.
* Now, whenever a user sends a request to the server, the cookie is added with that request automatically. 
* Due to the cookie, the server
recognizes the users.

<img src="images/cookie.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q113">**⬆ Back to Question 113**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

114. ### Where are cookies stored?

* During browsing session browser stored cookies in memory, at the time of quitting they go to file called as cookies.txt.
* Different browser store cookies file in a different location on disk.
* For instance, on windows chrome stores the cookies in below location, 
* `C:\Users\<YourUser>\AppData\Local\Google\Chrome\UserData\Default\`
* As cookie expires it is no longer saved on hard drive.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q114">**⬆ Back to Question 114**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

115. ### Where are parameters of cookie?

* There are six parameters of cookie: name, value, expires, path, domain and security.
* The name and value are required whereas all other parameters are optional.
```javascript
document.cookie=”name=VALUE;expires=DATE;path=PATH;domain=DOMAIN;secure”;
```
* **Name and Value** : The first part of cookie must have name and value. The entire name/value must be a single string with no commas, semicolons or whitespace charactors.
* **Expires** : The cookie will disappear when user exits the browser, to
give more life to the cookies you must set an expiration date in the following format.
`DD-Mon-YY HH:MM:SS GMT`
* **Path** : Usually the path is set to root level directory (‘/’), which means the cookie is available for all the pages of your site. If you want the cookie to be readable in specific directory
`<directoryname>`, path should be specified as `path=/<directoryname>`.
* **Domain** : Some websites have lots of domains. The purpose of the ‘domain’ is to allow cookies to other subdomains. In case, if website is `http://www.<domain>.com` with subdomains `http://www.
<subdomainone>.<domain>.com` and `http://www.<subdomaintwo>.<domain>.com`. 

  * If web page on subdomainone set a cookie pages on subdomaintwo cannot read that cookie. But if you add `domain=<domain>` then all subdomains ending with `<domain>` can read the cookie.
* **Secure** : The last parameter of cookie is secure which is a Boolean
value. Its default value is false. If cookie is marked as secure then cookie will be sent to web server and try to retrieve it using secure communication channel.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q115">**⬆ Back to Question 115**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

116. ### Can user disable cookies?

* Yes, user can disable cookies from browser.
* In chrome, you can go to **settings-->Advanced Settings-->Privacy**
and **security-->Content setting-->Cookies** and **disable cookies**.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q116">**⬆ Back to Question 116**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

117. ### How to create cookie?

* When visitor visits web page for first time he enters his or her name.
* This name will be stored in cookies as below,
```javascript
function createCookie(username, value) {
  document.cookie=username + ”=” + value;
}
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q117">**⬆ Back to Question 117**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

118. ### How to read cookie?

* Javascript cookies can be read like this,
```javascript
var x = document.cookie;
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q118">**⬆ Back to Question 118**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

119. ### How to delete cookie?

* While deleting cookie you don’t have to specify value.
* Javascript cookies can be deleted by specifying expires parameter to a past date.
```javascript
document.cookie="username=; expires=Thu,01 Jan 1970 00:00:00 UTC; path= /;";
```
* Some browsers will not let you delete cookie if you don’t specify the path.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q119">**⬆ Back to Question 119**</a>

----
  _Questions_ <a href="#Q111">**111**</a> | <a href="#Q112">**112**</a> | <a href="#Q113">**113**</a> | <a href="#Q114">**114**</a> | <a href="#Q115">**115**</a> | <a href="#Q116">**116**</a> | <a href="#Q117">**117**</a> | <a href="#Q118">**118**</a> | <a href="#Q119">**119**</a> | <a href="#Q120">**120**</a>
  ----

120. ### What is difference between local storage and session storage?

* **Local Storage** : 

  * For every HTTP request, the data is not sent back to the server (HTML, images, JavaScript, CSS, etc) reducing the total traffic between client and server. 
  * Data will stay until it is manually cleared using settings or through program.
* **Session Storage** : 

  * It is similar to local storage; the only difference is data stored in local storage has no expiration time whereas data stored in session storage gets cleared when the page session ends.
  * Session Storage will cleared when the browser is closed.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q120">**⬆ Back to Question 120**</a>
----
## 9. Form validation
----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

121. ### What is form validation?

* **Form validation** verifies whether all fields in form are filled according
to required format.
* If data entered by user is not according to format then appropriate
error message is displayed to the user.
* Forms can be validated using server-side as well as client-side
validations.
* Server-side validation is more secure and required server connection to validate, whereas client-side validation is quicker and doesn’t require server connection but it is less secure.
* Javascript is used for client side validation.
* _Advantages of client side validation_ is that, it saves time, reduces
load on server and can validate form element even before form is submitted.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q121">**⬆ Back to Question 121**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

122. ### What is required attribute?

* The required attribute in HTML element prevents that element being submitted as blank.

e.g.
```html
<input type=”text” name=”employeename” required>
```
* In above case, as long as text field employeename is blank form submission will be prevented.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q122">**⬆ Back to Question 122**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

123. ### What is pattern attribute?

* The pattern attribute specifies a regular expression against which
elements value is checked.
* If element value does not match the regex pattern form submission will be prevented.

e.g
```html
<input type=”text” name=”employeename” pattern=”[A-Za-z]”>
```
* In above case, if employee name contains value which is not alphabet then form submission will be prevented.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q123">**⬆ Back to Question 123**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

124. ### How to validate form using Javascript function?

* Below example shows validation of form using Javascript.
* Here, we have created form having name input and then when while saving save validateName function will be called and it will validate if name is blank.
```javascript
<script>
function validateName() {
var name = document.nameform.name.value;
if(name==undefined || name==””) {
alert(“Kindly enter the name!!!”);
return false;
}
Return true;
}
</script>
```
```html
<form name="nameform" method="post" onsubmit="return validateform()”>
Name: <input type="text" name="name">
<input type="submit" name="save">
</form>
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q124">**⬆ Back to Question 124**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

125. ### How to validate email in the form?

* Below function can be used to validate email in the form.
```javascript
function validateEmail(emailField){
var reg = /^([A-Za-z0-9_\-\.])+\@([A-Za-z0-9_\-\.])+\.([A-Za-z]
{2,4})$/;
if (reg.test(emailField.value) == false)
{
alert('Invalid Email Address');
return false;
}
return true;
}
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q125">**⬆ Back to Question 125**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

126. ### How to validate field without submitting form?

* To validate field without submitting form you can use validation function in onblur event of input field.
```html
<input type="text" onblur="validateEmail(this);" />
```
* Here, input field will be available to validateEmail function.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q126">**⬆ Back to Question 126**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

127. ### What is .test method?

* The `.test()` API runs a search for a match between a regex and a string.
* The `.test()` API returns a Boolean(true/false), returns true if test
passes and false if it doesn’t.
* Using `.test()` returns no data, so don’t expect any.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q127">**⬆ Back to Question 127**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

128. ### What is .match method?

* Using `.match()` is best when you are expecting data back in test result, **.match()** returns an array with matches or simply null if there are none.
* With match you won’t just be testing for presence of data, you will also see if data pattern exist and return that data.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q128">**⬆ Back to Question 128**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

129. ### How to validate Date?

```javascript
function validateDate(dateField) {
var reg = /^([0-9]{2})\/([0-9]{2})\/([0-9]{4})$/
if (reg.test(dateField.value) == false) {
alert(“Invalid Date!!!”);
return false;
}
return true;
}
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q129">**⬆ Back to Question 129**</a>

----
  _Questions_ <a href="#Q121">**121**</a> | <a href="#Q122">**122**</a> | <a href="#Q123">**123**</a> | <a href="#Q124">**124**</a> | <a href="#Q125">**125**</a> | <a href="#Q126">**126**</a> | <a href="#Q127">**127**</a> | <a href="#Q128">**128**</a> | <a href="#Q129">**129**</a> | <a href="#Q130">**130**</a>
  ----

130. ### How to allow number only in input field?

```javascript
function validateNumber(numField) {
var reg = /^[0-9]+$/
if (reg.test(numField.value) == false) {
alert(“Invalid Number!!!”);
return false;
}
return true;
}
```
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q130">**⬆ Back to Question 130**</a>
----
## 10. Error and Exception Handling
----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

131. ### What is error object?

* When an exception occurs, an object representing the error is constructed and thrown.
* The Error constructor creates an error object.
* When runtime errors occur, instances of Error objects are thrown.
* The Error object can be used as a base object for user-defined exceptions.
```javascript
var error = new Error("error message");
```
* **“Error”** objects contain two properties, *“name”* and *“message”*. 
  * The “name” property specifies the type of exception 
  * The “message” property provides a more detailed description of the exception.The “message” gets its value from the string passed to the constructor of exception.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q131">**⬆ Back to Question 131**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

132. ### What are different error types in Javascript?

Below are primary error types in javascript:
* **SyntaxError** : Raised when syntax error occurs while parsing the Javascript code.
* **RangeError** : Raised when numeric value exceeds allowed range.
* **EvalError** : Raised when the eval() function is used in an incorrect manner.
* **ReferenceError** : Raised when an invalid reference is used 
* **TypeError** : Raised when type of variable is not as expected.
* **URIError** : Raised when the encodeURI() or decodeURI() functions are used in an inaccurate manner.
* **InternalError** : Raised when internal error in the javascript engine is
thrown.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q132">**⬆ Back to Question 132**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

133. ### How to handle exceptions in JavaScript?

* JavaScript uses the try...catch...finally statement as well as the throw operator to handle exceptions.
* You can catch user-defined and runtime exceptions, but you cannot catch JavaScript syntax errors.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q133">**⬆ Back to Question 133**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

134. ### Explain try…catch…finally.

* **Try** : wraps suspicious code that may throw an error in try block.
* **Catch** : 
  
  * Write code to do something when error occurs in catch block. 
  * The catch block can have parameters which will give you error information. Usually, catch block is used to log an error or display specific messages to the user.
* **Finally** : 

  * code in finally block will always be executed regardless of the occurrence of an error. 
  * The finally block is usually used to
  complete the remaining task or reset variables that might have changed before error occurred in try block.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q134">**⬆ Back to Question 134**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

135. ### How to throw exceptions programmatically?

* It is possible to throw exceptions programmatically using **“throw”** statement.
* There is no restriction on data type that can be thrown as an exception.

e.g.
```javascript
throw “error occurred!!”;
throw new SyntaxError(“syntax error  occurred!!”);
```
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q135">**⬆ Back to Question 135**</a>
----
## 11. Debugging
----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

136. ### What is debugging?

* Debugging is the process of detecting and fixing existing and potential errors in software code that can cause it to behave unexpectedly.
* To debug a program, programmer has to start with problem, identify source of the problem and then fix it.
* Sometimes it takes more time debugging a program than coding it.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q136">**⬆ Back to Question 136**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

137. ### What is debugger keyword?

* Debugger statement stops the execution of Javascript. If debugging functionality is not available, this statement has no effect.
* Debugger keyword is like breakpoint in script source code.

e.g.
```javascript
function someErroraniousFunction() {
debugger;
code;
}
```
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q137">**⬆ Back to Question 137**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

138. ### What is console object?

* Console object provides access to browsers debugging console.
* If browser supports debugging you can use `console.log()` method to display required text in debugging window.
* Console object provides methods like debug(), log(), error(), info(),
trace(), warn() which are useful for code debugging.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q138">**⬆ Back to Question 138**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

139. ### How to activate debugging in browser?

* You can activate debugging in browser by pressing F12 and then select console in debugger menu.
  
  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q139">**⬆ Back to Question 139**</a>

----
  _Questions_ <a href="#Q131">**131**</a> | <a href="#Q132">**132**</a> | <a href="#Q133">**133**</a> | <a href="#Q134">**134**</a> | <a href="#Q135">**135**</a> | <a href="#Q136">**136**</a> | <a href="#Q137">**137**</a> | <a href="#Q138">**138**</a> | <a href="#Q139">**139**</a> | <a href="#Q140">**140**</a>
  ----

140. ### How to get mobile devices view of webpage in desktop browser?

* In browser press F12,
Then click on toggle device toolbar,

<img src="images/console-1.png">

* Then, select device for which you want webpage view.

<img src="images/console-2.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q140">**⬆ Back to Question 140**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

141. ### How to deactivate breakpoint in browser?

* This can be done by clicking on “deactivate breakpoints” icon in “Sources” tab of browser developer tool.

<img src="images/deactive-console.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q141">**⬆ Back to Question 141**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

142. ### How to pause script execution?

* This can be done by clicking on “pause script execution” icon in “Sources” tab of browser developer tool.

<img src="images/pause-console.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q142">**⬆ Back to Question 142**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

143. ### How to execute function line by line while debugging?

* This can be done by clicking on “Step into next function call” icon in “Sources” tab of browser developer tool.

<img src="images/LineByLine-console.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q143">**⬆ Back to Question 143**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

144. ### How to execute function without stepping into it while debugging?

* This can be done by clicking on “Step over next function call” icon in
“Sources” tab of browser developer tool.

<img src="images/StepOver-console.png">

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q144">**⬆ Back to Question 144**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

145. ### What is code smell?

* In computer programming, a code smell is any characteristic in the source code of a program which possibly indicates a deeper problem.
* Determining what is a code smell and what is not a code smell is subjective, and varies by language, developer, and development methodology.
* The two main know open source tools used for JavaScript code analysis are JSLint and JSHint, the second being a fork of the first one. 
* There are however many different tools that try to achieve the same goal and you might find something more suited to your own needs.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q145">**⬆ Back to Question 145**</a>
----
## 12. AJAX overview
----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

146. ### What is AJAX?

* **AJAX** stands for Asynchronous Javascript and XML. 
* It is collection of related technologies like Javascript, XML, JSON, HTML and XMLHttpRequest etc.
* AJAX allows you to send and receive data asynchronously without reloading web page and hence makes web pages more fast and interactive.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q146">**⬆ Back to Question 146**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

147. ### What is difference between GET and POST?

|   | GET | POST |
|----|----|----|
| History | Parameters remain in browser history as they are part of URL. | Parameters are not saved in browser history. |
| Security | GET is less secure as data sent as part of URL. | POST is more secure than GET because parameters are not stored in browser history. |
| Parameters | Parameter data is limited to what you can stuff in URL. Safest to use less than 2K of parameters. | Parameters can contain uploaded data files and larger data than GET. |
| Caching | Can be cached. | Not cached. |

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q147">**⬆ Back to Question 147**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

148. ### What is XMLHttpRequest object?

* XMLHttpRequest object is used for asynchronous communication between client and server.
* It provides methods like open(), send(), setRequestHeader() for exchanging data between client and server.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q148">**⬆ Back to Question 148**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

149. ### How to make HTTP GET call using AJAX?

* To make HTTP call in AJAX, you first need to initialize a new XMLHttpRequest() object.
* Specify URL endpoint, HTTP method (GET) to open() method of XMLHttpRequest() object.
* Then call send() method to hit the request.
* Receive the response using `XMLHttpRequest.onreadystatechange` property.

e.g.
```javascript
const xmlHttpRequest = new XMLHttpRequest();
xmlHttpRequest.open(“GET”,”http://some.domain.com/method”);
xmlHttpRequest.send();
xmlHttpRequest.onreadystatechange=(e)=>{
  console.log(xmlHttpRequest.responceText);
}
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q149">**⬆ Back to Question 149**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

150. ### How to make HTTP POST call using AJAX?

* To make HTTP call in AJAX, you first need to initialize a new XMLHttpRequest() object.
* Specify URL endpoint, HTTP method (POST) to open() method of XMLHttpRequest() object.
* Then call send() and pass data to send() method to hit the request.
* Receive the response using `XMLHttpRequest.onreadystatechange` property.

e.g.
```javascript
const xmlHttpRequest = new XMLHttpRequest();
xmlHttpRequest.open(“POST”,"http://some.domain.com/method");
xmlHttpRequest.send("fname=Sandeep&lname=Dalal");
xmlHttpRequest.onreadystatechange=(e)=>{
  console.log(xmlHttpRequest.responceText);
}
```

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q150">**⬆ Back to Question 150**</a>

----
  _Questions_ <a href="#1Q41">**141**</a> | <a href="#Q142">**142**</a> | <a href="#Q143">**143**</a> | <a href="#Q144">**144**</a> | <a href="#Q145">**145**</a> | <a href="#Q146">**146**</a> | <a href="#Q147">**147**</a> | <a href="#Q148">**148**</a> | <a href="#Q149">**149**</a> | <a href="#Q150">**150**</a>
  ----

151. ### What are HTTP status codes?

* HTTP status code are the standard response code given by website servers.
* These codes help identify the cause of problem when web page or other resource does not load properly.

  * 4xx Client Error:
  
    * This category of HTTP status code includes those where request for a web page or other resource contains bad syntax or cannot be filled for some other reason, presumably due to fault of client.
    * Some common client error HTTP status codes are 404 (Not Found), 403 (Forbidden) and 400 (Bad request).
  
  * 5xx Client Error:

    * This category of HTTP status code include those where the request for a web page or other resource is understood by the websites server but is incapable of filling it for some reason.
    * Some common server error HTTP status codes are 500 (Internal server error), 503 (Service Unavailable) and 502 (Bad Gateway).
* There are also 1xx, 2xx and 3xx code that are informational, confirm success or dictate redirection which are not errors, so you shouldn’t be alerted about them.

  **[⬆ Back to Top](#table-of-contents)**   |   <a href="#Q151">**⬆ Back to Question 151**</a>

