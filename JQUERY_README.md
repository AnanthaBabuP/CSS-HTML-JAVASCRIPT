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
    3. Calculator Program

PART-5:
    1.manipulate HTML Element's Dimenstions
        1.height()
        2.innerHeight()
        3.outerHeight()
        4.offset()
        5.position()
        6.width()
        7.innerWidth()
        8.outerWidth()
    2.Syntex:
        1.$('selector').height('value');
        2.$('selector').innerHeight('value');
        3.$('selector').outerHeight('value');
        4.$('selector').offset('value');
        5.$('selector').position('value');
        6.$('selector').width('value');
        7.$('selector').innerWidth('value');
        8.$('selector').outerWidth('value');
    
    3.The Following table lists jQuery methods for traversal DOM Element
        1.children()
        2.each()
        3.find()
        4.first()
        5.next()
        6.parent()
        7.prev()
        8.siblings()
    4.Syntex:
        1.$('selector').each(CallBack Function);
        2.$('selector').children();
        3.$('selector').find('selector to find child');
        4.$('selector').next();
        5.$('selector').parent();
        6.$('selector').siblings();

PART-6:
    1.CSS Manipulation:
        1.css()
        2.addClass()
        3.hasClass()
        4.removeClass()
        5.toggleClass()
       Syntex:
        1.$('selector').css({
            'style Property Name':'value',
        });
        2.$('selector').addClass('css class Name');
        3.$('selector').toggleClass('css class Name');
    
    3.JQuerey Animation:
        1.animate()
        2.queue()
        3.stop()
        4.fedeln()
        5.fadeOut()
        6.fadeTo()
        7.fadeToggle()
        8.hide()
        9.show()
        10.toggle()
        11.slideUp()
        12.slideDown()
        13.slideToggle() 
       
       Animated syntex:
        1.$('selector').animate(
            {'stylepropertyname':'value'},
            duration,
            easing,
            callback
            ); 
                (or)
        $('selector').animate({'propertyName':'value'},{Options})
    
    2.Set Animation Duration
        $('img').animate({
            height:'100px',
            width:'100px'
        },5000);

    3.Apply Easing Method
        1.linear
        2.swing

        $('img').animate({
            height:'100px',
            width:'100px'
        },5000,'swing')
    4.callback Function on Animation Complete
        $('img').animate({
            height:'100px',
            width:'100px'
        },5000,function(){
            $('msg').text('Animating Complited...)
        });

        <img src='sample.jpg'></img>
        <p id='msg'></p>
    5. Specify Animation Options
            You can specify various options as JSON Object.
            The option include duration,easing.queue,step,progress,complite,start,done and always.
    
    6.syntex:
        1. $('selector').queue(); -show or manipulate the queue
        2. $('selector').fadeIn(speed,easing,callback); -fading to clear
        3. $('selector').fadeIn(speed,easing,callback); -clear to fading
        $('selector').hide(speed,easing,callback);
        $('selector').show(speed,easing,callback);
        $('selector').toggle(speed,easing,callback);

PART-7:
    1.JQUery Animation1 - Example
    2.JQuery Event Methods
        1.form Event
        2.Keyboard Event
        3.Mouse Event
        4.Browser Event
        5.Document Loading
        
        1.Form Event Methods():

            JQuery Event - DOM Event
            1.blur       - onBlur
            2.change     - onchange
            3.focus      - onFocus
            4.focusin    - onFocusin
            5.select     - onSelect
            6.submit     - onSubmit    
        
        2.Keyboard Event
            1.keydown    - onKeydown
            2.keyUp      - onKeyUp
            3.keyPress   - onKeyPress
            3.focusOut   -

        3.Mouse Evnet
            1. click
            2. dblclick
            3. focusout
            4. hover
            5. mousedown
            6. mouseenter
            7. mouseleave
            8. mousemove
            9. mouseout
            10.mouseover
            11.mouseup
            12.toggle
        4.Browser Event Methods()
            1.Error
            2.Resize
            3.scroll
        5.Document loading Methods():
            1.load
            2.ready
            3.unload

PART-8:
    1.Event Object:
        1.JQuery Passes an event object to every event handler function.
            1.target
            2.pageX
            3.pageY
            4.related Target..etc..
    2.this Keyword in Event Handler
    3.Hover()
        1.mouseenter,mouseleave,etc...
    4.Event Binding Using on()
        synt:
            on(type,selector,data,fn);
    5.Event Binding Multiple Elements:
        example:
            $('#myDiv').on('mouseenter mouseleave)',function(){
                $('myDiv').text('The Mouse entered or left from the div');
            });

            <div id='myDiv' style='width:100px;height=100px;'></div>
    6.Specify Named function as Event Handler
        ex:$('#myDiv').on('mouseenter',namedFunction);
            var namedFunction = function(){
                alert('The Mouse Entered!');
            }
    7.Event Bubbling

PART-9:
    1.JQuery DOM Manipulation:
        1.jQuery Provide methods such as attr(),html(),text() and vla() which act as getter and setter.
        2.Standard library Methods:
            1.Extract the content of an element
            2.Change the content of an element
            3.Adding a child element under an existiong element
            4.Adding a parent element above an existing element
            5.Adding an element before or after an existing element
            6.Replace an existiong element with another element
            7.Wrapping content with-in an element
        3.Get Form Fields:
            $('selector').val() // get the value from any form field
        4. Select Content
            1.$('selector').html(val,[function]);
            2.$('selector').text(val,[function]);
        5. Set Form Fields:
            $('selector').val('value')
        6.Replacement Element
            $('selector').replaceWidth('value');
            // example H1 change to p tag

PART-10:
    1.jQuery - Add Elements: 
        1.Apend() Method: nxt
            $('Selector').append(content,[content]);
        2.After() Mehtod: end 
            $('Selector').after(content,[content]);
        2.Before() Mehtod:  First
            $('Selector').after(content,[content]);
        2.prepend() Mehtod: just before
            $('Selector').after(content,[content]);
    
    2.Traversing Ancestors:
        The method casn be used to find a PArent,grandparent,great-grandparent
        Three Methods: Refer To Code
            1.parent()
            2.parents()
            3.parentUntill() 

    3.Trversing Descendants:
        The method casn be used to find a Child,grandchild,great-grandchild
        Two Methods: Refer To Code
            1.children()
            2.find()

PART-11:
    1.jQuery Find()
         $('Selector').find(filter)
    2. Callback Function

    3.jQuery Utilities:
        1.$.trim
        2. $.each() 
        3.$.inArray()
        4.$.extend()
        5.$.proxy() - Return a function
        6.$.browser()
        7.$.contains()
        8.$.data()

        1.$.trim -Remove white Spaceses
            $.trim('  lots of whitespace  ');
        2. $.each() - Used to Iterate Arrays and Objects
            1.$.each(['a','b','c'],function(ind,val){
                console.log('Element '+ ind + ' Is '+val);
            });

            2.$.each({a:'a',b:'b',c:'c'},function(key,val){
                console.log(key + ' : '+val);
            });
        3.$.inArray() - Check Array Size. Is Null return -1
            1.var myArray = [1,2,3,4,5];
            if($.inArray(4,myArray) != -1){
                console.log('found it!'); 
            }
        4.$.extend() - Change the property of first Object
            1.var firstObject = {foo:'bar',a:'b'};
              var secondbject = {foo:'faz'};
              var newObject = $.extend(firstObject,secondbject);
              console.log(firstObject.foo);
              console.log(newObject.foo);

PART-12:  
    1.$.now()
    2.$.isXMLDoc()
    3.$.globalEval()
    4.$.dequeue()

    5.jQuery Intraction
        1.Drag
        2.Drop
        3.Resixw
        4.Select
        5.Sort

PART-13:
    1.Page piling
    2.jQuery Form-serialize()
    3.jQuery Form-serializeArray()

PART-14: Refer to images
    1.jQuery UI - It is categorized 4 groups.
        1.interacations 
        2.widgets
        3.Effects
        4.Utilities

        definition:
        
        3.Effect:
            add css
            remove Css
            COlor Animation
            Hide show 
            toggle
            toggle Class
            Effect
            switchclass
        4.Utilities:
            1.tooltip
            S.Accordion

    2.Benifits Of jQuery UI:
        1.Cohesive and Consistent APIs.
        2.Comprehensive Browser Support.
        3.Open Sourse and Free to Use.
        4.Good Documentation.
        5.Powerful Theming Mechanism.
        6.Stable and Maintenance Friently.
    
    3.Explaination:
        1.interacations:
            Draggable
            Dropable
            Sortable
            Selectable
            Resizable

PART-15:
    1.JQuery widgets:
            It's a Specialized,platform-independent,cross browser compatable,stable blugins.
    2.Top jQuery Widgets:
            1. Accordion widgets 
                1.Accordion Wedget in jquery UI is a jQuery Based expandable and Collapsible content holdis broken into sections and properly look like tabs.

                Syntax: -2
                    1. $('Selector',content).accordian(options) Method
                    2. $('Selector',content).accordian('action',options) Method
                
                1.1. $('Selector',content).accordian(options) Method:
                    Options:
                        1. Action       - page is first Access.
                        2. Animate      - How to animate Changing panels(default value is {}
                        3. Callapsible  - Default value false (+ or - ) menu
                        4. Disable      - when that is true the accoridian will be disable
                        5. Event        - This option specify the event used to select on accordion.
                        6. Header       - Default apttern for identifying the header element.   
                        7. HeightStyle  - Control the height
                        8. Icons        - Open and close Icon
            3. Button  widgets
            4. Datepicker widgets
            5. Dialog widgets 
            6. Menu  widgets
            7. Progressbar widgets
            8. Select the Menu widgets
            9. Slider widgets
            10.Spinner widgets
            11.Tab widgets
            12.Tooltip widgets