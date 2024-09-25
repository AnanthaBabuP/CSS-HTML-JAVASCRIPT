# CSS-HTML-JAVASCRIPT
Day to day Learning

JQUERY 

PART-1:
    1.JQuery Introduction
    2.JQuery Feauture:
        1.simple and easy to learn
        2.Light Weight
        3.css Manipuation
        4.Html manipulation
        5.Dom Traversal and Manipualtion
        6.Cross browser support
        7.Event Handling
        8.JavaScript Library
    3.Add JQUERY
        1.Download From www.jquery.com
        2.Includ JQuery from a CDN(Content Delevery Network)
    4. Add jquery on web-page
        <head>
            <script src="jquery-1.11.3.js"></script>
        </head>
    
    5.JQuery CDN
        1. CDN-Content Delivery (or)  Distribution Network
        2. Here Lot of files are stored,using CDN you can directly use  these files on your website,no need to upload these files on your server. 
        3.TypeTo Implement CDN For:
            1. Google CDN: https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js
            2. Microsoft CDN: https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.6.0.min.js
            3. CDNJS: https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js
            4. jsDelivr: https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.min.js
    6. Advantages of using CDN?
        1.It reduce the load from your server.
        2.It saves bandwidth.
        When any User visit on other website it save in browser, as a result next time easy to load.
    7.Editiors for JQuery:
        (Notepad,++,VSCode,CKEditior,TinyMCE,etc..)

    8. JQuery Syntax
        $(selector).action();

        Example:
            $('.input1').hide(); 
    9. What is dollar Sign ($) in JQUERY?  
        synt:
            $(document).ready(function(){

            });
                    (or)
            JQuery(document).ready(function(){

            });
    10. Document Ready Event:
        You can notice in any Jquery example or code jquery methods are inside document ready Event.

        syntax:
            $(document).ready(function(){
                // Jquery Methods
            });
    
    11. Downloading JQuery:
        Versions:
            1.Product Version - Complite Version
            2. Development Version  - developer Vaersion
    12.GoogleCDN-Example

PART-2:
    1. Microsoft CDN-Exapmle
    2. JQuery CDN-Example
    3. DeveloperCDN - Example

PART-3:
    1.Element Selector
    2. Event handling
        1.Mouse Event 
        2.Keyboard Event
        3.Form Event
        4.Windows Event
    3. DOM Manipulation Methods
        1.append()
        2.before()
        3.after()
        4.prepend()
        5.remove()
        6.replaceAll()
        7.wrap()

PART-4:
    1.Mainpulate the HTML Attributes
        1.attr()
        2.prop()
        3.html()
        4.text()
        5.val()
    2. syntax:
        $('selector').attr('name','value');
        $('selector').prop('name','value');  
        $('selector').html('content');  
        $('selector').text('content'); 
        $('selector').val('content');